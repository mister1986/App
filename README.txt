SPIKER — INTERNET DEPLOYMENT

This folder is ready for a static HTTPS host.

Fastest option: Netlify Drop
1. Open https://app.netlify.com/drop
2. Drag the entire spiker-deploy folder onto the page.
3. Netlify gives you a public HTTPS URL.
4. Open that URL and test YouTube mode.

Other supported hosts:
- Cloudflare Pages
- Vercel
- GitHub Pages

Important:
- Do not distribute index.html as a file:// download for YouTube embedding.
- Users should visit the hosted HTTPS URL.
- Some YouTube videos may still disallow embedding; the app should offer Open on YouTube as fallback.
- Browser speech recognition still requires permission for the selected input/virtual audio cable.
