# Structural Plan — 48' × 25' Single-Story Home

> RCC moment-frame on isolated pad footings, engineered for the narrow **48'-0" (N–S) × 25'-0" (E–W)** footprint and **future 2nd-floor** vertical extension. Designed to **BNBC 2020, Seismic Zone-2** (Dhaka/central region). All columns carry starter bars for Phase-2.

---

## 1. Design Basis

| Parameter | Value |
|---|---|
| Building use | Residential (single story, future G+1) |
| Footprint | 48'-0" × 25'-0" = 1,200 sqft |
| Code | BNBC 2020 |
| Seismic zone | Zone-2, Z = 0.20 |
| Basic wind speed | 65 m/s (Dhaka region) |
| Soil safe bearing capacity (SBC) | **assumed 75 kN/m² (1.5 ksf)** — *confirm by soil test* |
| Concrete grade | **M20** (footing/grade beam), **M20–M25** (column/slab) — 1:1.5:3 |
| Steel grade | **500W** (fy = 500 MPa) — BSRM / AKS / KSRM |
| Clear cover | Footing 50 mm · Column 40 mm · Beam 25 mm · Slab 20 mm |
| Floor-to-roof | 10'-6" (9'-3" clear + 1'-3" beam/slab) |
| Plinth height | 2'-6" above NGL |
| Founding depth | 4'-6" below NGL |

> ⚠️ **Hold point:** Footing sizes below assume SBC = 75 kN/m². If the soil test reports lower, footings must be enlarged. Do not cast footings before the test is reviewed.

---

## 2. Column Grid (3 × 5 = 15 columns)

```
            A            B            C        ← grid lines E–W (x)
            x=0          x=12.5'      x=25'
            │            │            │
   5  ●────────────●────────────●               y = 48'-0"  (NORTH)
            │            │            │
            │  bay       │  bay       │   12'-0"
   4  ●────────────●────────────●               y = 36'-0"
            │            │            │   12'-0"
   3  ●────────────●────────────●               y = 24'-0"
            │            │            │   12'-0"
   2  ●────────────●────────────●               y = 12'-0"
            │            │            │   12'-0"
   1  ●────────────●────────────●               y = 0'-0"   (SOUTH)
            │            │            │
       └──── verandah cantilever 6'-0" projects SOUTH (no extra columns) ────┘

   ●  = RCC column 12"×12"
   Bays:  E–W = 2 × 12'-6"   |   N–S = 4 × 12'-0"
```

| Item | Value |
|---|---|
| Grid E–W | A = 0', B = 12'-6", C = 25'  → 2 bays @ 12'-6" |
| Grid N–S | 1=0', 2=12', 3=24', 4=36', 5=48' → 4 bays @ 12'-0" |
| Total columns | **15** |
| Verandah | 6'-0" cantilever to south (column-free) |
| Max clear span | 12'-6" (economical) |

---

## 3. Foundation — Isolated Pad Footings (15)

| Footing | Location | Size (ft) | Depth | Reinforcement |
|---|---|---|---|---|
| **F1** (corner) ×4 | A1,C1,A5,C5 | 5'-0" × 5'-0" | 1'-3" | T12 @ 5" c/c both ways |
| **F2** (edge) ×8 | B1,B5,A2,A3,A4,C2,C3,C4 | 5'-6" × 5'-6" | 1'-3" | T12 @ 5" c/c both ways |
| **F3** (interior) ×3 | B2,B3,B4 | 6'-0" × 6'-0" | 1'-6" | T12 @ 4.5" c/c both ways |

**Footing build-up (bottom → top):**
1. 6" brick flat soling (CC)
2. 3" PCC (1:4:8) leveling course
3. RCC pad footing (size/depth above), M20
4. RCC pedestal 12"×18", up to plinth beam bottom

> All footings tied together by **plinth (grade) beams** for seismic integrity (Zone-2 requirement).

---

## 4. Column Schedule

