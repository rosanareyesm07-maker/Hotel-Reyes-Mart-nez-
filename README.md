# Hotel Reyes Martínez — Website starter

A responsive tropical/island-themed hotel landing page with:
- Hotel presentation and island-inspired design (waves, flowers, palm, surf, crab motifs).
- Room categories NK1, NQQ, Suite, and 100-room total inventory (no category-specific room counts assigned).
- Amenity showcase.
- Interactive front-end concierge chat widget available on the page at all times.
- WhatsApp booking handoff buttons.

## Setup before publishing
1. Open `index.html`.
2. Find `const WHATSAPP_NUMBER = "573000000000"` and replace the placeholder with the hotel's official WhatsApp number, country code included, digits only.
3. Confirm the listed amenities and room descriptions/occupancy against the real hotel; these are initial placeholder descriptions.
4. The chatbot is a scripted front-end demo, not an AI backend. It does not store messages and cannot check real inventory, rates, availability, or answer outside the scripted topics. For an actual AI 24/7 concierge, integrate a server-side service (for example, an API route/server) and keep credentials out of client code.

## Publish with GitHub Pages
Repository Settings → Pages → Build and deployment → Source: Deploy from a branch → `main` → `/(root)` → Save.
The entry point is `index.html`.
