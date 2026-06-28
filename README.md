# DILG-RC - Road Clearing Violation Reporting System

## 🏛️ Department of the Interior and Local Government
### Santa Cruz, Laguna - Road Clearing Operations

<p align="center">
<img src="https://img.shields.io/badge/Laravel-11.x-FF2D20?style=for-the-badge&logo=laravel&logoColor=white" alt="Laravel">
<img src="https://img.shields.io/badge/PHP-8.2-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
<img src="https://img.shields.io/badge/Phase-4B_COMPLETED-10b981?style=for-the-badge" alt="Phase 4B">
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

---

## ✨ PHASE 3 COMPLETED FEATURES

### 🔐 Phase 3A - Authentication & Role-Based Access
- ✅ Secure login system with role validation
- ✅ DILG Admin role: Full monitoring access across all barangays
- ✅ Barangay Staff role: Restricted to assigned barangay only
- ✅ Middleware protection for routes and data
- ✅ 27 test accounts (1 DILG Admin + 26 Barangay Staff)

### 📊 Phase 3B - DILG Admin Analytics Dashboard
- ✅ DILG-wide violation statistics overview
- ✅ Total reports across all 26 barangays
- ✅ Violation type distribution
- ✅ Status summary with percentages
- ✅ Top performing barangay highlight
- ✅ Most recurring violation identification
- ✅ Monthly trend analysis (last 6 months)
- ✅ Resolved vs Pending comparison

### 🏘️ Phase 3C - Barangay Transparency Analytics
- ✅ Barangay-specific violation statistics
- ✅ Resolution rate and performance metrics
- ✅ Status distribution charts
- ✅ Violation type breakdown by barangay
- ✅ Recent actions taken table
- ✅ Response transparency summary
- ✅ Average response time tracking
- ✅ Only shows data for assigned barangay (Barangay Staff)

### 🏆 Phase 3D - Barangay Performance Ranking
- ✅ Comprehensive performance ranking table
- ✅ All 26 Santa Cruz barangays listed
- ✅ Performance score calculation (0-100)
- ✅ Resolution rate percentage
- ✅ Average response time (hours)
- ✅ Total/Verified/Resolved/Pending counts
- ✅ Rating system: Excellent, Good, Needs Improvement, Critical, No Data
- ✅ DILG Admin only access

### 📅 Phase 3E - Status Transparency Timeline
- ✅ Complete status change history for each report
- ✅ Timeline visualization with colored status badges
- ✅ Action taken documentation
- ✅ Personnel assignment tracking
- ✅ Timestamp for each status update
- ✅ Remarks and notes system
- ✅ Visual status indicators
- ✅ Supports all statuses: Submitted → For Verification → Verified → Assigned → In Progress → Action Taken → Resolved/Closed
- ✅ Rejection flow: Submitted → For Verification → Rejected

### 📄 Phase 3F - Printable Auto-Generated Reports
- ✅ Official government document format
- ✅ DILG-wide summary report (DILG Admin only)
- ✅ Barangay-specific summary report
- ✅ Professional print CSS (hides sidebar/buttons)
- ✅ Official DILG header with logo
- ✅ Summary statistics cards
- ✅ Violation type summary tables
- ✅ Status summary with percentages
- ✅ Top performing barangay highlight
- ✅ Barangay needing attention callout
- ✅ Recent actions taken table
- ✅ Signature section (Prepared by / Noted by)
- ✅ System-generated disclaimer note
- ✅ Export placeholders (CSV/PDF) for Phase 17
- ✅ Print button with browser print dialog

### 🧹 Phase 3G - Final Phase 3 Verification
- ✅ All routes verified and accessible
- ✅ Role-based access properly enforced
- ✅ Middleware protection confirmed
- ✅ Layouts consistent (DILG yellow/gold theme)
- ✅ Sidebar menus correct for each role
- ✅ Dashboard cards functioning
- ✅ Analytics pages working
- ✅ Performance ranking operational
- ✅ Status timelines displaying correctly
- ✅ Printable reports generating properly
- ✅ Export placeholders showing correct messages
- ✅ UI consistency maintained throughout
- ✅ No broken links or routes
- ✅ Dummy data cleaned (road clearing violations only)
- ✅ README.md updated with Phase 3 completion

### 🗺️ Phase 4B - GIS Boundary Integration
- ✅ Leaflet.js interactive map integration (local installation via npm)
- ✅ OpenStreetMap tile layer
- ✅ GeoJSON boundary file support (public/gis/boundary.geojson)
- ✅ Santa Cruz, Laguna barangay boundaries display
- ✅ Clickable barangay popups with names
- ✅ Auto-fit map to boundary layer
- ✅ Intelligent barangay name detection from GeoJSON properties
- ✅ Gold boundary styling with hover effects
- ✅ Map legend with future features preview
- ✅ Boundary information sidebar
- ✅ Graceful handling if GeoJSON file is missing
- ✅ Role-aware layout (DILG Admin and Barangay Staff access)
- ✅ Professional DILG yellow/gold theme
- ✅ Production ready: All Leaflet assets stored locally (no CDN dependency)
- ✅ Foundation for Phase 4C (GPS detection) and Phase 4D (markers & clustering)

---

## 🎯 CURRENT SYSTEM STATUS

