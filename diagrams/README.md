# Yumea Wiki Diagrams

Beautiful system diagrams for the Yumea board game wiki. These visual explanations capture the dreamlike aesthetic while maintaining rigorous accuracy.

## Diagrams

### Phase 1 — System Architecture (Complete)

| Diagram | File | Description |
|---------|------|-------------|
| **Core Loop** | `core-loop.svg` | Circular flow: Tile Placement → Harmony → Tension → Nightmare → Purification → Energy |
| **Emotional Axis** | `emotional-axis.svg` | Four mirrored pairs: Fear↔Courage, Despair↔Hope, Isolation↔Connection, Chaos↔Balance |
| **Nightmare Pyramid** | `nightmare-pyramid.svg` | Three-tier escalation: Whispers (10) → Echoes (12) → Reverberations (8+) |

## Visual Style

### Color Palette

**Harmony (Warm):**
- Primary: `#D4A574` (warm gold)
- Secondary: `#E8D5B7` (soft cream)
- Accent: `#F4E4C1` (light amber)

**Tension (Sharp):**
- Primary: `#E07A5F` (terracotta)
- Secondary: `#F2CC8F` (caution yellow)
- Accent: `#D62828` (alert red)

**Nightmares (Corrupted):**
- Primary: `#3D5A80` (desaturated blue)
- Secondary: `#98C1D9` (sickly cyan)
- Accent: `#1D3557` (deep void)

**Purification (Restoration):**
- Primary: `#6B9B7A` (forest green)
- Secondary: `#A8D5BA` (soft mint)

**Neutral:**
- Background: `#FDFBF7` (warm white)
- Text: `#2B2D42` (soft black)

### Design Principles

- **Soft edges**: Rounded corners, organic shapes
- **Layered depth**: Subtle shadows via SVG filters
- **Symbolic icons**: Minimal, emotionally resonant
- **Generous whitespace**: Breathing room for clarity
- **Colorblind-friendly**: Pattern/text distinctions, not just color

## Usage

### Viewing

Open SVG files directly in any modern browser:
```bash
# macOS
open core-loop.svg

# Linux
xdg-open core-loop.svg

# Or simply drag into browser
```

### Embedding in Markdown

```markdown
![Core Loop](diagrams/core-loop.svg)
*The emotional arc of a turn: choice → consequence → collaboration*
```

### Rendering to PNG (if needed)

Using ImageMagick:
```bash
convert -density 150 core-loop.svg core-loop.png
```

Using Inkscape:
```bash
inkscape core-loop.svg --export-type=png --export-dpi=150
```

Using a browser + screenshot:
```bash
# Serve files locally
python3 -m http.server 8080
# Open in browser at 100% zoom, screenshot
```

## Technical Details

- **Format**: SVG (Scalable Vector Graphics)
- **ViewBox**: Optimized for consistent rendering
- **Fonts**: Georgia (serif) for headers, system sans-serif fallback
- **Effects**: SVG filters for soft shadows and glows
- **Accessibility**: Semantic structure, color-independent visual cues

## Maintenance

To modify a diagram:
1. Edit the SVG directly (text editor or Inkscape)
2. Maintain the Yumea color palette for consistency
3. Keep the dreamlike aesthetic: soft, watercolor-inspired
4. Test at multiple sizes (50%, 100%, 200%)

## Future Diagrams

Per `DIAGRAM_GENERATION_PLAN.md`:

### Phase 2 — Evolution Diagrams
- [ ] Game version timeline (v0.1 → v0.2 → v0.3 → v0.4)
- [ ] Energy economy evolution
- [ ] Persona balance journey

### Phase 3 — Comparative & Component
- [ ] Replayability score breakdown
- [ ] Card ecosystem diagram
- [ ] Board state visualization

---

*Created for the Yumea wiki — where dreamlike beauty meets crystalline clarity.*