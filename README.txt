VYOM MENU REVAMP — CUSTOMER MENU + STAFF POS
============================================

Files to upload to the ROOT of existing GitHub repository:
- customer.html  Updated customer-facing QR menu and WhatsApp checkout
- pos.html       Updated staff POS menu and billing

Do not replace index.html (hostel homepage). Do not remove cafe menu photos or any other repository files.

PROPOSED SELLING PRICES (INR)
- Poha stays at ₹110.
- Regular breakfast and beverages remain accessible, with small alignment adjustments.
- Platters and thalis now reflect full meal portions and more complete accompaniments.
- “Unlimited Backpacker Thali” is renamed “Backpacker Thali” at ₹279 because the previous description did not define unlimited refills or a fixed serving. Only use “Unlimited” if the kitchen genuinely offers unlimited refills and has food-costed the offer.
- Special Thali ₹329.
- Added six vegetarian Chinese dishes: Veg Hakka Noodles ₹219; Chilli Garlic Noodles ₹229; Veg Fried Rice ₹199; Honey Chilli Potato ₹239; Veg Manchurian (Dry/Gravy) ₹259; Chilli Paneer (Dry/Gravy) ₹289.

Pricing benchmark was cross-checked against public Pushkar menu data. For example, Nutmeg Cafe lists Hakka noodles ₹250, garlic noodles ₹270, chilli paneer ₹370, veg Manchurian ₹320 and fried rice ₹200; Om Shiva Garden lists chilli paneer ₹200, veg Manchurian ₹180–200, veg fried rice ₹170 and Schezwan chowmein ₹200. Public Pushkar thali examples include ₹270 and ₹320. VYOM's proposal sits in a mid-range backpacker-cafe position rather than matching either the cheapest restaurant or the premium cafe. Actual margin cannot be guaranteed without ingredient, portion, labour and overhead costing.

Operational notes:
- All Chinese items are vegetarian.
- For dry/gravy dishes, customer can specify preference in order notes.
- POS and customer menu now use the same item order and prices.
- Existing WhatsApp click-to-chat recipient remains +91 73403 36308. Customer still needs to tap Send in WhatsApp.
- This does not yet add cloud syncing or automatic kitchen ticket routing.

Deploy:
1. Open the existing repository: shashank29296-star/vyom-cafe-ordering.
2. Upload ONLY customer.html and pos.html from this package into the repository root, replacing files with matching names.
3. Do not replace index.html or remove other site files.
4. Commit changes. GitHub Pages redeploys automatically.
5. Test https://vyomhostel.com/customer.html and https://vyomhostel.com/pos.html after deploy.

Prices are proposed menu prices, not audited food-cost prices. Run a recipe cost calculation and check supplier rates before printing the menu.

MENU UPDATE (20 NOV 2026)
- Added Honey Chilli Potato to the Chinese category at ₹239. Description: Crispy potato fingers tossed in sticky honey-chilli sauce, finished with sesame and spring onion.
- The customer menu and staff POS have matching item and price entries.
