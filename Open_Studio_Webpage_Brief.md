# point a. Open Studio 5-Day Intensive — Webpage Brief

**Status:** Ready for development (pending review)
**Priority:** Standard
**Audience:** Prospective learners (school leavers, career changers, university students)
**Call to Action:** Register your interest in the programme

---

## PROJECT SCOPE

Single-page, scrollable landing page with sticky CTA footer. Responsive design (desktop: horizontal card scroll, mobile: stacked cards). Form submission at page bottom. Visual and copy-led approach aligned to point a.'s existing brand style.

---

## HERO SECTION

**Layout:** Full-width hero, centred alignment

**Headline**
Five Days to Real Capability

**Subheading**
A working studio week that builds your portfolio.

**Hook**
Learn from practitioners doing this work right now. Use the tools professionals use. Build something you can actually be proud of.

**Visual Preview**
Horizontal progress indicator or card preview showing all five days (Day 1, 2, 3, 4, 5 with titles). Design should feel lightweight and scannable, not visual-heavy.

**Spacing:** Breathing room around hero; typically 60-80px padding above/below on desktop.

---

## WHAT YOU GET SECTION

**Layout:** 5-column grid (desktop) or 1-column stacked (mobile/tablet). Cards or simple list format.

### Copy Blocks

**Learn from People Actually Doing It**
Every session is led by practitioners working in creative and tech. Real problems. Real solutions. No theory.

**A Certificate That Counts**
Powered by Middlesex University Dubai. Strengthens your resumé, counts towards uni applications, and signals to employers you can work the tools.

**Work on Professional Tools**
Figma. DaVinci Resolve. Claude. The same software used in studios worldwide. You own what you build.

**Structured Like a Real Studio**
Five focused days that mirror how creative teams actually work. Collaborative. Practical. Built for learning by doing.

**Fuel Included**
Lunch or refreshments every day. We take care of the basics so you can focus.

**Design Notes:** Keep this scannable. Minimal graphics; focus on clear hierarchy and breathing room between blocks.

---

## THE FIVE-DAY JOURNEY SECTION

**Layout:** Horizontal scrollable cards (desktop) / stacked vertically (mobile). Each card contains Day, Title, Description, Duration.

### Card Structure

**DAY 1**
**Design Thinking**
Step out and observe real user behaviour. Apply design logic. Ideate tangible solutions. Everything starts with understanding the problem.
*5 hours*

**DAY 2**
**Digital Design & UX**
Move into Figma. Learn visual storytelling and UX fundamentals by building real things: a creative concept and a mobile app interface.
*5 hours*

**DAY 3**
**Content Creation & Podcasting**
Understand how social media platforms work. Script. Produce content. Then, record live in our dedicated podcasting zone. From idea to published audio, you'll do it all.
*5 hours*

**DAY 4**
**Post-Production & AI**
Professional editing on DaVinci Resolve. Then learn how Claude becomes a tool in your workflow, not a replacement for your thinking.
*5 hours*

**DAY 5**
**The Capstone Brief**
Receive a professional brief spanning design, UX, content, and post-production. Work alongside our educators-. Build something complete. Refine it with AI. Leave with a finished piece.
*5 hours*

**Design Notes:** 
- Desktop: horizontal scroll, cards visible in viewport, scroll indicator if needed
- Mobile: stack vertically, full-width cards
- Each card should have consistent spacing and visual weight
- Duration (5 hours) should be subtle, not prominent

---

## WHAT YOU'LL HAVE BY THE END SECTION

**Layout:** Simple bulleted list or minimal icon + text format

- A portfolio project you built in five days
- A certificate from Middlesex University Dubai
- Tools you know how to use
- Real feedback from working practitioners
- Clarity on your next move

**Design Notes:** Light treatment; list items should feel lightweight and supportive rather than graphically heavy.

---

## PRICING & CTA SECTION (Bottom of Page)

