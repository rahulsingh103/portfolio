# Rahul Singh Portfolio Website

This is my personal portfolio website built with HTML, CSS, and JavaScript.

## Deployment Instructions

### Option 1: Deploy to Netlify (Recommended)

1. Create a Netlify account at https://www.netlify.com/
2. Install Netlify CLI:
   ```bash
   npm install -g netlify-cli
   ```
3. Login to Netlify:
   ```bash
   netlify login
   ```
4. Deploy the site:
   ```bash
   netlify deploy
   ```
5. Follow the prompts to connect your GitHub repository
6. Set up your custom domain (rahulsingh.com) in Netlify's domain settings

### Option 2: Deploy to GitHub Pages

1. Create a GitHub repository named `rahulsingh.github.io`
2. Push your code to the repository
3. Go to repository Settings > Pages
4. Select the main branch as the source
5. Your site will be available at https://rahulsingh.github.io

### Option 3: Traditional Hosting

1. Upload all files to your web hosting provider's root directory
2. Configure your domain's DNS settings to point to your hosting provider
3. Set up SSL certificate for HTTPS

## Local Development

To run the site locally:

1. Clone the repository
2. Open `index.html` in your browser
3. Or use a local server:
   ```bash
   python -m http.server 8000
   ```
   Then visit http://localhost:8000

## Customization

- Edit `index.html` to update content
- Modify `css/style.css` to change styling
- Update `js/main.js` for interactive features 