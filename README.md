# CODTECH-Task-01

**Name:** SHASHANK SATISH MISHRA

**Company:** CODTECH IT SOLUTIONS PVT. LTD

**ID:** CT0806DB

**Domain:** CYBER SECURITY AND ETHICAL HACKING

**Duration:** 3 WEEKS

**Mentor:** NEELA SANTOSH KUMAR

**Overview of the project**

**Project: Password Strength Checker**

**Objective**
The primary objective of this project is to create a Password Strength Checker that helps users assess and improve the security of their passwords. By evaluating a password based on established security criteria, the tool educates users on creating stronger passwords and highlights potential weaknesses. This encourages better security practices, reducing the likelihood of security breaches due to weak passwords.

**Key Features**

Password Input Field:

A user can enter a password in a text field that hides the password as it is typed (using the * symbol).
Password Visibility Toggle:

There is a button that allows the user to toggle the visibility of the password. This button switches between showing and hiding the password when clicked.
Password Strength Check:

A button triggers a function that evaluates the entered password for the following criteria:
Minimum length of 10 characters.
At least one lowercase letter.
At least one uppercase letter.
At least one digit.
At least one special character (e.g., !, @, #, $, etc.).
Feedback on Password Strength:

The application provides real-time feedback on the password's strength. If the password does not meet one or more of the required criteria, a message will be displayed with the corresponding issue in red text.
If the password meets all the requirements, a message indicating the password is strong is displayed in green text.

**How It Works**

The user is prompted to enter a password.
Upon clicking the "Check Strength" button, the application runs a series of checks to validate the password against the defined criteria using regular expressions (re module).
Based on the outcome of the checks, an appropriate message is displayed, indicating whether the password is strong or needs improvement.
The user can toggle between showing and hiding the password using the "Show Password" / "Hide Password" button.

**Components Used**

Tkinter: For creating the window, labels, buttons, and text fields for the GUI.
Regular Expressions (re module): To define patterns for checking the presence of lowercase letters, uppercase letters, digits, and special characters in the password.

**Additional Notes**

The project is intended to help users choose strong passwords, which are essential for ensuring account security.
The password strength checks are customizable, and you could extend the functionality by adding more rules or adjusting the existing ones as needed.

