Web Ctrl A — static site
========================
Open index.html in a browser. Pages: index, services, projects, flamingo (project page), packages, about, contact.

Files
- style.css   shared styles: base, per-page styles (scoped by body.pg-*), motion, scroll, responsive, mobile menu, hero video
- assets/     logos, project images, hero video (hero-loop.webm / .mp4, silent, seamless loop) and poster
- Fonts (Bricolage Grotesque, Instrument Sans) load from Google Fonts.

Mobile / tablet menu
- At 1024px and below the header shows a hamburger button that opens a dropdown menu (CSS only, no JavaScript).
- The header "Free estimate" button moves inside the menu on those sizes.

Notes
- The contact form is visual only; connect it to your email service or CRM before launch.
- Accent color is #2B5CFF; change it in style.css and the inline styles (search/replace).
- The Arabic (RTL) version is not included yet.
