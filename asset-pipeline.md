# Asset Pipeline — Finalization Plan

> *The unsolved blocker. Generate → Validate → Integrate. Turn art direction into executable workflow.*

---

## The Problem

70+ cards need art:
- 30 Nightmares (3 tiers)
- 12 Personas
- 40 Blueprints/Anchors
- 20 Goal cards
- Box art, tokens, rulebook illustrations

**Stuck on:**
- Prompt consistency across batches
- Validation criteria (what makes art "good enough?")
- Workflow integration (where does approved art go?)
- Scale (can't hand-curate every image)

---

## Phase 1: Prompt Templates (Finalized)

### Nightmare Template
```
Dreamlike watercolor, corrupted memory, [EMOTION] embodied, 
jagged edges, desaturated [COLOR], ethereal nightmare creature,
board game card art, empty center for text, --ar 2:3
```

Variables:
- [EMOTION]: fear, despair, isolation, chaos
- [COLOR]: blues for fear, greys for despair, etc.
- Tier: subtle (Whispers), manifest (Echoes), boss (Reverberations)

### Persona Template
```
Dreamlike watercolor portrait, [ARCHETYPE] guardian,
[COLOR] aura, symbolic [ELEMENT], crystalline clarity,
soft ethereal background, distinct silhouette,
emotional resonance, board game card art --ar 2:3
```

Variables:
- [ARCHETYPE]: Guardian, Scholar, Architect, etc.
- [COLOR]: per persona
- [ELEMENT]: shield, book, compass, etc.

### Blueprint Template
```
Minimalist watercolor, symbolic pattern, [TYPE] anchor,
geometric clarity, warm gold accents, spatial design,
clean lines, board game card art --ar 2:3
```

---

## Phase 2: Validation Criteria (Checklist)

### Technical
- [ ] Readable at 2.5" × 3.5" (card size)
- [ ] Colorblind-friendly (don't rely on color alone)
- [ ] 300 DPI minimum for print
- [ ] Consistent aspect ratio (2:3)

### Aesthetic
- [ ] Matches Yumea style (dreamlike watercolor)
- [ ] Clear silhouette at small size
- [ ] Emotional resonance matches card function
- [ ] Not too busy (cluttered cards unreadable)

### Integration
- [ ] File named: `{card-type}-{number}-{name}.png`
- [ ] Stored in: `projects/yumea/art/{batch}/`
- [ ] Referenced in wiki: `![Name](yumea-diagrams/path)`

---

## Phase 3: Workflow (Batch Process)

### Batch Size: 10 Cards

**Step 1: Generate (automated)**
- Run prompt template with variables
- Generate 3 variants per card
- Output: 30 images

**Step 2: Review (Omar — 15 min)**
- Quick pass: thumbs up/down
- Select best variant per card
- Flag any for re-generation

**Step 3: Validate (automated check)**
- Resolution check
- File naming check
- Place in wiki staging

**Step 4: Approve (Omar — 5 min)**
- View cards in context (wiki page)
- Approve batch or flag specific cards
- Auto-commit to wiki on approval

**Step 5: Integrate (automated)**
- Move to `art/approved/`
- Update wiki references
- Log in asset tracking

---

## Phase 4: Production Schedule

| Batch | Content | Target | Status |
|-------|---------|--------|--------|
| 1 | 10 Nightmares (Whispers) | Feb 10 | Pending pipeline finalization |
| 2 | 10 Nightmares (Echoes) | Feb 15 | |
| 3 | 10 Personas | Feb 20 | |
| 4 | 20 Blueprints | Feb 28 | |
| 5 | Remaining + Polish | Mar 7 | |

---

## Tools & Automation

### Generation
- **Midjourney:** Primary (best watercolor style)
- **Leonardo AI:** Backup (more control)
- **Nano Banana Pro:** Quick variants

### Validation
- **ImageMagick:** Batch resolution/format check
- **Python script:** File naming, metadata extraction

### Integration
- **Git:** Version control
- **Wiki server:** Auto-refresh on file change
- **Symlink:** `art/approved/` → `wiki/diagrams/`

---

## Success Criteria

Pipeline is "done" when:
1. Templates produce consistent results (3/3 usable)
2. Review takes < 2 min per card
3. Full batch (10 cards) from generation to wiki in < 1 hour
4. Omar can delegate generation, only do approval

---

## Next Actions

1. **Finalize prompt templates** — Test each, iterate until consistent
2. **Set up automation** — Scripts for validation, integration
3. **Generate Batch 1** — 10 Nightmares, validate workflow
4. **Iterate** — Adjust based on first batch experience
5. **Scale** — Run remaining batches with refined process

---

*This is the blocker that stopped me in 2025. Not design perfection — production complexity. Finalizing this pipeline is the path to PnP.*