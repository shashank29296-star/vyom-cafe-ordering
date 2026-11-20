VYOM DOMAIN-READY SITE
======================

FILES TO UPLOAD TO THE ROOT OF THE EXISTING GITHUB REPOSITORY:
- index.html               Hostel brand homepage
- customer.html            Cafe customer menu + WhatsApp checkout
- pos.html                 Staff POS (renamed from original POS index.html)
- menu-beverages.jpg       Supplied menu image
- menu-platters.jpg        Supplied menu image
- vyom-cafe-qr.png         QR target: https://vyomhostel.com/customer.html
- vyom-cafe-qr-poster.pdf  A5 print poster with same QR

URL STRUCTURE AFTER CUSTOM DOMAIN + GITHUB PAGES ARE CONNECTED:
- Hostel homepage: https://vyomhostel.com/
- Cafe menu:       https://vyomhostel.com/customer.html
- Staff POS:       https://vyomhostel.com/pos.html

WHATSAPP:
The customer menu has WA recipient +91 73403 36308. Customer taps Place Order,
WhatsApp opens with name, items, total and payment method prefilled; customer must
tap Send. This is click-to-chat, NOT automated WhatsApp API delivery. Current POS
does not automatically receive website/WhatsApp orders across devices. The POS
prototype stores staff data locally in that browser.

GITHUB PAGES CUSTOM DOMAIN:
1. Upload/replace these files in the repository root. Do not place them in a nested folder.
2. GitHub repo: shashank29296-star/vyom-cafe-ordering
3. Settings -> Pages -> Custom domain: vyomhostel.com -> Save.
4. In the registrar's DNS manager add:
   A     @     185.199.108.153
   A     @     185.199.109.153
   A     @     185.199.110.153
   A     @     185.199.111.153
   CNAME www   shashank29296-star.github.io
   TTL Auto/default.
5. Keep existing MX and TXT records (email verification / mail) intact. Do not delete unrelated records.
6. If another active website is already using the root domain, changing @ A records will route it to GitHub Pages. Check before changing.
7. After DNS resolves, GitHub Settings -> Pages -> Enforce HTTPS.

The domain/DNS has not been configured by this package. Do not print the new QR
until https://vyomhostel.com/customer.html opens successfully on a phone.

IMAGE AND CONTENT NOTE:
The homepage uses externally hosted photo URLs as in the latest backpacker design.
Check photo reuse permissions before commercial publication.

WhatsApp number should be confirmed as the correct cafe/hostel contact before launch.
