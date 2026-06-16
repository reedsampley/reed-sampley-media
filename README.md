# Reed Sampley Media — Website

This is a high-end, modern, cinematic static website built specifically for Reed Sampley Media using Grok Build.

## Current Status
- Fully functional single-file site (index.html)
- Premium tech / Apple / x.ai inspired aesthetic (deep blacks, elegant typography, generous space, subtle motion)
- All content pulled directly from your detailed bio and real client work
- Filterable portfolio with real projects
- Working project detail modals
- Contact form (ready for Netlify Forms)
- Mobile responsive + keyboard friendly

## How to Preview Right Now
```bash
cd ~/reed-sampley-media
python -m http.server 8000
```
Then open http://localhost:8000 in your browser.

## How to Make It Yours (Next Steps)

### 1. Replace Images (Most Important)
- The current images are high-quality placeholders from picsum.photos
- Open your actual photo library (you have thousands of incredible shots)
- Replace the `src` attributes with your real images or host them and link to them
- For video: Replace the "Watch Reel" buttons with real YouTube/Vimeo embeds or self-hosted players

Recommended structure later:
```
reed-sampley-media/
├── index.html
├── assets/
│   ├── photos/
│   └── videos/
```

### 2. Deploy (Extremely Easy)
**Option A — Netlify (Recommended for you)**
1. Go to netlify.com and drag the entire `reed-sampley-media` folder onto the dashboard
2. Your site will be live instantly at a random .netlify.app address
3. Add your custom domain in Netlify settings
4. For the contact form: Add `netlify` attribute to the form tag (see comments in HTML) and redeploy — forms will just work

**Option B — Cloudflare Pages**
Also excellent and very fast.

### 3. Domain (Keep it at Wix)
You do NOT need to move your domain registration.
Just go into your Wix domain DNS settings and point it to the new host (Netlify or Cloudflare will give you the exact A record + CNAME values).

### 4. Future Improvements (Easy to Add Later)
- Add real video embeds in the project modals
- Create a dedicated /work page if the portfolio grows huge
- Add a subtle hero background video (you have amazing drone footage)
- Turn the contact form into a proper lead capture
- Add a "Latest Work" or "Reel" page

## Design Philosophy
- Modern, cool, impressive — tech-website energy (x.ai / Apple)
- Show, don't tell — heavy on imagery and real client stories
- Personal but professional — your story (age, journey, pride in America, Olivia, outdoors, 4Runner, home ownership) is woven in without being distracting
- Cinematic but clean

The site is ready to impress high-profile clients immediately.

---

Built live with Grok Build in your terminal. All content is 100% based on the detailed story you shared.

Let me know what to change first (hero copy, specific projects to highlight more, color accents, animations, anything). We can iterate instantly.