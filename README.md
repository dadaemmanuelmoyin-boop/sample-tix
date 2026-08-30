# Sample Tix — Ticket Transfer Demo

A front-end simulation of a ticketing app's order detail and ticket-transfer
flow (login → OTP authentication → order detail → select tickets → recipient
details → OTP verification → success), built with React, Tailwind CSS, and
lucide-react icons.

## Running locally

```bash
npm install
npm run dev
```

Then open the printed local URL (usually http://localhost:5173).

## Demo login

- Email: `demo@example.com`
- Password: `Demo123!`
- One-time verification code (login and transfer): `123456`

## Notes

- This is a client-side simulation: ticket ownership and transfer history are
  stored in `localStorage`, not a real backend/database.
- No real email/SMS is sent for the one-time code.
- "Upgrade" and "Sell" and "Select From Contacts" are shown but intentionally
  disabled — out of scope for this demo.

## Build

```bash
npm run build
npm run preview
```
