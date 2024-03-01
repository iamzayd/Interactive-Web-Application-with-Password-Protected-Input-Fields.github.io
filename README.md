# Interactive Web Application with Password-Protected Input Fields

## Deployed website

https://iamzayd.github.io/Interactive-Web-Application-with-Password-Protected-Input-Fields.github.io/

## Overview
This repository contains a web-based application designed to enhance user interactivity and security. The application features a password-protected mechanism that controls access to input fields for mobile numbers and email addresses. It validates the user input to ensure data integrity.

## Features
- **Password-Protected Input Activation**: Input fields are initially disabled and are activated upon entering the correct password.
- **User-Friendly Interface**: The application presents a simple and intuitive interface with input fields for a mobile number and an email address.
- **Input Validation**:
  - **Mobile Number Validation**: Checks if the mobile number consists of 10 digits.
  - **Email Validation**: Ensures the email address follows a standard format.
- **Alerts for Incorrect Format**: If the user enters data in an incorrect format, the application displays an alert message with guidance.
- **Submission Confirmation**: Includes a submit button that triggers a confirmation box, allowing users to confirm their data submission.

## How to Use
1. **Access the Application**: Open the `index.html` file in a web browser.
2. **Enter the Password**: Upon loading, enter the correct password to activate the input fields.
3. **Fill in the Details**: Enter your mobile number and email address in the respective fields.
4. **Submit**: Click the submit button and confirm your submission in the confirmation box that appears.

## Technology Stack
- **HTML**: Structure of the web page.
- **CSS**: Styling of the application.
- **JavaScript**: Interactivity and validation logic.

## Validation Logic
The application uses regular expressions to validate the format of the mobile number and email address:
- **Mobile Number**: The regular expression `/^\d{10}$/` is used to ensure the number consists of 10 digits.
- **Email Address**: The regular expression `/^[^\s@]+@[^\s@]+\.[^\s@]+$/` is used to validate the standard email format.

## Picture of the site

![image](https://github.com/iamzayd/Interactive-Web-Application-with-Password-Protected-Input-Fields.github.io/assets/91972048/7c71b8c7-b1b1-4a66-8442-34e71b1ef9ec)

## Contributing
Feel free to fork this repository and submit pull requests to contribute to this project. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the [MIT License](LICENSE).

## Contact
For any queries or suggestions, please contact [Najeeb Saiyed](officialnajeebsaiyed@gmail.com).
