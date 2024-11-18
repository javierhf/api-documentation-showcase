---
title: My Technical Writer Portfolio
description: >-
  Disclaimer: The following pages contain my version of the public and official
  documentation of the OpenWeather API. The sole purpose of this page is to
  showcase my technical writing practice.
---

# OpenWeather - Once Call API 3.0

!!! info "About this page"  
    This is my version of the public and official documentation of Openweather - [One Call API 3.0](https://docs.openweather.co.uk/api/one-call-3).  I've applied my technical writing practice regarding page layout and structure, text formatting, topic completeness, and information disclosure.

     If you want to create the product or project documentation your users will love, or improve the one you're already have, [drop me a message!](https://www.linkedin.com/in/javier-hernandez-fernandez/).

## Overview

**OpenWeather - One Call 3.0 API provides the following information:**

* Essential weather data
* Short-term and long-term forecasts
* Aggregated weather data easily

**One Call API 3.0 is based on the proprietary OpenWeather Model** and provides 4 endpoints**.** Our endpoints are _updated every 10 minutes_ to deliver accurate and up-to-date weather data.  

## Resources

**One Call API 3.0 provides 4 resources** or endpoints, accessing to different data as shown in the following table:

<table><thead><tr><th width="198">Endpoint</th><th>Scope</th><th>Features</th></tr></thead><tbody><tr><td><code>/onecall</code></td><td><a href="https://openweathermap.org/api/one-call-3#current"><strong>Current weather and forecasts:</strong></a></td><td><ul><li>Minute forecast for 1 hour</li><li>Hourly forecast for 48 hours</li><li>Daily forecast for 8 days</li></ul></td></tr><tr><td><code>/timemachine</code></td><td><a href="https://openweathermap.org/api/one-call-3#history"><strong>Weather data for any timestamp</strong></a></td><td>45 years historical archive and 4 days ahead forecast.</td></tr><tr><td><code>/day_summary</code></td><td><a href="https://openweathermap.org/api/one-call-3#history_daily_aggregation"><strong>Daily aggregation</strong></a></td><td>Daily agreggation of weather data for 45 years archive and 1.5 years ahead forecast.</td></tr><tr><td><code>/overview</code></td><td><a href="https://openweathermap.org/api/one-call-3#weather_overview"><strong>Weather overview</strong></a></td><td>Weather overview with a human-readable weather summary for today and tomorrow's forecast, utilizing OpenWeather AI technologies.</td></tr></tbody></table>

**One Call API 3.0 data** is available in JSON, XML, or HTML format.

!!! warning "Dark Sky API users"  
    If you are using Dark Sky API, check our easy-to-follow[ migration process.](https://openweathermap.org/darksky-openweather-3)  

## _API Keys and Default API Calls_

**You can generate as many API keys as needed for your subscription.** We track the total usage from all of them.

**One Call API 3.0 sets a default limit of 2000 API calls per day** (free plan). If you need to change this limit, check the information in the ["Your account billing plans"](https://home.openweathermap.org/subscriptions) tab and update the standard settings.&#x20;

