🚀 API Test Automation Project - Hotel Booking System

This project demonstrates a functional API Test Automation suite built using Postman. It simulates a real-world scenario of managing hotel bookings through a RESTful API, ensuring data integrity and system reliability through automated scripts.

📌 Project Overview

The primary goal of this project is to automate the end-to-end flow of a booking system. It validates that a user can successfully create a booking and that the system correctly stores and retrieves that specific data.

🛠️ Tech Stack & Tools

Postman: Used for building, organizing, and executing API requests.

JavaScript: Used within Postman "Scripts" to write automated test assertions.

Restful-Booker API: A public API used as the testing environment.

Postman Collection Runner: Used to run the entire test suite in a single click.

✅ Key Testing Scenarios

1. Create Booking (POST)
   
Goal: Verify that the system allows the creation of a new booking.

Assertions: Checks if the status code is 200 OK and ensures a bookingid is returned.

Automation: Captures the bookingid from the response and dynamically saves it as an Environment Variable for future use.

2. Get Booking Details (GET)
   
Goal: Verify that the system retrieves the correct details for a specific ID.

Assertions: Uses the saved bookingid to fetch data and validates that the firstname in the response matches the original input ("Kasun").

Reliability: Ensures the data remains consistent across different API calls.

📊 How to Import and Run

Download: Clone or download the JSON files in this repository.

Import: Open Postman and click the Import button. Select both the Collection and Environment JSON files.

Set Environment: From the top-right dropdown in Postman, select Testing Env.

Run: Open the Collection, click the Run button, and view the automated test results in the Collection Runner.

📸 Proof of Execution

<img width="1918" height="876" alt="image" src="https://github.com/user-attachments/assets/1b4409d1-69b3-4fce-9872-5a344374d33c" />
