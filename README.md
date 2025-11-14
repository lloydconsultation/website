# Lloyd Consultation Website

This is a static website for Lloyd Consultation, hosted on GitHub Pages.

## Features

- Multi-page responsive design
- Hero section with background image
- Services overview
- Contact form powered by [Formspree](https://formspree.io/) API
- Modern CSS styling

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/lloydconsultation/website.git
   ```
2. **Edit content:**
   - Update `index.html` and other pages as needed.
   - Place your hero background image in the `images/` folder.
3. **Configure Formspree:**
   - Sign up at [Formspree](https://formspree.io/).
   - Create a new form and copy your endpoint URL.
   - Replace the `action` attribute in the contact form with your Formspree endpoint:
     ```html
     <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST"></form>
     ```

## Deployment

1. **Push changes to GitHub:**
   ```sh
   git add .
   git commit -m "Update site"
   git push origin main
   ```
2. **Enable GitHub Pages:**
   - Go to your repository's Settings > Pages.
   - Select the `main` branch and `/ (root)` folder.
   - Save and wait a few minutes for deployment.
   - If site is disabled ensure the branch is set to `main`

Your site will be live at:

```
https://lloydconsultation.github.io/website/
```

## License

MIT
