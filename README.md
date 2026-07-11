# Flowly — Welcome Email Template 

A responsive, hand-designed HTML welcome/onboarding email template built for **Task 2: Email Template**.

Live email marketing template made from scratch with inline illustrations, a progress tracker, a live product mockup, and a referral incentive block — designed to look like a real SaaS onboarding email, not a generic template.

---

##  Preview

Open [`3-welcome-flowly.html`](./3-welcome-flowly.html) directly in your browser to preview the full template.

>  Tip: For the most accurate preview, test it inside [Litmus](https://litmus.com) or [Email on Acid](https://www.emailonacid.com), or send a test email through Gmail/Outlook — real inbox rendering differs slightly from a browser preview.

---

##  Features

- **Personalized greeting** with a gradient avatar badge (initial-based)
- **Setup progress tracker** — visual progress bar showing onboarding completion
- **Live product mockup** — a fake browser window containing an illustrated kanban board (To Do / In Progress / Done)
- **Social proof stats bar** — teams onboarded, average rating, setup time
- **Template gallery** — three pickable starter templates with custom icons
- **Step-by-step onboarding checklist** with a completed-state checkmark
- **Referral incentive banner** — "invite 3 teammates, get a free month"
- **Fully responsive** — single-column stacking layout on mobile (<600px)
- **Custom inline SVG illustrations** — no external image hosting required, everything renders inline
- **Outlook-safe layout** — built with table-based structure and MSO conditional comments for cross-client compatibility

---

##  Built With

- Pure **HTML** + **inline CSS** (email-safe, no external stylesheets)
- **Table-based layout** (the email industry standard, since most clients strip modern CSS)
- **Inline SVG** for all icons and illustrations
- Media queries for responsive stacking on mobile clients that support them

---

##  File Structure

```
├── 3-welcome-flowly.html   # Main email template file
└── README.md               # This file
```

---

##  Design System

| Element        | Value                          |
|----------------|--------------------------------|
| Primary color  | `#1f8a6e` (teal green)         |
| Accent 1       | `#f4b183` (soft coral)         |
| Accent 2       | `#e0a53e` (warm gold)          |
| Background     | `#e8f2ee` (light mint)         |
| Text (dark)    | `#173a30`                      |
| Text (muted)   | `#5b7568`                      |
| Font           | Arial / Helvetica (email-safe) |

---

##  Email Client Compatibility Note

This template uses **inline SVG** for illustrations, which renders beautifully in browsers, Apple Mail, and most modern Gmail clients. However, **Outlook (desktop) and some older email clients don't support inline SVG**. For production sends where guaranteed rendering across every client is required, the SVGs should be exported as PNG/JPG images and hosted externally (e.g. via a CDN or image host) instead of inlined.

---

## How to Customize

1. Replace `Ganesh` in the greeting with a dynamic merge tag (e.g. `{{first_name}}`) if wiring this up to an ESP (Mailchimp, SendGrid, Klaviyo, etc.)
2. Swap the `#` placeholder `href` links with real URLs (workspace setup, help center, referral link, etc.)
3. Update the footer address to your real company details — most ESPs require a physical mailing address for CAN-SPAM/GDPR compliance
4. Adjust colors in the design system table above to match your brand

---

## 📄 License

Free to use and modify for personal, academic, or portfolio purposes.
