# Smart Warranty Management System

**A web-based application that helps users digitally manage product warranties — from bill upload to automated expiry reminders.**

![Python](https://img.shields.io/badge/Python-Backend-blue)
![Flask](https://img.shields.io/badge/Flask-Framework-black)
![SQLite](https://img.shields.io/badge/SQLite-Database-lightgrey)
![Gemini](https://img.shields.io/badge/Google%20Gemini-1.5%20Flash-orange)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

---

## Overview

Keeping track of product warranties is a common but often overlooked problem — bills get lost, expiry dates are forgotten, and users miss the window to claim repairs or replacements. The **Smart Warranty Management System** solves this by giving users a single dashboard to upload bills, automatically extract product details using AI, track warranty status, and receive timely email reminders before expiration.

---

## Key Features

- **User Registration & Login** — Secure authentication for individual user accounts.
- **Product Bill Upload** — Upload scanned or photographed bills directly through the dashboard.
- **AI-Assisted Data Extraction** — Uses Google Gemini 1.5 Flash to automatically extract product details from invoices.
- **Automatic Warranty Expiry Calculation** — Computes expiry dates based on extracted purchase data.
- **QR Code Generation** — Generates a unique QR code per product for quick lookup and identification.
- **Product Dashboard** — Centralized view of all registered products and their warranty status.
- **Warranty Status Tracking** — Visual indicators for active, expiring, and expired warranties.
- **Email Reminder Notifications** — Automated alerts sent ahead of warranty expiration.
- **Product Edit & Delete** — Full CRUD functionality for managing saved products.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python, Flask |
| Database | SQLite |
| Frontend | HTML, CSS, JavaScript |
| AI Integration | Google Gemini 1.5 Flash |

---

## Project Workflow

1. User uploads a product bill.
2. The system extracts product information from the bill using AI.
3. Warranty expiry date is calculated automatically.
4. A unique QR code is generated for the product.
5. Product details are stored securely in the database.
6. Users view and manage warranties through the dashboard.
7. Reminder emails are sent before warranty expiration.

## 🚀 Live Demo

🌐 https://beamish-gecko-0ed0d8.netlify.app


## Screenshots

<img width="734" height="744" alt="image" src="https://github.com/user-attachments/assets/9bd214c1-c2bb-4b25-aafa-55488f59ac06" />
<img width="773" height="702" alt="image" src="https://github.com/user-attachments/assets/bb404e67-ec87-40f9-8921-b5acc95f5253" />


### Dashboard

<img width="1738" height="836" alt="image" src="https://github.com/user-attachments/assets/c875d70f-069f-45f6-9762-c059405d1a56" />


### Upload Bill

<img width="739" height="702" alt="image" src="https://github.com/user-attachments/assets/225679c4-e657-456b-b7ff-bf09ecd63477" />


### Product Details

<img width="588" height="731" alt="image" src="https://github.com/user-attachments/assets/72244b22-0378-4cac-91e2-4a3918ef8aa4" />
<img width="793" height="619" alt="image" src="https://github.com/user-attachments/assets/7c61e4f2-136f-457a-b331-f49e371800e0" />
<img width="793" height="719" alt="image" src="https://github.com/user-attachments/assets/fe0de07a-17ca-4c4e-a271-6cc45d3c9c47" />


### QR Code Generation

<img width="673" height="606" alt="image" src="https://github.com/user-attachments/assets/f2f46d9f-1b78-4796-943b-6b4feb983762" />

Project Highlights

- Developed a full-stack web application using Python and Flask.
- Integrated Google Gemini 1.5 Flash for AI-powered invoice data extraction.
- Implemented QR code generation for quick product identification.
- Automated warranty expiry tracking with email reminder notifications.
- Built secure user authentication with complete CRUD functionality.

---

## Learning Outcomes

- Gained hands-on experience in full-stack web development using Flask.
- Integrated Generative AI (Google Gemini 1.5 Flash) into a production workflow.
- Implemented database operations using SQLite.
- Strengthened understanding of authentication, file handling, and RESTful application design.


## Future Enhancements

- **Cloud Storage Integration** — Store uploaded bills and QR codes on cloud storage instead of locally.
- **Warranty Renewal Suggestions** — Recommend renewal or extended warranty options as expiry approaches.

---

## Author

**Varsha Santhosh**
B.Tech Computer Science Engineering
Mangalam College of Engineering
