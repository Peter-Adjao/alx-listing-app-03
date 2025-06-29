# -alx-listing-app-03

ALX Listing App

The ALX Listing App is a foundational project designed to scaffold a modern Airbnb-style property listing platform using Next.js, TypeScript, TailwindCSS, and ESLint. The goal is to progressively build a scalable, maintainable, and responsive application structured for real-world production scenarios.

---

## 🚀 Project Objectives

- Scaffold a production-ready Next.js app with integrated TypeScript and TailwindCSS.
- Implement reusable and modular components (e.g., Card, Button, BookingForm, OrderSummary).
- Ensure type safety using custom interfaces and component props.
- Maintain a clean and scalable folder structure following best practices.
- Manage static assets efficiently for UI development.
- Enable responsive design principles for mobile, tablet, and desktop views.
- Build a dynamic **Booking Detail Page** with user input, form handling, and order summary components.

---

## Milestone: Booking Detail Page

This milestone introduces a fully responsive booking page that allows users to input personal and payment details, view order summaries, and understand the cancellation policy before confirming a booking.

###  Features

- **Booking Form**  
  Users can enter:
  - Contact Information (First name, Last name, Email, Phone)
  - Payment Information (Card Number, Expiry Date, CVV)
  - Billing Address (Street, Apartment, City, State, Zip Code, Country)

- **Order Summary**  
  Displays:
  - Property name, image, review score
  - Stay information (start date, total nights)
  - Breakdown: booking fee, subtotal, and grand total

- **Cancellation Policy & Ground Rules**  
  - Refund guidelines and key guest rules listed for transparency

### 📁 Folder Structure

alx-listing-app-03/
├── components/
│   └── booking/
│       ├── BookingForm.tsx
│       ├── OrderSummary.tsx
│       └── CancellationPolicy.tsx
├── pages/
│   └── booking/
│       └── index.tsx
├── public/
│   └── images/
│       └── property.jpg     # (Optional static asset)
├── styles/
│   └── globals.css
├── .eslintrc.json
├── next.config.js
├── tailwind.config.js
├── tsconfig.json
├── package.json
└── README.md


---

##  Tech Stack

- **Next.js 13+** – App routing, server/client rendering
- **TypeScript** – Type safety and interface-driven development
- **TailwindCSS** – Utility-first responsive styling
- **ESLint** – Code linting and formatting standards

---

## 📄 License

This project is part of the ALX Software Engineering Program. Educational use only.

