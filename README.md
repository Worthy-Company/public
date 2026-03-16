# public

content from Worthy Company. Served at **worthycompany.org**.

- **Site**: https://worthycompany.org  

### Custom domain (worthycompany.org)

- This repo has a **CNAME** file so GitHub Pages serves the site for `worthycompany.org`.
- In the repo: **Settings → Pages → Custom domain** → enter `worthycompany.org` → Save. GitHub will show the DNS records to use.
- At your domain registrar for worthycompany.org, add:
  - **A records** for `worthycompany.org` → `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
  - (Optional) **CNAME** for `www.worthycompany.org` → `worthy-company.github.io`
- After DNS propagates, enable **Enforce HTTPS** in Pages settings.