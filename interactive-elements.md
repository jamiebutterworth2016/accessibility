# 1. Interactive Elements ▶️
Triggered by an action: click, tap, pinch, long press, gestures 👆

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
- Is it clearly interactive?
- Are signifiers strong and unambiguous?
- Is the action obvious?

<hr>

# 2. Signifiers 🛜
👉 Signals an element is interactive, how to use it and what happens next.

**Types**
- Visual → colour, shape, underline, icons 👀
- Auditory → screen reader output, confirmation sounds 🔊
- Physical → touch, vibration, device movement ✋

**Best Practices**
- Buttons should “look clickable”
- Icons suggest gestures (tap, pinch, swipe)
- Use haptic feedback for touch-based devices
- Consider mobile, wearables, controllers

<hr>

# 3. Button Wording & Styling
- Use action verbs: Save, Publish, Send
- Task-specific: ❌ Submit → ✅ Publish, ❌ Yes/No → ✅ Save/Discard
- Keep concise and clear
- Front-load keywords: first 1–2 words should communicate the action (also helps scanning and SEO)

## Styling (Signifiers)

### 1. Shape & Consistency
- Typically rectangular with slight rounding
- Consistent signifiers help users recognise patterns quickly
<img width="1243" height="196" alt="image" src="https://github.com/user-attachments/assets/576a0edd-32b6-40cd-bceb-04454f625979" />

### 2. Hierarchy
👉 Aim for one primary button per page. Use hierarchy (multiple button types) to reduce competition.
- Primary → solid fill
- Secondary → outline/stroke
- Tertiary → borderless / text-only
<img width="489" height="273" alt="image" src="https://github.com/user-attachments/assets/95e80eeb-a069-4167-aba1-2dd84d6bde63" />
<img width="566" height="260" alt="image" src="https://github.com/user-attachments/assets/7547ac4a-ec5b-469d-a347-e58819bc6f78" />

### 3. Border Radius (Personality)
- 0px → serious, formal
- **~4px → balanced**
- 100% → rounded, playful, friendly
<img width="1315" height="257" alt="image" src="https://github.com/user-attachments/assets/6f72937a-46bf-420b-879c-254379c7b9e9" />

### 4. Shadows (Elevation)
- Suggest depth and interactivity
- Can reinforce hover/active states
<img width="656" height="152" alt="image" src="https://github.com/user-attachments/assets/5cec8d3e-6fab-4e13-9b36-4df7906db267" />

### 5. Proximity
- Group related elements.
- Use whitespace between grouped elements.
- Use larger touch targets - selectable by everyone, including people with motor disabilities.
<img width="468" height="286" alt="image" src="https://github.com/user-attachments/assets/60dd57de-cceb-4eb1-b4f8-8ea079029ad3" />

### 6. Capitalisation
Keep consistent and readable
<img width="651" height="137" alt="image" src="https://github.com/user-attachments/assets/4fa2889a-c063-45f3-829d-514039d2d74e" />

<hr>

# 4. Link Wording & Styling
- Links = promises → text must match destination and action
- Must be clear, descriptive, unique, front-loaded
   - ❌ Read more → ✅ SEO hacks for 2026
   - ❌ Click here → ✅ View samples from past work

**Indicating Behaviour**
- External links → icon after text
- File downloads → include file type (e.g. Report PDF)

**Accessibility**
- Must make sense in isolation (Links List)
- Screen reader friendly
- Supports fast scanning

**Visual Signifiers**
- Use underline (not colour alone)
- Bold for standalone links
- Blue🟦 is classic, but can use brand colours if consistent
- Avoid blue text unless link
- Underline links in body text
- Menus may not need underline (context is clear)
- Avoid borders (looks like buttons)
- Maintain contrast:
   - ≥ 3:1 vs surrounding text
   - ≥ 4.5:1 vs background

**Headings as Links (Best Practice):**
- Improves discoverability, accessibility, SEO
- Avoid “Read More” links
```
<h3>
  <a href="/article">How to Bake a Cake</a>
</h3>
```

<hr>

# 5. Buttons vs Links

**Use LINK to 🔗**
- Navigate pages
- Jump to sections
- Change URL
- No data/state change
- Open new tab/window

**Use BUTTON to ▶️**
- Perform actions (Submit, Upload)
- Change state (UI/backend)
- Trigger JS (modals, toggles)

**Keyboard**
- Button → Enter + Space
- Link → Enter

<hr>

# 6. Interactive States

Changes in appearance or behaviour based on user or system interaction.
- Buttons, Links, Cards/Tiles, Toggles, Checkboxes, Radio buttons, Dropdowns, Icons, Lists, Accordions, Forms

**Fundamental States**
- Default / Enabled
- Focus (keyboard) 🔍
- Hover (mouse) 👆
- Pressed / Active
- Visited (links) 🔗
- Disabled 🚫
- Selected / Toggled ✔️
- Processing (loading) 🔃
- Abort / Cancel ❌
- Error (forms)

**Design Best Practices**
- Plan states early with the component
- Design in UI context & design system
- Use placeholders for unconfirmed states
- Designers own states, collaboration with devs