**✅ Phase 3 COMPLETE** - All transparency, analytics, authentication, ranking, timeline, and printable report features are fully functional and verified.

**✅ Phase 4B COMPLETE** - GIS Boundary Integration with Leaflet.js interactive map displaying Santa Cruz, Laguna barangay boundaries from boundary.geojson.

### System Architecture

**Roles:**
- **DILG Admin** - Read-only monitoring access across all 26 barangays
- **Barangay Staff** - Full update permissions for assigned barangay only

**26 Santa Cruz, Laguna Barangays:**
Alipit, Bagumbayan, Bubukal, Calios, Duhat, Gatid, Jasaan, Labuin, Malinao, Oogong, Pagsawitan, Palasan, Patimbao, Poblacion I, Poblacion II, Poblacion III, Poblacion IV, Poblacion V, San Jose, San Juan, San Pablo Norte, San Pablo Sur, Santisima Cruz, Santo Angel Central, Santo Angel Norte, Santo Angel Sur

**Authentication:**
- Login Route: `/login`
- 27 Test Accounts (see `ACCOUNTS_CREDENTIALS.md`)
- All passwords: `password` (for proposal/testing)

**DILG Admin Routes:**
- `/dilg-dashboard` - DILG-wide analytics dashboard
- `/violation-reports` - All violation reports (read-only)
- `/violation-reports/{id}` - Individual report details
- `/barangay-performance` - Performance ranking table
- `/analytics-reports` - DILG-wide analytics & reports
- `/analytics-reports/print` - Printable DILG-wide report
- `/ai-analytics` - Placeholder for Phase 4A
- `/gis-map` - **GIS Boundary Map (Phase 4B ✅)**
- `/profile` - Profile page placeholder

**Barangay Staff Routes:**
- `/barangay/{barangay}/dashboard` - Barangay dashboard
- `/barangay/{barangay}/incoming-reports` - New reports for verification
- `/barangay/{barangay}/verified-reports` - Verified reports for assignment
- `/barangay/{barangay}/response-tracking` - Track ongoing reports
- `/barangay/{barangay}/analytics-reports` - Barangay analytics
- `/barangay/{barangay}/analytics-reports/print` - Printable barangay report
- `/violation-reports/{id}` - Individual report details (assigned barangay only)
- `/barangay/{barangay}/profile` - Profile page placeholder

**Violation Types (Road Clearing Only):**
- Illegal Parking
- Road Obstruction
- Sidewalk Obstruction
- Vending Obstruction
- Construction Materials Obstruction
- Encroachment
- Abandoned Vehicle
- Illegal Structure
- Waste/Garbage Obstruction
- Other Road Clearing Violation

**Status Flow:**
1. Submitted (citizen report)
2. For Verification (barangay review)
3. Verified (valid violation confirmed) OR Rejected (invalid/duplicate)
4. Assigned (personnel assigned)
5. In Progress (action being taken)
6. Action Taken (enforcement completed)
7. Resolved (violation cleared)
8. Closed (case closed)

---

## 🗺️ GIS BOUNDARY SETUP

### 📍 Place boundary.geojson File

**Required location:**
```
public/gis/boundary.geojson
```

**What to include:**
- Santa Cruz, Laguna barangay boundary polygons
- GeoJSON format with Feature Collection
- Properties should include barangay name (see supported property keys below)

**Supported barangay name property keys:**
The system intelligently detects barangay names from these GeoJSON properties (in order of priority):
- `name`, `Name`, `NAME`
- `barangay`, `Barangay`, `BARANGAY`
- `brgy`, `Brgy`, `BRGY`
- `BGY_NAME`, `BRGY_NAME`
- `ADM4_EN`, `ADM4_NAME`
- `NAME_4`, `NAME_3`

**Access the GIS Map:**
```
http://127.0.0.1:8000/gis-map
```

**If boundary.geojson is missing:**
- The map will display a friendly warning message
- The page will not crash
- Santa Cruz, Laguna center point will be shown as fallback

**Map Features:**
- ✅ Interactive Leaflet.js map
- ✅ OpenStreetMap base layer
- ✅ Gold boundary outlines (DILG theme)
- ✅ Clickable barangay popups
- ✅ Hover effects on boundaries
- ✅ Auto-fit to boundary layer
- ✅ Map legend
- ✅ Boundary information sidebar
- ✅ Loading indicator
- ✅ Error handling

---

## 🚀 NEXT PHASE

### Phase 4C - GPS-Based Barangay Detection

**Planned Features:**
- 📍 Point-in-Polygon GPS verification
- 🎯 Automatic barangay assignment from GPS coordinates
- 🗺️ GPS validation using boundary.geojson
- 📱 Mobile app GPS integration foundation
- 🔍 Coordinate-to-Barangay API endpoint

### Phase 4D - Report Markers & Clustering

**Planned Features:**
- 📍 Report markers on GIS map
- 🔍 Report clustering for better readability
- 🔥 Violation hotspot heatmaps
- 🏢 Barangay office markers
- 📊 Office recommendation based on proximity
- 🗺️ Filter reports by type/status on map

**NOT Included in Phase 4:**
- NLP/Machine Learning (Phase 5+)
- Computer Vision (Phase 5+)
- Dataset Training (Phase 5+)
- Real-time Notifications (Phase 6+)
- Public Reporting Portal (Phase 7+)

---

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
