# Weather Informer
![Static Badge](https://img.shields.io/badge/Version-1.0-fedcba?style=flat-square) ![Static Badge](https://img.shields.io/badge/Dle-13_And_Up-green?style=flat-square) ![License: Unlicense](https://img.shields.io/badge/License-MIT-blue.svg?style=flat-square) [![Static Badge](https://img.shields.io/badge/Download-Weather_Informer-red.svg?style=flat-square)](https://ticcix.com/16-weather-informer.html) [![Static Badge](https://img.shields.io/badge/Documentation-Green.svg?style=flat-square)](https://ticcix.com/16-weather-informer.html)
![img](https://ticcix.com/uploads/posts/2022-09/dwqd.png)
###### Hack for creating blocks with information about some weather data of certain countries. All data that can be obtained is presented in the screenshot.
![img](https://ticcix.com/uploads/posts/2022-09/thumbs/poster.png)![img](https://ticcix.com/uploads/posts/2022-09/thumbs/3.png)![img](https://ticcix.com/uploads/posts/2022-09/thumbs/2.png)

Registration on the site ``` https://openweathermap.org/ ``` to receive the key.
Key generation page, ``` https://home.openweathermap.org/api_keys ```

``` [weather-block city="..."] ... [/weather-block] ``` - Defines an informer block. In the city parameter, enter the name of the city in **English**. In each block, for each country, the following tags apply.

``` {weather-temp} ```- **Temperature**

``` {weather-value ```} - **Weather**

``` {weather-icon} ``` - **[{THEME}/weather/icons/{weather-icon}.png]**
``` {weather-country} ``` - **Two-character country code**
``` {weather-humidity} ``` - **Humidity**
``` {weather-pressure} ``` - **Pressure**
``` {weather-wind} ``` - **Wind speed**
``` {weather-clouds} ``` - **Cloudiness**
