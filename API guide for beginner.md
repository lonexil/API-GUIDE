 # What is an Api? A Beginner's Guide

 ## 1.Introduction
 Evertime you check weather app or log into Twitter, you are using API without even knowing it.
 An application Programming interface (API) is just a way for systems to talk to each other.

 ## 2. What Is An Api?
 Think of an API like a resturant waiter.
 - You the customer dont go to the kitchen yourself to cook.
 - You tell the waiter what you want ("I want pizza")
 - The waiter goes to the kitchen, gives your order to the chef, and brings back food.

 In this case the API is the waiter

 The kitchen is the system/App

 You are the user/program that needs something

 So API is the messenger that takes your  request, tells the system what to do, and brings back the result.

 ## 3. What does an API do?
 - It connects two things together (like two apps talking)
 - It hides complexities (you dont see the kitchen work)
 - It then delivers the result in a format the computer understands (often JSON or XML)

 For example
 - You open the weather app and see 29 degree
 - Your weather app is not measuring the weather itself
 - It is calling a weather API, which send it the latest temperature.

 ## 4. How does API work?

How does an API work?

- Endpoints = menu sections (e.g., /menu/chicken or /weather/lagos).

- HTTP Methods = actions you want to perform:

- GET → fetch data (like getting your food order).

- POST → add something new (place a new order).

- PUT → update something (ask for extra cheese).

- DELETE → remove something (send back the wrong dish).

- Data format = JSON → structured way computers share info.

Example of JSON format..

`{
  "city": "Lagos",
  "temperature": 29,
  "condition": "Cloudy"
 } `

## 5. Real life application of API

- Weather app: uses OpenWeather API to fetch current temperature for your city.

- Login with Google/Facebook: APIs are used to authenticate you safely without creating new accounts everywhere.