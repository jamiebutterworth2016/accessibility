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

<img width="605" height="253" alt="image" src="https://github.com/user-attachments/assets/f266e4d2-56b7-4c5f-8d3a-98344450aa17" />

<img width="250" height="357" alt="image" src="https://github.com/user-attachments/assets/35a33308-0774-436f-8c3f-adf240d42f0e" />

<img width="446" height="276" alt="image" src="https://github.com/user-attachments/assets/dc014836-1ded-436f-9c0d-396528b85d3d" />

<img width="440" height="172" alt="image" src="https://github.com/user-attachments/assets/19c8bf60-44d2-4dfe-a19e-41b95b260ffb" />


# Interactive States

A state is how an interactive element changes based on:
- User interaction (hover, click, focus)
- System status (loading, error)

👉 States do not change the element itself, only how it behaves or appears

- Design all states, not just default/hover
- Plan states early and together
- Every interactive element needs states
- All states must be: Accessible, Consistent, Clear (strong signifiers)

👉 Interactive states communicate system status and user interaction, and must be designed consistently and accessibly across all elements using clear, perceivable signifiers.

<hr>

## 1. Stateful Elements

👉 If it’s interactive → it needs states

- Buttons, Links
- Cards / Tiles
- Toggles, Checkboxes, Radio buttons
- Dropdowns (incl. multi-select)
- Icons (e.g. favourite, rating stars)
- Lists (emails, tables)
- Accordions
- Forms & inputs

<hr>

## 2. Fundamental States (10)

👉 Not every element uses all states, but these are the core set

- Default / Enabled
- Focus (keyboard navigation)
- Hover (mouse users)
- Pressed / Active
- Visited (links)
- Disabled
- Selected / Toggled
- Processing (loading)
- Abort (cancel)
- Error (especially forms)

<hr>

## 3. Key Best Practices

**Design states early**
- Plan states together, not later
- Avoid inconsistencies (e.g. reusing same style for different states)

**Use placeholders**
- Add state placeholders in your design system
- Only fully design states once element is confirmed

**Work in both places**
- In context (on page) → ensures it fits UI
- In design system → ensures consistency

👉 Move between both

**Designer responsibility**
- Don’t leave states to developers
- Collaborate, but you define the design

<hr>

## 4. Accessibility: 6 Key Questions
Use these to evaluate any state or UI element:
1. What is the state?
2. Is it essential? If removed → does it break usability/accessibility?
3. Is it contrast compliant?
4. Is it colour independent? Not relying on colour alone
5. Is it noticeable enough? Clear visual difference
6. Does it use clear signifiers?

👉 Goal: answer YES to all

<hr>

## 5. Accessibility Principles (from WCAG)

From World Wide Web Consortium:
- **POUR Principles:** Perceivable, Operable, Understandable, Robust
- **Hierarchy: Principles:** → Guidelines → Criteria → Techniques

👉 All states must be accessible and usable

<hr>

## 6. Focus States (Important)
Focus = keyboard navigation indicator

- Clearly visible
- High contrast
- Not colour-only
- Large/noticeable

👉 Critical for accessibility (keyboard users)

<hr>

## 7. Hover States (Important)
**For usability:**
- Needed for mouse users
- Improves discoverability

**For accessibility:**
- Must maintain text contrast (4.5:1)
- Noticeable
- Not rely on colour only

👉 Hover may or may not be “essential” → affects strict WCAG requirements

<hr>

## 8. Style Guide vs Design System
**Design System**
- Full system (UI + code + principles)
- Living, evolving product

**Style Guide**
- Part of design system
- Colours
- Typography
- Visual styles

**Other components**
- Pattern library
- Writing guidelines
- Branding

👉 All ensure consistency + scalability
