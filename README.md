# 🧮 Nutrition Requirement Calculator

A modern, browser-based calculator built with **HTML**, **Tailwind CSS**, and **JavaScript** to estimate daily nutritional requirements for patients.  
The calculator determines **BMI**, **Ideal Body Weight (IBW)**, **caloric and protein needs**, and the **required number of formula scoops or mL per feeding**.

---

## 🚀 Features

✅ Calculates **BMI** and **Ideal Body Weight** automatically  
✅ Adjusts **caloric** and **protein** requirements based on BMI  
✅ Supports multiple **milk/formula types**  
✅ Converts **Novasource Renal** and **Nephro** bottles into **millilitres (mL)**  
✅ Provides both **daily** and **per-feeding** recommendations  
✅ Beautiful, mobile-friendly **Tailwind CSS** interface  
✅ Fully client-side — runs entirely in your browser  

---

## 🧠 How It Works

1. Select **Sex** (Male or Female)  
2. Enter **Height** in centimetres  
3. Enter **Weight** in kilograms  
4. Select the **Milk Formula**  
5. Click **Calculate**

The calculator outputs:
- BMI (Body Mass Index)
- Ideal Body Weight (IBW)
- Daily Calorie & Protein Requirements
- Total scoops or bottles required in 24 hours
- Scoops or mL per 3-hour feed (8 feeds per day)

---

## 🧩 Formula References

### Ideal Body Weight (Devine Formula)
- **Men:** `50 + 2.3 × (height_in - 60)`  
- **Women:** `45.5 + 2.3 × (height_in - 60)`

*(Height in inches = height in cm ÷ 2.54)*

### BMI

### Calorie Requirement
| BMI Range | Formula |
|------------|----------|
| < 30 | Weight × 25 |
| 30–50 | Weight × 14 |
| > 50 | IBW × 25 |

### Protein Requirement
| BMI Range | Formula |
|------------|----------|
| < 30 | Weight × 2 |
| 30–40 | IBW × 2 |
| > 40 | IBW × 2.5 |

---

## 🥛 Milk Formula Reference Table

| Formula | Energy (kcal) | Protein (g) | Unit | Volume (mL) |
|----------|----------------|--------------|------|--------------|
| Enercal | 40 | 1.2 | scoop | — |
| Glucerna | 45 | 2.0 | scoop | — |
| Nutrien Optimum | 36 | 1.2 | scoop | — |
| Ensure | 43 | 1.3 | scoop | — |
| **Novasource Renal** | **474** | **24.57** | **bottle** | **237 mL** |
| **Nephro** | **396** | **17.6** | **bottle** | **220 mL** |
| Peptamen | 25 | — | scoop | — |
| Myotein | 22 | 5 | scoop | — |

🧾 For *Novasource Renal* and *Nephro*, the calculator converts total bottles into **mL/day** and **mL/feed** automatically.

---

## 📊 Example Calculation

**Input:**  
- Male, 75 kg, 160 cm, **Novasource Renal**

**Output:**
BMI: 29.30
IBW: 56.88 kg
Calorie Requirement: 1875 kcal/day
Protein Requirement: 150 g/day

Selected Formula: Novasource Renal (474 kcal/bottle)
→ Total: 3.95 bottles (≈ 937 mL/day)
→ Per Feed (8/day): 117 mL/feed