**Accessibility Checklist for States:**
1. What is the state?
1. Is it essential?
1. Is it contrast compliant?
1. Is it colour-independent?
1. Is it noticeable?
1. Clear signifiers?

**Focus & Hover**
- Focus → essential, high contrast, keyboard users
- Hover → improves discoverability, maintain contrast, not colour-only

<hr>

# 7. User Scanning & Behaviour
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

# 8. Usability & Testing 🧪
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

# Interactive States

Interactive states describe how an element changes appearance or behaviour based on:
- User interaction (hover, click, focus)
- System status (loading, error)

👉 States do not change the element itself, only how it behaves or appears

**Interactive states communicate:**
- What the system is doing
- What the user is doing
- What can be done next

<hr>

## 1. Stateful Elements

👉 If it’s interactive → it needs states

- Buttons, Links
- Cards / Tiles
- Toggles, Checkboxes, Radio buttons
- Dropdowns (incl. multi-select)
- Icons (favourites, ratings)
- Lists (emails, tables)
- Accordions
- Forms & inputs

<hr>

## 2. Fundamental States (10)

👉 Not every element uses all states, but these are the core set

- Default / Enabled
- Focus (keyboard users)
- Hover (mouse users) 👆
- Pressed / Active
- Visited (links) 🔗
- Disabled 🚫
- Selected / Toggled
- Processing (loading) 🔃
- Abort (cancel) ❌
- Error (especially forms)

<hr>

## 3. Designing States (Best Practice)

**Design Early**
- Plan states with the component, not after
- Avoid inconsistent behaviour across components

**Work in Two Contexts**
- In UI screens → ensures it works in context
- In design system → ensures consistency

👉 Move between both

**Use Placeholders**
- Add state placeholders early
- Fully design only when component is confirmed

**Ownership**
👉 Designers define states — not developers
Collaboration is key, but design responsibility stays with designers

<hr>

## 4. Accessibility: 6 Key Questions
Use this checklist for every state:
1. What is the state?
2. Is it essential? (If removed, does usability break?)
3. Is it contrast compliant?
4. Is it colour independent?
5. Is it noticeable enough?
6. Does it use clear signifiers?

👉 Goal: Yes to all

<hr>

## 5. Key State Types
### Focus States 🔍
- Must be clearly visible
- High contrast
- Not colour-only
- Large and obvious

👉 Essential for keyboard users

### Hover States 👆
- Improve discoverability
- Must maintain text contrast (4.5:1)
- Should not rely on colour alone

👉 Not always “essential”, but very important for usability

<hr>

## 7. Core Principles (POUR)

**👀 Perceivable**
- Text readable (contrast ≥ 4.5:1)
- States visible (focus, hover, error)
- Not colour-only communication

**🖱 Operable**
- Fully keyboard accessible
- Clear focus states
- Large, tappable targets

**🧠 Understandable**
- Clear wording (buttons, links, errors)
- Predictable interactions
- Consistent patterns

**🔧 Robust**
- Works with screen readers
- Semantic HTML
- Cross-browser/device compatible

<hr>

## 3. Consistency vs Similarity vs Distinctness
- Aim for consistency.
- Only sacrifice consistency to improve the UX.

<img width="653" height="251" alt="image" src="https://github.com/user-attachments/assets/dfad0caf-97d8-463b-8c8b-f1eb5923dd0d" />

## 4. Link Signifiers

Be different from non-clickable text.
Use signifier.
Underline, not bold.
Don't use colour as signifier.
Google's links. Use bold for links and spacing and blue link colour and underline on hover and display naked URL above link.
Use low hanging underlines.
Underline styling.
Blue is classic link colour - but can change colour to match brand.
Don't need to underline menu items - obviously links.
Underline links with surrounding text. Embolden standalone links.

Alternatives to underlines.
Avoid borders - looks too much like a button.
Luminous links - 3 to 1 constrast ratio with surrounding black unlinked text. For colourblind.
4.5+ to 1 against white background. For low vision.

Avoid blue text if not a link. Blue text is strongly associated with links.

Or reserve a chosen coour for links.

<img width="605" height="253" alt="image" src="https://github.com/user-attachments/assets/f266e4d2-56b7-4c5f-8d3a-98344450aa17" />

<img width="250" height="357" alt="image" src="https://github.com/user-attachments/assets/35a33308-0774-436f-8c3f-adf240d42f0e" />

<img width="446" height="276" alt="image" src="https://github.com/user-attachments/assets/dc014836-1ded-436f-9c0d-396528b85d3d" />

<img width="440" height="172" alt="image" src="https://github.com/user-attachments/assets/19c8bf60-44d2-4dfe-a19e-41b95b260ffb" />

## 8. WCAG Hierarchy (How It’s Structured)

The accessibility guidelines are organised like this:

**1. Principles (Top Level)**

POUR (Perceivable, Operable, Understandable, Robust)

**2. Guidelines**

High-level goals under each principle

Example: “Provide text alternatives for non-text content”

**3. Success Criteria**

- A (basic)
- AA (standard — most products aim for this)
- AAA (advanced)

Example: Text contrast must be at least 4.5:1

**4. Techniques to meet criteria**

- Add focus outlines
- Use semantic HTML
- Provide labels for inputs
