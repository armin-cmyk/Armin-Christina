# Armin & Christina — Clean One-Page Guest Site

**Date:** August 5, 2026  
**Resort:** Secrets Moxché Playa del Carmen

This is a very clean, minimal one-page site designed specifically to be scanned via QR code on a printed itinerary given to guests when they arrive at the resort.

## What’s included
- Minimal elegant hero
- Clean accordion / dropdown sections (easy to scan on phone)
- Restaurants & Dining (real names + short descriptions from resort)
- Transportation — direct link to Amstar (official partner)
- Resort Map — link to interactive layout
- Things to Do
- Share Your Photos
- Quick Essentials (WiFi, concierge, reservations, emergency)

Removed: Welcome bags, full wedding schedule, extra fluff, countdown, long story.

## How to customize quickly

1. **Date** — Update hero and footer if needed
2. **Photo album** — Replace the placeholder link in the "Share Your Photos" section with your real Google Photos / Drive album link
3. **Restaurants** — Currently based on public resort info. Update descriptions or add/remove as needed
4. **Amstar** — Already linked to https://www.amstardmc.com/en/destinations/mexico/cancun/cancun-airport-transportation/
5. **Resort Map** — Points to https://www.resortsmaps.com/map-SecretsMoxchePlayadelCarmen-RivieraMaya.html (has printable version)
6. **QR Code** — Generate a QR that points to this page (or your final deployed URL) and print it on the itinerary

## Ideas for the printed QR + itinerary (since guests are already at the resort)

Here are focused, practical ideas for what to include on the printed card + what this site can support:

### Must-haves on the printed itinerary
- Big QR code (this site)
- Wedding date + time + location on property (e.g. “Beach at 4:30pm”)
- Your names + “Welcome!”
- Very short welcome sentence
- Key phone numbers (concierge, wedding contact)
- WiFi network + password
- “Make dining reservations via World of Hyatt app or front desk”

### Good additions for the site (already in the current version)
- Full list of on-site restaurants with cuisine type (no overwhelming menus)
- Direct Amstar transportation link (in case someone needs a ride later)
- Easy resort map link
- “Things to do” nearby (5th Ave, cenotes, etc.)
- Photo album link so guests can upload/share immediately

### Other strong ideas you could add
- Daily activities / entertainment note (“See the World of Hyatt app or lobby board”)
- How to get to the ceremony location (“Meet at the beach, follow signs”)
- Spa booking info
- Preferred Club vs regular guest differences (if relevant)
- Taxi / golf cart info within the resort
- Simple packing reminder for the wedding day (e.g. “Light colors, comfortable shoes for sand”)
- Local weather tip or what to expect
- “Questions? Talk to the concierge — they’re amazing”

### QR best practices for printed itinerary
- Make the QR large and high-contrast
- Short URL if possible (bit.ly or your custom domain)
- Test it on multiple phones before printing
- Add tiny text below QR: “Scan for restaurants, map & more”

## Quick preview
Double-click `index.html` or run:
```bash
python3 -m http.server 8080
```

## Deploy
Push to your existing Vercel project or Netlify. Update the QR on the printed itinerary with the live link.

---

Let me know if you want:
- A specific section added/removed
- Different restaurant descriptions
- A version with your real photo album link pre-filled
- A printable “card” version (separate simple HTML for the physical itinerary)