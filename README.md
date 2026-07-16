# Developer Portfolio

This repository contains the source code for my personal portfolio website, designed and developed to showcase my projects, technical skills, and professional journey.

Built with HTML, CSS, and JavaScript and deployed using Netlify, this portfolio demonstrates my approach to creating responsive, accessible, and user-focused web experiences. The project serves as both a personal brand platform and a continuous learning environment where I apply front-end development practices, UX design principles, and modern web technologies.

Future updates will include additional case studies, development projects, cloud-based experiments, and AI-focused work.

## Edit the portfolio

This is a static website, so no framework or build step is required:

- Edit page text, projects, contact details, and links in `index.html`.
- Edit colors, spacing, typography, and layouts in `styles.css`.
- Edit the mobile menu and scroll animations in `script.js`.
- Replace each project link currently set to `#` with the live project or GitHub URL.
- Replace `hello@example.com`, the GitHub link, and the LinkedIn link with your own information.

To add a portrait, place an image in the project folder and replace the `portrait-placeholder` element in `index.html` with an image such as:

```html
<img class="portrait" src="your-photo.jpg" alt="Tamira Hawkins" />
```

## Preview locally

For a quick preview, double-click `index.html` to open it in your browser. To preview it with Netlify's local environment, run this command from the project folder:

```bash
/opt/buildhome/node-deps/node_modules/.bin/netlify dev --port 8889
```

Then open `http://localhost:8889` in a browser. Press `Ctrl+C` to stop the server.

## Publish changes

After editing and previewing the site, push it to the Git repository connected to Netlify:

```bash
git add .
git commit -m "Update portfolio website"
git push
```

Netlify redeploys the site automatically after the push.
