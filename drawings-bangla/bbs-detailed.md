# বার বেন্ডিং শিডিউল - বিস্তারিত তালিকা (Detailed Bar Bending Schedule)

> ছবি `bbs-reference-bangla.png` এর সাথে এই কাগজ মিলিয়ে কাজ করুন।
> **এই তালিকা সরবরাহকারীকে (rod supplier) দিয়ে rod order করতে পারবেন।**

---

## ১. গুরুত্বপূর্ণ নিয়ম (Steel Rules)

### ক. রডের গ্রেড
- **সব রড 500W গ্রেড** (Yield strength ৫০০ N/mm² minimum)
- ব্র্যান্ড: BSRM Xtreme / AKS / KSRM / RSRM (BSTI certified)
- ⚠️ Local mill-এর সস্তা রড ব্যবহার করা যাবে না

### খ. প্রতি ১ মিটারে রডের ওজন (পরীক্ষার জন্য)

| ডায়া | ওজন (kg/m) | ১২ মিটার বার এর ওজন |
|---|---:|---:|
| T৮ (8mm) | ০.৩৯৫ | ৪.৭৪ kg |
| T১০ (10mm) | ০.৬১৭ | ৭.৪০ kg |
| T১২ (12mm) | ০.৮৮৮ | ১০.৬৬ kg |
| T১৬ (16mm) | ১.৫৮০ | ১৮.৯৬ kg |
| T২০ (20mm) | ২.৪৭০ | ২৯.৬৪ kg |

⚠️ প্রতি bundle delivery হওয়ার পর সাইটে weigh করতে হবে — হালকা হলে reject

### গ. Lap Length (যোগ দেওয়ার দৈর্ঘ্য)

| ডায়া | Lap = ৪০d (mm) | Lap (ft) |
|---|---:|---:|
| T৮ | ৩২০ | ১.১ |
| T১০ | ৪০০ | ১.৩ |
| T১২ | ৪৮০ | ১.৬ |
| T১৬ | ৬৪০ | ২.১ |
| T২০ | ৮০০ | ২.৭ |

### ঘ. Cover (কংক্রিট আবরণ)

| স্ট্রাকচার | Cover |
|---|---:|
| ভিত্তি (Footing) | ২" (৫০mm) |
| কলাম (Column) | ১.৫" (৪০mm) |
| বিম (Beam) | ১" (২৫mm) |
| স্ল্যাব (Slab) | ৩/৪" (২০mm) |
| বাথরুম sunken slab | ১" (waterproof) |

### ঙ. Hook Lengths

| Hook type | দৈর্ঘ্য |
|---|---|
| ৯০° Hook (footing) | ৯d = ৯ × ডায়া |
| ১৩৫° Hook (stirrup) | ১০d বা minimum ৭৫mm |
| Standard L-hook | ১২d |

---

## ২. পরিমাণ অনুমান (Quantity Take-off) — বিস্তারিত

### A. ভিত্তি (Footings) — ১৬টি

প্রতিটি ভিত্তি ৫'-৬" × ৫'-৬", রড T১২ @ ৫" দূরত্বে দুই দিকে।

| বিষয় | হিসাব |
|---|---|
| প্রতি ভিত্তিতে রড সংখ্যা (এক দিক) | ৫.৫ ÷ ০.৪২ + ১ = ১৪ টি |
| প্রতি রডের দৈর্ঘ্য (with hooks) | ৫.৫ + ২×০.৫ = ৬.৫ ft |
| প্রতি ভিত্তিতে রড দৈর্ঘ্য (দুই দিক) | ১৪ × ৬.৫ × ২ = ১৮২ ft |
| ১৬টি ভিত্তিতে | ১৬ × ১৮২ = ২,৯১২ ft = ৮৮৮ m |
| ওজন (T১২) | ৮৮৮ × ০.৮৮৮ = **৭৮৮ kg** |
| ১০% wastage সহ | **৮৬৫ kg** |

### B. কলাম (Columns) — ১৬টি

প্রতি কলামে ৬টা T১৬ vertical + T১০ rings @ ৬"।

**Vertical rebar (T১৬):**
| বিষয় | হিসাব |
|---|---|
| প্রতি কলামের রড সংখ্যা | ৬ |
| প্রতি রডের দৈর্ঘ্য | ভিত্তি থেকে ছাদের উপরে ৪' starter পর্যন্ত = ১৪ ft |
| Lap allowance (২ ft) | প্রতি bar bundle এ |
| মোট প্রতি কলামে | ৬ × ১৬ ft = ৯৬ ft (lap সহ) |
| ১৬ কলামে | ১৬ × ৯৬ = ১,৫৩৬ ft = ৪৬৮ m |
| ওজন (T১৬) | ৪৬৮ × ১.৫৮ = **৭৩৯ kg** |

