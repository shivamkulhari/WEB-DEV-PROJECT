# Shivam Kulhari — Portfolio

A personal portfolio website built with plain HTML and CSS, with Tailwind CSS used for simple layout utilities (flex, grid, gap).

**🔗 Live site:** [https://shivamkulhari.github.io/WEB-DEV-PROJECT/](https://shivamkulhari.github.io/WEB-DEV-PROJECT/)

---

## About

This site introduces me, a computer science student from Mumbai studying a B.Sc. in Computer Science at BITS Pilani and the UGP in CS & AI at Scaler School of Technology. It covers my background, skills, projects and contact details in a single-page layout with a sticky sidebar.

## Sections

- **About:** who I am and what I'm focused on
- **Skills:** languages I use and libraries I'm currently learning
- **Projects:** three HTML/CSS practice projects (below)
- **Journey:** education and activities timeline
- **Contact:** email, GitHub, LinkedIn and a contact form

## Practice Projects

Each project lives in its own folder under `projects/` and can be opened on its own.

| Project | Description | Built with |
| --- | --- | --- |
| [Weather Dashboard UI](projects/weather/) | A static weather page with a card per city, made to practice CSS Grid. No real weather data. | HTML, CSS, Grid |
| [Blog Card Layout](projects/blog/) | A simple blog page with tags and a grid of cards, to practice text styling and hover effects. | HTML, CSS, Grid |
| [Sign In Page](projects/login/) | A login card with styled form fields. Design only, no real login. | HTML, CSS, Forms |

## Tech Stack

- HTML5
- CSS3 (custom styles in `style.css`)
- [Tailwind CSS](https://tailwindcss.com/) via CDN, for layout utilities only

## Project Structure

```
shivam-portfolio/
├── index.html          # Main portfolio page
├── style.css           # Styles for the main page
├── images/
│   └── shivam.png      # Profile photo
└── projects/
    ├── blog/           # Blog card layout
    │   ├── index.html
    │   └── style.css
    ├── login/          # Sign in page
    │   ├── index.html
    │   └── style.css
    └── weather/        # Weather dashboard UI
        ├── index.html
        └── style.css
```

## Run Locally

No build step or dependencies are needed.

```bash
# Clone the repository
git clone https://github.com/shivamkulhari/WEB-DEV-PROJECT.git
cd WEB-DEV-PROJECT

# Open index.html in your browser
# or serve it locally, for example with Python:
python -m http.server 8000
```

Then visit `http://localhost:8000`.

> Note: Tailwind is loaded from a CDN, so an internet connection is needed for the layout classes to work.

## Notes

- The contact form is front-end only and does not send messages yet.
- The weather dashboard uses hard-coded sample data.
- The sign in page is a design exercise with no authentication.

## Contact

- **Email:** [shivam.26bcs10333@sst.scaler.com](mailto:shivam.26bcs10333@sst.scaler.com)
- **GitHub:** [github.com/shivamkulhari](https://github.com/shivamkulhari)
- **LinkedIn:** [linkedin.com/in/shivam-kulhari-797589307](https://www.linkedin.com/in/shivam-kulhari-797589307/)

---

© 2026 Shivam Kulhari
