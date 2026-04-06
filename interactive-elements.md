# 1. Interactive Elements ▶️
Triggered by an action: click, tap, pinch, long press, gestures 👆

- Buttons, Links
- Checkboxes, Radio buttons
- Sliders, Carousels
- Cards / Tiles, Menus, Dropdowns
- Breadcrumbs, Progress trackers, Drop zones

**Design Guidelines**
- Size: large enough to tap/click
- Spacing: prevents accidental interaction
- Location: placed where users expect

**Checklist**
- Is the element clearly interactive?
- Are signifiers strong and unambiguous?
- Can users easily understand what it does and how to use it?

<hr>

# 2. Signifiers 🛜
- Signals an element is interactive
- Communicates how to interact and provides feedback.
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

# 3. Buttons: Wording & Styling (Signifiers)
**Wording**
- **Use action verbs:** Save, Publish, Send
- Task-specific: ❌ Submit → ✅ Publish, ❌ Yes/No → ✅ Save/Discard
- Keep text concise and clear
- Front-load keywords: first 1–2 words should communicate the action (also helps scanning and SEO)

## 1. Shape & Consistency
- Buttons are typically rectangular with slightly rounded corners
- Consistent signifiers help users recognise patterns quickly
<img width="1243" height="196" alt="image" src="https://github.com/user-attachments/assets/576a0edd-32b6-40cd-bceb-04454f625979" />

## 2. Hierarchy
👉 Aim for one primary button per page. Use hierarchy (multiple button types) to reduce competition.
- Primary → solid fill
- Secondary → outline/stroke
- Tertiary → borderless / text-only
<img width="489" height="273" alt="image" src="https://github.com/user-attachments/assets/95e80eeb-a069-4167-aba1-2dd84d6bde63" />
<img width="566" height="260" alt="image" src="https://github.com/user-attachments/assets/7547ac4a-ec5b-469d-a347-e58819bc6f78" />

## 3. Border Radius (personality)
- 0px → serious, formal
- **~4px → neutral / balanced**
- 100% → rounded, playful, friendly
<img width="1315" height="257" alt="image" src="https://github.com/user-attachments/assets/6f72937a-46bf-420b-879c-254379c7b9e9" />

## 4. Shadows (elevation)
<img width="656" height="152" alt="image" src="https://github.com/user-attachments/assets/5cec8d3e-6fab-4e13-9b36-4df7906db267" />

## 5. Proximity
- Elements too close in proximity can suffocate each other (breathability).
- Group related elements.
- Use white space between grouped elements.
- Use larger touch targets - selectable by everyone, including people with motor disabilities.
<img width="468" height="286" alt="image" src="https://github.com/user-attachments/assets/60dd57de-cceb-4eb1-b4f8-8ea079029ad3" />

## 6. Capitalisation
<img width="651" height="137" alt="image" src="https://github.com/user-attachments/assets/4fa2889a-c063-45f3-829d-514039d2d74e" />

<hr>

# 4. Link: Wording & Styling
- Links = promises → text must match destination and action
- Must be clear, descriptive, unique, front-loaded
   - ❌ Read more → ✅ SEO hacks for 2026
   - ❌ Click here → ✅ View samples from past work

**Indicating Behaviour**
- External links → icon after text
- File downloads → include file type (e.g., Report PDF)

**Accessibility**
- Text makes sense in isolation (Links List)
- Screen reader friendly
- Supports fast scanning

**Visual Signifiers**
- Underline (avoid using colour only)
- Bold for standalone links
- Blue🟦 is classic, but brand colours ok if consistent
- Avoid blue text unless link

**Headings as Links (Best Practice):**
- Improves discoverability, accessibility, SEO
- Avoid vague “Read More” links
```
<h3>
  <a href="/article">How to Bake a Cake</a>
</h3>
```

**User Scanning Behaviour**
- F-pattern: top-left → horizontal → down-left
- Users read ~20–28% content → rely on headings, links, buttons

<hr>

# 5. Buttons vs Links

**When to Use Link 🔗**
<br>Navigate pages, scroll to sections, open new tab/window, action doesn’t change data

**When to Use Button ▶️**
- Perform actions (Submit, Upload, Play media)
- Change frontend/backend state
- Trigger JS (modals, tabs, toggles)

**Keyboard Activation**
- Buttons → Enter + Space
- Links → Enter

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
