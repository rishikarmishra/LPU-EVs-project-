# LPU EV's - Sign In/Sign Up Portal

This project is a web-based Sign In/Sign Up portal designed for LPU EV's, providing a user-friendly interface for users and drivers to sign in or register their accounts. This portal includes forms for user registration and login with specific fields, and utilizes PHP for server-side form handling.

## Project Structure

- **signin.html** - Main HTML file with the structure for the Sign In/Sign Up forms.
- **lpuev.sql** - SQL file to set up the database schema.

## Features

- **Sign Up**: Users can create a new account by providing their username, email, registration number, and password.
- **Sign In**: Existing users can log in by entering their username, password, and selecting their role (User or Driver).
- **Toggle Forms**: Smooth toggle between Sign In and Sign Up forms for ease of use.
- **Role Selection**: Users have the option to sign in as either "User" or "Driver."
- **Forgot Password**: Placeholder for future password recovery functionality.

## Getting Started

### Prerequisites

- PHP and a web server (e.g., Apache)
- MySQL or a compatible database for user data storage

### Installation

1. Clone this repository or download the source files.
2. Import the `lpuev.sql` file into your MySQL database to set up the required tables.
3. Place the files in your web server directory and ensure PHP is enabled.
4. Update the database connection details in the PHP files if necessary.

### Usage

- Open `signin.html` in your browser.
- Toggle between Sign In and Sign Up modes using the buttons provided.
- Fill in the forms and submit to test user registration and login functionality.

## Technologies Used

- **HTML/CSS**: For structuring and styling the user interface.
- **JavaScript**: For form toggle functionality.
- **PHP**: For backend handling of form submissions.
- **MySQL**: For user data storage.

## Future Enhancements

- Implement "Forgot Password" functionality.
- Add user and driver dashboards post-login.
- Enhance security with password encryption and input validation.

## License

This project is licensed under the MIT License.
