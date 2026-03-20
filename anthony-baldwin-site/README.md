# Anthony Baldwin — Personal Site

A static personal branding site, deployed via [Vercel](https://vercel.com).

## Project Structure

```
anthony-baldwin-site/
├── index.html        # Main page
├── public/           # Static assets (images, etc.)
├── vercel.json       # Vercel deployment config
├── .gitignore
└── README.md
```

## Before Launch Checklist

- [ ] Replace `mailto:anthony@[PLACEHOLDER].com` in the "Get in Touch" button with the real email address
- [ ] Replace `[CONTACT INFO PLACEHOLDER]` in the footer with real contact info
- [ ] Add real photos as `<img>` tags inside the `.photo-zone` divs in `index.html`
- [ ] Place any image files in the `public/` directory

## Deploy to Vercel

### First-time deploy (from project root)

```bash
npx vercel
```

Follow the prompts to link or create a Vercel project.

### Subsequent deploys

```bash
npx vercel --prod
```

### Deploy to production directly

```bash
npx vercel --prod
```

## Local Preview

Open `index.html` directly in a browser, or use any static file server:

```bash
npx serve .
```
