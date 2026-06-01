# Structural Plan — Foundation, Columns, Beams, Slab

*Designed for single-story load NOW + future 2nd-floor extension (Phase-2).*

---

## 1. Grid layout

**4 × 4 grid = 16 columns, uniform 12'-0" × 12'-2" bays**

```
                                  N ▲
                A           B           C           D
                0'        12'-0"      24'-0"       36'-0"
   4   36'-6" ●C1─────────●C2─────────●C3─────────●C4
              │           │           │           │
              │           │           │           │
              │           │           │           │
   3   24'-4" ●C5─────────●C6─────────●C7─────────●C8
              │           │           │           │
              │           │           │           │
              │           │           │           │
   2   12'-2" ●C9─────────●C10────────●C11────────●C12
              │           │           │           │
              │           │           │           │
              │           │           │           │
   1    0'-0" ●C13────────●C14────────●C15────────●C16
              0'        12'-0"      24'-0"       36'-0"
              ◄── verandah cantilever 6'-0" west ──
              (slab projects from line 1)
```

Column numbering: C1–C4 are the back (N) row; C13–C16 are the front (S) row.

---

## 2. Foundation plan

Each column sits on an **isolated RCC pad footing**, founded **4'-6" below natural
ground level** on a 3" plain-cement-concrete (PCC) levelling course over a
6" compacted brick-soling base.

### Footing schedule

| Column type | Footing size | Footing depth | Bottom reinforcement |
|---|---|---|---|
| Corner (C1, C4, C13, C16) | 5'-6" × 5'-6" | 1'-3" | T12 @ 5" c/c both ways |
| Edge (C2, C3, C5, C8, C9, C12, C14, C15) | 5'-6" × 5'-6" | 1'-3" | T12 @ 5" c/c both ways |
| Interior (C6, C7, C10, C11) | 6'-0" × 6'-0" | 1'-3" | T12 @ 5" c/c both ways |

