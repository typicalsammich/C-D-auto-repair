# C & D Advanced Auto Repair & Performance

Static multi-page website prepared for GitHub + Vercel.

## Pages
- index.html
- services.html
- appointments.html
- makes.html
- financing.html
- vehicles.html
- specials.html
- contact.html
- pay.html

## Stripe activation
The Pay Online page is intentionally not connected to a live payment destination yet. A live Stripe Payment Link must be created inside the client's Stripe account. Once provided, replace the placeholder click behavior for `#stripe-pay` in `assets/script.js` with `window.location.href = 'CLIENT_STRIPE_PAYMENT_LINK';` or change the button to an anchor using that URL.

## Appointment form
The branded appointment form prepares and reviews appointment details. Until a dedicated form backend is connected, the final CTA continues to C & D's existing live appointment request page so the site does not falsely claim a request was submitted.
