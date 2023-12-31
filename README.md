# Laravel Project - PDF Generator and Excel Import/Export

This Laravel project provides functionality for generating PDF files and importing/exporting data to/from Excel spreadsheets. It demonstrates how to integrate these features into your Laravel application.

## Prerequisites

Before running this Laravel project, ensure that you have the following:

1. PHP installed on your system.
2. Composer installed on your system.
3. Laravel framework installed globally.

## Getting Started

1. Clone the repository to your local machine:

git clone https://github.com/artam01/PDFGenerator-ExportandImportExcel.git
Install project dependencies using Composer:

composer install
Configure the database connection in the .env file:

Rename the .env.example file to .env.
Open the .env file and update the following lines with your database credentials:
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=your-database-name
DB_USERNAME=your-database-username
DB_PASSWORD=your-database-password
Run database migrations:
php artisan migrate
Run the project locally:
php artisan serve
