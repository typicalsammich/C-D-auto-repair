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


## Photorealistic 360 vehicle demo (v14)
The Vehicles page is wired to IMAGIN.studio 360 exterior imagery using angle frames 200-231. The included `customer=img` value is for a watermarked demo/prototype only. Before production launch, replace `IMAGIN_CUSTOMER='img'` in `makes.html` with the client's licensed IMAGIN.studio customer key and confirm the chosen modelFamily mappings under their account. The page automatically falls back to C & D's existing real serviced-vehicle photos if the remote 360 asset cannot load.


V19 FINAL SEO + MOBILE PASS
- Unique SEO titles and descriptions on every page
- Canonical URLs, Open Graph, Twitter cards, geo metadata and en-US alternate URLs
- Consistent AutoRepair/AutomotiveBusiness, WebSite, WebPage and Breadcrumb structured data
- Expanded service schema for repair, tires, towing/roadside, lockout/key help and paint/body
- Updated sitemap.xml and robots.txt
- Mobile touch targets, safe-area call button, responsive forms, vehicle selector, services, financing and footer
- Converted large key/body service photos to WebP for faster mobile loading
