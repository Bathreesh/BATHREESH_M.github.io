# BATHREESH.M - Professional Portfolio

A complete personal portfolio website for **BATHREESH.M**, built using pure HTML5 and CSS3. This project is a static website designed to showcase expertise in embedded systems, hardware-software integration, and technical projects.

## Project Structure

```
bathreesh-portfolio/
│
├── index.html              (Home/Hero)
├── about.html              (About Me & Career Objective)
├── skills.html             (Technical & Soft Skills)
├── projects.html           (Featured Projects)
├── experience.html         (Internship & Workshops)
├── certifications.html      (Certifications & Training)
├── contact.html            (Contact & Social Links)
│
├── css/
│   └── style.css           (Main stylesheet)
│
├── assets/
│   ├── images/             (Add your profile and project images here)
│   └── icons/              (Add PWA icons here: 192x192 and 512x512)
│
├── manifest.json           (PWA manifest)
├── offline.html            (Offline fallback page)
└── README.md
```

## Features

- **Responsive Design**: Mobile-first approach, fully compatible with Mobile, Tablet, and Desktop screens.
- **Embedded Systems Focus**: Content tailored to highlight hardware/software engineering skills.
- **PWA Support**: Includes `manifest.json` and `offline.html` for basic installability.
- **Pure HTML/CSS**: Highly performant, zero external dependencies, no JavaScript.
- **Professional Aesthetics**: Custom theme using Dark Blue, Light Gray, and Cyan accents.

## Deployment Instructions (Google Antigravity IDE)

1. **Upload Files**: Ensure all files are uploaded to your workspace root.
2. **Directory Check**: Ensure the `/css/style.css` path is correct relative to the HTML files.
3. **Preview**: Use the built-in browser preview to view the site.
4. **Local Server (Optional)**: If running locally without an IDE, you can use a simple server:
   ```bash
   python -m http.server
   ```

## Customization

- **Images**: Replace placeholders in `assets/images/` with your actual project photos.
- **Icons**: Update `assets/icons/` with your own manifest icons.
- **Contact Info**: The contact form is static; for real email functionality, consider integrating a service like Formspree or a backend API.

## Design Details

- **Color Theme**:
  - Primary: `#1a3a52` (Dark Blue)
  - Background: `#f0f2f5` (Light Gray)
  - Accent: `#00d4ff` (Cyan)
- **Typography**: Responsive system fonts stack for maximum performance and compatibility.

---
Built by Antigravity for BATHREESH.M.
