# Shree Laxmi Amul Shopiee - Web Project Portfolio

![Amul Logo](PHP%20website/images/Amul.jpg)

## Live Websites
- **HTML Version:** [https://shreelaxmiamul.netlify.app/](https://shreelaxmiamul.netlify.app/)
- **PHP Version:** [https://shreelaxmiamul.fast-page.org](https://shreelaxmiamul.fast-page.org)
- **Login Page:** [https://sign-in-pagee.netlify.app/](https://sign-in-pagee.netlify.app/)
- **Alternate Links For PHP:**
  - [https://shreelaxmiamul.fast-page.org](https://shreelaxmiamul.fast-page.org)  
  - [http://shreelaxmiamul.byethost33.com](http://shreelaxmiamul.byethost33.com)
- **Admin Panel:** [http://localhost/Amul-Shop-AdminPanel](http://localhost/Amul-Shop-AdminPanel) (Local Development)

## Project Overview
This project demonstrates a comprehensive web development portfolio for "Shree Laxmi Amul Shopiee," an official Amul outlet located in Pachmarg, Maharashtra. The project showcases static HTML, dynamic PHP implementations, a user authentication system, and an admin panel for managing website interactions.

## Components

### 1. HTML Shop Website (Static Version)
A responsive static website built with HTML, Bootstrap 5, and CSS animations hosted on Netlify.

**Features:**
- Responsive design optimized for mobile and desktop devices
- Interactive product catalog with dynamic filtering system
- Animated UI elements using Animate.css library
- Floating ice cream animation background for visual appeal
- Product categorization with interactive tabs
- Optimized images and assets for fast loading

**Pages:**
- Home (Landing page with hero section and featured products)
- About Us (Information about the store and its history)
- Products (Comprehensive catalog with filtering options)
- Gallery (Visual showcase of products and store)
- Contact Us (Contact form and information)

### 2. PHP Website (Dynamic Version)
An enhanced version of the website with server-side functionality, hosted on multiple platforms for reliability.

**Additional Features:**
- Dynamic content rendering using PHP
- Includes system with reusable header and footer components
- Server-side form handling for the contact page
- Improved carousel with advanced features
- Mobile-optimized performance enhancements
- WhatsApp integration for direct messaging
- FSSAI certification display
- Detailed nutritional information for products

**Technical Improvements:**
- Modular code structure with PHP includes
- Enhanced image loading with preloading for critical assets
- Improved responsive behavior across all device types
- Advanced animations with better performance

### 3. User Registration System
A standalone signup page with modern design and interactive elements.

**Features:**
- Clean, responsive form design with two-column layout on larger screens
- Client-side form validation
- Animated background with floating elements
- Subtle animations for form elements
- Modern UI with FontAwesome icons
- Smooth gradient animation for background

### 4. Admin Panel
A complete PHP-based administrative interface for managing website interactions.

**Features:**
- Secure login system with role-based access control (Admin and Guest roles)
- Dashboard with statistics and recent activity overview
- Contact messages management with detailed views
- Product enquiries management with priority indicators
- User management system (Admin only)
- Admin tools for database operations (Admin only)
- Data export functionality to CSV format (Admin only)
- Responsive design built with Bootstrap 5
- Interactive data tables with sorting, searching, and pagination
- Secure session management and SQL injection protection

## Technologies Used

### Frontend:
- HTML5
- CSS3 with custom animations
- Bootstrap 5.3.2 framework
- JavaScript for interactive elements
- Animate.css and AOS (Animate On Scroll) libraries
- FontAwesome and Bootstrap Icons
- Custom background animations and effects
- Responsive design principles

### Backend:
- PHP 7.4+ for server-side functionality
- MySQL/MariaDB for database management
- Form handling and data processing
- Component-based architecture with includes
- Session management for user authentication
- Prepared SQL statements for security

### Deployment:
- Netlify for static HTML website and login page
- CakeTech Web Services, Fast-Page, and Byethost for PHP version
- XAMPP for local development environment
- GitHub for version control

## File Structure

```
Diploma-ITR/
│
├── Shop Website/                  # HTML Static Version
│   ├── index.html                 # Home page
│   ├── about.html                 # About page
│   ├── products.html              # Products catalog
│   ├── gallery.html               # Gallery page
│   ├── contact.html               # Contact page
│   ├── style.css                  # Main stylesheet
│   └── images/                    # Images folder
│
├── PHP website/                   # PHP Dynamic Version
│   ├── index.php                  # Home page
│   ├── about.php                  # About page
│   ├── products.php               # Products catalog
│   ├── gallery.php                # Gallery page
│   ├── contact.php                # Contact page
│   ├── enquiry.php                # Product enquiry form
│   ├── faq.php                    # Frequently asked questions
│   ├── terms.php                  # Terms of service
│   ├── privacy-policy.php         # Privacy policy
│   ├── nutritional-info.php       # Nutritional information
│   ├── header.php                 # Common header component
│   ├── footer.php                 # Common footer component
│   ├── .php-preview-router.php    # Development router for PHP preview
│   ├── LICENSE                    # License information
│   ├── README.md                  # PHP version documentation
│   ├── css/                       # Organized CSS directory
│   │   ├── common.css             # Shared styles
│   │   ├── color-fixes.css        # Color correction styles
│   │   ├── animation-fixes.css    # Animation optimization
│   │   ├── mobile-fixes.css       # Mobile responsiveness
│   │   ├── floating-animation.css # Background animations
│   │   ├── layouts/               # Layout-specific styles
│   │   │   └── header-footer.css  # Header and footer styles
│   │   ├── pages/                 # Page-specific styles
│   │   │   └── [page-specific CSS files]
│   │   └── compatibility/         # Compatibility fixes
│   │       └── infinity-compatibility.css # InfinityFree hosting fixes
│   ├── js/                        # JavaScript files
│   │   ├── animations.js          # Animation scripts
│   │   ├── common.js              # Common functionality
│   │   ├── floating-background.js # Background animation
│   │   ├── icecream-bg.js         # Ice cream background elements
│   │   └── main.js                # Main site scripts
│   └── images/                    # Images folder
│
├── Log in page/                   # User Registration
│   ├── index.html                 # Sign-up form
│   └── style.css                  # Form stylesheet with animations
│
└── Amul-Shop-AdminPanel/          # Administrative Interface
    ├── config/                    # Configuration files
    │   └── database.php           # Database connection settings
    ├── includes/                  # Common components
    │   ├── session.php            # Session management
    │   ├── header.php             # Common header
    │   └── footer.php             # Common footer
    ├── index.php                  # Redirect to login
    ├── login.php                  # Login page
    ├── auth.php                   # Authentication handler
    ├── logout.php                 # Logout handler
    ├── dashboard.php              # Main dashboard
    ├── contact_messages.php       # Contact messages management
    ├── product_enquiries.php      # Product enquiries management
    ├── user_management.php        # User management (Admin only)
    ├── admin_tools.php            # Admin tools (Admin only)
    ├── admin_actions.php          # AJAX handler for admin operations
    ├── export.php                 # CSV export functionality
    └── README.md                  # Admin panel documentation
```

## Setup & Deployment Instructions

### Local Development:
1. Clone or download this repository
2. For HTML version:
   - Open any HTML file in a modern browser to view
   - No server required
3. For PHP version:
   - Set up a local PHP server (XAMPP, WAMP, or MAMP)
   - Place files in the server's web directory
   - Access through localhost
4. For Admin Panel:
   - Install XAMPP with Apache and MySQL
   - Copy "Amul-Shop-AdminPanel" to XAMPP htdocs directory
   - Create a MySQL database named "amul" with required tables
   - Access through http://localhost/Amul-Shop-AdminPanel

### Deployment:
- **HTML Files & Login Page:** 
  - Deploy to Netlify by connecting to your GitHub repository
  - Alternatively, use drag-and-drop upload through Netlify's web interface
  - Current deployment: https://shreelaxmiamul.netlify.app/

- **PHP Version:** 
  - Upload to PHP-enabled hosting services via FTP
  - Current deployments:
    - [https://shreelaxmiamul.fast-page.org](https://shreelaxmiamul.fast-page.org)
    - [http://shreelaxmiamul.byethost33.com](http://shreelaxmiamul.byethost33.com)

## Browser Compatibility
- Google Chrome (recommended)
- Mozilla Firefox
- Apple Safari
- Microsoft Edge
- Opera

## Admin Panel Access

### Login Credentials
- **Admin User:** 
  - Username: `om`
  - Password: `om27031980`
  - Role: Full access to all features
- **Guest User:**
  - Username: `guest`
  - Password: `1234`
  - Role: View-only access

## Future Enhancements
- Integration of user authentication with the main website
- Online ordering functionality with shopping cart
- Product search feature with advanced filtering
- Payment gateway integration for online purchases
- Mobile app development using the same design principles
- Customer accounts with order history
- Real-time stock updates

## Credits
- **Design & Development:** Om Pradip Patil
- **Project Supervisor:** Pradip Laxuman Patil
- **Store Management:** Shree Laxmi Amul Shopiee
- **Images:** Amul product catalog and custom photography
- **Icons:** FontAwesome, Bootstrap Icons
- **Animations:** Animate.css and custom CSS animations

## Store Information
- **Official Name:** Shree Laxmi Amul Shopiee
- **Address:** 210, pachmarg road, opp. police station, Delwadi, Kudan, Maharashtra 401502
- **Phone:** +91-9028915605, +91-9890377098

## Contact Developer
- **Name:** Om Pradip Patil
- **Email:** [omspradippatil@gmail.com](mailto:omspradippatil@gmail.com)
- **Phone:** +91-9890377098
- **LinkedIn:** [Om Pradip Patil](https://www.linkedin.com/in/om-pradip-patil/)

## Project History
- **December 2023:** Initial launch of all three versions
- **January 2024:** Updated with performance improvements and mobile optimizations
- **February 2024:** Added detailed product catalog and enhanced animations
- **March 2024:** Implemented PHP version with dynamic components
- **June 2024:** Added Admin Panel for website management

---

© 2024 Shree Laxmi Amul Shopiee. All Rights Reserved.

*Note: This is a student project created as part of a diploma in Information Technology. Not affiliated with the official Amul brand.*

