# Events Booking Platform – Next.js Event Ticketing and Reservation System

This project is a full-featured event booking platform that allows users to browse trending events, purchase tickets, reserve seats or time slots, and manage bookings through a modern and responsive interface. Administrators can create and manage events, upload images, configure schedules, and oversee all bookings. The system supports secure payments through Stripe and integrates authentication and data validation for a production-ready experience.

---

## Overview

The platform is built with a modular architecture that supports real-time data handling, secure payment workflows, and efficient event management. Users can authenticate, explore available events, view event details, choose available dates or slots, and purchase tickets through a streamlined checkout experience. Admin users have dedicated access to create events, update information, manage bookings, and analyze engagement.

Designed to resemble a modern ticketing system, this project showcases how to build a scalable and maintainable event reservation platform using Next.js, TypeScript, and a cloud-based backend.

---

## Features

### User-Facing Functionality
- Browse all available events with filtering and sorting.
- View detailed event information including date, time, description, venue, and pricing.
- Choose available time slots or ticket categories.
- Add tickets to the cart and complete payment through a secure checkout flow.
- Receive confirmation upon successful booking.
- Manage bookings through a personal dashboard.

### Admin Dashboard
- Create new events with images, descriptions, location details, and pricing.
- Configure event dates, time slots, capacity limits, and ticket categories.
- Update existing events with full version control.
- View all bookings and monitor sales performance.
- Manage attendees and event status.

### Payments and Billing
- Fully integrated payments using Stripe.
- Real-time checkout with automatic ticket validation.
- Secure payment intent creation and processing.
- Transaction and receipt management.

### Authentication and User Accounts
- Secure user authentication using an identity provider.
- Protected routes and dashboards for both users and admins.
- Automated webhook handling for account sync when required.

### Booking Logic
- Seat or slot availability validation.
- Prevention of overbooking through server-side checks.
- Persistent booking records stored in MongoDB.
- Confirmation page with booking details and metadata.

### File Upload and Media Handling
- Image upload interface for banners and event posters.
- Optimized image storage for stable performance.
- Drag-and-drop upload experience for administrators.

### UI/UX
- Fully responsive interface for all devices.
- Clean layout with modern interaction patterns.
- Accessible components built with Radix primitives.
- Smooth transitions, date pickers, and user-friendly forms.

---

## Tech Stack

- Framework: Next.js 14  
- Language: TypeScript  
- Database: MongoDB with Mongoose  
- Authentication: Clerk  
- Payments: Stripe  
- File Uploads: UploadThing  
- Forms: React Hook Form  
- Validation: Zod  
- UI Layer: Tailwind CSS, Radix UI components, Lucide icons  
- Date Selection: React Datepicker  
