# Weather App - DataOps

## Description

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Installation
- Clone this repo
- On your terminal
    - `cd` to root folder
    - delete data folder
    - setup `.env` with:
        - `PORT` of your choosing
        - `CITY` of your choosing
        - `API_KEY` from openweather
    - `npm i` to install dependencies
    - `node fetchWeather.js` to create/update data folder
    - `node app.js` to start server
- Open browser on `PORT` to see weather and graph

### Using docker

- Open your Docker Desktop
- Make sure you are on the same path as Dockerfile
- On your terminal run:
 - `docker build -t <app-name>:<tag> .` or `docker build -t weather-app .` - to build an image based on the Dockerfile
 - `docker run -p <local-port>:<container-port> <image-name>` or `docker run -p 3000:5000 weather-app` to run a container based on an image


## Tests

We have tests to check if files inside the data folder is correct