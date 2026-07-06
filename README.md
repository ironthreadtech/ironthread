# IronThread Tech Website

This is a simple static website for IronThread Tech, designed for GitHub Pages.

## Files Included

- `index.html` - Homepage
- `services.html` - Services page
- `about.html` - About page
- `contact.html` - Contact page
- `privacy.html` - Privacy policy
- `styles.css` - Site styling
- `script.js` - Small script for dynamic footer year

## How to Publish on GitHub Pages

1. Create a GitHub account if you do not already have one.
2. Create a new repository named:
   `ironthreadtech.com`
   or
   `ironthreadtech-site`
3. Upload all files from this folder to the repository.
4. In GitHub, go to:
   Settings → Pages
5. Under "Build and deployment":
   - Source: Deploy from a branch
   - Branch: `main`
   - Folder: `/root`
6. Save.

GitHub will give you a temporary URL like:

`https://yourusername.github.io/ironthreadtech-site/`

## Connecting ironthreadtech.com

Once GitHub Pages is working, add your custom domain in:

Settings → Pages → Custom domain

Enter:

`ironthreadtech.com`

GitHub will tell you which DNS records to add in Namecheap.

Usually this means:

- A records for the root domain
- CNAME for `www`

Do not delete your Microsoft 365 email records:
- MX
- SPF TXT
- DKIM CNAMEs
- Autodiscover CNAME
- DMARC TXT

Those are for email and should remain untouched.

## Recommended Next Edits

- Replace the text with your exact final messaging.
- Add your official logo when ready.
- Add your LinkedIn URL on the contact page.
- Consider adding a scheduling link later, after your domain reputation is stronger.
