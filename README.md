# Mehrab Hussain Zuhan - Personal Academic Website

This is a complete static personal website designed for graduate scholarship and professor outreach. It uses only HTML, CSS, and JavaScript, so it is free to host on Netlify, GitHub Pages, Cloudflare Pages, or Vercel.

## What is included

- `index.html` - all website sections and content
- `styles.css` - responsive formal academic design
- `script.js` - mobile menu, reveal animation, and footer year
- `netlify.toml` - optional Netlify configuration
- `assets/files/Mehrab_Hussain_Zuhan_CV.pdf` - downloadable CV
- `assets/files/Mehrab_Hussain_Zuhan_LinkedIn_Profile.pdf` - source LinkedIn export, included for your reference
- `assets/img/` - profile, project, certificate, and gallery placeholders

## Best free deployment option: Netlify

1. Go to Netlify and create a free account.
2. From your Netlify dashboard, choose **Add new site**.
3. Choose **Deploy manually**.
4. Drag and drop the whole `mehrab_personal_website` folder, or upload the ZIP file.
5. Netlify will give you a free URL like `https://your-name.netlify.app`.
6. Rename the site from Netlify settings to something professional, such as `mehrab-zuhan.netlify.app` if available.

## How to add your own photos and certificates

The site is already prepared with placeholder image slots. Replace these files inside `assets/img/` with your own images. Keep the same filename to avoid editing the HTML.

### Important replacements

- Replace `profile-placeholder.svg` with a professional portrait.
  - Recommended name if using JPG: `profile.jpg`
  - Then update the image path in `index.html` from `assets/img/profile-placeholder.svg` to `assets/img/profile.jpg`.
- Replace project placeholders:
  - `project-era.svg`
  - `project-vfd.svg`
  - `project-power-factor.svg`
  - `project-lab-kit.svg`
  - `project-transformer.svg`
  - `project-robotics.svg`
- Replace certificate placeholders:
  - `certificate-research-assistant.svg`
  - `certificate-industrial-training.svg`
  - `certificate-mentorship.svg`
  - `certificate-robo-soccer.svg`
  - `certificate-lfr.svg`
  - `certificate-robofest.svg`
- Replace gallery placeholders:
  - `photo-lab.svg`
  - `photo-project.svg`
  - `photo-conference.svg`
  - `photo-award.svg`

## Recommended image sizes

- Profile photo: square or vertical image, at least 900 x 1000 px.
- Project images: landscape image, at least 1200 x 750 px.
- Certificates: landscape or scanned certificate image, at least 1200 px wide.
- Gallery images: square or landscape, at least 1000 px wide.

## Things to update later

- Add Google Scholar, ORCID, GitHub, ResearchGate, or personal domain links when available.
- Replace `https://example.com` inside the JSON-LD script in `index.html` with your real website URL after deployment.
- Update publication links or DOI links once they are live.
- Replace the CV PDF with your newest CV when needed, keeping the same filename: `assets/files/Mehrab_Hussain_Zuhan_CV.pdf`.

## Local preview

You can open `index.html` directly in your browser. For a cleaner local server preview, run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.
