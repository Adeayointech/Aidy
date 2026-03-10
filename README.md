# Aidy Website

This folder contains the official website for Aidy with the required pages for Google OAuth verification.

## Files Included

- **index.html** - Home page describing Aidy
- **privacy.html** - Privacy Policy (required for OAuth)
- **terms.html** - Terms of Service (required for OAuth)
- **style.css** - Styling for all pages

## Deployment Options

### Option 1: GitHub Pages (Recommended - Free & Easy)

1. Create a new repository on GitHub (e.g., `aidy-website`)
2. Push the `website` folder contents to the repository
3. Go to repository Settings → Pages
4. Select main branch and root folder
5. Your site will be available at: `https://yourusername.github.io/aidy-website/`

### Option 2: Vercel (Professional - Free)

1. Install Vercel CLI: `npm install -g vercel`
2. Navigate to the website folder: `cd website`
3. Run: `vercel`
4. Follow the prompts to deploy
5. Your site will be available at: `https://your-project.vercel.app`

### Option 3: Firebase Hosting (Already using Firebase)

1. Install Firebase CLI: `npm install -g firebase-tools`
2. Run: `firebase init hosting`
3. Set public directory to `website`
4. Deploy: `firebase deploy --only hosting`
5. Your site will be available at: `https://your-project.web.app`

### Option 4: Netlify (Drag & Drop - Free)

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the `website` folder
3. Instant deployment!
4. Your site will be available at: `https://your-site.netlify.app`

## For Google OAuth Verification

Once deployed, add these URLs to your Google Cloud Console:

1. **Application homepage**: `https://your-domain.com/`
2. **Privacy Policy**: `https://your-domain.com/privacy.html`
3. **Terms of Service**: `https://your-domain.com/terms.html`

## Customization

Before deploying, you may want to:

1. Replace `privacy@aidyapp.com` and `support@aidyapp.com` with your actual email addresses
2. Add your actual download link in the "Download for Android" button
3. Update any specific details about your implementation
4. Add your custom domain if you have one

## Testing Locally

To test the website locally:

1. Open `index.html` in your browser
2. Or use a simple HTTP server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Then visit http://localhost:8000
   ```

## Notes

- The website is fully responsive and mobile-friendly
- All pages use a clean, minimalist design matching your app
- Privacy policy includes Gmail API disclosure as required by Google
- Terms of service covers all app features
