# Admissible Systems — Final Deployment Guide

## Files you now have

1. **admissible_systems_homepage_final.html** — Your merged, production-ready homepage
2. **position_paper_final.html** — Your full position paper ("The Evidence Stops at Commissioning")

These two files form the foundation of your public platform.

---

## Quick deployment (20 minutes)

### Step 1: Create GitHub repository

1. Go to https://github.com
2. Click **+** (top right) → **New repository**
3. Repository name: `admissible-systems`
4. Visibility: **Public**
5. Check **Add a README file**
6. Click **Create repository**

### Step 2: Upload files

1. In your repository, click **Add file** → **Upload files**
2. Upload both HTML files
3. Rename `admissible_systems_homepage_final.html` to `index.html`
4. Rename `position_paper_final.html` to `position-paper.html`
5. Click **Commit changes**

### Step 3: Enable GitHub Pages

1. Click **Settings** (top menu)
2. In left sidebar, click **Pages**
3. Under **Build and deployment**:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/(root)**
4. Click **Save**

### Step 4: Access your site

After 1–3 minutes, your site will be live at:

```
https://yourusername.github.io/admissible-systems/
```

The position paper will be at:

```
https://yourusername.github.io/admissible-systems/position-paper.html
```

---

## Domain name options (since admissiblesystems.com is taken)

### Try these in order:

1. **admissible-systems.com** (hyphenated) — ~ £10–12/year
2. **admissiblesys.com** — ~ £10–12/year
3. **admissibletech.com** — ~ £10–12/year
4. **admissible.io** — ~ £30–40/year (modern, technical)
5. **admissible.tech** — ~ £20–30/year

### Registration (using Namecheap as example):

1. Go to namecheap.com
2. Search for your preferred domain
3. Add to cart and purchase
4. Enable free WHOIS privacy

### DNS setup for GitHub Pages:

**In Namecheap DNS settings:**

1. **CNAME record:**
   - Type: `CNAME`
   - Host: `www`
   - Value: `yourusername.github.io`
   - TTL: `Automatic`

2. **A records** (create four):
   - Type: `A`
   - Host: `@`
   - Values: 
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - TTL: `Automatic`

**In GitHub repository:**

1. Go to **Settings → Pages**
2. Under **Custom domain**, enter: `www.admissible-systems.com` (or your chosen domain)
3. Click **Save**
4. Wait 24–48 hours for DNS propagation
5. Check **Enforce HTTPS** once available

---

## Site structure

Your site now has:

- **Homepage** (`index.html`):
  - Strong opening: "We build the evidence layer…"
  - Four principles
  - Founder note (gas-turbine background)
  - Call to action
  - About section

- **Position paper** (`position-paper.html`):
  - Full essay: "The Evidence Stops at Commissioning"
  - All seven sections from your original document
  - Explicit limitations
  - Collaboration invitation

---

## Next steps

### Immediate (this week):

1. Deploy the site to GitHub Pages
2. Register your domain
3. Test both pages on desktop and mobile
4. Share with 2–3 trusted colleagues for feedback

### Short-term (next 2–4 weeks):

1. Finalise the position paper PDF version
2. Upload PDF to `papers/` folder
3. Update homepage button to link to PDF
4. Create LinkedIn profile for Admissible Systems
5. Post the position paper on LinkedIn

### Medium-term (Months 2–3):

1. Write Essay 2: "Can Your Asset Be Observed?"
2. Create `research.html` page listing all publications
3. Add a simple blog structure
4. Begin regular LinkedIn posting (2–3 times per week)

---

## Email setup

Once you have your domain, set up professional email:

**Option 1: ForwardEmail.net (free)**
- Forward `hello@yourdomain.com` to your personal email
- Free, simple

**Option 2: Google Workspace (£3–6/month)**
- Full Gmail with custom domain
- More professional

**Option 3: Proton Mail**
- Encrypted email
- Paid plan required for custom domain (~ £4/month)

---

## Content checklist

Before going fully public:

- [ ] Both pages render correctly on desktop and mobile
- [ ] All links work (homepage → position paper, back link, email)
- [ ] Email address is correct
- [ ] No typos or formatting issues
- [ ] Position paper PDF is ready (optional but recommended)
- [ ] Domain is registered and configured
- [ ] HTTPS is enabled

---

## What makes this site different

This is not a generic consulting website. It is:

1. **Research-led** — The position paper is the centrepiece
2. **Honest about limitations** — Explicitly states simulation-only evidence
3. **Technically precise** — Four clear principles, no vague claims
4. **Founder-driven** — Your operational background is central
5. **Invitation-based** — Seeks collaboration, not immediate clients
6. **Minimalist** — No stock photos, no sales language, no fluff

This matches your strategy: build trust through evidence before seeking commercial opportunities.

---

## Troubleshooting

**Site not showing?**
- Wait 2–3 minutes after upload
- Check **Settings → Pages** for errors
- Ensure files are named `index.html` and `position-paper.html`

**Position paper link broken?**
- Check the filename matches exactly: `position-paper.html`
- The link in `index.html` should be: `href="position-paper.html"`

**Custom domain not working?**
- Wait 24–48 hours for DNS propagation
- Check DNS settings in your registrar
- Ensure CNAME and A records are correct

**Styling looks wrong?**
- CSS is embedded in each HTML file
- Check browser console for errors (F12 → Console)

---

## Cost summary

| Item | Annual cost |
|------|-------------|
| GitHub Pages hosting | Free |
| Domain name (.com) | ~ £10–12 |
| Email forwarding | Free (ForwardEmail) or ~ £36–72 (Google Workspace) |
| **Total** | **~ £10–50/year** |

---

## Final note

The site is intentionally minimal. It is designed to:

- Establish your intellectual position
- Demonstrate technical depth
- Invite serious collaboration
- Avoid premature commercialisation

This is the foundation. Over the next 6–12 months, you will add:

- More essays
- Research artefacts (code, notebooks, diagrams)
- Case studies (as evidence accumulates)
- Conference presentations
- Collaboration announcements

But this two-page foundation is enough to start building public trust.

Good luck with the deployment!
