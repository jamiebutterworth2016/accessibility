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
👉 Use action verbs: Save, Publish, Send
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

<img width="601" height="398" alt="image" src="https://github.com/user-attachments/assets/1a4e1654-dd63-495f-a8df-f3ba34e9fbd1" />

<img width="653" height="251" alt="image" src="https://github.com/user-attachments/assets/dfad0caf-97d8-463b-8c8b-f1eb5923dd0d" />

<img width="605" height="253" alt="image" src="https://github.com/user-attachments/assets/f266e4d2-56b7-4c5f-8d3a-98344450aa17" />

<img width="250" height="357" alt="image" src="https://github.com/user-attachments/assets/35a33308-0774-436f-8c3f-adf240d42f0e" />

<img width="446" height="276" alt="image" src="https://github.com/user-attachments/assets/dc014836-1ded-436f-9c0d-396528b85d3d" />

<img width="440" height="172" alt="image" src="https://github.com/user-attachments/assets/19c8bf60-44d2-4dfe-a19e-41b95b260ffb" />

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

Changes in appearance/behaviour based on interaction or system status.
- Buttons, Links, Cards/Tiles, Toggles, Checkboxes, Radio buttons, Dropdowns, Icons, Lists, Accordions, Forms

**States**
- Default / Enabled
- Focus (keyboard) 🔍
- Hover (mouse) 👆
- Active / Pressed
- Visited (links) 🔗
- Disabled 🚫
- Selected / Toggled ✔️
- Loading 🔃
- Abort / Cancel ❌
- Error (forms)

**Design Principles**
- Design states early
- Ensure consistency across system
- Work in UI screens (context) and Design system (consistency)

**Accessibility Checklist**
1. What is the state?
1. Is it essential?
1. Is it contrast compliant?
1. Is it colour-independent?
1. Is it noticeable?
1. Clear signifiers?

**Focus**
- High contrast
- Always visible
- Essential for keyboard users

**Hover**
- Improves discoverability
- Must not rely on colour alone

<hr>

# 7. User Scanning & Behaviour
- Users read ~20–28% of content
- Scan in F-pattern (top-left → horizontal → down left)
- Use information foraging (look for cues)
- Users rely on: Links, Headings, Buttons

**How Content is Scanned**
- Sighted users → visually scanning
- Blind users → structural scanning (screen readers)
- Search engines → structure + keywords

**Screen Reader Navigation**
- Links List
- Headings List
- Buttons List
- Form Fields List

<hr>

# 8. Usability & Testing 🧪
- Evaluate ease-of-use and clarity
- Include diverse participants, including users with disabilities
- Identify weak signifiers
- Discoverability → can users figure it out?
- Feedback → confirms actions (visual, sound, haptic)

**Methods:**
- Usability testing
- Accessibility tools
- “Explore by touch”

<hr>

# 9. POUR
- Perceivable 👀 → visible, readable, not colour-only
- Operable 🖱 → keyboard accessible, usable controls
- Understandable 🧠 → clear, predictable
- Robust 🔧 → works across devices & assistive tech

<hr>
