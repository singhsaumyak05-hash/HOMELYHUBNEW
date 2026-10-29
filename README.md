# HomelyHub — Property Booking Platform (starter demo)

A responsive React + Vite frontend built from scratch for learning and demos.

## Features in this starter
- Responsive homepage and property cards
- Destination search, guest count and property-type filters
- Property details, amenities, date selection and price calculation
- Demo booking requests saved in browser localStorage
- Demo account creation/sign-in flow (email only; not secure authentication)
- Booking dashboard and cancellation
- Host interest form
- Mobile-friendly navigation

## Requirements
- Node.js (LTS recommended)
- npm

## Run on Windows
1. Extract the ZIP.
2. Open the extracted `HomelyHub-From-Scratch` folder in VS Code.
3. Open Terminal > New Terminal.
4. Run:

   ```powershell
   npm.cmd install
   npm.cmd run dev
   ```

5. Open the local URL printed by Vite (usually http://localhost:5173/).

If port 5173 is already used, Vite will show another port such as 5174. Open the URL shown in your terminal.

## Build check
```powershell
npm.cmd run build
```

## Important limitations
This is a functional frontend prototype, not a production booking service. Listings are sample data in `src/App.jsx`; booking requests and demo accounts are stored only in the current browser's localStorage. There is no backend, shared database, secure password authentication, real availability locking, payment processing, or host approval workflow. Do not use it to collect real user credentials or payments.

Next production steps: build an Express API, connect MongoDB, implement password hashing and session/JWT security, validate availability on the server to prevent double bookings, add image storage, and integrate a payment provider only after backend validation.
