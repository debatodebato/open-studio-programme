# DEV PROMPT: point a. Open Studio 5-Day Intensive Landing Page

**For:** Froz / Vig
**Priority:** Standard
**Review Required:** Yes, before launch

---

## WHAT WE'RE BUILDING

A single-page landing page for the Open Studio 5-Day Intensive programme. Copy-led, responsive, mobile-first. Sticky CTA footer with form at page bottom.

**Full Brief:** See `Open_Studio_Webpage_Brief.md` (attached or linked in this ticket)

---

## KEY REQUIREMENTS AT A GLANCE

✓ Single-scroll page: Hero → What You Get → Five-Day Journey → Outcomes → Form  
✓ Sticky CTA bar at bottom of viewport (always visible)  
✓ Five-Day cards: horizontal scroll on desktop, stacked vertically on mobile  
✓ Form section at page bottom  
✓ Styling: match pointacademy.com (typography, colours, spacing, components)  
✓ Responsive: desktop, tablet, mobile  

---

## CONTENT

### Hero
- Headline: "Five Days to Real Capability"
- Subheading: "A working studio week that builds your portfolio."
- Hook: "Learn from practitioners doing this work right now. Use the tools professionals use. Build something you can actually be proud of."
- Visual: Simple horizontal progress/card preview of all 5 days

### What You Get (5 blocks)
1. Learn from People Actually Doing It
2. A Certificate That Counts
3. Work on Professional Tools
4. Structured Like a Real Studio
5. Fuel Included

(Full copy in brief)

### Five-Day Journey (5 scrollable cards)
Day 1: Design Thinking  
Day 2: Digital Design & UX  
Day 3: Content Creation & Podcasting  
Day 4: Post-Production & AI  
Day 5: The Capstone Brief  

(Full descriptions in brief)

### What You'll Have By The End
Bulleted list of 5 outcomes

### Pricing & Contact
AED 1,499 for 5 days  
Questions? hi@pointacademy.com

### Form Section
"Ready to start building?"  
Form fields: Name, Email, Phone (optional), Message (optional)  
Button: "Register Your Interest"

### Sticky CTA Bar (always visible at bottom)
"Ready to start building? [Register Button]"

---

## LAYOUT & INTERACTIONS

**Desktop (1024px+)**
- Full-width hero with breathing room
- What You Get: 5-column grid or card layout
- Five-Day cards: horizontal scroll with scroll hints
- Form: full-width at bottom
- Sticky bar: fixed at bottom, full-width

**Mobile (< 768px)**
- Single-column layout
- What You Get: stacked single column
- Five-Day cards: stacked full-width
- Form: full-width
- Sticky bar: fixed at bottom, adjusted height to avoid obscuring content

**Sticky CTA Bar Interaction:**
- Always visible at bottom of viewport
- Click button: smooth scroll to form section
- Consider auto-hide on small screens if height is an issue

---

## STYLING

**Brand Reference:** https://www.pointacademy.com
- Typography (font family, sizes, weights)
- Colour palette
- Spacing system (likely 8px or 16px base)
- Button styles
- Card treatments
- Grid/layout system

**Tone:** Energetic, grounded, approachable

---

## FORM INTEGRATION

- **Backend:** Google Sheet integration
- **Fields:** Name, Email, Phone (optional), Message (optional)
- **Submit button text:** "Register Your Interest"
- **Success state:** Confirmation message (e.g., "Thanks for registering. We'll be in touch soon.")

---

## TECHNICAL CHECKLIST

- [ ] Semantic HTML / accessible React component
- [ ] Mobile-first responsive design
- [ ] WCAG 2.1 AA compliance (minimum)
- [ ] Core Web Vitals optimized (LCP, CLS, FID)
- [ ] Smooth scroll interactions
- [ ] Form validation and submission
- [ ] Hover/focus states on all interactive elements
- [ ] Cross-browser testing (Chrome, Firefox, Safari, Edge)
- [ ] Mobile device testing

---

## DELIVERABLES

1. Responsive page (HTML/React component)
2. Mobile, tablet, desktop preview/screenshots
3. Form backend integration (once endpoint confirmed)
4. Accessibility report
5. Ready for review before launch

---

## QUESTIONS TO CLARIFY WITH DES

- Any animations or micro-interactions beyond smooth scroll?
- Launch timeline / review schedule?

---

## NEXT STEP

1. Review brief and confirm all requirements
2. Confirm form backend with Des/Kar
3. Start build
4. Share progress for review before launch

**Brief Owner:** Des
**Slack handle for questions:** @Des

---

**Good luck! 🚀**
