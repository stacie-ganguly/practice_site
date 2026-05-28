# WORK ORDER — EVERGREEN PET SUPPLY CO.
## SkillsUSA NLSC 2026 · Web Design · Practice Prompt #2

---

**Client:** Evergreen Pet Supply Co.
**Location:** Austin, Texas
**Founded:** 2015
**Tagline:** "Everything Your Pet Deserves"
**Deliverable:** A complete, functional, standards-compliant website (`index.html`, `styles.css`, `main.js`)

> **Instructions:** An AI-generated website has been provided. Review the source code against this work order, identify all errors and inconsistencies, and correct them to produce a complete, functional, and standards-compliant website.

---

## 1. COMPANY OVERVIEW

Evergreen Pet Supply Co. is a family-owned pet supply retailer based in **Austin, Texas**. Founded in **2015** by **Maria and Tom Nguyen**, the company specializes in natural, eco-friendly pet products for dogs, cats, and small animals. Their mission is to provide healthy, sustainable pet care products while supporting local animal shelters.

---

## 2. CONTENT SPECIFICATIONS

### 2.1 Page Title (Browser Tab)
```
Evergreen Pet Supply Co. - Natural Pet Products in Austin, TX
```

### 2.2 Navigation Links (in order)
1. Home
2. Shop
3. About
4. Shelter Partners
5. Contact

### 2.3 Hero Section
- **Headline:** Everything Your Pet Deserves
- **Subheadline:** Natural, eco-friendly pet supplies for dogs, cats, and small animals — delivered to your door or available in-store in Austin, TX.
- **Button 1 text:** Shop Now
- **Button 2 text:** Learn About Us

### 2.4 Stats Bar
| Stat | Value | Label |
|---|---|---|
| 1 | 10,000+ | Happy Customers |
| 2 | 500+ | Natural Products |
| 3 | 4.9/5 | Average Rating |
| 4 | 12 | Shelter Partners |

### 2.5 Featured Categories (in this exact order)
1. **Dogs** — Premium food, toys, grooming, and accessories for your canine companion.
2. **Cats** — Everything from organic food to enrichment toys for your feline friend.
3. **Small Animals** — Food, bedding, and accessories for rabbits, hamsters, and more.

### 2.6 About Section
- **Heading:** A Family Business Built on Love for Animals
- **Founded by:** Maria and Tom Nguyen
- **Year:** 2015
- **Location:** Austin, Texas
- **Body text must include:** The Nguyens started Evergreen after struggling to find truly natural products for their own pets. Today, every product in the store is vetted for quality, sustainability, and safety.
- **Credentials list (in order):**
  1. Certified by the Pet Industry Joint Advisory Council (PIJAC)
  2. Proud member of the Austin Chamber of Commerce
  3. Donate 5% of profits to local animal shelters
  4. Carbon-neutral shipping on all orders

### 2.7 Testimonials (3 total)
| # | Quote summary | Attribution |
|---|---|---|
| 1 | My dog has never been healthier since switching to Evergreen's food | — Carlos M., Austin TX |
| 2 | Best pet store I've found — the staff genuinely care about animals | — Priya S., Round Rock TX |
| 3 | Love that they partner with shelters. I adopted my cat and bought all her supplies here | — Janet W., Cedar Park TX |

### 2.8 Contact / Footer Info
- **Phone:** (512) 334-7890
- **Email:** hello@evergreenpetsupply.com
- **Address:** 4821 Burnet Road, Austin, TX 78756
- **Hours:** Mon–Sat 9am–7pm, Sun 11am–5pm
- **Copyright:** © 2024 Evergreen Pet Supply Co. All rights reserved.
- **Social links present:** Instagram, Facebook, Twitter

---

## 3. TECHNICAL REQUIREMENTS

### 3.1 HTML
- Valid `<!DOCTYPE html>` declaration
- `<html lang="en">` attribute present
- `<meta charset="UTF-8">` present
- Viewport meta: `content="width=device-width, initial-scale=1.0"` (correctly formatted)
- Page `<title>` matches specification exactly
- Correct landmark roles: `banner`, `main`, `contentinfo`

/*come back to this*/
- Skip link must be the first focusable element: `<a href="#main-content" class="skip-link">Skip to main content</a>`

- All non-decorative images must have descriptive `alt` text /*there are no non-decorative images. all r decorative svgs*/
- All decorative SVGs must have `aria-hidden="true"`

### 3.2 Accessibility
- All buttons and links must have discernible text or `aria-label`
- Mobile menu: `aria-expanded="false"` by default; toggles to `"true"` when open
- `#mobile-menu` must have `hidden` attribute by default
- `aria-hidden="true"` on all decorative icons

### 3.3 CSS
- All colors defined as CSS custom properties in `:root`
- Hover states on all interactive elements (nav links, buttons, cards)
- Mobile responsive — hamburger menu visible below 768px, desktop nav hidden

### 3.4 JavaScript
- Mobile menu toggle must correctly set `aria-expanded` and toggle `hidden` on `#mobile-menu`
- "Shop Now" hero button must navigate to `#shop` section when clicked
- Active nav link should receive class `active` when its section is in view
- Counter animation must count up from 0 to the target number on page load

---

## 4. ERROR CHECKLIST
*(For use after attempting to find errors independently)*

| # | Location | Error |
|---|---|---|
| 1 | `<title>` | Typo: "Naturel" should be "Natural" |
| 2 | Hero stat | "Happy Customers" value shows 8,000+ instead of 10,000+ |
| 3 | Hero stat | 4th stat label reads "Animal Shelters" instead of "Shelter Partners" |
| 4 | About section | Says founded in 2012, should be 2015 |
| 5 | About section | Says "San Antonio, Texas" instead of "Austin, Texas" |
| 6 | Credentials list | Item 3 says "10% of profits" instead of "5% of profits" |
| 7 | Testimonial 2 | Attribution reads "Priya S., Dallas TX" instead of "Round Rock TX" |
| 8 | Footer | Phone shows (512) 334-7000 instead of (512) 334-7890 |
| 9 | Footer | Copyright year shows 2022 instead of 2024 |
| 10 | `index.html` | Missing skip link as first element in `<body>` |
| 11 | `index.html` | Viewport meta missing comma: `width=device-width initial-scale=1.0` |
| 12 | `styles.css` | `.skip-link` class is missing entirely |
| 13 | `styles.css` | Nav links have no hover state defined |
| 14 | `main.js` | Menu toggle sets `mobileMenu.hidden = !isOpen` — logic is inverted |
| 15 | `main.js` | Counter animation targets wrong selector — uses `.stat-val` instead of `.stat-number` |

---

## 5. SCORING (Practice)

| Category | Points |
|---|---|
| HTML structure & standards | 15 |
| Content accuracy (9 content errors) | 45 |
| Accessibility (2 errors) | 15 |
| CSS (2 errors) | 15 |
| JavaScript (2 errors) | 10 |
| **Total** | **100** |

---

*Practice prompt for SkillsUSA NLSC 2026 preparation. Company is fictional.*
