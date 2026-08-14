# DSE CAP Round 2 Allotment Search — FEC Official

## What this website does
- Exact full-name search (case-insensitive)
- Exact Application ID search
- Partial names do not return results
- Duplicate full names are shown with Application IDs
- Mobile-friendly result card
- FEC Official branding and WhatsApp community promotion
- Static-site friendly for GitHub Pages

## Add the official data
After the official DSE CAP Round 2 allotment list is published, replace `data.json` with records in this format:

[
  {
    "name": "FULL NAME",
    "applicationId": "APPLICATION ID",
    "college": "COLLEGE NAME",
    "branch": "BRANCH NAME",
    "preference": "12",
    "meritNo": "12345",
    "category": "OPEN",
    "status": "Allotted / Betterment / No Change / Newly Allotted"
  }
]

Do not put passwords, OTPs, dates of birth, phone numbers, or other confidential information into the public JSON.

## Deploy on GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `data.json`, and `fec-logo.png`.
3. Open Settings → Pages.
4. Choose the main branch and root folder.
5. Save and open the generated GitHub Pages URL.

The site is a static frontend. The official allotment data must be sourced from the DSE/DTE publication and checked before publishing.
