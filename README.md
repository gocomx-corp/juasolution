# JUA Solution LLC — Website

Official website for **JUA Solution LLC** — Enterprise Technology Partners.

🌐 **Domain:** juasolution.com  
📅 **Book a meeting:** [Microsoft Bookings](https://outlook.office365.com/owa/calendar/JUAUSA@gocomx.com/bookings/)  
📁 **Documents:** [SharePoint Folder](https://gocomx.sharepoint.com/:f:/g/IgBRgG3EZ3ZNR4pJtexxdb5NAQRYwlKUk6pOY6VYF5ogcWM?e=CkC1Hx)

---

## First-Time Push to GitHub (from your machine)

### Step 1 — Install Git (if not already installed)
Download from https://git-scm.com/downloads and install.

Verify it works:
```bash
git --version
```

### Step 2 — Configure Git (one-time setup)
```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

### Step 3 — Clone the repo
```bash
git clone https://github.com/CholeGocomx/juasolution.git
cd juasolution
```

### Step 4 — Copy your files in
Drop `index.html`, `README.md`, and `CNAME` into the `juasolution` folder.

### Step 5 — Push to GitHub
```bash
git add .
git commit -m "Initial website launch"
git push origin main
```

If it asks for login, use your GitHub username and a **Personal Access Token**
(not your password). Create one at: GitHub → Settings → Developer Settings →
Personal Access Tokens → Tokens (classic) → Generate new token → check `repo`.

---

## Enable GitHub Pages (free hosting)

1. Go to your repo on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under **Source**, select: **Deploy from branch**
4. Branch: `main` · Folder: `/ (root)` → click **Save**
5. After ~60 seconds, your site is live at:
   `https://cholegocomx.github.io/juasolution/`

---

## Connect your custom domain juasolution.com

The `CNAME` file in this repo already contains `juasolution.com`.

Add these **A records** at your domain registrar (GoDaddy, Namecheap, etc.):

| Type | Name | Value |
|------|------|-------|
| A | @ | 185.199.108.153 |
| A | @ | 185.199.109.153 |
| A | @ | 185.199.110.153 |
| A | @ | 185.199.111.153 |
| CNAME | www | cholegocomx.github.io |

Then in GitHub Pages settings → enter `juasolution.com` under **Custom domain**
and check **Enforce HTTPS**.

DNS changes take 10 min – 48 hours to propagate.

---

## File Structure

```
juasolution/
├── index.html   ← Home page (single page)
├── CNAME        ← Custom domain config
└── README.md    ← This file
```

## Contact
📧 info@juasolution.com · 🌐 juasolution.com
