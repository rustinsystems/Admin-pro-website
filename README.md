# 🏢 Admin Professional Platform
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Uptime](https://img.shields.io/badge/Uptime-99.9%25-brightgreen)](https://www.adminprofessional.net)

> **Production web platform for [Admin Professional](https://www.adminprofessional.net/), a corporate administrative consultancy.**

## 📖 Overview
This repository hosts the source code for the **Admin Professional** digital identity. Launched in 2022, this platform transformed a local consultancy into a digitally accessible brand. It serves as the central hub for client inquiries, service showcasing, and appointment booking.

Beyond the frontend, this project represents a complete **Digital & Physical Infrastructure** solution. The web deployment is tightly coupled with a physical office reliability strategy, ensuring that while the website captures leads 24/7, the physical office remains online to process them via dedicated UPS and emergency power systems.

## 🚀 Key Features
* **High-Performance Frontend:** Built with **React** for instant page loads and seamless navigation.
* **Interactive UI:** Utilizes **Framer Motion** for professional, smooth entrance animations that guide user attention.
* **Responsive Design:** Fully mobile-optimized layout using **Bootstrap** grid systems.
* **Enterprise Email:** integrated with **Zoho Mail** for custom domain (`@adminprofessional.net`) communications.
* **Continuous Deployment:** Automated CI/CD pipelines via **Netlify** (configured via `netlify.toml`).

## 🛠️ Technical Stack

| Category | Technology |
| :--- | :--- |
| **Framework** | React.js (Bootstrapped via CRA) |
| **Styling** | Bootstrap 5, Custom CSS3 |
| **Animation** | Framer Motion |
| **Routing** | React Router |
| **Deployment** | Netlify |
| **DNS/Mail** | Zoho Mail API |

## 🔋 Infrastructure Context (Rustin Systems)
This project was delivered as part of a comprehensive "Office Resilience" package by **Rustin Systems**:
1.  **Digital Availability:** 99.9% Uptime via redundant CDN hosting.
2.  **Physical Availability:** Office Wi-Fi and Workstations protected by dedicated **UPS (Uninterruptible Power Supply)** units to bridge grid failures (Load Shedding).
3.  **Emergency Lighting:** Automated LED failover systems installed for continued operations during outages.

## 💻 Local Development

To run this project locally:

```bash
# 1. Clone the repository
git clone [https://github.com/rustinsystems/Admin-pro-website.git](https://github.com/rustinsystems/Admin-pro-website.git)

# 2. Install dependencies
cd Admin-pro-website
npm install

# 3. Start the development server
npm start