**Pricing Copy**
AED 1,499 for 5 days

**Questions Contact**
Questions? hi@pointacademy.com

**Spacing:** Clear separation above form section.

---

## FORM SECTION (Bottom of Page)

**Form Title/Prompt**
Ready to start building?

**Form Fields**
- Full Name
- Email
- Phone (optional)
- Message/Interest (optional textarea)

**Submit Button**
[Text: "Register Your Interest"]

**Form Backend**
Google Sheet integration. Form submission posts to a Google Sheet for tracking registrations.

**Post-Submission**
Confirmation message (e.g., "Thanks for registering. We'll be in touch soon.") or success state.

**Design Notes:** 
- Keep form minimal and approachable
- Single column, clear spacing
- Use point a. button styling (check pointacademy.com for reference)

---

## STICKY CTA BAR (Always Visible)

**Position:** Fixed at bottom of viewport (bottom: 0)

**Content**
Ready to start building? [Register Button]

**Interaction:** 
- Clicking button triggers smooth scroll to form section at page bottom
- Bar should not obscure content on small screens; consider dismissible on mobile or adjust height

**Design Notes:**
- High contrast against page background
- Subtle shadow or border to separate from content
- Check pointacademy.com for button and bar styling

---

## STYLING & BRAND ALIGNMENT

**Font:** Use point a. brand typeface (check pointacademy.com)
**Colour Palette:** Match point a. brand colours (check pointacademy.com)
**Spacing:** Align to point a. spacing system (typically 8px or 16px base grid)
**Components:** Use existing point a. components (buttons, cards, inputs, etc.)
**Tone:** Energetic, grounded, approachable (match point a.'s voice)

**Key Reference:** https://www.pointacademy.com
- Hero section style
- Card/grid treatments
- Button styling
- Typography hierarchy
- Spacing and rhythm
- Colour and contrast

---

## RESPONSIVE BREAKPOINTS

**Desktop (1024px+):** 
- Hero full-width with breathing room
- "What You Get": 5-column grid
- Five-Day Cards: horizontal scroll
- Sticky bar: full-width at bottom

**Tablet (768px - 1023px):**
- "What You Get": 2-3 column grid or stacked
- Five-Day Cards: consider stacking or reduced horizontal scroll
- Sticky bar: adjust height/padding for smaller screens

**Mobile (< 768px):**
- Hero: single column, centred
- "What You Get": single column stacked
- Five-Day Cards: full-width stacked cards
- Sticky bar: fixed at bottom, consider auto-hide on scroll or reduced height

---

## INTERACTIONS & MICRO-BEHAVIOURS

1. **Sticky CTA Bar:** Always visible; smooth scroll to form on click or modal trigger (TBC)
2. **Five-Day Cards:** Horizontal scroll with visual indicator on desktop (e.g., scroll hint, pagination dots)
3. **Anchor Links:** Smooth scroll navigation if needed
4. **Form Submission:** Clear success state or confirmation message
5. **Hover States:** Links and buttons should have clear hover feedback (match point a. style)

---

## TECHNICAL NOTES

- Build for semantic HTML, accessibility (WCAG 2.1 AA as minimum)
- Optimise for Core Web Vitals (LCP, CLS, FID)
- Mobile-first approach
- No heavy animations; keep it purposeful and fast
- Form backend integration (confirm endpoint/service with team)

---

## DELIVERABLES

- Responsive HTML/React component or static page
- Mobile, tablet, desktop preview
- Form integration (backend to be confirmed)
- Sticky bar interaction (scroll behaviour confirmed)
- Accessibility audit before launch

---

## NEXT STEPS

1. Review this brief with team
2. Confirm form backend and submission flow
3. Confirm sticky bar interaction (scroll to form vs. modal)
4. Check pointacademy.com for exact styling to match
5. Development and review cycle
6. QA and launch

---

**Brief Owner:** Des
**Review Required:** Yes
**Target Dev:** Froz or Vig