| Mark | Size | Vertical bars | Ties | Count |
|---|---|---|---|---|
| **C1** (all) | 12" × 12" | 6 – T16 | T10 @ 5" (ends) / 6" (mid) | 15 |

- Lap length: 50 × dia (≈ 32" for T16); stagger 50%.
- **Phase-2 starter bars:** extend the 6-T16 verticals **3'-0" above roof slab**, wrapped/greased, for the future 2nd-floor columns.
- Confinement: close ties (T10 @ 4") within L/6 of each joint (ductile detailing, Zone-2).

---

## 5. Beam Plan

### Plinth beams (grade beams) — tie all footings
| Mark | Size | Top | Bottom | Stirrups |
|---|---|---|---|---|
| **PB** | 10" × 12" | 3 – T16 | 3 – T16 | T10 @ 6" |

### Roof beams
| Mark | Direction | Size | Top | Bottom | Stirrups |
|---|---|---|---|---|---|
| **MB** (main) | N–S (lines A,B,C) | 10" × 15" | 3 – T16 + 2 – T12 (support) | 3 – T16 | T10 @ 5"/8" |
| **CB** (cross) | E–W (lines 1–5) | 10" × 12" | 2 – T16 | 3 – T16 | T10 @ 6" |
| **VB** (verandah) | cantilever edge | 10" × 15" | 3 – T16 (top steel critical) | 2 – T12 | T10 @ 5" |

> Cantilever verandah: **top reinforcement is the main steel** — never reduce it. Provide back-span anchorage into line-1 beams ≥ cantilever length.

---

## 6. Roof Slab

| Parameter | Value |
|---|---|
| Type | Two-way RCC slab, M20 |
| Thickness | **5"** (125 mm) |
| Main steel | T10 @ 5" c/c (bottom, both ways) |
| Top steel | T10 @ 6" c/c at supports / corners (anti-crack) |
| Verandah slab | 5", cantilever — **top steel T10 @ 4" c/c**, anchored back |
| Cover | 20 mm |

---

## 7. Stair (RCC switchback, south-center)

| Parameter | Value |
|---|---|
| Type | Dog-legged (switchback), 2 flights + mid-landing |
| Going / Riser | 10" going / 6" riser |
| Waist slab | 6" RCC, M20 |
| Width | 3'-3" per flight |
| Main steel | T12 @ 6" (along span) + T10 @ 8" (distribution) |
| Note | Built now to reach roof + serve future 2nd floor |

---

## 8. Lintels & Sun-shades

- **Lintels:** 5" RCC over all doors/windows, 2 – T10 + T8 stirrups @ 6", bearing 9" each side.
- **Chajja (sun-shade):** 4" RCC, 2'-0"–3'-0" projection over south/west openings, T8 @ 6" top steel.

---

## 9. Concrete & Steel Summary (see `component-calculation.md` for full take-off)

| Item | Quantity |
|---|---:|
| Total structural RCC | **55.9 m³ (≈1,973 cft)** |
| PCC (lean) | 3.2 m³ (≈113 cft) |
| Reinforcement steel | **9.3 ton** (≈166 kg/m³) |
| Cement (structure share) | ≈ 458 bags |

---

## 10. Future 2nd-Floor Provisions

1. All 15 columns + footings sized for **G+1** (2 floors) already.
2. Column **starter bars** project above the roof (greased/protected).
3. Stair already lands at roof level — extend upward in Phase-2.
4. Roof slab penetrations for future plumbing risers cast as sleeves.
5. Phase-2 adds ≈ 18 lakh (see `docs/phase-2-extension.md`).

---

## 11. Construction Hold Points (inspect before next step)

1. Excavation depth & soil at founding level (vs. soil test).
2. Footing rebar & cover **before** PCC/concrete pour.
3. Column rebar, ties spacing & verticality before casting.
4. Beam/slab rebar, cover blocks, electrical conduits before slab pour.
5. Slab concrete cube samples (3 nos / pour) for 7 & 28-day test.

> Bengali versions of these drawings for the mason → `drawings-bangla/`.
