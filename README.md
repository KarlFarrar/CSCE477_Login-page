# Simple Login Form – Testing Guide

This project contains a basic HTML and JavaScript login form that mimics the structure of a Juice Shop style login page. It includes client-side validation for email and password fields.

## Requirements

- A modern web browser (Chrome, Firefox, Edge, etc.)
- No server or additional software is required

## How to Run

1. Clone the repository: 
``` git clone https://github.com/KarlFarrar/CSCE477_Login-page.git ``` 
2. Click the login.html file to open it in your browser

## Testing the Form

### 1. Empty Fields Test
1. Click **Login** without entering anything.
2. The form should display the error: Both fields are required.


### 2. Invalid Email Test
1. Enter an email without the `@` symbol (example: `testemail.com`).
2. Enter any password longer than 8 characters.
3. Click **Login**.

Expected result: Please enter a valid email address.


### 3. Short Password Test
1. Enter a valid email such as: `test@test.com`
2. Enter a password shorter than 8 characters (example: `12345`).
3. Click **Login**.

Expected result: Password must be at least 8 characters.


### 4. Valid Input Test
1. Enter a valid email such as: `test@test.com`
2. Enter a password with at least 8 characters (example: `password123`).
3. Click **Login**.

Expected result: Login successful (demo)


A browser alert will appear indicating the login was successful.

## Notes

- All validation is performed on the **client side using JavaScript**.
- This form does **not connect to a backend server**.
- It is intended only as a **demonstration of basic input validation**.



