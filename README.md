# PHP E-commerce Web Application

This project is a basic e-commerce website developed using PHP and MySQL. It includes features like user registration, product catalog, shopping cart, order management, and admin interface.

## 📁 Features

- User registration and login (`signup.php`, `userpage.php`)
- Homepage with product listings (`homepage.php`)
- Shopping cart functionality (`cartpage.php`)
- Order placement and shipping (`orderpage.php`, `shippingpage.php`)
- Admin panel for managing data (`adminpage.php`)
- Database connection setup (`db_connect.php`)
- Reusable footer (`footer.php`)

## 🛠️ Setup Instructions

### Prerequisites

- Apache server (e.g., XAMPP, WAMP, or LAMP)

### Steps

1. **Clone or download the repository.**
2. **Move project files** to your local server directory (e.g., `htdocs` in XAMPP).
3. **Configure the database:**
   - Create a MySQL database.
   - Import your database schema (if not included, create tables manually as referenced in `db_connect.php`).
   - Update `db_connect.php` with your database credentials.

4. **Run the application:**
   - Start Apache and MySQL from your local server.
   - Open `http://localhost/index.php` in your browser.