> **Soil-condition contingency**: If auger soil test shows SBC < 1.2 ksf,
> upgrade to a **mat foundation** (9" thick RCC raft, 38' × 38' overall, with
> T12 @ 5" c/c top + bottom both ways). Cost delta: ~ BDT 1.2 lakh.

```
   Footing detail (typical isolated pad):

                  ┌───────────────────┐
                  │  RCC column above │
                  │  12" × 12"        │
                  │                   │
   NGL ────────── │ ─── pedestal ─── │ ←── 1'-6" pedestal
                  │  12" × 18"        │
                  ╞═══════════════════╡  ←── top of footing
                  │                   │
                  │  RCC footing      │  ←── 1'-3" thick
                  │  5'-6" × 5'-6"    │
                  ╞═══════════════════╡  ←── PCC 3" thick
                  ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃  ←── brick soling 6"
                  ───────────────────────  ←── 4'-6" below NGL
                  (firm bearing strata)
```

---

## 3. Column schedule

| Member | Size | Concrete grade | Vertical reinforcement | Ties |
|---|---|---|---|---|
| **All 16 columns** | **12" × 12"** | M25 | 6 × T16 (Fe-500) | T10 @ 6" c/c general; T10 @ 3" c/c within 1' of beam-column joints |

**Important: Phase-2 starter bars.** Each column's main bars are continued
**4'-0" above the roof slab**, wrapped in oiled cloth + dry sand, capped with
PVC end-caps. When Phase-2 is built, these become the dowels for the new
columns above.

---

## 4. Beam plan (roof level — same level as future 1st-floor slab in Phase-2)

```
                                  N ▲
              A           B           C           D
              ●═══════════●═══════════●═══════════●     ← B1 (main beam, E-W)
              ║           ║           ║           ║
              ║ B5        ║ B6        ║ B7        ║ B8
              ║(secondary)║           ║           ║
              ║           ║           ║           ║
              ●═══════════●═══════════●═══════════●     ← B2
              ║           ║           ║           ║
              ║ B9        ║ B10       ║ B11       ║ B12
              ║           ║           ║           ║
              ║           ║           ║           ║
              ●═══════════●═══════════●═══════════●     ← B3
              ║           ║           ║           ║
              ║ B13       ║ B14       ║ B15       ║ B16
              ║           ║           ║           ║
              ║           ║           ║           ║
              ●═══════════●═══════════●═══════════●     ← B4
              ◄── B17 verandah cantilever beam ──►
```

### Beam schedule

| Member | Size | Top steel | Bottom steel | Stirrups |
|---|---|---|---|---|
| Main beams B1–B4 (E-W) | 10" × 12" | 4 × T16 | 4 × T16 | T10 @ 6" c/c, @ 3" near supports |
| Secondary beams B5–B16 (N-S) | 10" × 12" | 3 × T12 | 4 × T16 | T10 @ 6" c/c |
| Verandah cantilever B17 | 10" × 12" | **5 × T16** (heavily reinforced top) | 3 × T12 | T10 @ 4" c/c, @ 3" at support |

---

## 5. Slab plan

**Two-way RCC slab, 5" thick, M20**, supported on the 4×4 grid (max bay 12'-0" × 12'-2" → span/depth ratio ≈ 30, well within code).

```
   Reinforcement:
   - Bottom main:    T10 @ 5" c/c, parallel to short span
   - Bottom distribution: T10 @ 5" c/c, perpendicular
   - Top steel:      T10 @ 5" c/c (over supports only, ~ L/4 from supports)
   - Verandah cantilever slab: T10 @ 4" c/c top, T8 @ 6" c/c bottom

   Slab finish (roof):
   - 1" lime terracing (waterproofing)
   - 2" brick-bat coba (slope 1:80 to four 4" PVC down-spouts)
   - Tile finish in roof-garden zone, parapet 3'-6" tall

   Future stair plug:
   - Rectangular opening 8'-0" × 5'-0" cast in slab at R10 location
   - Plugged with 6"-thick precast RCC slab section (removable)
   - Edge bars: 4 × T16 frame around the opening
```

---

## 6. Plinth plan

```
   Plinth beam (running along all 4 grid lines, both directions):
   - Size: 10" × 12"
   - Concrete: M20
   - Top + Bottom: 4 × T16 main
   - Stirrups: T10 @ 6" c/c
   - DPC: 1.5" cement-sand 1:3 + waterproofing additive (Dr Fixit / Saver)
   - Plinth filling: sand (compacted in 6" lifts to 95% Proctor) up to floor
     finish level (+2'-6" above NGL)
```

---

## 7. Reinforcement summary (estimated)

| Member | Approx steel (kg) |
|---|---:|
| 16 footings | 850 |
| 16 columns × 12'-6" + 4'-0" starters | 1,920 |
| Plinth beams (260 rft) | 580 |
| Main + secondary beams (roof level) | 1,650 |
| Verandah cantilever beam + slab | 320 |
| Slab (1,500 sqft net) | 2,100 |
| Stair plug + miscellaneous | 180 |
| **Total** | **≈ 7,600 kg (7.6 ton)** |

(Detailed BOQ — see `budget/boq.md`.)

---

## 8. Future Phase-2 modifications (when building 1st floor)

1. **Remove the precast plug** above R10 → install staircase.
2. **Splice new column bars** onto the existing 4'-0" starter bars; cast new
   12"×12" columns up to first-floor slab level.
3. **New roof beams + slab** at first-floor level — same dimensions as current.
4. **New mumty (stair cover)** above the stair opening, 8'-0" × 10'-0".
5. **New balcony cantilever** — directly above the existing verandah cantilever
   (uses the same beam line so structurally simple).

> Phase-2 design files will be detailed when the owner is ready to extend.

---

*See also: `budget/boq.md` for materials totals.*
