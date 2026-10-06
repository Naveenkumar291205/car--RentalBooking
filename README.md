# 🚗 Car Rental Booking Website

> A responsive car and bike rental website concept built with HTML and CSS, featuring vehicle listings, rental search inputs, and a simple reservation-focused interface.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📌 Overview

**Car Rental Booking Website** is a frontend project designed to present rental vehicles and provide users with a simple starting point for searching and renting cars or bikes.

The homepage is built with standard **HTML5 and CSS3** and includes:

- Rental service navigation
- Hero section
- Destination and date inputs
- Car listings
- Bike listings
- Rental pricing
- Rental action buttons
- Service advantages
- Footer section

The project is currently a **frontend/static prototype** rather than a complete booking platform with a connected backend and database.

---

## ✨ Features

### 🏠 Rental Homepage

The main page presents a rental service branded as **RentCar** with a large hero section:

```text
The car is waiting for you
```

It also contains a search area for entering:

- Destination
- Start date
- End date
- Vehicle search

---

## 🚘 Car Fleet

The website displays multiple cars with images, names, specifications, prices, and rental buttons.

Current car listings include:

| Vehicle | Listed Price |
|---|---:|
| Tata Altroz | 2,500 |
| Nissan | 3,000 |
| Volkswagen Polo | 3,500 |
| Suzuki Swift | 2,500 |
| Mahindra | 3,000 |
| Kwid | 3,500 |

Each vehicle card includes:

```text
Vehicle Image
Vehicle Name
Vehicle Description
Price
Rent a Car Button
```

---

## 🏍️ Bike Fleet

A dedicated bike section is included with:

| Vehicle | Listed Price |
|---|---:|
| Hero Xpulse | 2,500 |
| KTM Duke | 3,000 |
| Himalayan | 3,500 |

The same card-based layout is used for the bikes.

---

## 🔎 Rental Search Interface

The homepage includes a basic search component containing:

```text
Destination
Start Date
End Date
Find a Car
```

This provides the visual foundation for a future booking/search system.

> The current repository does not contain backend search logic or database-powered availability checking.

---

## ⭐ Service Advantages

The website highlights three service benefits:

### 24/7 Customer Online Support

```text
Call us Anywhere Anytime
```

### Reservation Anytime

```text
24/7 Online Reservation
```

### Multiple Pickup Locations

```text
250+ Locations
```

These are currently informational UI sections.

---

## 🎨 UI Design

The interface uses a straightforward rental-service layout with:

- Dark navigation bar
- Large hero area
- Vehicle cards
- Orange rental buttons
- Light advantage section
- Dark footer
- Vehicle imagery

The stylesheet uses standard CSS Flexbox for navigation and vehicle-card layouts.

---

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure |
| **CSS3** | Layout and styling |
| **JavaScript** | Linked in `index.html`, but no implementation is currently present in `index.js` |
| **Jinja/Flask references** | Present in separate login/signup files, but backend is not included |

---

## 📂 Project Structure

```text
car--RentalBooking/
│
├── index.html
├── index.css
├── index.js
│
└── images/
    ├── hero xpluse.jpg
    ├── himalayan.jpg
    ├── ktm duke.jpg
    ├── kwid.jpg
    ├── login.html
    ├── mahindra.jpg
    ├── nissan.jpg
    ├── singup.html
    ├── suzuki swift.jpg
    ├── tata altroz.jpg
    └── volkswagen.jpg
```

---

## 📄 File Description

### `index.html`

Main rental homepage containing:

- Navigation
- Hero section
- Search form
- Car listings
- Bike listings
- Advantages section
- Footer

### `index.css`

Contains styling for:

- Header
- Navigation
- Search box
- Fleet sections
- Vehicle cards
- Price styling
- Advantages
- Footer
- Rental buttons

### `index.js`

The file is included by the homepage, but the current repository contains an empty JavaScript file.

### `images/`

Contains the vehicle images used throughout the website.

### `login.html`

Contains a login form using Flask/Jinja-style template expressions.

### `singup.html`

