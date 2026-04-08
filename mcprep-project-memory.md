# McPrep Academy — Project Memory Document

## Overview
This document summarizes the full context of building mcprep.academy so Claude can pick up exactly where we left off in any future conversation.

---

## About the Business

**Business name:** McPrep Academy
**Website:** https://www.mcprep.academy
**Owner:** Ryan McCormick
**Contact:** ryan@mcprep.academy | 949-204-9980
**Location:** San Diego, CA (fully remote — no location-specific branding)

**What it is:** A gamified SAT/ACT test prep bootcamp delivered live on Zoom in small groups. Built around competition, leaderboards, team challenges, and bite-sized strategies to keep modern students engaged.

**Founder background:**
- UC Berkeley Business & Engineering Graduate
- 99th Percentile SAT & ACT scorer
- 10+ Years tutoring experience
- High school math teacher in San Diego
- Real classroom experience

**Key differentiator:** Gamified instruction using OnePrepXYZ software — includes AI chatbot feedback, question bank by topic, Question Rush for in-class competition, and a points/streak system.

---

## Programs & Pricing

**Structure:** 3 sessions · 2 hours each · 6 hours total · Live on Zoom · Small group

**Pricing model:**
- First class is FREE — no payment, no commitment
- Pay only if you continue after session 1
- Remaining 2 sessions: $160 total ($40/hr · 2 hrs/session)
- Payment via Venmo or Zelle before session 2
- No obligation ever — don't pay, don't return, no fees

**Current boot camp dates:**

| Test | Test Date | Class Days | Class Dates |
|------|-----------|------------|-------------|
| SAT | May 2, 2026 | Mondays 7–9 PM PT | Apr 13, 20, 27 |
| SAT | June 6, 2026 | Mondays 7–9 PM PT | May 18, 25, Jun 1 |
| ACT | June 13, 2026 | Tuesdays 7–9 PM PT | May 26, Jun 2, 9 |
| ACT | July 11, 2026 | Mondays 7–9 PM PT | Jun 22, 29, Jul 6 |
| Fall 2026 | TBD | TBD | TBD — collecting interest |

**Sign-up form (Google Form):**
https://docs.google.com/forms/d/e/1FAIpQLSffAE0_-9DkzWpJpTo1517CUEf1iJOSAJC4jynp8uZwx0DNqw/viewform?usp=sharing&ouid=100525222836573959882

**SAT vs ACT quiz (Google Form):**
https://docs.google.com/forms/d/e/1FAIpQLSffAE0_-9DkzWpJpTo1517CUEf1iJOSAJC4jynp8uZwx0DNqw/viewform?usp=sharing&ouid=100525222836573959882

---

## Curriculum Outline

