AQSA WEBSITE + PROMOTIONS ADMIN (Decap CMS)

SETUP (one time)
1. Create a free GitHub account and a new repository named aqsa-website.
   Upload ALL files and folders from this package (index.html, admin, data, uploads).
2. Open admin/config.yml on GitHub, change YOUR-GITHUB-USERNAME to your username.
3. Create a free Netlify account -> Add new site -> Import from GitHub -> pick aqsa-website -> Deploy.
4. In Netlify: Site configuration -> Access & security -> OAuth -> Install provider -> GitHub
   (follow the prompts). This lets the admin page log in with GitHub.
5. Open https://YOUR-SITE.netlify.app/admin  -> Login with GitHub.

DAILY USE
- Go to /admin -> Website Content. You can edit three things:
  Promotions & Offers, Product Categories (with photos), and Store Details
  (name, address, hours, phone, email, social links).
- Example: Promotions & Offers -> add an offer (title, text,
  start date, end date, image) -> Publish. The site updates in about a minute.
- Offers outside their dates, or marked inactive, are hidden automatically.

NOTES
- Only people you add as collaborators on the GitHub repository can edit.
- Empty phone/email/social fields show as placeholders on the site until you fill them in.
