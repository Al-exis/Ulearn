# Ulearn

Ulearn is a new concept platform which aims at connecting people that want to teach with those that want to learn. At the moment it has only been materialized in the form of a mobile app, and we expect to develop soon a website and other forms of online presence. Here we present the hypothetical features as well as the first prototype of the app.

## Motivations

Cooking is healthy, culturally rewarding, and above all funny. Yet, many people don't cook and have never learnt how to, either because it is not part of their culture and they never had the opportunity to, or because they simply don't have time for it.
As a team of cooking-lover engineers attending the Singapore Nanyang Technopreneurship Center *Startathon*, we decided to tackle this problem by developing an innovative and affordable solution: Smart Chef.

## Concept

A smartphone app guides the user through several recipes, coming from different parts of the world and having diverse levels of difficulty. Step by step, the user receives feedback about his or her cooking technique in a fun and interactive way, allowing him or her to quickly be able to cook delicious food.

A small device is attached to the cooking pan or pot, and measures several parameters related to the food being cooked, such as temperature, CO2, or vibrations. This data is sent over Bluetooth to the smartphone, which analyses them, and convert them into an intuitive feedback. The device is removable and discreet, so it does not bother the user.

<p align="center">
	<img src="doc/Technical_slide.jpg" width="750"/>
</p>

## Hardware Device

Main features:
* Three sensors measuring temperature, CO2 concentration, and acceleration
* Status LEDs
* Battery powered
* Optimized power consumption: BLE communication, low-power microcontroller, carefully selected sensors...

Early prototype:
* Arduino UNO
* Dallas DS18B20 thermocouple 
* InvenSense MPU-6050 IMU
* Bluetooth HC-05 module
* Green, Orange and Red LEDs controlled by the smartphone

## Game App

Main features:
* Various recipes (levels) accessed on a remote database
* Online account management
* Score and achievments sharing with friends
* Real-time communication with the device
* Feedback such as: "increase/decrease temperature", "give a stir" or "food is burning"

The early prototype was developed with Unity game engine and featured one full recipe. The Android version is already available for feedback on [Google Play Store](https://play.google.com/store/apps/details?id=com.SevaneGames.SmartChef).

<p align="center">
	<img src="doc/App_ui_2.png" height="400">
	<img src="doc/App_ui_1.png" height="400">
</p>

## What comes next

Additional features that could potentially be implemented:
* Allow the user to rate recipes and suggest improvements, use machine learning to update the database based on the score given by many users
* Advanced feedback to the user using fuzzy logic
* Automatic ingredients ordering to local groceries with home delivery

## Awards

This project won the third place of the Singapore Nanyang Technopreneurship Center *Startathon*, a 32-hour event focusing on idea development and implementation.

## Credits

* Software development: Alexis Pomares Pastor and Timoté Vaucher
* Hardware and firmware development: Paul-Edouard Sarlin
* Prototype design: Ignacio Albert Smet
* Business plan and speech: Jacques Weniger
