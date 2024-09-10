Job Finder and Weather Feature

Description

This project is a simple data feature that combines the power of The Muse API, OpenCage Geocoding API and OpenWeatherMap API to provide job seekers with relevant job listings in a specific location, alongside current weather information for that location. The purpose of this feature is to help users get a quick overview of both available jobs and the weather conditions in a city of their choice, saving time and providing useful insights at a glance.

APIs Used

The Muse API:

Provides job listings, companies, and other career-related data.

It was chosen because it offers a robust set of job data, including filtering by location, allowing users to find relevant job postings in a specific city.

OpenCage Geocoding API:

Converts city names to geographical coordinates (latitude and longitude).

This API was chosen because OpenWeatherMap API uses coordinates to provide weather information. It converts locations into coordinates.

OpenWeatherMap API:

Provides real-time weather data for any geographical location based on coordinates (latitude and longitude).

It was selected for its reliability and detailed weather information, allowing the app to display current weather conditions alongside job listings.

Purpose

The feature allows users to:

Select a location and retrieve job listings in that city.

View the current weather for the selected city, providing additional context for job seekers.

Features

Weather Information: Shows the current weather conditions (e.g., temperature, weather description) in the city selected by the user.

Job Listings: Fetches and displays job listings from The Muse API based on the city input.

Instructions for Use
Input Location: Enter the name of the city or location when prompted.
View Results: The program will first display the current weather in the city, followed by a list of job listings from The Muse API for that location.
