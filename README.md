# habit-tracker
Another test vibecoding project

---

## Changelog

### 2026-03-29 — Fireworks + year calendar (`4a6772f`)
- Replaced confetti with proper fireworks: rockets shoot up with glowing trails and explode into 80–130 sparks with gravity, fade, and slow-falling white glitter
- 6–8 rockets launch with staggered timing, each with a random red/yellow/orange palette
- Single habit completion keeps a small 32-particle radial burst
- Removed per-card weekly calendar rows
- Added full-year heatmap (March–December) below the habits list: GitHub contribution graph style with weeks as columns, Mon–Sun rows, month labels, and a 5-level red→yellow color scale; future days ghosted, today outlined

### 2026-03-29 — Redesign + new features (`2f2c4bd`)
- Restyled to a dark monochrome theme with red and yellow accents (removed purple)
- Drag-and-drop reordering of habits via a dot-grid handle
- Emoji picker per habit (40 options, saved per habit)
- Color label picker (11 colors) shown as a left border bar on each card and as dot tints in the weekly view
- Confetti animation: small radial burst when a single habit is completed, full screen rain when all habits are done
- Weekly calendar row on each card showing completion status for the last 7 days
- Migrated data schema to v3 (added `history` array, `emoji`, and `color` fields per habit)

### 2026-03-29 — Initial habit tracker (`5b86d6a`)
- Single-file HTML/CSS/JS habit tracker
- Add and delete habits
- Daily checkbox with streak tracking (resets if a day is missed)
- Progress summary bar showing habits completed today
- Data persisted in `localStorage`
- Midnight auto-reset to start a fresh day
- Purple/violet dark theme with animated UI
