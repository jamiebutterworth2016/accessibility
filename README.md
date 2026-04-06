# Accessibility & Usability Notes

## 1. Colour Contrast

👉 Check contrast during development.

**✅ Information-bearing elements need high contrast:**
- Text / UI elements: ≥ 4.5:1
- Large text / UI controls: ≥ 3:1
- Graphs: ≥ 3:1

**Decorative and disabled elements are exempt:**
<br>Background patterns, artistic borders, logos, photos, non-functional icons

<hr>

## 2. Colour Independence
👉 Don't rely on colour to convey information.
- Use multiple indicators instead: text, icons, shapes, underlines, bold, patterns
- Design initially in greyscale ⬛⬜ → Add colour later 🎨

CVD = Colour Vision Deficiency (colour blindness)

| CVD Type     |🟥   |🟩    |🟦| Description                                                       |
|--------------|------|------|---|-------------------------------------------------------------------|
| Deuteranopia |🟨/🟫|🟨/🟫|🟦| Green-blind (common). Red/Green → Yellow/Brown. Purple🟪 → Blue🟦|
| Protanopia   |⬛/🟫|🟨/🟩|🟦| Red-blind. Red → Black/Brown.                                     |
| Tritanopia   |🟥    |🟩   |🟩| Blue-yellow blind (rare). Blue → Green. Yellow🟨 → Grey/Pink⬜🩷 |
---

**Testing:**
- Greyscale test ⬛⬜ → checks colourblind accessibility  
- Use simulators/plugins to preview

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
