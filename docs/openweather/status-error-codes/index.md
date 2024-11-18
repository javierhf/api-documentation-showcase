---
title: My Technical Writer Portfolio
status: new
description: >-
  Disclaimer: The following pages contain my version of the public and official
  documentation of the OpenWeather API. The sole purpose of this page is to
  showcase my technical writing practice.
---

# Status and Error Codes

## Error Response Structure

**Errors response payload** returned for all types of errors has the following structure:

```json
{

`    `"cod":400,                          # Error code

`    `"message":"Invalid date format", # Error description

`    `"parameters": [                   # List of request parameters name related to the error

`        `"date"

`    `]

}  
```

## Error Codes

**Check the following table for more information** about the status and error codes:

<table><thead><tr><th width="180">Error Code</th><th>Description</th></tr></thead><tbody><tr><td><strong>401</strong></td><td><p>Unauthorized. You can get 401 error if API token did not provided in the request or in case API token provided in the request does not grant access to this API.</p><p></p><p>You must add API token with granted access to the product to the request before returning it.</p></td></tr><tr><td><strong>404</strong></td><td><p>Not Found. You can get 404 error if data with requested parameters (lat, lon, date etc) does not exist in service database.</p><p></p><p>You must not retry the same request.</p></td></tr><tr><td><strong>429</strong></td><td><p>Too Many Requests. You can get 429 error if the key quota of requests for the provided API to this API was exceeded.</p><p></p><p>You may retry the request after some time or after extending your key quota.</p></td></tr><tr><td><strong>5xx</strong></td><td><p>Unexpected Error. You can get '5xx' error in case of other internal errors. Error Response code will be <code>5xx</code>.</p><p></p><p>Please contact us and enclose an example of your API request that receives this error in your email to let us analyse it and find a solution for you promptly.</p><p></p><p>You may retry the request which led to this error.</p></td></tr></tbody></table>

