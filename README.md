# Weather-app-Java
Java-based weather app featuring a user-friendly graphical interface (GUI) that pulls real-time weather data from an external API.
<img width="327" alt="image" src="https://github.com/dypyp/Weather-app-Java/assets/147340179/24d05625-f6f5-4372-9766-353209105b1b">
## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [API Usage](#api-usage)

## Introduction
This Weather App is a simple yet effective tool to get real-time weather information for a given location. It combines the power of Java with external APIs to provide up-to-date data, and it presents the information in an easy-to-understand graphical format.

## Features
* Real-Time Weather Data: Fetches and displays real-time weather information, including temperature, weather condition, humidity, and wind speed.
* User-Friendly GUI: The graphical user interface provides an intuitive and visually appealing way to interact with the application.
* Location-Based Data: Enter a location, and the app will use geolocation data to retrieve weather information specific to that area.
* Dynamic Weather Icons: Icons representing different weather conditions enhance the user experience.
* Error Handling: The app gracefully handles errors such as API connection issues, ensuring a smooth user experience.

## Prerequisites
Before you get started, make sure you have the following:
* Java Development Kit (JDK)

## Installation
Clone this repository to your local machine using:
- git clone https://github.com/your-username/weather-app.git
Compile the Java source code using:
- javac WeatherApp.java WeatherAppGui.java

## Usage
* Run this application using:
* java WeatherAppGui
* The graphical interface will open. Enter the location for which you want to retrieve weather data in the search field and click the search button.
* The application will fetch and display real-time weather data based on the entered location.

## API Usage
This project relies on external APIs to fetch weather data. The primary API used is the Open Meteo API. Please note that you may need to register for an API key and replace it in the code for long-term usage.
