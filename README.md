# UNCP Introduction Website

This project is a professional, responsive website created as a short introduction to The University of North Carolina at Pembroke for the post-project assignment. It is built with plain HTML, CSS, and JavaScript so it is easy to understand, easy to customize, and simple to deploy on GitHub Pages.

## Features

- Responsive single-page layout
- Mobile navigation menu
- Event filtering controls
- Animated content reveals on scroll
- Accessible FAQ section using `<details>`
- Contact form with client-side validation
- Clean structure for future expansion

## Project Structure

```text
.
├── index.html
├── styles.css
├── script.js
└── README.md
```

## How to Run

Because this is a static website, you can open `index.html` directly in a browser.

If you want a local server, you can run one of these commands in the project folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Customization Ideas

- Add official UNCP photos or campus imagery
- Expand with more university pages or sections
- Connect the contact form to Formspree, Netlify Forms, Supabase, or a custom backend
- Add a gallery, news, or announcement section
- Link the site to official UNCP social media

## GitHub Pages Deployment

1. Create a new GitHub repository.
2. Upload these files to the repository.
3. Open the repository settings on GitHub.
4. Go to `Pages`.
5. Set the source branch to `main` and the folder to `/ (root)`.
6. Save the settings and wait for GitHub Pages to publish the site.

## Suggested Submission Notes

For the final submission, it helps to mention:

- The site is fully responsive
- It includes interactive JavaScript features
- It is deployable on GitHub Pages
- It is easy to maintain because it uses a simple frontend stack

## Future Improvements

If you want to impress further, a next version could include:

- Department spotlight pages
- Admissions or application resources
- Database-backed announcements
- Interactive campus guide
- Real-time university updates
