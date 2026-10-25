ORBIT STUDIO — VERCEL DEPLOY PACKAGE

FILES
- index.html   Main website entry point (keep this name)
- vercel.json  Minimal Vercel configuration for a static site

DEPLOY WITH VERCEL (recommended: GitHub import)
1. Extract ORBIT-Vercel.zip on your computer.
2. Create a new GitHub repository and upload index.html and vercel.json from this folder to the repository root.
3. Open https://vercel.com/new and connect/import that GitHub repository.
4. Framework Preset: Other
5. Build Command: leave empty
6. Output Directory: leave empty (or use ./ if Vercel asks)
7. Click Deploy.

NOTES
- Keep the main file named index.html and at the repository root.
- The page loads Google Fonts and Three.js from CDNs, so an internet connection is needed for those visual effects/fonts.
- This package is prepared for deployment; it has not itself been published to a public URL.
