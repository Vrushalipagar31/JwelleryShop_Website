# JwelleryShop_Website
# Jewellery Shop Website

Welcome to the Jewellery Shop Website project! This repository contains the source code for a full-stack e-commerce website designed for selling jewellery. The project is built using PHP for server-side logic and MySQL for database management.

## Features

- **User Authentication**: Secure login and registration system.
- **Product Management**: Add, edit, and delete products (admin only).
- **Dynamic Product Display**: Showcase jewellery items with details fetched from the database.
- **Shopping Cart**: Add-to-cart functionality with real-time updates.
- **Order Management**: Place and view orders.
- **Responsive Design**: Optimized for all devices.

## Technologies Used

- **PHP**: Backend development.
- **MySQL**: Database management.
- **HTML5**: Structuring the content.
- **CSS3**: Styling and layout.
- **JavaScript**: Interactivity and dynamic features.
- **Bootstrap**: Responsive design framework.

## Getting Started

Follow these steps to set up the project locally:

### Prerequisites

- A local server environment (e.g., XAMPP, WAMP, or MAMP).
- A modern web browser.
- A code editor (e.g., Visual Studio Code).
- Git (optional for cloning the repository).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/jewellery-shop-website.git
   ```

2. Move the project to your server's root directory:
   - For XAMPP: `htdocs` folder.
   - For WAMP: `www` folder.

3. Import the database:
   - Open `phpMyAdmin`.
   - Create a new database (e.g., `jewellery_shop`).
   - Import the `jewellery_shop.sql` file from the `database` folder.

4. Configure the database connection:
   - Open `config.php`.
   - Update the database credentials (e.g., `host`, `username`, `password`, `dbname`).

5. Start your local server and open the website:
   ```bash
   http://localhost/jewellery-shop-website
   ```

## Usage

- **Admin Panel**: Accessible at `/admin` for managing products and orders.
- **Customer Interface**: Browse products, add to cart, and place orders.
- **Database Configuration**: Ensure the `config.php` file has the correct credentials.

## Folder Structure

```
jewellery-shop-website/
├── admin/         # Admin panel files
├── assets/        # Images, CSS, and JavaScript files
├── database/      # Database schema and sample data
├── includes/      # Reusable PHP components
├── index.php      # Homepage
├── config.php     # Database configuration
└── README.md      # Project documentation
```

## Contributing

Contributions are welcome! If you find any bugs or have suggestions for new features, please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Acknowledgments

- Thanks to [Bootstrap](https://getbootstrap.com/) for the responsive design framework.
- Icons from [FontAwesome](https://fontawesome.com/).
- Sample data from [Unsplash](https://unsplash.com/) and other free resources.

---

Thank you for exploring the Jewellery Shop Website project! If you find this repository useful, please give it a star. 🌟

