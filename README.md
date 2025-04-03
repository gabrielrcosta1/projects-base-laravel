# Laravel Base Project

This repository serves as a base for Laravel projects, providing a pre-configured setup to streamline the development process.

## 🚀 Features

-   Laravel latest version pre-installed
-   Basic folder structure ready
-   Pre-configured environment settings
-   Essential packages included
-   Repository and service interfaces for better code organization

## 📦 Included Packages

This base project comes with the following tools and libraries pre-installed:

-   **Pest**: A testing framework that provides a clean and expressive way to write tests in Laravel.
-   **PHPStan**: A static analysis tool that helps detect potential issues in your codebase.

## 📦 Installation

To start a new project using this base, run the following command:

```bash
composer create-project gabrielrcosta1/projects-base-laravel my-new-project
```

Then, navigate into your new project folder and set up the environment:

```bash
cd my-new-project
cp .env.example .env
php artisan key:generate

# Run migrations (if necessary)
php artisan migrate
```

## 🛠 Customization

You can modify this base project according to your needs:

-   Update `composer.json` with required dependencies
-   Modify `.env` for environment-specific settings
-   Add your business logic to the `app/` directory

## 🤝 Contributing

Feel free to fork this repository and customize it to your workflow. Contributions are welcome!

## 📜 License

This project is open-source and available under the MIT License.
