# Needlemancer - Coming Soon Page

Static placeholder website for Needlemancer, a band-first platform for underground metal merch.

## Features

- Fully responsive, mobile-first design
- Underground metal aesthetic with clean layout
- Netlify Forms integration for email collection
- Single HTML file deployment
- No external dependencies (except Google Fonts)
- Accessible and SEO-friendly

## Deployment to Netlify

### Option 1: Drag and Drop
1. Zip the entire project folder
2. Go to [Netlify Drop](https://app.netlify.com/drop)
3. Drag and drop your folder
4. Done! Your site will be live instantly

### Option 2: Git Integration (Recommended)
1. Push your code to GitHub/GitLab/Bitbucket
2. Go to [Netlify](https://app.netlify.com)
3. Click "New site from Git"
4. Connect your repository
5. Build settings:
   - Build command: (leave empty)
   - Publish directory: `.` (current directory)
6. Click "Deploy site"

### Option 3: Netlify CLI
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod
```

## Form Submissions

Email submissions are handled by Netlify Forms. Once deployed:

1. Go to your Netlify site dashboard
2. Navigate to Forms tab
3. You'll see all submissions from the "launch-notifications" form
4. Optional: Set up email notifications in Netlify Forms settings

## Files

- `index.html` - Main landing page
- `thank-you.html` - Form submission success page
- `netlify.toml` - Netlify configuration
- `assets/` - Logo images
- `README.md` - This file

## Local Development

Simply open `index.html` in your browser. No build process required.

## Custom Domain

After deployment, you can add your custom domain (needlemancer.com):

1. Go to Netlify site settings
2. Domain settings > Add custom domain
3. Follow Netlify's instructions to configure DNS

## Tech Stack

- HTML5
- CSS3 (embedded)
- Google Fonts (Cabin Sketch)
- Netlify Forms

## License

All rights reserved - Needlemancer 2025
