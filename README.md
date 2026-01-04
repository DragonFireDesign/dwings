# DEATHWINGS - Coming Soon Landing Page

A minimal, fast-loading placeholder page for the Deathwings brand.

## Features

- Dark, minimalist aesthetic
- Email signup form (UI only)
- Mobile responsive design
- Fast loading with Tailwind CSS CDN
- No build process required

## Local Development

Simply open `index.html` in your browser. No build step needed.

## Deploying to Netlify

### Option 1: Drag and Drop (Fastest)

1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag the entire project folder (or just the `index.html` file)
3. Your site is live!

### Option 2: Git Deploy (Recommended)

1. Push this project to a GitHub repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin <your-repo-url>
   git push -u origin main
   ```

2. Go to [Netlify](https://app.netlify.com/)
3. Click "Add new site" → "Import an existing project"
4. Connect to your GitHub repository
5. Deploy settings:
   - **Build command:** Leave empty
   - **Publish directory:** `/` (root)
6. Click "Deploy site"

### Option 3: Netlify CLI

1. Install Netlify CLI:
   ```bash
   npm install -g netlify-cli
   ```

2. Deploy:
   ```bash
   netlify deploy --prod
   ```

## Custom Domain

After deploying to Netlify:
1. Go to Site settings → Domain management
2. Click "Add custom domain"
3. Follow the instructions to configure your DNS

## Adding Email Backend Later

Currently the form just shows a confirmation message. When ready to capture emails, you can:
- Use Netlify Forms (add `netlify` attribute to form)
- Integrate with services like Mailchimp, ConvertKit, or Buttondown
- Build a custom backend API

## Project Structure

```
.
├── index.html           # Main landing page
├── tailwind.config.js   # Tailwind configuration
├── README.md           # This file
└── .gitignore          # Git ignore rules
```

## License

All rights reserved.
