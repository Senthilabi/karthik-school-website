# Deployment Guide - Karthik School Website

## Current Status ✅
- [x] Website customized with school logo
- [x] Gallery page added with 6 placeholder items
- [x] Git repository initialized
- [x] Initial commit created
- [x] Configuration files added (README.md, .gitignore, netlify.toml)

## Next Steps

### 1. Push to GitHub

After creating your GitHub repository, run these commands:

```bash
# Navigate to the website directory
cd "c:\Users\senth\.gemini\antigravity\playground\tachyon-newton\Karthik School\Website"

# Add your GitHub repository as remote (replace YOUR_REPO_URL with actual URL)
git remote add origin YOUR_REPO_URL

# Push to GitHub
git branch -M main
git push -u origin main
```

### 2. Deploy to Netlify

**Option A: Connect GitHub to Netlify (Recommended)**
1. Go to [https://app.netlify.com](https://app.netlify.com)
2. Click "Add new site" → "Import an existing project"
3. Choose "GitHub" and authorize Netlify
4. Select your repository
5. Build settings are already configured in `netlify.toml`
6. Click "Deploy site"

**Option B: Drag and Drop**
1. Go to [https://app.netlify.com/drop](https://app.netlify.com/drop)
2. Drag the entire Website folder
3. Your site will be deployed instantly

### 3. Custom Domain (Optional)

Once deployed on Netlify:
1. Go to Site settings → Domain management
2. Add your custom domain (e.g., karthikschool.com)
3. Update DNS records as instructed by Netlify

## Website Structure

```
Website/
├── index.html          # Main website file
├── assets/
│   └── images/
│       └── logo.jpg    # School logo
├── README.md           # Project documentation
├── .gitignore          # Git ignore rules
└── netlify.toml        # Netlify configuration
```

## Pages Included

1. **Home** - Hero section with school highlights
2. **About** - Vision, mission, and leadership
3. **Academics** - Curriculum and higher secondary groups
4. **Facilities** - School infrastructure details
5. **Gallery** - Photo gallery (placeholder images)
6. **Admissions** - Admission process and online form
7. **Contact** - Contact information and location

## Next Customizations

To replace placeholder gallery images with real photos:
1. Add photos to `assets/images/gallery/` folder
2. Update the gallery section in `index.html` to use actual image paths
3. Commit and push changes

## Support

For any issues or questions, refer to the README.md file or contact the developer.
