# The Golden Tooth: full website (upload everything to the site root)

Replaces/updates:
- index.html, blogs.html, dental-implants-center.html (your existing pages, now linked to all new pages)

New:
- services.html, doctors.html, patient-stories.html, contact.html, book-appointment.html
- 20 service pages (*-thane.html)
- logo.png, sitemap.xml, robots.txt, llms.txt

Keep your existing /articles/ folder as it is.

Linking: the 8 core pages (Home, Services, Implants, Doctors, Patient Stories, Articles, Contact, Book) link to each other.
Home links to all 21 service pages (footer + "All our dental services" band). services.html links to every service page.
Every service page links back to services.html, related services, doctors, contact and booking.

After upload:
1. Open https://www.goldentoothdental.com/sitemap.xml to confirm it loads, then submit it in Google Search Console (Indexing > Sitemaps).
2. URL Inspection > Request indexing for index.html, services.html and a few service pages.
3. Remove article URLs from sitemap.xml that do not exist in /articles/.
4. Confirm the doctor named on each service page really handles that treatment.
5. Make sure your Google Business Profile address, phones and hours match the pages exactly.
