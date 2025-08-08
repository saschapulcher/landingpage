
# Quick Upload to GitHub (landingpage repo)

1) Upload the two folders to your repo root:
   - /impressum/index.html
   - /datenschutz/index.html

2) (Optional) Upload these redirects to the repo root (so old .html links still work):
   - /impressum.html  (redirects to /impressum/)
   - /datenschutz.html (redirects to /datenschutz/)

3) In your index.html footer, link like this (no leading slash):
   <a href="impressum/">Impressum</a> | <a href="datenschutz/">Datenschutzerklärung</a>

4) Wait ~30–90 seconds for GitHub Pages to deploy, then test:
   - https://saschapulcher.github.io/landingpage/impressum/
   - https://saschapulcher.github.io/landingpage/datenschutz/
   - https://provisionsfreie-kapitalanlagen.de/impressum/
   - https://provisionsfreie-kapitalanlagen.de/datenschutz/