Contains a signup form using Flask/Jinja-style template expressions.

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Naveenkumar291205/car--RentalBooking.git
```

### 2. Navigate Into the Project

```bash
cd car--RentalBooking
```

### 3. Open the Website

Since the main page is a static HTML page, it can be opened directly:

```text
index.html
```

For a better local development experience, use VS Code with **Live Server**.

---

## 💻 Run With VS Code Live Server

1. Open the project in VS Code.
2. Install the **Live Server** extension.
3. Open `index.html`.
4. Right-click the file.
5. Select **Open with Live Server**.

The website will open in your browser.

---

## 🔄 Website Flow

```text
User Opens Website
        │
        ▼
   Landing Page
        │
        ├── Browse Cars
        │
        ├── Browse Bikes
        │
        ├── Select Destination
        │
        ├── Select Rental Dates
        │
        └── Choose Rental Vehicle
```

The current implementation stops at the frontend interaction layer.

---

## 🧱 Current Architecture

```text
Frontend
│
├── HTML
│   └── index.html
│
├── CSS
│   └── index.css
│
├── JavaScript
│   └── index.js
│
└── Assets
    └── Vehicle Images
```

There is currently no connected:

```text
Backend API
Database
Authentication System
Booking Management
Payment Gateway
Admin Dashboard
```

---

## 🔐 Login & Signup Status

The repository contains:

```text
images/login.html
images/singup.html
```

These files use Flask/Jinja expressions such as:

```text
{{ url_for(...) }}
```

and form actions referencing backend routes.

However, no Flask application or server-side authentication implementation is present in the repository structure currently available.

Therefore, these should be treated as **unfinished backend-integrated templates** rather than a functional authentication system.

---

## 📱 Responsive Design

The current stylesheet provides the basic layout for the website, but the repository does not currently contain a comprehensive responsive breakpoint system.

Recommended improvements include:

- Mobile navigation
- Responsive vehicle grids
- Tablet layouts
- Mobile-friendly search form
- Flexible image sizing
- Responsive typography

---

## 📈 Future Improvements

This project can be developed into a complete rental management platform by adding:

### Booking System

- Vehicle availability checking
- Pickup and return dates
- Booking confirmation
- Rental history
- Booking cancellation

### User Authentication

- Registration
- Login/logout
- Password reset
- User profile
- Booking dashboard

### Backend

A backend such as **Flask, FastAPI, Node.js, or Django** could provide:

```text
Authentication API
Vehicle API
Booking API
User API
Payment API
Admin API
```

### Database

Possible database options:

- MySQL
- PostgreSQL
- MongoDB

### Admin Dashboard

Add an admin system for:

- Vehicle management
- Pricing management
- Booking management
- Customer management
- Availability management
- Revenue reports

### Payment Integration

Future versions could integrate a payment provider for online rental payments.

### UI Improvements

- Modern responsive design
- Vehicle filtering
- Vehicle detail pages
- Search and sorting
- Location selection
- Rental comparison
- Booking summary
- Better animations

---

## 📊 Project Status

| Component | Status |
|---|---|
| Homepage | ✅ Implemented |
| Navigation | ✅ Implemented |
| Car Listings | ✅ Implemented |
| Bike Listings | ✅ Implemented |
| Search UI | ✅ Implemented |
| Rental Buttons | ✅ UI only |
| Pricing Display | ✅ Implemented |
| Advantages Section | ✅ Implemented |
| JavaScript Functionality | ⚠️ Not implemented |
| Authentication | ⚠️ Template files only |
| Backend | ❌ Not included |
| Database | ❌ Not included |
| Real Booking System | ❌ Not included |
| Payment System | ❌ Not included |
| Admin Dashboard | ❌ Not included |

---

## 🎯 Learning Outcomes

This project demonstrates practical experience with:

- Semantic HTML structure
- CSS layouts
- Flexbox
- Web page organization
- Image asset management
- Form UI design
- Card-based interfaces
- Basic rental-platform UX concepts
- Separating page structure and styling

---

## 💼 Portfolio Value

This project is useful as a **frontend mini-project** demonstrating the ability to create a rental-service interface from scratch.

To make it stronger for a full-stack portfolio, the next major step is converting the static interface into a working system with:

```text
React / JavaScript Frontend
        +
Flask / FastAPI Backend
        +
MySQL Database
        +
Authentication
        +
Real Booking Management
```

---

## 👨‍💻 Author

**Naveen Kumar M**

GitHub:  
https://github.com/Naveenkumar291205

---

## 🔗 Repository

https://github.com/Naveenkumar291205/car--RentalBooking

---

## 📄 License

No explicit license file is currently included in the repository.
