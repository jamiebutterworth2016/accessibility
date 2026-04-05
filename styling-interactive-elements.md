# Styling Interactive Elements

👉 Style interactive elements with signifiers.
- Improves discoverability, accessibility
- Reduces confusion

<hr>

## 1. Buttons vs Links

**🔗 Use LINK when:**
- Navigating between pages
- Scrolling to a section on the page
- Changing the URL
- Opening a new tab/window
- The action does not change data
- The action is less prominent

**▶️ Use BUTTON when:**
- Performing an action: Submit, Upload, Sign in
- Changing frontend or backend state
- Triggering JavaScript: Date picker, Modal, Tabs, Show/hide content, Play media

👉 Using the wrong element confuses keyboard users, reducing usability and accessibility.
- Buttons are activated with: Enter + Space
- Links are activated with: Enter only

<hr>

## 2. Button Signifiers (7)

### 1. Shape & Consistency
- Buttons are typically rectangular with slightly rounded corners
- Consistent signifiers help users recognise patterns quickly

<img width="1243" height="196" alt="image" src="https://github.com/user-attachments/assets/576a0edd-32b6-40cd-bceb-04454f625979" />

<hr>

### 2. Border Radius (Personality)
- 0px → serious, formal
- ~4px → neutral / balanced
- 100% → rounded, playful, friendly

<img width="1315" height="257" alt="image" src="https://github.com/user-attachments/assets/6f72937a-46bf-420b-879c-254379c7b9e9" />

<hr>

### 3. Fill & Colour (Hierarchy)

**Use styling to show importance (fill, stroke, weight, size)** - not colour (for colourblind users).
- Primary button - Solid fill
- Secondary button - Outline / stroke
- Tertiary button - Borderless / text-only

<img width="489" height="273" alt="image" src="https://github.com/user-attachments/assets/95e80eeb-a069-4167-aba1-2dd84d6bde63" />

<img width="566" height="260" alt="image" src="https://github.com/user-attachments/assets/7547ac4a-ec5b-469d-a347-e58819bc6f78" />

<hr>

### 4. Shadows
- Shadows convey elevation.
- Buttons with higher contrast stand out more.
- Can use small shadow as hover state.

<img width="656" height="152" alt="image" src="https://github.com/user-attachments/assets/5cec8d3e-6fab-4e13-9b36-4df7906db267" />

<hr>

### 5. Competition
- Aim for one primary button per page.
- Use hierarchy (multiple button types) to reduce competition.

<hr>

### 6. Proximity
- Elements too close in proximity can suffocate each other (breathability).
- Group related elements.
- Use white space between grouped elements.
- Use larger touch targets - selectable by everyone, including people with motor disabilities.

<img width="468" height="286" alt="image" src="https://github.com/user-attachments/assets/60dd57de-cceb-4eb1-b4f8-8ea079029ad3" />

<hr>

### 7. Label Capitalisation

<img width="651" height="137" alt="image" src="https://github.com/user-attachments/assets/4fa2889a-c063-45f3-829d-514039d2d74e" />


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

## 6. Accessibility Foundations (Expanded)
### A. POUR Principles (from WCAG)

These come from the World Wide Web Consortium and form the foundation of accessibility.

**1. Perceivable**

👉 Users must be able to see or sense the UI

- Text is readable (contrast)
- States are visible (focus ring, hover change)
- Not relying on colour alone

👉 If users can’t perceive a state → it doesn’t exist

**2. Operable**

👉 Users must be able to interact with it

- Keyboard navigation works
- Focus states are visible
- Click/tap targets are usable

👉 If a user can’t operate it → it’s unusable

**3. Understandable**

👉 Users must be able to understand what’s happening

- Clear error messages
- Predictable interactions
- Consistent state behaviour

👉 Confusing states = broken UX

**4. Robust**

👉 Works across:

- Browsers
- Devices
- Assistive technologies (screen readers)

Examples:
- Proper semantic HTML
- Accessible states (ARIA where needed)

👉 Future-proof and compatible

### B. WCAG Hierarchy (How It’s Structured)

The accessibility guidelines are organised like this:

**1. Principles (Top Level)**

POUR (Perceivable, Operable, Understandable, Robust)

**2. Guidelines**

High-level goals under each principle

Example: “Provide text alternatives for non-text content”

**3. Success Criteria**

👉 These are the actual rules you must meet

- A (basic)
- AA (standard — most products aim for this)
- AAA (advanced)

Example: Text contrast must be at least 4.5:1

**4. Techniques**

👉 Practical ways to meet criteria

- Add focus outlines
- Use semantic HTML
- Provide labels for inputs
