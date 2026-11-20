# BAT PARMAR / VIDYAGRAM Website

Static build of the BAT PARMAR (Parmar SSC Free Batches & Parmar Academy) website.

Originally from Lovable.app. Cleaned and prepared for static hosting.

## Deploy

### Vercel (recommended)
1. Push this repo to GitHub
2. Import the repo in [Vercel](https://vercel.com)
3. Framework Preset: Other / Static
4. Deploy

Or use Vercel CLI:
```bash
npx vercel
```

### GitHub Pages
- Enable Pages from the `main` branch / root
- Note: Client-side routing may need a 404.html copy of index.html

## Notes
- This is a static SPA. Backend APIs (Supabase, classx.co.in, Cloudflare workers) must remain available and allow CORS from your domain.
- Telegram WebApp script is included.
