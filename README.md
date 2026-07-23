# DEKA Affiliate Landing Page

A single, self-contained static landing page (`index.html`) for the **Spartan DEKA North America 2026 affiliate program**. It walks a gym owner through two steps — sign the affiliate agreement, then start their affiliation — and is built to sit behind a QR code.

The page is fully self-contained: all CSS, JavaScript, and the DEKA logo (embedded as base64) live inside `index.html`. There are no external asset dependencies.

## Destination links

The page contains two outbound call-to-action links:

1. **Affiliate agreement** — https://share.hsforms.com/1moVRSehBRHmLe360O_GZ1A4bm8z
2. **Stripe checkout** — https://buy.stripe.com/28o7sO8Dr28s69G6ot

## Updating the page

Edit `index.html`, then: `git add index.html && git commit -m "Update landing page" && git push` — GitHub Pages redeploys automatically.
