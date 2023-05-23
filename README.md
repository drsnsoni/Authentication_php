# PHP Login and Register System

This is a simple login and registration system implemented in PHP using MySQL as the database. The system allows users to register an account with a username and password, and then log in with their credentials.

## Features

- User registration: Users can create an account by providing a username and password.
- Secure password storage: Passwords are hashed using the `password_hash` function to ensure they are securely stored in the database.
- User login: Registered users can log in using their username and password.
- Basic form validation: The system includes basic form validation to ensure required fields are filled and to provide feedback to the user if there are any errors.
- MySQL database: The user information is stored in a MySQL database.

## Prerequisites

- PHP 5.6 or higher
- MySQL database

## Usage

1. Register a new user:
   - Open the `register.php` file in your browser.
   - Fill in the username and password fields in the registration form and click "Register".
   - You should see a success message if the registration was successful.

2. Log in as a registered user:
   - Open the `login.php` file in your browser.
   - Enter the username and password of a registered user and click "Login".
   - You should see a success message if the login was successful.

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
