# NAVYON Tech Solutions website

Responsive multi-page static website for NAVYON Enterprises / NAVYON Tech Solutions.

## Pages
- `index.html` — Home
- `services.html` — Services
- `work.html` — Work, live portfolio links, Ponthamarai Foundation, Yuga 2K26, and upcoming Sash Cakes and Bakes
- `internships.html` — Internship information and application form
- `about.html` — About NAVYON and its practical-learning mission
- `contact.html` — Contact details and WhatsApp enquiry form

## Run locally
Run `python3 -m http.server 8000` in this directory, then visit `http://localhost:8000`.

## Form behaviour
- Contact form requires name, email, and enquiry type. Project details are optional; choosing Other reveals an optional free-text field. It prepares a WhatsApp message for the visitor to review and send.
- Internship form requires name, email, interest area, preferred format, and availability. It opens the visitor's default email application with a prepared message addressed to navyonenterprises@gmail.com. This static-site form does not automatically store or deliver applications. For reliable collection, connect a form backend or hosted form service before public launch.
- Theme choice persists in local storage across pages in the same browser.
- Yuga 2K26 is included in Our Work, not a dedicated page. The old yuga.html URL redirects to the section.
- Add verified screenshots, permissions, and confirmed case-study details before launch.
- Fonts load from Google Fonts with system fallbacks.

Every main page includes the developer credit: “Created by Navyon Enterprises”.
