# TechFixDesk — Complete Website Package

A multi-page static tech blog for Vercel. Plain HTML, CSS and JavaScript; no build step or npm dependencies required.

## Included
- Responsive homepage, search page, dark mode, mobile navigation, FAQ
- About, Contact, Privacy Policy, Terms of Use, Disclaimer, Editorial Policy, HTML sitemap
- Six category pages and eight original starter troubleshooting articles
- Shared CSS and JavaScript, JSON article reference data
- `robots.txt`, `sitemap.xml`, canonical and Open Graph metadata, Article structured data, and `vercel.json`

## Deploy to Vercel
1. Extract this ZIP; keep `index.html` at the project root.
2. Replace every occurrence of `https://YOUR-VERCEL-PROJECT.vercel.app` with your actual Vercel domain or custom domain. Update the canonical tags and JSON-LD in HTML, plus `robots.txt` and `sitemap.xml`.
3. Push the folder to a GitHub repository and import it at https://vercel.com/new, or use Vercel's supported static deployment workflow.
4. Choose no framework preset and no build command for this plain static site. If required, set output directory to `.`.
5. Deploy and test `/`, `/robots.txt`, `/sitemap.xml`, and multiple article links.
6. Configure the final domain in Vercel and ensure sitemap/canonical URLs use that domain.

## Before launch
- Replace `REPLACE-WITH-YOUR-EMAIL@example.com` in `contact.html`. The contact form opens a visitor's email application; it does not send to a server. Connect a form endpoint/serverless function if you need direct submission.
- Review and customize legal pages for your jurisdiction and actual business practices. They are starter templates, not legal advice.
- The included starter guides are initial editorial drafts. Verify each instruction against current official documentation and your target OS versions before publishing; do not claim hands-on testing unless performed.
- Search is client-side and covers the cards included in `search.html`. Add each new post there and to the homepage/category pages/sitemaps as needed. `data/articles.json` is a reference dataset; it does not auto-build pages.
- No database, CMS, comments, newsletter service, analytics, contact backend, or favicon is included. Do not advertise newsletter functionality until connected.
- After deployment, submit `/sitemap.xml` in Google Search Console. Indexing is not guaranteed.

## Editing and adding posts
Copy an existing file from `articles/`, update its title, description, canonical URL, text, structured data, date and related links. Add the article to `data/articles.json`, homepage/search/category lists, `sitemap.html`, and `sitemap.xml`. Keep content useful, accurate, and distinct rather than publishing thin or repetitive pages.

TechFixDesk is an independent educational website and is not affiliated with Microsoft, Google, or device manufacturers.