**Rings/Ties (T১০):**
| বিষয় | হিসাব |
|---|---|
| প্রতি ring এর দৈর্ঘ্য | ৪ × ০.৭৫ + ২ × ০.৩৩ = ৩.৬৬ ft |
| ring সংখ্যা প্রতি কলামে | ১০' উচ্চতায় avg ৬" gap = ২০ + শেষে ঘন ৩" = ১০ = ৩০ rings |
| প্রতি কলামে total | ৩০ × ৩.৬৬ = ১১০ ft |
| ১৬ কলামে | ১৬ × ১১০ = ১,৭৬০ ft = ৫৩৬ m |
| ওজন (T১০) | ৫৩৬ × ০.৬১৭ = **৩৩১ kg** |

**Column total: T১৬ ৭৩৯ kg + T১০ ৩৩১ kg = ১,০৭০ kg**
**১০% wastage সহ: T১৬ ৮১৩ kg + T১০ ৩৬৪ kg**

### C. প্লিন্থ বিম (Plinth Beam)

প্রতি বিম ১০"×১২", রড: উপরে ৪-T১৬ + নিচে ৪-T১৬, stirrup T১০ @ ৬"।

**Plinth beam length total:**
- পরিধি: ২ × (৩৬.৫ + ৩৬) = ১৪৫ ft (external)
- Internal cross beams: ৪ × ৩৬ + ৪ × ৩৬.৫ = ২৯০ ft
- Total plinth beam length: **৪৩৫ ft = ১৩২.৬ m**

**T১৬ main bars (top + bottom):**
- ৮ bars (৪ top + ৪ bottom) × ১৩২.৬ = ১,০৬১ m
- ওজন: ১,০৬১ × ১.৫৮ = **১,৬৭৬ kg**

