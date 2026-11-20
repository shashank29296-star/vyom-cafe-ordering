VYOM CAFE POS + CUSTOMER QR ORDERING — PROTOTYPE

FILES
- index.html: staff POS, kitchen queue, sales and settings
- customer.html: customer-facing digital menu and WhatsApp checkout
- menu-platters.jpg / menu-beverages.jpg: your supplied menu photos

LOCAL TEST
1. Extract the ZIP and open vyom-pos/index.html in a browser to use the staff POS.
2. Open customer.html to test the customer menu and WhatsApp order message.
3. The WhatsApp recipient is +91 73403 36308. Customer enters their name, adds items and taps Place order on WhatsApp. They must then tap Send in WhatsApp.

PUBLISH + QR
1. Publish the entire vyom-pos folder to a static HTTPS host (GitHub Pages is one free option). Keep all files in the same folder.
2. Your public customer URL will end in /customer.html.
3. In staff POS, open Settings, paste that public URL in Customer QR ordering, and click Generate QR code. Print the QR and test it with another phone before displaying it.
4. QR generation uses an online QR image service, so internet access is needed to generate it.

IMPORTANT LIMITATIONS
- This is a prototype, not a production POS. The staff POS saves orders in local browser storage only; it does not sync across devices.
- QR customer orders are sent as a WhatsApp message. WhatsApp click-to-chat does not send an order webhook back into this POS, so staff must manually enter/confirm the received order in the POS. For fully automatic kitchen ticket creation from customer WhatsApp/QR orders, the next build needs a hosted backend/database and an approved WhatsApp Business Platform integration or a direct web-order backend.
- Customer WhatsApp number: +91 73403 36308. Customers must tap Send.
- Not a GST-compliant accounting system; tax settings and invoice compliance are not configured.
- Verify menu item spellings and prices before live use. Paratha prices were interpreted from the printed menu.
