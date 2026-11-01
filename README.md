# SRIDHAR NLP portfolio — fixed, single-file Vercel version

This update restores the original interactive design language: animated Buddy guide, navigation and tour, typing hero, confetti celebration, working browser text exercise previews for notebooks, interactive study cases, chat demo, and accessibility tools. It also retains DeepShield AI, 10-star breakdown, three notebook titles, three assignments and case-study research briefs.

## Easiest GitHub/Vercel update
1. In your GitHub repository, open `index.html`. Choose **Edit** or upload a replacement `index.html` at the repository root and commit.
2. **This one file includes its CSS**. No Tailwind CDN, build command, Node dependencies, or stylesheet folder is required for the design.
3. Vercel automatically deploys the new main-branch commit if connected. You can also redeploy in Vercel.
4. Hard refresh the site (Ctrl+Shift+R) after deployment.

## Optional assets
- Upload a real photo as `assets/profile.jpg` in GitHub. With no picture, a built-in avatar appears instead of a broken image. Photo uploads inside the website are browser-local previews only.
- You can provide the actual Jupyter notebooks in `notebooks/brown-corpus.ipynb`, `notebooks/practice-doc-1.ipynb`, `notebooks/practice-doc-2.ipynb`. The interactive example is JavaScript text analysis, **not** remote Python/Jupyter execution.

## Dependencies
Uses Google Fonts, Font Awesome and optional GSAP and confetti libraries through CDNs. The page remains readable and interactive if those optional assets fail, though icons/fonts and advanced scroll effects can differ. No server or paid API is needed.
