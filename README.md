# DriveX – Premium Car Showroom 🚗💨

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Pure CSS](https://img.shields.io/badge/JavaScript-Zero%20(100%25%20Pure%20HTML%2FCSS)-success?style=for-the-badge)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

> **College Web Development Assignment Submission**  
> A modern, responsive, and interactive automobile showroom web application built **strictly and exclusively with pure HTML5 and CSS3** (zero JavaScript, zero external frameworks).

---

## 📌 1. Project Overview

**DriveX** is a premier digital car showroom webpage designed to provide an engaging, luxury automotive exploration experience. Visitors can browse popular Indian car models, check sample specifications and ex-showroom prices in Indian Rupees (₹), compare vehicles side-by-side, view detailed technical popups, and submit simulated test-drive bookings with real-time field validation.

The project emphasizes clean, beginner-friendly code, semantic HTML5 structure, responsive layout techniques, and modern UI/UX design principles.

---

## 🎨 2. Website Design & Color Theme

DriveX utilizes a luxury supercar-inspired dark palette:
- **Primary Background:** `#0a0b10` (Deep Carbon Onyx)
- **Secondary Surfaces & Cards:** `#11141d` & `#1c212f` (Studio Slate)
- **Primary Accent:** `#e50914` (Racy Crimson Red) with soft ambient neon glows
- **Typography:**
  - Headings: `Outfit` (Bold, modern geometric sans)
  - Body: `Plus Jakarta Sans` (Crisp, readable UI font)
- **Effects:** Smooth scroll transitions, hover card lift, glassmorphic navigation header, glowing action buttons, and responsive modal dialogues.

---

## 🌟 3. Key Website Sections

| Section | Description |
| :--- | :--- |
| **A. Navigation Bar** | Sticky glassmorphic header with DriveX emblem logo, smooth scrolling nav links, active scroll spy, mobile hamburger drawer, and quick CTA button. |
| **B. Hero Section** | High-impact car showcase banner, bold headline *"Find Your Dream Car"*, subtitle, dual CTA buttons (*Explore Cars* & *Book a Test Drive*), and 3 key guarantee badges. |
| **C. About Showroom** | Introduction to DriveX showroom values: *Quality Vehicles*, *Trusted Service*, *Customer Satisfaction*, and *Professional Support*, plus an animated live statistics counter. |
| **D. Car Models Section** | Interactive category filter tabs (*All Models*, *SUVs*, *Hatchbacks*, *Premium & 4x4*) with **6 featured car cards**: Tata Nexon, Mahindra XUV700, Hyundai Creta, Maruti Suzuki Swift, Toyota Fortuner, and Kia Seltos. |
| **E. Car Features Section** | 6 highlight cards showcasing: Engine Performance, 5-Star Safety Standards, Comfortable Interiors, Modern Infotainment, Class-Leading Efficiency, and Aerodynamic Styling. |
| **F. Compare Cars Section** | Side-by-side responsive comparison table evaluating 3 models across Price, Engine, Transmission, Seating, Mileage, Safety Ratings, and Key Features with horizontal swipe support. |
| **G. Special Offers Section** | 4 promotional cards (*Exchange Bonus up to ₹50,000*, *Festive Season Special*, *Free Accessories Kit*, and *VIP Doorstep Test Drive*) clearly labeled as demo offers. |
| **H. Test Drive Booking** | Interactive booking form with input fields for Full Name, Email, 10-digit Phone (+91), Car Model selector, Preferred Date (future dates only), and Time Slot. Includes client-side validation and receipt confirmation modal. |
| **I. Contact Section** | Showroom address, sample phone numbers, email placeholders, operating hours, interactive map card, and social media connectivity links. |
| **J. Footer** | Comprehensive footer with logo, quick navigation links, vehicle directory links, assignment disclaimer, newsletter subscription, and copyright information. |

---

## ⚡ 4. Interactive JavaScript Features

- **Smooth Navigation Scroll:** Clicking any header or footer link smoothly scrolls to the target section with sticky header offset correction.
- **Scroll Spy:** Automatically highlights the currently active section link in the navigation menu as the user scrolls.
- **Mobile Hamburger Drawer:** Fluid slide-in drawer menu for tablets and mobile devices.
- **Dynamic Category Filtering:** Instant filtering of cars by category without page reloads.
- **Car Details Modal:** Clicking *"View Details"* on any card launches a comprehensive modal showing detailed engine, power, torque, ground clearance, boot space, safety metrics, and color options.
- **One-Click Test Drive Auto-Selection:** Clicking *"Book Test Drive"* on any car card or comparison column automatically selects that exact car in the booking form and smoothly scrolls down to the form.
- **Form Validation:**
  - Full Name: Minimum 3 characters required.
  - Email: Valid regex email pattern verification.
  - Phone: Exactly 10 digits starting with Indian telecom prefix [6-9].
  - Car Model: Compulsory selection.
  - Date: Dynamically restricted to today or future dates (`min` attribute).
  - Time Slot: Mandatory selection.
- **Booking Confirmation Modal:** On valid submission, generates a simulated booking reference ID (e.g. `DX-74921`) and presents a receipt card with full appointment details.
- **Back-to-Top Floating Button:** Appears automatically once scrolled past 350px and smoothly scrolls back to the top of the page.
- **Live Animated Stats Counter:** Showroom statistics count up smoothly when scrolled into view.

---

## 📁 5. Folder Structure

```text
car-showroom-website/
│
├── index.html          # Semantic HTML5 webpage structure
├── style.css           # Modern CSS3 styling, variables, layout, animations & media queries
├── script.js           # Vanilla JavaScript for interactive features and form validation
├── README.md           # Project documentation and submission report
│
└── images/             # High-resolution car visuals
    ├── hero-car.jpg            # DriveX flagship hero car background
    ├── tata-nexon.jpg          # Tata Nexon compact SUV
    ├── mahindra-xuv700.jpg     # Mahindra XUV700 luxury 7-seater SUV
    ├── hyundai-creta.jpg       # Hyundai Creta mid-size SUV
    ├── maruti-swift.jpg        # Maruti Suzuki Swift sporty hatchback
    ├── toyota-fortuner.jpg     # Toyota Fortuner 4x4 SUV
    └── kia-seltos.jpg          # Kia Seltos tech-loaded SUV
```

---

## 💻 6. How to Run the Project Locally

No node packages, build steps, or local server installations are required!

### Option A: Direct Browser Launch (Easiest)
1. Download or clone this repository.
2. Locate the `car-showroom-website` folder on your computer.
3. Double-click `index.html` to open it in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, or Brave).

