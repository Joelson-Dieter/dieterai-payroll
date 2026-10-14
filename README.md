# Dieterai Payroll Management System

<p align="center">
  <img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="300" alt="Laravel Logo">
</p>

<p align="center">
  <strong>A Modern Payroll Management Solution for Kenyan Businesses</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Laravel-13-FF2D20?logo=laravel&logoColor=white" alt="Laravel 13">
  <img src="https://img.shields.io/badge/PHP-8.3%2B-777BB4?logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/Database-MySQL-4479A1?logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/Status-Under%20Development-orange" alt="Project Status">
</p>

About Dieterai Payroll

**Dieterai Payroll** is a web-based payroll management system developed to simplify employee management, salary administration, payroll processing, statutory deductions, payslip generation, and payroll reporting for businesses in Kenya.

Built using Laravel, PHP, and MySQL, the system aims to provide an organized platform for managing payroll operations, reducing repetitive manual calculations, improving record-keeping, and supporting efficient human resource and financial administration.

The application is designed around Kenyan payroll requirements and supports the administration of statutory deductions, employee earnings, employer contributions, and payroll records.

Key Features

Employee Management
- Maintain employee profiles and employment records.
- Organize employees by departments and positions.
- Manage employee salary information and assignments.
- Track employee-specific payroll adjustments.

Salary Management
- Configure salary structures and basic salaries.
- Manage allowances, earnings, and deductions.
- Maintain salary structure assignment history.
- Support employee-specific adjustments.

Payroll Processing
- Create and manage payroll periods.
- Process payroll runs and calculate employee earnings.
- Calculate deductions and determine net salaries.
- Generate detailed employee payslips.
- Track payroll processing statuses.

Kenyan Statutory Deductions
The system includes modules for administering and calculating applicable Kenyan payroll deductions, including:

- Pay As You Earn (PAYE)
- National Social Security Fund (NSSF)
- Social Health Insurance Fund (SHIF)
- Affordable Housing Levy
- National Industrial Training Authority (NITA) levy
- Pension contributions
- Higher Education Loans Board (HELB) deductions

Statutory calculations and reporting should be verified against the applicable legislation and current requirements before production use.

### Reports and Analytics
- Payroll register reports.
- Payroll history reports.
- Salary reports.
- Employee deduction reports.
- Employer cost reports.
- Payslip records and payroll summaries.

### Security and Administration
- User authentication.
- Role-based access control.
- Company and payroll settings.
- Organized employee and payroll records.

## Technology Stack

| Technology | Purpose |
|---|---|
| Laravel 13 | Backend application framework |
| PHP 8.3+ | Server-side programming |
| MySQL | Relational database |
| Blade | Server-rendered user interface |
| HTML, CSS and JavaScript | Frontend development |
| Laragon | Local development environment |

## Installation and Setup

### Requirements

Ensure your development environment has PHP, Composer, MySQL, and the required PHP extensions installed.

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/dieterai-payroll.git
cd dieterai-payroll
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install dependencies

```bash
composer install
```

### 3. Configure environment variables

```bash
copy .env.example .env
php artisan key:generate
```

Update your `.env` file with your database credentials:

```env
APP_NAME="Dieterai Payroll"
APP_ENV=local
APP_DEBUG=true
APP_URL=http://dieterai-payroll.test

DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=dieterai_payroll
DB_USERNAME=root
DB_PASSWORD=
```

Create the database in MySQL before proceeding. Adjust the credentials to match your environment.

### 4. Run database migrations

```bash
php artisan migrate
```

Run seeders if the project includes them and they are required:

```bash
php artisan db:seed
```

### 5. Start the application

For a standard Laravel development server:

```bash
php artisan serve
```

Open the local URL displayed in your terminal. If using Laragon virtual hosts, configure the domain and project directory accordingly.

## Development Status

Dieterai Payroll is under active development. Features, statutory calculations, reports, and workflows may evolve as the application is tested and improved.

Contributions, suggestions, bug reports, and constructive feedback are welcome.

## Future Enhancements

Planned areas for improvement may include:

- Bulk employee import using Excel templates.
- Employee self-service portal.
- Email notifications and payslip delivery.
- Enhanced dashboards and analytics.
- Automated statutory return preparation.
- Integrations with relevant external services.

## Contributing

To contribute, fork the repository, create a feature branch, implement and test your changes, and submit a pull request describing your improvements.

## Security

If you discover a security vulnerability, avoid publishing sensitive exploit details in public issues. Contact the repository owner privately to coordinate responsible disclosure.

## License

The project's distribution and licensing terms should be defined by its owner. Until a license is added to the repository, all rights remain with the copyright holder, subject to applicable law.

---

**Dieterai Payroll — Simplifying Payroll Management for Kenyan Businesses.**