**Powered by:** OnePrepXYZ (https://www.oneprep.xyz)
- AI chatbot feedback
- Full SAT/ACT question bank broken down by topic
- Question Rush for in-class competition
- Points and streak system

### Class 1 — Test Overview & Math: Algebra
- High-level overview of SAT or ACT structure, timing, scoring
- Core test-taking strategies and mindset
- Math: Algebra and Advanced Math sections
- Live practice problems via OnePrepXYZ

*Between sessions: assigned practice problems on Algebra/Advanced Math*

### Class 2 — Math: Data, Geometry & Trigonometry
- Problem Solving & Data Analysis (ratios, percentages, statistics)
- Geometry and Trigonometry
- Live practice + Question Rush competition

*Between sessions: assigned practice problems on Data Analysis, Geometry, Trig*

### Class 3 — Reading, Writing & (ACT) Science
- Craft & Structure
- Expression of Ideas
- Information & Ideas
- Standard English Grammar
- ACT students: Science section (data interpretation, passage-based reasoning)

*After session 3: Full-length official practice test under real testing conditions*

---

## Website Tech Stack

**Built with:** HTML, CSS, JavaScript (vanilla)
**Files:** index.html, bootcamp-table.html
**Version control:** Git / GitHub
**Hosting:** Netlify (auto-deploys on git push)
**Editor:** Cursor (AI-powered code editor)

**Key workflow:**
1. Make changes in Cursor via AI chat prompts
2. Review diff (All Changes tab)
3. Commit to main branch
4. `git push` to deploy to Netlify
5. Live at mcprep.academy within ~1–2 minutes

---

## Website Sections (in order)

1. **Navbar** — McPrep logo + pencil rocket favicon, nav links: Home, Meet Your Instructor, Programs, Curriculum, Results, FAQ, Contact. "SAT or ACT? Take the quiz" CTA button.
2. **Hero** — "Boost your SAT or ACT score in just 3 sessions" + animated leaderboard widget
3. **Meet Your Instructor** — Two-column layout: bio text (left) + Loom intro video (right). Credential cards below (4 cards full width).
4. **Programs** — Single offer + date picker card layout. 4 selectable test date cards. Fall 2026 interest banner. Pricing block (green tint). Dynamic CTA button.
5. **Curriculum Outline** — OnePrepXYZ banner (light blue gradient). 3 session cards (Class 1/2/3 with colored top borders + light tinted backgrounds). Practice assignment blocks. Full-length test milestone (light red gradient).
6. **See It in Action** — Curriculum walkthrough Loom video section.
7. **Results & Testimonials** — Interactive carousel/slider with 3 testimonials.
8. **FAQ** — Accordion-style collapsible cards.
9. **Contact** — Email + phone.

---

## Videos

**About Me / Intro video (Loom):**
https://www.loom.com/embed/a7086b8d6dcf422cb3027c3210ca0403
- Placed in Meet Your Instructor section (right column)
- Hosted as self-contained MP4 at videos/ryan-intro.mp4

**Curriculum Walkthrough video (Loom):**
https://www.loom.com/embed/dad37061c14b4287a83f87a4935aab62
- Placed in "See It in Action" section
- Hosted as self-contained MP4 at videos/curriculum-walkthrough.mp4

---

## Design System

**Font:** DM Sans (Google Fonts)
**Primary accent color:** Indigo #4f46e5
**Color palette:**
- SAT pill: purple bg #EEEDFE, text #3C3489
- ACT pill: coral/orange bg #FAECE7, text #993C1D
- Free/green: bg #dcfce7, border #86efac, text #15803d
- Pricing block: bg #f0fdf4, border #bbf7d0
- Fall banner: gradient #eef2ff → #e0e7ff, border #c7d2fe
- Card default: white bg, 1px #e5e7eb border, radius 12px
- Section neutral bg: #f8f8f6 or #f9fafb

**Card borders (curriculum):**
- Class 1: blue top border, bg #faf5ff (purple tint)
- Class 2: teal top border, bg #f0fdfa (teal tint)
- Class 3: orange top border, bg #fff7ed (orange tint)
- Full practice test: light red gradient bg #fff1f2 → #ffe4e6

**Handwritten annotations:** Caveat font (Google Fonts), indigo #6366f1, curved SVG arrows, used in Meet Your Instructor section

**Date picker card selected state:**
- border: 2px solid #4f46e5
- background: #eef2ff
- checkmark in top right corner

**CTA button:** Indigo #4f46e5, white text, full width, hover #4338ca + scale(1.01)

---

## FAQ Questions (current)

1. Should I take the SAT, ACT, or both?
2. Is the SAT or ACT still important for college admissions?
3. How much can my score improve?
4. Who is this program best for?
5. When should I take the SAT or ACT?
6. How many times should I take the test?

All answers use accordion collapse/expand with JavaScript. Indigo chevron icon rotates on open.

---

## Favicon & Logo

**Favicon:** Pencil rocket icon (pencil shaped as rocket with flames)
**Files location:** /favicon/ folder in project root
**Files:** apple-touch-icon.png, favicon-96x96.png, favicon.ico, favicon.svg, site.webmanifest, web-app-manifest-192x192.png, web-app-manifest-512x512.png
**Navbar logo:** favicon-96x96.png displayed at 28x28px left of "McPrep" text

---

## External Tools & Services

| Tool | Purpose |
|------|---------|
| OnePrepXYZ | In-class software platform |
| Google Forms | Sign-up and SAT vs ACT quiz |
| Loom | Video recording and original embed |
| Netlify | Hosting + auto-deploy |
| GitHub | Version control / git remote |
| Cursor | AI code editor |
| Realfavicongenerator.net | Favicon generation |
| remove.bg | Background removal for logo |
| Venmo / Zelle | Payment collection |

---

## Branding Notes

- Fully remote — NO mentions of Carlsbad, Encinitas, or San Diego in the site copy
- Browser tab title: "McPrep — Gamified SAT/ACT Prep | Online"
- Footer: "Live online SAT & ACT prep · Zoom"
- Meta tags, OG tags, and keywords should all reference online/remote, not location

---

## Things Still In Progress / To Do

- [ ] Replace Loom embeds with self-hosted MP4 files (videos/ryan-intro.mp4 and videos/curriculum-walkthrough.mp4) to remove Loom branding
- [ ] Finalize favicon — pencil rocket PNG with transparent background
- [ ] Add video to "See It in Action" section once MP4 is ready
- [ ] Update Google Form description to reflect current pricing ($160 for 2 sessions, first class free, 2026 dates)
- [ ] Collect and add more student testimonials
- [ ] Plan Fall 2026 boot camp dates and update the Fall interest banner
- [ ] Consider adding a blog or resources section for SEO

---

## Git Workflow Reminders

- Always commit before pushing: `git add . → git commit -m "description" → git push`
- Use `git revert HEAD` + `git push` to undo a deployed change safely
- Cursor checkpoints = local fast undo (not Git)
- Branch strategy: commit directly to main (solo developer, no collaborators)
- Tag stable versions before big changes: `git tag stable-[description]`
