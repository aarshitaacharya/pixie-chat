# Pixie Chat

Pixie Chat is a real-time chat application designed for local development, allowing users to engage in instant conversations with others. Built using HTML, CSS, JavaScript, and PHP, Pixie Chat offers a seamless chatting experience within a familiar web environment. Utilizing XAMPP and MySQL via PHPMyAdmin, Pixie Chat provides a secure and efficient platform for communication.

# Link to demo
[![Watch the demo](https://i9.ytimg.com/vi/jgQ431y84WA/mqdefault.jpg?v=68473227&sqp=CIjjnMIG&rs=AOn4CLCvIefmv1r_ZHZ4Z1mK7AjFgpi6IA)](https://youtu.be/jgQ431y84WA)



## Features

- **User Authentication**: Secure login/signup functionality with credentials handling.
- **Real-time Messaging**: Instant messaging feature for seamless communication.
- **User Dashboard**: Display of user activity status (active/offline).
- **Integration with XAMPP and MySQL**: Utilize local server and database for development.
- **Intuitive Interface**: User-friendly design for an enjoyable chatting experience.

## Configuration
Before running Pixie Chat, configure the database connection settings in the config.php file. Update the following variables with your MySQL database credentials:

```php
$hostname = "localhost"; // Hostname (usually "localhost" for local development)
$username = "root"; // MySQL username
$password = ""; // MySQL password (leave blank for no password)
$dbname = "chat"; // Database name
```
Once updated, save the config.php file.

## Installation
Follow these steps to set up Pixie Chat on your localhost:

Clone the repository to your local machine:

```bash
git clone https://github.com/aarshitaacharya/pixie-chat.git
```
Move the cloned directory to the 'htdocs' directory in your XAMPP installation path:

```bash
Windows: C:\xampp\htdocs
Linux: /opt/lampp/htdocs
```
Import the provided MySQL database dump (chat.sql) into your MySQL database.

Open a web browser and navigate to http://localhost/pixie-chat/index.php.

## Usage
Start your XAMPP server and ensure MySQL is running.

Register for a new account or log in with existing credentials.

Enjoy real-time chatting with other users!

## Contributing
Contributions are welcome! If you encounter any bugs or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
