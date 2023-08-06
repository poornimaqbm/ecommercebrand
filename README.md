# E-Grievance Handling Portal in PHP
E-Grievance Handling Portal

Welcome to the e-Grievance Handling Portal! This project is a web-based application built using PHP, MySQL, HTML, and CSS to manage and handle grievances submitted by users. The goal of this portal is to provide a seamless and efficient process for users to raise their concerns and for administrators to resolve them.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

The e-Grievance Handling Portal is a user-friendly and secure platform where individuals can register, log in, and submit their grievances. Administrators can review and address these grievances, ensuring timely resolution. The application promotes transparency and accountability by maintaining a record of each grievance's status and updates.

## Features

- User Registration: Users can sign up for the portal using their email address and a password.

- User Login: Registered users can log in to access their account and submit grievances.

- Grievance Submission: Users can submit their grievances by providing necessary details and selecting the appropriate category.

- Grievance Status Tracking: Users can track the status of their submitted grievances and view any updates made by administrators.

- Administrator Panel: Administrators can log in using their credentials and access the admin panel.

- Grievance Review: Administrators can review the submitted grievances, assign them to specific departments, and provide updates to users.

- Grievance Resolution: Administrators can update the status of grievances as they are resolved.

- Email Notifications: Users receive email notifications for important updates and responses to their grievances.

## Requirements

Before installing the application, make sure you have the following requirements met:

- Web server (e.g., Apache)
- PHP 7.0 or later
- MySQL 5.7 or later
- Composer (Dependency Manager for PHP)

## Installation

1. Clone the repository to your local machine:

```
git clone https://github.com/your-username/e-grievance-handling-portal.git
cd e-grievance-handling-portal
```

2. Install the required dependencies using Composer:

```
composer install
```

3. Create a new MySQL database and import the provided SQL dump file `database.sql`.

4. Configure the database connection settings. Open the `config.php` file located in the `includes` directory and update the following lines with your database credentials:

```php
define('DB_HOST', 'your_db_host');
define('DB_USER', 'your_db_username');
define('DB_PASS', 'your_db_password');
define('DB_NAME', 'your_db_name');
```

5. Set up your web server to point to the `public` directory of the project.

6. Navigate to the URL of your web server in your browser to access the application.

## Usage

1. Users should first register for an account using a valid email address and password.

2. After registration, users can log in using their credentials.

3. Upon logging in, users can submit grievances by providing relevant details and selecting the appropriate category.

4. Administrators can log in using their credentials and access the admin panel.

5. In the admin panel, administrators can review grievances, assign them to respective departments, and update their status as they are resolved.

## Contributing

We welcome contributions to enhance the functionality and features of this e-Grievance Handling Portal. If you wish to contribute, please follow the guidelines in the `CONTRIBUTING.md` file.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

If you have any questions or suggestions regarding the e-Grievance Handling Portal, please contact us at royraman32@gmail.com.

Thank you for using our e-Grievance Handling Portal! We hope it serves its purpose efficiently and effectively.
