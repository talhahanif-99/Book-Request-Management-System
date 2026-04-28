# Book Request System

A web-based Book Request System designed to streamline the process of requesting and managing books in an organized and efficient way.

---

## Features

- Browse books by category  
- Submit book requests  
- User authentication (login/logout)  
- Admin panel to manage requests  
- Approve or reject requests  
- Organized database management  

---

## Tech Stack

- Frontend: HTML, CSS  
- Backend: PHP  
- Database: MySQL  
- Server: Apache (XAMPP / WAMP)

---

## Project Structure

```

book-request-system/
│── api/                # Backend APIs (fetch, request handling)
│── config/             # Database configuration
│── includes/           # Authentication & reusable components
│── assets/             # CSS, JS, images
│── pages/              # User & admin pages
│── index.php           # Entry point
│── login.php
│── register.php
│── dashboard.php
│── logout.php

````

---

## Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/book-request-system.git
````

---

### 2. Move to Server Directory

Place the project folder inside:

* `htdocs` (for XAMPP)
* `www` (for WAMP)

---

### 3. Setup Database

1. Open phpMyAdmin
2. Create a database (e.g., `book_system`)
3. Import the provided `.sql` file

---

### 4. Configure Database Connection

Edit:

```
config/db.php
```

Update:

```php
$host = "localhost";
$user = "root";
$password = "";
$database = "book_system";
```

---

### 5. Run the Project

Start Apache and MySQL, then open:

```
http://localhost/book-request-system/
```

---

## User Roles

### User

* Register and login
* Browse categories
* Request books

### Admin

* View all requests
* Approve or reject requests
* Manage categories

---

## Contributing

Contributions are welcome. Fork the repository and submit a pull request.
