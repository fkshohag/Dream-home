# Floor Plan & Design Decisions — 48' × 25' Home (based on `design 2.png`)

> Layout follows your sketch `diagram/design 2.png`: a **central-dining pinwheel** in a narrow **48'-0" (South↔North) × 25'-0" (East↔West)** envelope. Main verandah + gate on **SOUTH**, secondary door on **WEST**. Program: **3 bedrooms + 3 baths** (2 attached + 1 common), drawing, dining, kitchen, stair, verandah.

*(Your sketch is drawn south-up; this document uses standard north-up convention. South = front = bottom.)*

---

## 1. Design Decisions

| # | Decision | Rationale |
|---|---|---|
| D1 | **Footprint 48' (N–S) × 25' (E–W) = 1,200 sqft**; verandah projects 6' south (≈150 sqft extra) | Matches your dimensions; keeps interior at 1,200 |
| D2 | **Main entry + gate on SOUTH** (full-width verandah) | Best breeze + winter sun; faces road/approach |
| D3 | **Secondary "West Gate" = 3'-6" door into Drawing room (west wall)** | Side-yard access as you marked |
| D4 | **Room 2 (NE) & Room 3 (NW) = master suites** with attached baths | Quiet rear; cross-vent on long E/W walls |
| D5 | **Room 1 (SE) = 3rd bedroom**, uses the common bath | Near entry → doubles as guest room |
| D6 | **Dining = central hub** (no wasted corridor) | Connects all four quadrants efficiently |
| D7 | **Stair = compact switchback at the SOUTH entry** (south-center, by main door); store under | Stair on south side as required; short travel; lands at future 2nd-floor opening |
| D8 | **Kitchen on the NORTH external wall** (north-center), with north window + exhaust fan straight outside | Cooking heat/smoke vents directly outdoors — proper airflow |
| D8a | **Service spine runs S→N: Stair (entry) → Dining (center) → Kitchen (north wall)** | Every spine element either sits at a door or on an outside wall |
| D8b | **Room 2 & Room 3 doors at their SOUTH ends** (Room 3 → SW, Room 2 → SE), far from the north-center kitchen | Keeps kitchen smell/heat out of the bedrooms |
| D11 | **Verandah is OUTSIDE the 48'** — the 48'-0" is the building only; the 6'-0" verandah projects south beyond it | Interior stays 1,200 sqft; verandah is extra covered area |
| D9 | **Common bath central-east** ("Birth room" in sketch) | Serves Room 1 + guests off the dining |
| D10 | **Structure: RCC frame, 3×5 = 15 columns**, isolated footings, future-2nd-floor ready | Economical spans (12'-6" × 12'-0") |

---

## 2. Room Schedule

| # | Room | Position | Size (ft) | Area (sqft) |
|---|---|---|---|---:|
| 1 | Verandah | South (proj.) | 25 × 6 | 150 |
| 2 | Drawing Room | South-West | 11 × 16 | 176 |
| 3 | Room 1 (bed) | South-East | 10 × 16 | 160 |
| 4 | Stair | **South entry (center)** | 6 × 11 | 66 |
| 5 | Dining | Center hub | 12 × 15 | 180 |
| 6 | Common Bath | East-center | 7 × 6 | 42 |
| 7 | Kitchen | **North-center (ON north wall)** | 8 × 10 | 80 |
| 8 | Room 2 (master) | North-East | 11 × 13 | 143 |
| 9 | Att. Bath 2 | in Room 2 | 6 × 5 | 30 |
| 10 | Room 3 (master) | North-West | 11 × 12 | 132 |
| 11 | Att. Bath 3 | in Room 3 | 6 × 5 | 30 |
| 12 | Circulation/walls | — | — | ~161 |
| | **Interior total** | | | **~1,200** |

---

## 3. Architecture Diagram (ASCII)

```
                          NORTH (rear)
  W ◄───────────────────────────────────────────────► E
y48┌────────────┬───────────────┬─────────────────────┐
   │ ROOM 3      │   KITCHEN      │   ROOM 2            │
   │ (MASTER)    │   8'×10'       │   (MASTER)          │
   │ 11'×12'     │ [N window +    │   11'×13'           │
   │ ┌──────┐    │  exhaust fan]  │          ┌──────┐   │
   │ │ATT B3│    ├───────┬────────┤          │ATT B2│   │
   │ └──────┘    │       │        │          └──────┘   │
   │             │  DINING (hub)  │   ┌───────────────┐ │
   │             │   12'×15'      │   │  COMMON BATH  │ │
   │             │                │   │    7'×6'      │ │
y15├─────────────┴───┬────────────┴───┴───────────────┤ │
   │ DRAWING ROOM    │    STAIR     │   ROOM 1 (BED)   │
   │  11'×16'        │    6'×11'    │    10'×16'       │
   │                 │  (at entry)  │                  │
[D2]║◄ west door      │              │                  │
y0 └─────────────────┤  D1 MAIN  ├──┴──────────────────┘
   ┌─────────────────────────────────────────────────────┐
   │              VERANDAH 25' × 6'  (main gate)           │
   └─────────────────────────────────────────────────────┘
                          SOUTH (front / road)

   ✔ STAIR at the south entry   ✔ KITCHEN on the north wall (vents outside)
```

> Schematic — exact partition positions tuned around the 15-column grid (see `structural-plan.md`). A cleaner rendered diagram is in `drawings/architecture-diagram.png`.

---

## 4. Circulation

- **Main:** Verandah (S) → **D1** → entry/stair foyer → **Dining (center)** → branches to Drawing (SW), Room 1 (SE), Kitchen (N), Room 2 (NE), Room 3 (NW), Common Bath (E).
- **Secondary:** **D2 west door** → directly into Drawing room.
- **Vertical:** Stair (S-center) switchback → future 2nd-floor opening.

---

## 5. Door & Window Count (preliminary)

- **Doors (10):** D1 main (4'×7'6"), D2 west (3'6"×7'), Drawing↔Dining (open), Room1, Room2, Room3, Kitchen service, 3× bath doors.
- **Windows (13):** Drawing ×2, Room1 ×2, Room2 ×2, Room3 ×2, Kitchen ×1, 3× bath vents, Dining ×1.

Detailed schedules + structural quantities → see `structural-plan.md` and `component-calculation.md`.
