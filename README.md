# Accessibility & Usability Notes

## 1. Colour Contrast

**Why it matters**
- Low contrast sensitivity is common, especially with age
- Ensures text and important elements are readable for all users
- Guided by the W3C Web Accessibility Initiative

**What needs contrast**
Information-bearing elements only, such as:
- Text
- Images of text
- UI components (buttons, toggles, charts)

**What can be ignored**
Decorative elements:
- Background patterns
- Artistic borders
- Logos
- Photos
- Non-functional icons

**Contrast ratio guidelines**
Standard: 4.5 : 1
Exceptions: 3 : 1 for:
- Large text (14pt bold or 18pt regular)
- UI controls (e.g. toggles)
- Graph elements (e.g. pie chart segments)

**Best practices**
- Check contrast during development
- Ask: Is this element informative or decorative?
- Use contrast checking tools to identify violations

<hr>

## 2. Colour Vision Deficiency (CVD)
**Deuteranopia** 🟦🟨 (green-blind, most common)
Mainly sees blue and yellow; cannot distinguish red and green
**Problematic combinations:**
- Red / Green 🟥🟩
- Green / Blue 🟩🟦
- Green / Black/Grey 🟩⬛

**Protanopia** 🟦🟨 (red-blind)
Mainly sees blue and yellow; cannot distinguish red and green
**Problematic combinations:**
- Red / Green 🟥🟩
- Red / Black/Grey 🟥⬛

**Tritanopia** 🩵🩷 (blue-yellow blind): Sees pinks and blues differently
Difficulty distinguishing blue and yellow; sees pinks and other colours differently
**Problematic combinations:**
- Blue / Grey 🟦⬛
- Blue / Purple 🟦🟪

**Achromatopsia** ⬛⬜ (monochrome)
Sees only greyscale; affects ~1 in 12 men
**Problematic combinations:**
Any colour-only differences; rely on patterns, shapes, and labels instead

**Tools**: Use simulators or plugins to preview designs under different CVD conditions

<hr>

## 3. Colour Independence
**Principle**: Colour must not be the only way to convey information
**Testing**
- Greyscale test ⬛⬜ → colourblind accessibility
- Contrast test → visual clarity
**Design approach**
- Start in black and white; add colour later as enhancement
- Use alternative indicators: text labels, icons, shapes, underlines, bold text, patterns.

<hr>

## 4. UI & Interaction Design
**State indication (menus, steps, etc.)**
- Underlines
- Bold text
- Icons (e.g. ticks ✔)
- Connection lines
Highlight current step clearly
Use multiple visual cues, not just colour

**Progress / Step trackers**
Indicate completion with:
- Tick symbols
- Lines between steps
- Bold or underlined current step

<hr>

## 5. Data Visualisation (Charts & Graphs)
**General principles**
- Must be colour independent
- Always pass greyscale test
- Maintain minimum 3:1 contrast

**Bar charts**
- Pattern fills (instead of only colour)
- Labels or values above bars
- Interactive highlighting (hover/tap)

**Line graphs**
Differentiate lines using:
- Dashes
- Dots
- Unique shapes

**Additional tips**
- Provide alternative formats (e.g. tables)
- Use scalable SVGs
- Ensure clear contrast and readability

<hr>

## 6. Maps & Visual Systems
- Labels instead of colour-only indicators
- Different line styles (solid, dotted)
- Patterns and shapes
Ensure usability in greyscale

<hr>

## 7. Types of Impairments to Consider
- Visual (contrast, acuity, colour vision)
- Auditory
- Motor
- Cognitive
**Key terms**
- CVD (Colour Vision Deficiency): difficulty distinguishing colours
- Acuity: how clearly someone can see details

![Untitled](https://github.com/user-attachments/assets/0ec6cfb7-8cb0-46c8-a370-2907b949f12e)