### Option B: Using VS Code Live Server
1. Open the `car-showroom-website` folder in **Visual Studio Code**.
2. If installed, right-click on `index.html` and click **"Open with Live Server"**.
3. The showroom webpage will automatically launch at `http://127.0.0.1:5500/`.

---

## 🚀 7. GitHub Deployment (GitHub Pages)

This project is 100% static and pre-configured for instant deployment on **GitHub Pages**:

1. **Create a New Repository on GitHub:**
   - Go to [github.com/new](https://github.com/new).
   - Enter repository name: `car-showroom-website` (or `drivex-car-showroom`).
   - Set visibility to **Public**.
   - Leave "Initialize with README" unchecked.
   - Click **Create repository**.

2. **Push the Files via Git Terminal:**
   ```bash
   cd car-showroom-website
   git init
   git add .
   git commit -m "Initial commit - DriveX Premium Car Showroom website"
   git branch -M main
   git remote add origin https://github.com/<YOUR-USERNAME>/<YOUR-REPO-NAME>.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - In your GitHub repository, click on the **Settings** tab.
   - On the left sidebar under *Code and automation*, click **Pages**.
   - Under **Build and deployment > Source**, select **Deploy from a branch**.
   - Under **Branch**, select `main` and folder `/ (root)`.
   - Click **Save**.

4. **Access Your Live Website:**
   - Wait 1–2 minutes for GitHub Actions to complete the deployment.
   - Your live car showroom will be accessible at:  
     `https://<YOUR-USERNAME>.github.io/<YOUR-REPO-NAME>/`

---

## 📱 8. Responsive Design Breakpoints

The website has been thoroughly tested across diverse viewport sizes:
- **Large Desktops & Monitors:** `> 1200px` (Full 3-column and 4-column grids)
- **Laptops & Notebooks:** `992px – 1199px` (Adaptive 2-column grids)
- **Tablets & iPads:** `768px – 991px` (2-column cards, optimized spacing)
- **Mobile Phones (Portrait):** `480px – 767px` (Slide-out navigation drawer, stacked cards, scrollable compare table)
- **Small Screens:** `< 480px` (Compact padding, full-width touch targets)

---

## ⚠️ 9. Academic Disclaimer

This project is created strictly for **educational and college assignment purposes**. 
- Car specifications, fuel figures, and prices in Indian Rupees (₹) are sample demonstration values and do not represent binding dealer offers.
- Contact numbers, email addresses, showroom addresses, and financing figures are simulated demonstration placeholders.
- The test-drive booking form validates input client-side and generates a mock confirmation receipt without submitting data to a remote backend server.

---

## 👨‍💻 10. Student Author & Credits

- **Course:** Web Development & Internet Technologies
- **Assignment:** Responsive Car Showroom Website
- **Technologies:** HTML5, CSS3, Vanilla JavaScript
- **Icons:** Font Awesome 6 (Free)
- **Typography:** Google Fonts (`Outfit` & `Plus Jakarta Sans`)

---

*DriveX – Premium Car Showroom © 2026. All rights reserved.*