**T১০ stirrups:**
- Stirrup per ft: ২ (with ৬" spacing)
- প্রতি stirrup = ৩ ft (৮"+১০"+২×৫" hook)
- মোট: ৪৩৫ × ২ × ৩ = ২,৬১০ ft = ৭৯৫ m
- ওজন: ৭৯৫ × ০.৬১৭ = **৪৯০ kg**

### D. ছাদ বিম (Roof Beams) — same as plinth + cantilever

Same as plinth beam quantities:
- T১৬ main: **১,৬৭৬ kg** + cantilever extra ৫০ kg = **১,৭২৬ kg**
- T১০ stirrups: **৪৯০ kg** + cantilever extra ২০ kg = **৫১০ kg**

### E. ছাদ স্ল্যাব (Roof Slab)

৩৬.৫ × ৩৬ = ১,৩১৪ sqft, ৫" thick, T১০ @ ৫" both ways nicher + supports এর কাছে T১০ @ ৫" top।

| Item | হিসাব | ওজন |
|---|---|---:|
| Bottom main T১০ | ১৩১৪ sqft × ২.৪ ft/sqft = ৩,১৫৪ ft | ৫৯২ kg |
| Bottom distribution T১০ | ১৩১৪ sqft × ২.৪ = ৩,১৫৪ ft | ৫৯২ kg |
| Top supports T১০ | ৪০% area = ৫২৬ × ২.৪ = ১,২৬২ ft | ২৩৭ kg |
| **মোট স্ল্যাব** | | **১,৪২১ kg** |

### F. ক্যান্টিলিভার ভেরান্ডা slab

১৫ × ৬ = ৯০ sqft। Top reinforcement T১০ @ ৪", bottom T৮ @ ৬"।

- Top T১০: ৯০ × ৩ = ২৭০ ft = ৮২ m → ৫১ kg
- Bottom T৮: ৯০ × ২ = ১৮০ ft = ৫৫ m → ২২ kg
- **মোট ভেরান্ডা: T১০ ৫১ kg + T৮ ২২ kg**

---

## ৩. সারমর্ম (Summary Total)

| ডায়া | পরিমাণ (kg) | ১০% wastage সহ | বার বান্ডিল (12m bars) |
|---|---:|---:|---:|
| T৮ (8mm) | ২২ | ২৫ | ৫-৬ টি |
| T১০ (10mm) | ৩,৩১৫ | ৩,৬৪৭ | ৫০০ টি |
| T১২ (12mm) | ৭৮৮ | ৮৬৭ | ৮২ টি |
| T১৬ (16mm) | ৪,১৪১ | ৪,৫৫৫ | ২৪০ টি |
| **মোট** | **৮,২৬৬ kg** | **৯,০৯৪ kg** | **৮২৭ bundle** |

⚠️ **৯,১০০ kg ≈ ৯.১ টন রড অর্ডার করতে হবে।**

### আনুমানিক খরচ (Cost @ ৯০-১০০ টাকা/kg)

৯,১০০ × ৯৫ = **৮,৬৪,৫০০ টাকা** (delivery + cutting/bending charge সহ)

---

## ৪. অর্ডার দেওয়ার পদ্ধতি

### পর্যায় ১ (ভিত্তির কাজ শুরুর আগে)
| অর্ডার | পরিমাণ |
|---|---:|
| T১২ × ১২m | ৮২ bundle (৮৬৭ kg) |
| T১৬ × ১২m | ১৫ bundle (২৮৫ kg) — শুধু starter bars এর জন্য |
| T১০ × ১২m | ৫০ bundle (৩৬৪ kg) — column ties এর জন্য |

### পর্যায় ২ (প্লিন্থ বিম + কলাম এর জন্য)
| অর্ডার | পরিমাণ |
|---|---:|
| T১৬ × ১২m | ১৩৪ bundle (২,৫৪০ kg) |
| T১০ × ১২m | ১৪০ bundle (১,০২২ kg) |

### পর্যায় ৩ (ছাদ বিম + স্ল্যাবের জন্য)
| অর্ডার | পরিমাণ |
|---|---:|
| T১৬ × ১২m | ৯১ bundle (১,৭৩০ kg) |
| T১০ × ১২m | ৩১০ bundle (২,২৬১ kg) |
| T৮ × ১২m | ৬ bundle (২৫ kg) |

---

## ৫. সাইটে রডের সংরক্ষণ

- ⛏️ **মাটির উপরে** রড রাখবেন না — কাঠ বা ইট দিয়ে ১২" উপরে রাখুন
- ☔ **পানি লাগানো যাবে না** — Tarpaulin দিয়ে ঢেকে রাখুন
- 🛡️ **মরিচা থেকে রক্ষা** — মাসে ১বার চেক, মরিচা ধরলে wire brush
- 📏 **size অনুসারে আলাদা bundle** — সাইটে confusion এড়াতে
- 🚨 **প্রতি delivery তে weigh + tag** — supplier কে invoice signed
- ⚠️ **৩ মাসের বেশি রাখবেন না** outdoors — ব্যবহার করে ফেলুন

---

## ৬. কাটা ও বাঁকানোর নিয়ম (Cutting & Bending Rules)

### কাটার মেশিন
- Manual cutter বা hydraulic cutter
- ⚠️ Gas cutting / welding ব্যবহার করা যাবে না (heat strength নষ্ট করে)

### বাঁকানোর মেশিন
- Mechanical bar bender (recommended)
- যদি manual: বার বেন্ডার pipe + foot pedal
- ⚠️ Hammer দিয়ে বাঁকানো যাবে না

### Mandrel size (বাঁকানোর কেন্দ্রের ব্যাস)

| রড ডায়া | Mandrel ⌀ |
|---|---:|
| T৮ - T১২ | ৪d |
| T১৬ | ৫d |
| T২০ | ৬d |
| T২৫+ | ৮d |

### Bending sequence

1. Cut → 2. Mark hook position → 3. Bend in one motion → 4. Check angle (90° / 135°)
5. Tag with structure ID (e.g. "F-1 footing-1 bottom mat")
6. Stack by structure for easy installation

---

## ৭. Quality Control Checklist

প্রতি pour এর আগে এই list চেক করতে হবে:

### ভিত্তি (Footing)
- [ ] Bottom mat T১২ @ ৫" দুই দিকে (৭ + ৭ = ১৪ bars দেখা যাবে)
- [ ] ২" cover (চারদিকে ও নিচে) — চক বা বিস্কুট দিয়ে maintain
- [ ] Hook ৯০°, ৬" foot
- [ ] Lap (যদি থাকে) ৪০d
- [ ] Tie wire সব intersection-এ
- [ ] কোনো মরিচা নাই

### কলাম (Column)
- [ ] ৬টা T১৬ ঠিকমতো plumb (পল্যাম্বব দিয়ে check)
- [ ] T১০ rings @ ৬" সাধারণ, @ ৩" জয়েন্টে
- [ ] ১৩৫° hook সঠিক
- [ ] ১.৫" cover (চারদিকে)
- [ ] Lap ৪০d = ২'-১"
- [ ] স্টার্টার rods ছাদের উপরে ৪'-০"

### বিম-স্ল্যাব (Beam-Slab)
- [ ] বিম উপরে ৪-T১৬, নিচে ৪-T১৬
- [ ] Stirrup T১০ @ ৬" / @ ৩" সাপোর্টে
- [ ] স্ল্যাব main T১০ @ ৫" নিচে
- [ ] স্ল্যাব distribution T১০ @ ৫" নিচে (perpendicular)
- [ ] স্ল্যাব top supports T১০ @ ৫" (L/৪ পর্যন্ত)
- [ ] Cover: বিম ১", স্ল্যাব ৩/৪" (চক বা PVC chair)
- [ ] কোনো welding নাই (overlap by binding wire)

⚠️ **এই checklist শেষ না হলে concrete order করবেন না।**

---

## ৮. ইঞ্জিনিয়ার approval

প্রতিটি pour এর আগে ইঞ্জিনিয়ার সাহেব এসে rebar দেখে written approval দেবেন। Approval slip-এ লিখা থাকবে:

```
স্ট্রাকচার: ____________
তারিখ: ____________
ইঞ্জিনিয়ারের স্বাক্ষর: ____________
মন্তব্য: ____________
ঢালাই অনুমতি: ✅ হ্যাঁ / ❌ না
```

এই slip ছাড়া concrete mixer চালু করা যাবে না।

---

**যোগাযোগ:**
- রড supplier: ____________________
- Bar bender: ____________________
- Structural Engineer: ____________________
