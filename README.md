# VisaDash

**Your complete visa dashboard** — H1B case tracking, wage validation, employer grading, transfer risk, visa bulletin, and salary explorer. Powered by official US government data, updated automatically.

🌐 **Live site:** https://YOUR_USERNAME.github.io/visadash

## Data

All JSON files in `/data/` are auto-updated by the [pipeline repo](https://github.com/YOUR_USERNAME/visadash-pipeline) (private):

| File | Source | Updated |
|------|--------|---------|
| `data/visa_bulletin.json` | travel.state.gov | Monthly |
| `data/processing_times.json` | USCIS egov API | Monthly |
| `data/wage_data.json` | DOL OFLC LCA Disclosure | Quarterly |
| `data/employers.json` | USCIS H-1B Employer Hub | Annually |

## Deploy to custom domain

1. Buy `visadash.com` on Namecheap (~$12/yr)
2. GitHub → Settings → Pages → Custom domain → enter `visadash.com`
3. Namecheap DNS → CNAME: `www` → `YOUR_USERNAME.github.io`
4. Add A records pointing to GitHub Pages IPs (listed in GitHub Pages docs)
5. Done — HTTPS auto-configured

## License

© 2026 KKB CoRi Technologies Private Limited. All rights reserved.
Data sourced from US Department of Labor and USCIS — public government records.
