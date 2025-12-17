# Cloudflare Pages Deployment

This directory contains the modernized Productivity Mon landing page, ready for deployment.

## Deployment Instructions

1.  **Direct Upload**: You can drag and drop the `website` folder into the Cloudflare Pages dashboard.
### 2. Git Integration (Recommended)
- Push your code to GitHub.
- Connect your repository in the Cloudflare Pages dashboard.
- **IMPORTANT**: Set the **Build command** to be **EMPTY** (delete everything in that box).
- Set the **Build output directory** to **`.`** (just a single period).
- Save and deploy.

## Directory Structure
- `index.html`: Main landing page.
- `assets/`: Icons and images.
- `js/`: Interactivity and animations.
- `styles/`: Core design and theme.
