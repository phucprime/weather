# Weather

Access current weather data from APIs for any location on Earth including over 200,000 cities!

![Imgur](https://i.imgur.com/NxzPH5C.png)

## Features

1. Search cities by its name

2. Units of measurement: `standard`, `metric` and `imperial` units are available

3. Current local time and date

4. Temperatures and humidity

5. Wind speed and direction

6. Sunrise and sunset times

## Installation

1. `git clone https://github.com/phucprime/weather.git`

2. `cd weather`

3. `yarn install`

4. Log-in to [openweathermap.com](https://openweathermap.org/)

5. Create an API key

6. `cp .env.example .env.local`

7. Paste API key for `OPENWEATHER_API_KEY` variable

>It will be used in `https://api.openweathermap.org/data/2.5/weather?q={cityName}&appid={API_KEY}`
>
>If you do not see some of the parameters in your API response it means that these weather phenomena are just not happened for the time of measurement for the city or location chosen. Only really measured or calculated data is displayed in API response.


8. `yarn run dev`

## Contributions

Any feature requests and pull requests are welcome!

## License

APIs via [Open Weather Map](https://openweathermap.org/)

[MIT license](https://choosealicense.com/licenses/mit/)
