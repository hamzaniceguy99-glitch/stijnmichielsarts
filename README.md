# Stijn Michiels — stijn michiels arts bv

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `stijnmichielsarts.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/stijnmichielsarts.mjs`).
> To change the content, edit that file and run `node build.mjs stijnmichielsarts` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@stijnmichielsarts.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($On request / $Included / $Excluded) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are the practice of Stijn Michiels, a physician in Brasschaat in the province of Antwerp. The company was registered in September 2026, so it is genuinely new and claims no history it does not have. This page is information rather than advertising, since the rules on what a doctor may say publicly exclude comparisons, claims of superiority, patient testimonials and promises about outcomes. What is worth stating for a practice at this stage is what is already in place rather than what has accumulated over years. Continuity of care is a legal obligation in Belgium, not a courtesy: a practitioner must ensure that the care they provide continues when they are absent, which means arranging for a suitably qualified colleague to take over and making the patient record accessible so that the person covering is not working blind. The second thing is the record itself. A patient record has to be kept for at least thirty years after the last contact, and may be kept for up to fifty, which means it will long outlive the episode that created it. That is exactly why how it is kept matters from the first week rather than from the point at which a practice feels established. Site: stijnmichielsarts.shop
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
