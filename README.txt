BETTER LINE LIMO LLC — DEMO PWA

Open index.html for a preview. To install as an app, publish the folder on HTTPS hosting (for example a free static hosting tier) and then use browser Add to Home Screen / Install App.

What works: booking form, set your own named fixed-price routes and Sedan/SUV prices, copy booking details, prepare email to company, PWA manifest and service worker.

IMPORTANT LIMITATIONS: This is a prototype. Prices and booking email settings are saved in localStorage on each device, NOT shared with your customers; do not rely on it for production reservations. No credit card processing exists yet. No central reservation records, no protected admin login, and no availability checks. The sample prices are placeholders, NOT company prices. The customer booking message is only sent when the customer actually sends the email in their mail app, and the booking is NOT confirmed automatically.

To go live: implement protected business admin + shared database for routes, pricing and bookings, backend price validation, Stripe Checkout or another approved payment provider with server-generated sessions and webhook confirmation, transactional email, HTTPS hosting, privacy policy and terms. Do not put Stripe secret keys in the frontend. Never treat an unverified client-calculated price as a charge amount.
