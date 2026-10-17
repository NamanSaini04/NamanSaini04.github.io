# Naman Saini — Professional Portfolio

Source repository for the public portfolio of Naman Saini.

**Target URL:** https://www.naman-saini.com  
**Temporary GitHub Pages URL (after activation):** https://namansaini04.github.io/

## Website files
- `index.html` — responsive portfolio, project filters and contact links
- `resume.html` — printable resume; use **Print / Save as PDF** in a browser
- `robots.txt`, `sitemap.xml`, `.nojekyll` — search indexing and Pages setup

The site is intentionally a static HTML/CSS/JavaScript project; no build step, subscription or web server required.

## Publish in GitHub Pages
1. Repository **Settings → Pages**.
2. Under **Build and deployment**, set **Source: Deploy from a branch**.
3. Select branch **main**, folder **/(root)**, and **Save**.
4. Wait for a successful deployment; test https://namansaini04.github.io.

## Safely connect naman-saini.com
1. In your **GitHub account Settings → Pages**, add the domain `naman-saini.com` and copy the unique verification TXT record.
2. Add that TXT record at the provider managing your domain DNS. Verify it in GitHub and leave it in DNS.
3. In this repository **Settings → Pages → Custom domain**, enter `www.naman-saini.com` and save.
4. Add DNS where your nameservers are managed:
   - CNAME host `www` → `NamanSaini04.github.io`
   - A host `@` → `185.199.108.153`
   - A host `@` → `185.199.109.153`
   - A host `@` → `185.199.110.153`
   - A host `@` → `185.199.111.153`
5. Remove only conflicting parking records for `www` or `@`. Retain TXT ownership-verification, email and other unrelated records.
6. When GitHub allows it, select **Enforce HTTPS**; test www and root-domain redirect.

For current instructions: [GitHub Pages custom domain](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site).

**Privacy:** A public portfolio makes contact details publicly accessible. This site's printable CV uses email and professional profile links rather than a phone number.
