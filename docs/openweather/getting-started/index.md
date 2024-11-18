---
title: My Technical Writer Portfolio
status: new
description: >-
  Disclaimer: The following pages contain my version of the public and official
  documentation of the OpenWeather API. The sole purpose of this page is to
  showcase my technical writing practice.
---

# Getting Started  with the OpenWeather API  

## First Steps

**To get started with the OpenWeather API** follow these steps:

1. [Sign up](https://home.openweathermap.org/users/sign\_up) to OpenWeather to create your account.
2. Open the [Pricing](https://openweathermap.org/price) page.
3. Under **Professional Collections**, select [Get API Key](https://home.openweathermap.org/users/sign\_up) (free plan).

**You will receive a confirmation email.** Complete the email instructions and then follow these steps:

1. Open your [OpenWeather API key](https://home.openweathermap.org/api\_keys) page.
2. Provide a name for your new API Key.

## Making Your First API Call

!!! info "Free plan calls limit"  
    The OpenWeather API free plan sets a default limit of 2000 API calls per day. If you need to change this limit, check the standard settings in [Your account billing plans](https://home.openweathermap.org/subscriptions) tab.

**After getting your API Key, you can make your first API call to request for current weather forecast** for a specific latitude and longitude (_latitude=33.44 and longitude =-94.04_ ).&#x20;

The API call will look as follows:

_`https://api.openweathermap.org/data/2.5/weather?lat=33.44&lon=-94.04&appid={API key}`_

## Reading Your First API Response

!!! info "Parameters not showing"  
    Parameters not showing in the API response indicate that the related weather phenomena just did not happen for the data of measurement provided.

**For the previous API call,** the API response (in JSON format) will look as follows:

API response (JSON):

```json
{

`  `"coord": {

`    `"lon": 10.99,

`    `"lat": 44.34

`  `},

`  `"weather": [

`    `{

`      `"id": 501,

`      `"main": "Rain",

`      `"description": "moderate rain",

`      `"icon": "10d"

`    `}

`  `],

`  `"base": "stations",

`  `"main": {

`    `"temp": 298.48,

`    `"feels\_like": 298.74,

`    `"temp\_min": 297.56,

`    `"temp\_max": 300.05,

`    `"pressure": 1015,

`    `"humidity": 64,

`    `"sea\_level": 1015,

`    `"grnd\_level": 933

`  `},

`  `"visibility": 10000,

`  `"wind": {

`    `"speed": 0.62,

`    `"deg": 349,

`    `"gust": 1.18

`  `},

`  `"rain": {

`    `"1h": 3.16

`  `},

`  `"clouds": {

`    `"all": 100

`  `},

`  `"dt": 1661870592,

`  `"sys": {

`    `"type": 2,

`    `"id": 2075663,

`    `"country": "IT",

`    `"sunrise": 1661834187,

`    `"sunset": 1661882248

`  `},

`  `"timezone": 7200,

`  `"id": 3163858,

`  `"name": "Zocca",

`  `"cod": 200

}    
```

## Rate Limits and Thresholds

**The OpenWeather API’s free plan has a limit of 2000 calls a day**. If you need to increase the rate limit and thresholds, update the standard settings in the [Billing plans](https://home.openweathermap.org/subscriptions) tab in your account.

