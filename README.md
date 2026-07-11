# 🏨 Hotel Reservation System

A full-featured hotel reservation management application built with **Angular 16** and **Bootstrap 5.3**.

## ✨ Features

- **Create Reservations** — Add new guest reservations with check-in/check-out dates, guest details, and room assignment
- **View All Reservations** — Browse all reservations in a clean, responsive table layout
- **Edit Reservations** — Update existing reservation details seamlessly
- **Delete Reservations** — Remove reservations with a single click
- **Form Validation** — Real-time validation with user-friendly error messages
- **Data Persistence** — Reservations are saved to `localStorage` so data persists across browser sessions

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Angular 16 | Frontend framework |
| TypeScript | Type-safe development |
| Bootstrap 5.3 | Responsive UI styling |
| Reactive Forms | Form handling & validation |
| localStorage | Client-side data persistence |

## 📁 Project Structure

```
src/app/
├── home/                    # Landing page with navigation
├── models/
│   └── reservation.ts       # Reservation data model (interface)
├── reservation/
│   ├── reservation.service.ts   # CRUD operations & localStorage logic
│   └── reservation.module.ts    # Feature module
├── reservation-form/        # Create & Edit reservation form
├── reservation-list/        # Reservation table with actions
├── app-routing.module.ts    # Route configuration
├── app.module.ts            # Root module
└── app.component.*          # Root component
```

## 🚀 Getting Started

### Prerequisites

- **Node.js** (v16 or higher)
- **Angular CLI** v16.1.6

### Installation

```bash
# Clone the repository
git clone https://github.com/srjay999-giT/hotel-appointment-system.git

# Navigate to the project directory
cd hotel-appointment-system

# Install dependencies
npm install
```

### Run the Development Server

```bash
npm start
```

Navigate to **http://localhost:4200/**. The app will automatically reload on file changes.

## 📌 Routes

| Route | Page |
|---|---|
| `/` | Home — Welcome page with navigation buttons |
| `/new` | Create — New reservation form |
| `/list` | List — View all reservations |
| `/edit/:id` | Edit — Update an existing reservation |

## 🧪 Running Tests

```bash
# Unit tests via Karma
npm test
```

## 📦 Build for Production

```bash
ng build
```

Build artifacts will be stored in the `dist/` directory.

## 📄 License

This project is open source and available for educational purposes.
