# Jess Bellissimo Personal Website

Clean, minimal static website built with HTML/CSS.

## Structure

```
jess-website/
├── index.html       # Homepage
├── work.html        # Case studies
├── thinking.html    # Essays (coming soon)
├── reading.html     # Book list
├── now.html         # Current focus
├── styles.css       # All styling
└── README.md        # This file
```

## Deployment Options

### Option 1: Netlify (Recommended - Easiest)

1. Sign up for free account at [netlify.com](https://netlify.com)
2. Drag and drop the entire `jess-website` folder onto Netlify dashboard
3. Get instant URL like `yoursite.netlify.app`
4. Point your domain:
   - In Netlify: Site settings → Domain management → Add custom domain
   - In your domain registrar (wherever jessbellissimo.com is registered):
     - Add A record: `185.199.108.153`
     - Add A record: `185.199.109.153`
     - Add A record: `185.199.110.153`
     - Add A record: `185.199.111.153`
     - Or add CNAME record: `yoursite.netlify.app`

### Option 2: Vercel

1. Sign up at [vercel.com](https://vercel.com)
2. Click "Add New Project"
3. Upload files or connect GitHub repo
4. Deploy automatically
5. Add custom domain in project settings

### Option 3: GitHub Pages (Free, requires GitHub account)

1. Create new repository called `jessbellissimo.github.io`
2. Upload all files to repository
3. Enable GitHub Pages in repository settings
4. Site lives at `jessbellissimo.github.io`
5. Add custom domain in settings

## Updating Content

### To Add Essays

1. Create new HTML file in root (e.g., `essay-title.html`)
2. Copy structure from `thinking.html`
3. Write essay content
4. Update `thinking.html` to link to new essay
5. Redeploy (Netlify/Vercel auto-deploy on file changes)

### To Update Book List

1. Edit `reading.html`
2. Add books to appropriate sections
3. Save and redeploy

### To Update Now Page

1. Edit `now.html`
2. Update "Last updated" date at bottom
3. Save and redeploy

## Design Notes

- Clean, minimal typography inspired by Patrick Collison
- Mobile-responsive
- No JavaScript required
- Fast loading
- Easy to maintain

## Customization

All colors and spacing controlled in `styles.css` via CSS variables:

```css
:root {
    --text-primary: #1a1a1a;
    --text-secondary: #4a4a4a;
    --accent: #0066cc;
    --background: #ffffff;
}
```

Change these values to adjust the entire site's appearance.

## Current Status

- Homepage: Complete
- Work: Complete with 3 case studies
- Thinking: Essay list (essays to be written)
- Reading: Template (add your books)
- Now: Complete

## Next Steps

1. Deploy to Netlify/Vercel
2. Point jessbellissimo.com domain
3. Write first essay
4. Populate reading list
5. Start posting on Twitter to drive traffic
