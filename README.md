# Craig Psychologies — craig psychologies ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `craigpsychologiesltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/craigpsychologiesltd.mjs`).
> To change the content, edit that file and run `node build.mjs craigpsychologiesltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@craigpsychologiesltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($Quote / $Quote / $Quote) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Craig Psychologies Ltd, a private limited company registered in England and Wales (company number 12857693), is an independent educational and child psychology practice working with children, young people, families and schools: psychological assessment of learning, cognition and development, consultation and advice for school staff, work with parents and carers on understanding and supporting a child's needs, and independent psychological advice for statutory processes including education, health and care needs assessments. Work is carried out by a practitioner psychologist registered with the Health and Care Professions Council, with informed consent obtained before any assessment. This is not an emergency or crisis service. Site: craigpsychologiesltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
