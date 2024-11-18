---
title: My Technical Writer Portfolio
description: >-
  Disclaimer: The following pages contain my version of the public and official
  documentation of the OpenWeather API. The sole purpose of this page is to
  showcase my technical writing practice.
---

# Best Practices  

## Overview  

_TO DO_

**The following table provides the best practices** that allow you to get the most out of the OpenWeather API:

<table><thead><tr><th width="330">Scope</th><th>Best Practice</th></tr></thead><tbody><tr><td><strong>API Key Management</strong></td><td><p>Securely store your API key. Do not hardcode it in your application's source code, especially if the code is publicly accessible.</p><p></p><p>Use environment variables or secure app settings for API key management.</p></td></tr><tr><td><strong>Efficient Use of API Calls</strong></td><td><p>To avoid reaching your API call limit, cache responses whenever possible, especially if you're requesting data that doesn't change frequently.</p><p></p><p>OpenWeather data updates every 10 minutes, so plan your requests accordingly.</p></td></tr><tr><td><strong>Use the Correct Endpoint</strong></td><td><p>OpenWeather offers various endpoints for different types of data (current weather, forecasts, historical data, etc.).</p><p></p><p>Use the specific endpoint that matches your data needs to ensure efficient use of the API.</p></td></tr><tr><td><strong>Use the Correct Endpoint</strong></td><td><p>OpenWeather offers various endpoints for different types of data (current weather, forecasts, historical data, etc.).</p><p></p><p>Use the specific endpoint that matches your data needs to ensure efficient use of the API.</p></td></tr><tr><td><strong>Handle Errors Gracefully</strong></td><td><p>Implement error handling in your application to manage API request failures or unexpected responses.</p><p></p><p>This includes handling HTTP status codes and parsing error messages returned by the API.</p></td></tr><tr><td><strong>Optimize Requests with Parameters</strong></td><td>Use API request parameters effectively to get only the data you need. For example, you can exclude parts of the data you don't need with the exclude parameter in the One Call API 3.0.</td></tr><tr><td><strong>Respect API Limits</strong></td><td><p>Be aware of your subscription plan's API call limits and ensure your application does not exceed them. </p><p></p><p>Implement logic to throttle requests if necessary.</p></td></tr><tr><td><strong>Use Units and Language Parameters</strong></td><td>Customize API responses for your audience by using the units parameter to specify temperature and wind speed units, and the lang parameter to localize weather descriptions.</td></tr><tr><td><strong>Geocoding</strong></td><td>Use the Geocoding API to convert between city names and geographical coordinates when necessary, as direct requests by city name may be deprecated for some endpoints.</td></tr><tr><td><strong>Subscription Management</strong></td><td><p>Keep track of your subscription status and the features available to you. </p><p></p><p>Some features, like the One Call API 3.0, require a separate subscription.</p></td></tr><tr><td><strong>Stay Updated</strong></td><td><p>OpenWeather periodically updates its APIs and documentation. </p><p></p><p>Stay informed about any changes that might affect your application by regularly checking the OpenWeather website or subscribing to their updates.</p></td></tr></tbody></table>

