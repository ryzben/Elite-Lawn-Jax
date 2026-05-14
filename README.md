# Elite Trusted Services

Static marketing website for Elite Lawn Jax, a lawn care service operated by Elite Trusted Services LLC in Jacksonville, Florida.

## Project Structure

- `Elite Trusted Services/index.html` - Main single-page website. Contains HTML, embedded CSS, and embedded JavaScript.
- `Elite Trusted Services/pics/` - Image assets used by the website.
- `Pics/` - Duplicate/source image assets, including business card images.

## Site Notes

- Brand shown on the site: `Elite Lawn Jax`
- Legal/business name: `Elite Trusted Services LLC`
- Phone: `(904) 608-6076`
- Email: `info@elitelawnjax.com`
- Service area: Jacksonville, FL and surrounding areas
- Domain referenced in SEO tags: `https://www.elitelawnjax.com/`
- Domain ownership/hosting: `elitelawnjax.com` is owned by the client and hosted through Hostinger.

## Current Implementation

The site is a standalone static HTML page with:

- SEO metadata and LocalBusiness structured data
- Fixed navigation and mobile menu
- Hero section
- Services grid
- Why choose us section
- About section
- Testimonials
- Contact section with phone, WhatsApp, email, service areas, and a quote form that opens a prefilled email draft
- Footer

## Important Follow-Ups

- The contact form currently opens the visitor's email app with a prefilled message to `info@elitelawnjax.com`. For direct lead capture, connect it to a backend or form service.
- The project folder is not currently a Git repository.
- Some icon/emoji characters may display as mojibake in terminals if encoding is not read as UTF-8. Check the rendered page in a browser before changing visual characters.
- There are duplicate image assets in both `Pics/` and `Elite Trusted Services/pics/`; confirm which folder is used before deleting or replacing files.

## How To Preview

Open `Elite Trusted Services/index.html` directly in a browser, or serve the folder with any static file server.

Example:

```powershell
cd "Elite Trusted Services"
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Hostinger Deployment Notes

For Hostinger hosting, upload the contents of `deploy/` into the site's `public_html` directory. The `deploy/` folder is a clean upload package generated from `Elite Trusted Services/`.

Expected live structure:

```text
public_html/index.html
public_html/pics/grass-cutting-jacksonville.jpg
public_html/pics/lawn-maintenance-plans.jpg
public_html/pics/edging-trimming.jpg
public_html/pics/yard-cleanup-debris-removal.jpg
public_html/pics/bush-hedge-trimming.jpg
public_html/pics/commercial-lawn-care.jpg
```

After upload, check both:

- `https://elitelawnjax.com`
- `https://www.elitelawnjax.com`

Make sure Hostinger SSL is enabled so the site loads over HTTPS.
