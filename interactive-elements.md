# 1. Interactive Elements ▶️
Triggered by an action: click, tap, pinch, long press, gestures

- Buttons, Links
- Checkboxes, Radio buttons
- Sliders, Carousels
- Cards / Tiles, Menus, Dropdowns
- Breadcrumbs, Progress trackers, Drop zones

**Design Guidelines**
- Size → large enough to tap/click
- Spacing → prevents accidental interaction
- Location → placed where users expect

**Checklist**
- Is the element clearly interactive?
- Are signifiers strong and unambiguous?
- Can users easily understand what it does and how to use it?

<hr>

# 2. Signifiers 🛜
- Signals that an element is interactive, communicates how to interact and provides feedback.
- Reduce confusion and improve usability.
- Example: a blue🟦, underlined word signals a clickable link

**Types**
- Visual - colour, shape, underline, icons 👀
- Auditory - screen reader output, confirmation sounds 🔊
- Physical - touch, vibration, device movement ✋

**Best Practices**
- Buttons should “look clickable”
- Icons can suggest gestures (tap, pinch, swipe)
- Use haptic feedback for touch-based devices
- Consider mobile, wearables and controllers

<hr>

# 3. Button Design & Styling
- **Use action-oriented verbs:** Save, Publish, Send
- Task-specific wording: ❌ Submit → ✅ Publish, ❌ Yes/No → ✅ Save/Discard
- Keep text concise, clear, descriptive
- Front-load keywords: first 1–2 words should communicate the action (also helps scanning and SEO)

**Visual Styling**
- Strong contrast
- Clear shape
- Hover/focus animations for feedback

<hr>

# 4. Link Design & Wording
- Links = promises → text must match destination and action
- Must be clear, descriptive, unique, front-loaded
   - ❌ Read more → ✅ SEO hacks for 2026
   - ❌ Click here → ✅ View samples from past work

**Indicating Behaviour**
- External links → icon after text
- File downloads → include file type: “Report (PDF)”

**Accessibility**
- Text must make sense in isolation (Links List)
- Screen reader friendly
- Supports scanning for fast information foraging

**Headings as Links (Best Practice):**
- Improves discoverability, accessibility, SEO
- Avoid vague “Read More” links
```
<h3>
  <a href="/article">How to Bake a Cake</a>
</h3>
```
Avoid:
❌ Read more, Learn more, Click here, Here, Details, Naked URLs

Visual Signifiers: Underline, bold styling → users recognize these as links

- Vague link text hides the action, increasing cognitive load
- Clear link text immediately communicates purpose and supports scanning

<hr>

# 5. User Scanning & Behaviour
- Users read ~20–28% of content; scan in F-pattern (top-left → horizontal → down left)
- Information Foraging: rely on links, headings, buttons
- Clear link/button text reduces cognitive load
- Sighted users → scan visually
- Blind users → scan structurally

How Content is Scanned:
- Sighted users → visually
- Blind users → screen readers (structural scanning)
- Search engines → page structure & keywords

How content is scanned:
- Sighted users → visually
- Blind users → structurally via screen readers

Screen Reader Navigation Features:
- Links List
- Headings List
- Buttons List
- Form Fields List

<hr>

# 6. Usability & Testing 🧪
- Evaluate ease-of-use and intuitiveness
- Include diverse participants, including users with disabilities
- Observe confusing or weak signifiers
- Identify misleading affordances (e.g., Norman Doors)

**Core UX Concepts:**
- Discoverability: user can figure out actions without instructions
- Feedback: visual, auditory or haptic signals to confirm actions

**Tools & Methods:**
- Accessibility testing apps
- Explore by touch
- Usability testing with real users

<img width="601" height="398" alt="image" src="https://github.com/user-attachments/assets/1a4e1654-dd63-495f-a8df-f3ba34e9fbd1" />
