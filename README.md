# ShopKart Advanced (Full-Stack E‑Commerce)

A production-ready scaffold for a full-stack e-commerce app matching the requested UI and features.

## Tech
- **Frontend**: React + Vite + TailwindCSS + Redux Toolkit + React Router + shadcn/ui + Recharts + Lucide
- **Backend**: Node.js + Express + MongoDB (Mongoose) + JWT Auth + Multer (image upload) + Cloud stub
- **Payments**: Razorpay + Stripe stubs with toggles
- **Admin Panel**: React (same app, protected `/admin`) + shadcn/ui + Chart.js/Recharts

## Quick Start

### 1) Backend
```bash
cd backend
cp .env.sample .env    # set values
npm i
npm run dev            # starts on http://localhost:5000
```
Seed sample data:
```bash
npm run seed
```

### 2) Frontend
```bash
cd frontend
cp .env.sample .env    # set VITE_API_URL (default http://localhost:5000/api)
npm i
npm run dev            # http://localhost:5173
```

### Admin Login
After seeding, an admin user is created:
- Email: admin@shopkart.dev
- Password: Admin@123

> **Note**: Payment keys are not included. Use test keys in `.env`; stubs fall back to cash-on-delivery.

## Scripts
- **backend**: `dev`, `start`, `seed`
- **frontend**: `dev`, `build`, `preview`, `lint`

## Features Covered
- Top navs, category menu, banner slider, filter sidebar
- Product grid (Best of Mobiles, Trending Deals)
- Product detail with image zoom, offers, add-to-cart / buy-now
- Cart, checkout, order summary, address & payment, order tracking
- Auth (JWT), order history
- Admin: dashboard cards, charts, product/order/user management, CSV export
- File upload stubs (store locally by default)

## Structure
```
/backend
/frontend
```
