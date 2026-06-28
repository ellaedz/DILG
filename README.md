# DILG-RC - Road Clearing Violation Reporting System

## 🏛️ Department of the Interior and Local Government
### Santa Cruz, Laguna - Road Clearing Operations

<p align="center">
<img src="https://img.shields.io/badge/Laravel-11.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
<img src="https://img.shields.io/badge/PHP-8.2-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
<img src="https://img.shields.io/badge/Phase-4B_COMPLETED-10b981?style=for-the-badge">
</p>

---

## 📖 About DILG-RC System

DILG-RC is a comprehensive road clearing violation reporting and monitoring system designed for the Department of the Interior and Local Government (DILG) in Santa Cruz, Laguna. The system enables efficient reporting, verification, tracking, and resolution of road clearing violations across 26 barangays.

### ✅ Key Features

- **🏛️ Role-Based Authentication** - DILG Admin and Barangay Staff with distinct access levels
- **📊 Real-Time Analytics** - Comprehensive violation statistics and performance metrics
- **🏘️ Barangay Performance Ranking** - Transparent ranking system with resolution rates
- **📈 Status Transparency Timeline** - Complete audit trail of report status changes
- **📄 Printable Reports** - Professional auto-generated reports for compliance
- **🎯 Smart Filtering** - Role-based data filtering and barangay assignment
- **📱 Responsive Design** - Mobile-friendly interface with DILG yellow/gold theme
- **🗺️ GIS Boundary Map** - Interactive Leaflet.js map with barangay boundaries


## 🛠️ Installation & Setup

```bash
# Clone repository
git clone <repository-url>
cd DILG-RC

# Install dependencies
composer install
npm install

# Leaflet.js is already installed locally
# No need to download separately - it's in public/js/ and public/css/

# Copy environment file
cp .env.example .env

# Generate application key
php artisan key:generate

# Run migrations
php artisan migrate

# Seed database (includes 27 test accounts)
php artisan db:seed

# Start development server
php artisan serve

# Login credentials (see ACCOUNTS_CREDENTIALS.md)
# DILG Admin: admin@dilg.gov.ph / password
# Barangay Staff: {barangay-slug}@barangay.dilg.gov.ph / password
```

---

## 📚 Documentation Files

- `ACCOUNTS_CREDENTIALS.md` - All 27 test accounts
- `PHASE_3E_COMPLETION_REPORT.md` - Status timeline feature details
- `TESTING_GUIDE.md` - Testing procedures
- `QUICK_ACCESS_GUIDE.md` - Quick reference guide
- `TEST_ALL_LINKS.md` - Link verification results
- `PHASE_4B_COMPLETION_REPORT.md` - GIS boundary integration details
- `LEAFLET_LOCAL_SETUP.md` - Leaflet.js local installation guide

---

## 🎨 UI Theme

**DILG Official Colors:**
- Primary: `#F4C542` (DILG Yellow)
- Secondary: `#D4A017` (DILG Dark Gold)
- Background: `#FFFFFF` (White)
- Text: `#333333` (Dark Gray)
- Success: `#10b981` (Green)
- Warning: `#f59e0b` (Orange)
- Error: `#ef4444` (Red)

**Design Guidelines:**
- Clean, professional government interface
- Notion-style rounded badge buttons
- Font Awesome 6.4.0 icons
- Responsive grid layouts
- Official document formatting for printables
- Times New Roman for printable reports
- Proper page breaks and print CSS

---

## 📄 License

This system is developed for the Department of the Interior and Local Government (DILG) - Santa Cruz, Laguna. Built on Laravel framework which is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

---

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework. You can also check out [Laravel Learn](https://laravel.com/learn), where you will be guided through building a modern Laravel application.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains thousands of video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Laravel Sponsors

We would like to extend our thanks to the following sponsors for funding Laravel development. If you are interested in becoming a sponsor, please visit the [Laravel Partners program](https://partners.laravel.com).

### Premium Partners

- **[Vehikl](https://vehikl.com)**
- **[Tighten Co.](https://tighten.co)**
- **[Kirschbaum Development Group](https://kirschbaumdevelopment.com)**
- **[64 Robots](https://64robots.com)**
- **[Curotec](https://www.curotec.com/services/technologies/laravel)**
- **[DevSquad](https://devsquad.com/hire-laravel-developers)**
- **[Redberry](https://redberry.international/laravel-development)**
- **[Active Logic](https://activelogic.com)**

## Contributing

Thank you for considering contributing to the Laravel framework! The contribution guide can be found in the [Laravel documentation](https://laravel.com/docs/contributions).

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

## Security Vulnerabilities

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
