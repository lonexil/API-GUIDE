# What is an API? A Beginner's Guide

## Table of Contents
1. [Introduction](#1-introduction)
2. [What is an API?](#2-what-is-an-api)
3. [What does an API do?](#3-what-does-an-api-do)
4. [How does an API work?](#4-how-does-an-api-work)
5. [Real life application of API](#5-real-life-application-of-api)
6. [Practicing with a Fake API](#6-practicing-with-a-fake-api)
7. [What is an API key?](#7-what-is-an-api-key)
8. [Why APIs are Important](#8-why-apis-are-important)
9. [Conclusion](#9-conclusion)

---

 # What is an Api? A Beginner's Guide

 ## 1.Introduction
 Everytime you check weather app or log into Twitter, you are using API without even knowing it.
 An application Programming interface (API) is just a way for systems to talk to each other.

 ## 2. What Is An API?
 Think of an API like a restuarant waiter.
 - You the customer don't go to the kitchen yourself to cook.
 - You tell the waiter what you want ("I want pizza")
 - The waiter goes to the kitchen, gives your order to the chef, and brings back food.

 In this case,
 - The API is the waiter

 - The kitchen is the system/App

 - You are the user/program that needs something

 So API is the messenger that takes your  request, tells the system what to do, and brings back the result.

 ## 3. What does an API do?
 - It connects two things together (like two apps talking).
 - It hides complexities (you dont see the kitchen work).
 - It then delivers the result in a format the computer understands (often JSON or XML)

 For example
 - You open the weather app and see 29 degree
 - Your weather app is not measuring the weather itself
 - It is calling a weather API, which send it the latest temperature.

 ## 4. How does an API work?

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

## 6. Practicing with a Fake API

A great beginner tool is JSONPlaceholder.

It’s a free fake API for testing and learning.



Examples:
#### GET request - fetch posts
curl https://jsonplaceholder.typicode.com/posts/1

#### POST request - create new data
curl -X POST https://jsonplaceholder.typicode.com/posts \
-H "Content-Type: application/json" \
-d '{"title": "My first API call", "body": "Learning API", "userId": 1}' 

#### PUT request - update data
curl -X PUT https://jsonplaceholder.typicode.com/posts/1 \
     -H "Content-Type: application/json" \
-d '{"id": 1, "title": "Updated title", "body": "Updated body", "userId": 1}'

#### DELETE  - remove data
curl -X DELETE https://jsonplaceholder.typicode.com/posts/1

These examples use JSONplaceholder, a fake API.

....

## 7. What is an API key?

- Think of it as a membership card.

- Free APIs sometimes don’t need it.

 Real-world APIs usually require it to:

- Identify you (who is making the request).

- Prevent abuse (limit how many times you can ask in a day).gi

## 8. Why APIs are Important

- Connect apps (Twitter bots, crypto wallets, Web3 dApps).

- Save time (no need to build everything from scratch).

- Enable innovation (developers combine APIs to create new apps).

## 9. Resources


## 10. Conclusion

APIs are everywhere. From checking the weather to transferring crypto, APIs quietly power the digital world.

Try making your first request with a fake API like JSONPlaceholder or a real one like OpenWeather.



