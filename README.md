# JUA Solution LLC — Website

Official website for **JUA Solution LLC** — Enterprise Technology Partners based in Irvine, California.

🌐 **Live site:** [https://juasolution.com](https://juasolution.com)  
📅 **Book a meeting:** [Microsoft Bookings](https://outlook.office365.com/owa/calendar/JUAUSA@gocomx.com/bookings/)  
📁 **Documents folder:** [SharePoint](https://gocomx.sharepoint.com/:f:/g/IgBRgG3EZ3ZNR4pJtexxdb5NAQRYwlKUk6pOY6VYF5ogcWM?e=CkC1Hx)

---

## Stack

- Pure HTML5 / CSS3 / Vanilla JS — no build tools required
- Microsoft Fluent Design language (white + `#0078d4` blue)
- Google Fonts: Inter
- Fully responsive, mobile-friendly

## File Structure

```
/
├── index.html          # Main website (single-file)
└── README.md           # This file
```

## Services Covered

- Microsoft Dynamics 365 Finance & Operations (D365 F&O)
- EDI — TrueCommerce Foundry
- SPS Commerce / Data Mason
- Microsoft Azure
- Power Platform (Power Apps, Power Automate, Power BI)
- AI & Intelligent Automation (Azure OpenAI, Copilot)
- SharePoint & Microsoft 365
- Ticket & Help Desk Systems
- Managed Services (24/7)

## Deploy to GitHub Pages

1. Push to the `main` branch of `https://github.com/CholeGocomx/juasolution.git`
2. Go to **Settings → Pages**
3. Set source to **Deploy from branch → main → / (root)**
4. Site will be live at `https://cholegocomx.github.io/juasolution/`

To use the custom domain `juasolution.com`:
1. Add a `CNAME` file containing `juasolution.com`
2. Point your DNS A records to GitHub Pages IPs:
   ```
   185.199.108.153
   185.199.109.153
   185.199.110.153
   185.199.111.153
   ```
3. Enable **Enforce HTTPS** in Pages settings

## Update Document URLs

When individual SharePoint share links are available for each PDF, update these two `href` values in `index.html`:

| Document | Variable to update |
|---|---|
| Master Services Agreement | `#msa-download` button href |
| Statement of Work | `#sow-download` button href |

## Contact

- 📧 info@juasolution.com  
- 📍 51 Linhaven, Irvine, CA 92602  
- 🌐 juasolution.com
