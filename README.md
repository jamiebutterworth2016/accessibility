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
- 
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

## 3. Colour Vision Deficiency (CVD)
**Common types**
- Protanopia (red-blind): Difficulty distinguishing red and green
- Deuteranopia (green-blind) (most common): Mainly sees blue and yellow
- Tritanopia (blue-yellow blind): Sees pinks and blues differently
- Achromatopsia (monochrome): Sees only greyscale. Affects ~1 in 12 men

**Key issues**
- Users may not distinguish certain colour combinations
- Example: red berries on a green bush may be invisible

Problematic colour combinations
- Red / Green
- Green / Blue
- Green / Grey
- Green / Black
- Blue / Grey
- Blue / Purple

**Tools**
Use plugins/simulators to preview designs under different colour vision conditions

4. Colour Independence
Core principle
Colour must NOT be the only way to convey information
Testing methods
Greyscale test → checks colourblind accessibility
Contrast test → checks visual clarity
Design approach
Start in black and white
Add colour later as enhancement only
Alternative indicators

Use:

Text labels
Icons
Shapes
Underlines
Bold text
Patterns

Avoid relying only on colour changes

4. UI & Interaction Design
State indication (menus, steps, etc.)
Use:
Underlines
Bold text
Icons (e.g. ticks ✔)
Connection lines
Highlight current step clearly
Use multiple visual cues, not just colour
Progress / Step trackers
Indicate completion with:
Tick symbols
Lines between steps
Bold or underlined current step
5. Data Visualisation (Charts & Graphs)
General principles
Must be colour independent
Always pass greyscale test
Maintain minimum 3:1 contrast
Bar charts
Use:
Pattern fills (instead of only colour)
Labels or values above bars
Interactive highlighting (hover/tap)
Line graphs
Differentiate lines using:
Dashes
Dots
Unique shapes
Additional tips
Provide alternative formats (e.g. tables)
Use scalable SVGs
Ensure clear contrast and readability
6. Maps & Visual Systems
Use:
Labels instead of colour-only indicators
Different line styles (solid, dotted)
Patterns and shapes
Ensure usability in greyscale
7. Types of Impairments to Consider
Visual (contrast, acuity, colour vision)
Auditory
Motor
Cognitive
Key terms
CVD (Colour Vision Deficiency): difficulty distinguishing colours
Acuity: how clearly someone can see details

![Untitled](https://github.com/user-attachments/assets/0ec6cfb7-8cb0-46c8-a370-2907b949f12e)
