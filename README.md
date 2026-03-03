# Freelance Developer Website

Single-page personal website for a freelance Magento 2 frontend developer.

## Quick Start

Open `index.html` in a browser to preview locally.

## Deployment — GitHub Pages

1. Create a new GitHub repository
2. Push the files:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/yourusername/your-repo.git
   git push -u origin main
   ```
3. Go to **Settings → Pages → Source**: select `main` branch, `/ (root)` folder
4. Your site will be live at: `https://yourusername.github.io/your-repo`

### Custom Domain

1. Add a file called `CNAME` with your domain name (e.g. `yourdomain.com`)
2. Configure your DNS to point to GitHub Pages ([docs](https://docs.github.com/en/pages/configuring-a-custom-domain-for-github-pages))

## Deployment — Netlify (alternative)

1. Go to [netlify.com](https://www.netlify.com) and sign up
2. Drag and drop the project folder to deploy
3. Optionally connect to your GitHub repo for automatic deploys

## Contact Form Setup (Formspree)

1. Sign up at [formspree.io](https://formspree.io) (free tier)
2. Create a new form
3. Copy your form ID (e.g. `xpznqkdl`)
4. In `index.html`, replace `YOUR_FORM_ID` in the form action:
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

## Customisation

- **Name & details**: search for "Your Name", "yourdomain.com", and placeholder text in `index.html`
- **Projects**: edit the project cards in the `#work` section
- **Colors**: update CSS variables in the `:root` block at the top of the `<style>` tag
- **LinkedIn**: replace the placeholder `href="#"` on the LinkedIn link in the contact section
