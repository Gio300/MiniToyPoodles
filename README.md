# MiniToyPoodles.com

A static website for Mini Toy Poodles breeding and adoption information.

## Project Structure

```
├── index.html          # Main website page
├── assets/
│   ├── images/        # Place your puppy images here
│   └── videos/        # Place your puppy videos here
└── README.md          # This file
```

## Image and Video Guidelines

### Images
- **Hero image**: `assets/images/hero.jpg` (recommended size: 1920x1080px)
- **Puppy photos**: `assets/images/puppy1.jpg`, `puppy2.jpg`, `puppy3.jpg` (recommended size: 500x500px)
- **Video thumbnail**: `assets/images/video_thumbnail.jpg` (recommended size: 500x500px)

### Videos
- **Puppy video**: `assets/videos/puppy_video.mp4` (recommended format: MP4, max 50MB)

## Deployment Instructions

### GitHub Pages Setup

1. **Create a new repository** on GitHub named `minitoypoodles.github.io`
2. **Upload your files** to the repository
3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

### Custom Domain Setup (minitoypoodles.com)

1. **Add CNAME file** to your repository root:
   ```
   minitoypoodles.com
   ```

2. **Configure DNS** with your domain provider:
   - Add a CNAME record: `www` → `minitoypoodles.github.io`
   - Add an A record: `@` → `185.199.108.153`
   - Add an A record: `@` → `185.199.109.153`
   - Add an A record: `@` → `185.199.110.153`
   - Add an A record: `@` → `185.199.111.153`

3. **Enable HTTPS** in GitHub Pages settings (automatic after DNS propagation)

## Adding Your Content

1. **Replace placeholder images**:
   - Upload your hero image as `assets/images/hero.jpg`
   - Upload puppy photos as `assets/images/puppy1.jpg`, `puppy2.jpg`, `puppy3.jpg`
   - Upload video thumbnail as `assets/images/video_thumbnail.jpg`

2. **Add videos**:
   - Upload your puppy video as `assets/videos/puppy_video.mp4`

3. **Customize content**:
   - Edit `index.html` to update text content
   - Modify CSS variables in the `:root` section to change colors
   - Add more images to the gallery by duplicating the `<img>` tags

## Features

- **Responsive design** that works on all devices
- **Minimal UI** with clean, professional appearance
- **Optimized for GitHub Pages** deployment
- **SEO-friendly** with proper meta tags
- **Fast loading** with optimized structure

## Support

For questions about deployment or customization, contact: info@minitoypoodles.com
