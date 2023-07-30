# Historic Weather API

![Weather API Logo](https://example.com/weather-api-logo.png)

Unleash the past weather with our Historic Weather API! 🌦️🕰️

## Introduction

Welcome to the Historic Weather API, a powerful Python Flask-based application that allows you to query historical weather data for various weather stations. Dive into the weather records of your favorite locations on specific dates and embrace the elements like never before! ⏳🌡️

## Features

- Retrieve weather data for a specific station on a particular date
- Get all available weather data for a chosen station
- Explore weather records for a station throughout a given year

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Make sure you have the necessary data files in the `Data/data_small/` directory.

## Usage

- Run the application using `python app.py`.
- Access the API via the following endpoints:
    - `/api/v1/<station>/<date>` - Get weather data for a specific station on a particular date.
    - `/api/v1/<station>` - Get all available weather data for a chosen station.
    - `/api/v1/year/<station>/<year>` - Explore weather records for a station throughout a given year.

## Example

To get the weather data for station `10` on date `19881025`, use the following URL:
http://127.0.0.1:5000/api/v1/10/19881025/

## Contributing

We welcome contributions from everyone! Feel free to open issues or submit pull requests to help improve the API.

## License

This project is licensed under the [MIT License](https://opensource.org/license/mit/).

---

Join us in this weather time travel - the coolest way to geek out with climate data! ❄️🔮
