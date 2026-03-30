# Accessibility & Usability Notes

## 1. Colour Contrast
- Low contrast sensitivity is common, especially with age
- Ensure text and key elements are readable
- Guided by the W3C Web Accessibility Initiative

**Information-bearing elements need high contrast:**
- Text, images of text
- UI components: buttons, toggles, charts

**Decorative/disabled elements are exempt:**
- Background patterns, artistic borders, logos, photos, non-functional icons

**Contrast ratios**
Standard: 4.5 : 1
Exceptions: 3 : 1 for:
- Large text (14pt bold / 18pt regular)
- UI controls (toggles)
- Graph elements (pie chart segments)

**Best practices**
- Check contrast during development
- Ask: _Is this element informative or decorative?_
- Use contrast checking tools

<hr>

## 2. Colour Vision Deficiency (CVD) & Colour Independence

**Principle:** Colour must not be the only way to convey information  

---

**Deuteranopia** 🟦🟨 (green-blind, most common)  
- Reduced sensitivity to green → red/green confusion  

**Hard to distinguish:**
- Red / Green 🟥🟩  
- Green / Brown 🟩🟫  
- Green / Blue 🟩🟦 (sometimes)  


**Protanopia** 🟦🟨 (red-blind)  
- Reduced sensitivity to red (reds appear darker) → red/green confusion  

**Hard to distinguish:**
- Red / Green 🟥🟩  
- Red / Black/Grey 🟥⬛  


**Tritanopia** 🩵🩷 (blue-yellow blind, rare)  
- Difficulty distinguishing blue/green and yellow/violet  

**Hard to distinguish:**
- Blue / Green 🟦🟩  
- Blue / Purple 🟦🟪  
- Yellow / Violet 🟨🟪  


**Achromatopsia** ⬛⬜ (monochrome, very rare)  
- No colour vision (greyscale only)  

**Hard to distinguish:**
- Any colour-only differences

---

**Testing:**
- Greyscale test ⬛⬜ → checks colourblind accessibility  
- Contrast test → checks visual clarity
- Use simulators/plugins to preview

**Design approach:**
- Start in black & white → add colour later
- Use multiple indicators: text, icons, shapes, underlines, bold, patterns
- Never rely on colour alone

**UI & Interaction Cues**
- Use multiple cues for state (menus, steps): underlines, bold, icons (ticks ✔), connection lines
- Highlight current step clearly
- Progress trackers: tick symbols, lines, bold/underlined current step

<hr>

## 3. Visualisation & Maps: Colour-Independent Design
**Principles**:
- Colour-independent design
- Minimum 3:1 contrast
- Pass greyscale test ⬛⬜
- Provide alternative formats (e.g., tables)

**Charts & Graphs**
- **Bar charts:** pattern fills, labels/values above bars, interactive highlighting (hover/tap)
- **Line graphs:** differentiate lines with dashes, dots, shapes; alternative formats; scalable SVGs

**Maps & Visual Systems**
- Use labels instead of colour-only indicators
- Different line styles: solid, dotted
- Patterns, shapes
- Ensure usability in greyscale

Rule: Never rely on colour alone to convey information

<hr>

## 4. Types of Impairments
- Visual: contrast, acuity, colour vision
- Auditory
- Motor
- Cognitive

**Key terms**
- CVD (Colour Vision Deficiency): difficulty distinguishing colours
- Acuity: clarity of vision

![Untitled](https://github.com/user-attachments/assets/0ec6cfb7-8cb0-46c8-a370-2907b949f12e)
