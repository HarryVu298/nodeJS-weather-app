# Node.js Weather App

A simple web application that provides weather information for a specified city using the OpenWeatherMap API. The application is built with Node.js and Express and uses EJS for templating.

## Features

- Retrieve and display current weather information for any city
- Display temperature, weather conditions, and location
- User-friendly interface

## Prerequisites

- Node.js and npm installed on your machine
- OpenWeatherMap API key

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/HarryVu298/nodeJS-weather-app.git
    cd nodeJS-weather-app
    ```

2. Install the dependencies:

    ```bash
    npm install
    ```

3. Create a `.env` file in the root directory and add your OpenWeatherMap API key:

    ```plaintext
    API_KEY=your_openweathermap_api_key
    ```

## Usage

1. Start the application:

    ```bash
    npm start
    ```

2. Open your web browser and navigate to:

    ```
    http://localhost:3000
    ```

3. Enter the name of a city in the input field and click "Get Weather" to see the weather information.

## File Structure

