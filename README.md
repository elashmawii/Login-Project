# PHP Login System

A simple and secure login system built with PHP, MySQL, and PDO.

## Features

- User registration with email
- Secure login with password hashing
- Session management
- Responsive design
- Protection against SQL injection
- Input validation

## Requirements

- PHP 7.0 or higher
- MySQL 5.6 or higher
- Web server (Apache/Nginx)

## Setup Instructions

1. Create a MySQL database and import the database structure:
   ```sql
   mysql -u your_username -p < database.sql
   ```

2. Configure the database connection:
   - Open `config.php`
   - Update the following variables with your database credentials:
     ```php
     $db_user = 'your_username';
     $db_pass = 'your_password';
     ```

3. Place all files in your web server's document root or a subdirectory.

4. Ensure your web server has write permissions for the session directory.

5. Access the application through your web browser:
   ```
   http://localhost/your-directory
   ```

## Security Features

- Passwords are hashed using PHP's password_hash() function
- Prepared statements to prevent SQL injection
- Session management for secure user authentication
- Input validation and sanitization
- CSRF protection through session tokens

## File Structure

- `index.php` - Login page
- `register.php` - Registration page
- `dashboard.php` - User dashboard
- `config.php` - Database configuration
- `login_process.php` - Login form processing
- `register_process.php` - Registration form processing
- `logout.php` - Logout handler
- `database.sql` - Database structure

## License

This project is open-source and available under the MIT License.
⌢䰠杯湩倭潲敪瑣•਍