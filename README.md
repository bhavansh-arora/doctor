# Meridian Care Clinic — Website Template

A conversion-focused, mobile-optimized website template for doctors and medical clinics. Plain HTML/CSS/JS — no build step, no framework, works by just opening `index.html` or hosting the folder anywhere.

## Pages

- `index.html` — Home
- `about.html` — About / Our Story
- `services.html` — Services
- `team.html` — Our Doctors
- `testimonials.html` — Patient Testimonials
- `blog.html` / `blog-post.html` — Health Blog + article template
- `contact.html` — Contact
- `appointment.html` — Book Appointment

## Structure

```
css/style.css       shared design system + styles
js/script.js        nav, animations, forms, modals, sticky bar
assets/images/       local site photography (no external image CDN dependency)
assets/favicon.svg
```

## Notes

- All photos ship as local files under `assets/images/` — nothing hotlinked.
- External dependencies (Google Fonts, Font Awesome via cdnjs) are the only remote requests, both standard and reliable.
- Every page includes a sticky bottom bar promoting the template itself for sale — remove the `.sell-bar` block in each HTML file and its CSS/JS hooks when handing this off to a buyer.
