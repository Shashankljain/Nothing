[[IMNCI]]
# IMNCI Assessment & Management of Acute Diarrhea [⭐ High-Yield]

### 1. Definition [⭐ High-Yield]

- **Acute Diarrhea**: Passage of **3 or more loose or watery stools per day** (or more frequent than normal for an infant) lasting **<14 days**.
- **IMNCI Clinical Framework**: The Integrated Management of Neonatal and Childhood Illness (**IMNCI**) protocol evaluates every child presenting with diarrhea through a three-step action plan: **Assess → Classify → Treat**.
- **Diarrhea Subtypes under IMNCI**:
    1. **Acute Watery Diarrhea**: Lasts **<14 days**; main danger is acute dehydration and weight loss.
    2. **Dysentery**: Diarrhea with **visible blood in stool**; main danger is intestinal mucosal damage, sepsis, and malnutrition.
    3. **Persistent Diarrhea**: Lasts **≥14 days**; main danger is severe malnutrition and non-intestinal infections.

---

### 2. Etiology / Causes / Risk Factors

- **Viral Etiology**: **Rotavirus** (most common overall cause in children <5 years), Norovirus, Adenovirus, Astrovirus.
- **Bacterial Etiology**:
    - _Watery Diarrhea_: **Enterotoxigenic _E. coli_ (ETEC)**, _Vibrio cholerae_.
    - _Dysentery_: _**Shigella flexneri**_ (most common cause of dysentery), Enteroinvasive _E. coli_ (EIEC), _Campylobacter jejuni_, _Salmonella enteritidis_.
- **Protozoal Etiology**: _Giardia lamblia_, _Entamoeba histolytica_, _Cryptosporidium parvum_.
- **Risk Factors**: Lack of exclusive breastfeeding, unhygienic complementary feeding, contaminated water supply, lack of handwashing, severe malnutrition, and incomplete rotavirus immunization.

---

### 3. Classification / IMNCI Triage Categories [⭐ High-Yield]

IMNCI classifies dehydration into three color-coded action categories based on four key clinical signs (**Mental Status**, **Eyes**, **Thirst / Drinking capability**, **Skin Pinch Test**):

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[Child Presenting with Acute Diarrhea]:::primary --> B[Assess 4 Clinical Signs: Mental Status, Eyes, Thirst, Skin Pinch]:::warning
B --> C{Presence of 2 or More Key Signs?}:::warning
C -->|Lethargic/Unconscious + Sunken Eyes + Unable to Drink + Very Slow Pinch >2s| D[PINK: Severe Dehydration]:::danger
C -->|Irritable/Restless + Sunken Eyes + Drinks Eagerly/Thirsty + Slow Pinch ≤2s| E[YELLOW: Some Dehydration]:::warning
C -->|Not Enough Signs to Classify as Some/Severe| F[GREEN: No Dehydration]:::success
D --> G[Plan C: Immediate IV Ringer Lactate 100 mL/kg + Urgent Hospital Referral]:::danger
E --> H[Plan B: Low-Osmolarity ORS 75 mL/kg over 4 Hours at Facility]:::warning
F --> I[Plan A: Home Care - Extra Fluids + ORS + Zinc 14 Days + Continued Feeding]:::success
```

---

### 4. Pathophysiology [⭐ High-Yield]

- **Osmotic / Secretory Fluid Loss**: Pathogens release enterotoxins (e.g., _V. cholerae_, ETEC) or damage villous brush border microvilli (Rotavirus), causing massive secretion of sodium and water into the intestinal lumen.
- **Extracellular Fluid (ECF) Depletion**: Rapid fluid and electrolyte loss leads to **hypovolemia**, metabolic acidosis (loss of bicarbonate in stool), and hypokalemia.
- **Microvascular Perfusion Failure**: Progressive loss of **>10% body weight** impairs systemic perfusion, producing hypovolemic shock, prerenal acute kidney injury, and end-organ hypoxia.

---

### 5. Clinical Features & IMNCI Assessment Matrix [⭐ High-Yield]

#### A. Clinical Signs (Look, Feel, Decide)

- **Mental Status**: Lethargic/unconscious (severe) vs. restless/irritable (some) vs. well/alert (no dehydration).
- **Eyes**: Very sunken and dry (severe) vs. sunken (some) vs. normal (no dehydration).
- **Thirst / Drinking**: Unable to drink or drinking poorly (severe) vs. drinking eagerly/thirsty (some) vs. drinks normally (no dehydration).
- **Skin Pinch Test**:
    - Pinched skin on abdomen fold (midway between umbilicus and lateral flank) goes back **very slowly (>2 seconds)** in severe dehydration.
    - Goes back **slowly (≤2 seconds)** in some dehydration.
    - Goes back **immediately (<1 second)** in no dehydration.

#### B. Diagnostic Assessment Table

|Feature / Sign|**PINK: Severe Dehydration**|**YELLOW: Some Dehydration**|**GREEN: No Dehydration**|
|:--|:--|:--|:--|
|**Required Criteria**|**Two or more** of the following signs:|**Two or more** of the following signs:|Not enough signs to classify as some or severe dehydration|
|**Mental Status**|Lethargic or unconscious|Restless, irritable|Well, alert|
|**Eyes**|Sunken|Sunken|Normal|
|**Drinking Ability**|Unable to drink or drinks poorly|Drinks eagerly, thirsty|Drinks normally, not thirsty|
|**Skin Pinch Test**|Goes back **very slowly (>2 seconds)**|Goes back **slowly (≤2 seconds)**|Goes back **immediately (<1 second)**|
|**IMNCI Action Plan**|**PLAN C**: Emergency IV Fluids (**100 mL/kg**)|**PLAN B**: Facility ORS (**75 mL/kg over 4 hours**)|**PLAN A**: Home Care (Extra fluids + Zinc)|

---

### 6. Diagnosis / Investigations

- **Clinical Assessment**: Diagnosis under IMNCI is **strictly clinical** and action-oriented to prevent delay.
- **Stool Examination**:
    - Routine stool routine/microscopy is **not required** for acute watery diarrhea.
    - Indicated in **Dysentery** (presence of RBCs and pus cells) or persistent diarrhea.
- **Serum Electrolytes & RFT**: Reserved for severe dehydration requiring Plan C or cases with suspected hypernatremia, severe hypokalemia, or oliguria.

---

### 7. Differential Diagnosis

|Feature|**Acute Watery Diarrhea**|**Dysentery**|**Persistent Diarrhea**|
|:--|:--|:--|:--|
|**Duration**|**<14 days**|**<14 days**|**≥14 days**|
|**Stool Character**|Watery, loose without blood|Contains **visible blood and mucus**|Variable, loose, foul-smelling|
|**Primary Etiology**|Rotavirus, ETEC|_**Shigella flexneri**_, EIEC, _E. histolytica_|Post-enteritis lactose intolerance, SAM|
|**Primary Danger**|Acute dehydration & hypovolemia|Intestinal perforation, sepsis, toxic megacolon|Malnutrition, micronutrient deficiency|
|**Antibiotic Role**|**None** (except Cholera)|**Routine** (Oral Ciprofloxacin 3 days)|Specific to isolated pathogen|

---

### 8. Treatment / Management [⭐ High-Yield]

#### A. PLAN A: Home Management (No Dehydration)

Designed to treat diarrhea at home, prevent dehydration, and prevent malnutrition:

1. **Rule 1: Give Extra Fluid**:
    - Give **WHO Low-Osmolarity ORS** or home-made fluids (salted rice water, soups, green coconut water).
    - **ORS Quantity After Each Loose Stool**:
        - **<2 years**: **50–100 mL**
        - **2–10 years**: **100–200 mL**
        - **>10 years**: As much as wanted (**Ad libitum**)
2. **Rule 2: Give Zinc Supplementation for 14 Days**:
    - Accelerates mucosal recovery and reduces recurrence over the next 2–3 months.
3. **Rule 3: Continue Feeding**:
    - Continue frequent breastfeeding or age-appropriate energy-dense home foods; do not restrict food.
4. **Rule 4: Counsel on When to Return Immediately**:
    - Return if child develops: unable to drink/breastfeed, drinking poorly, fever, blood in stool, or condition worsens.

#### B. PLAN B: Facility Treatment with ORS (Some Dehydration)

- **Fluid Quantity**: Give **75 mL/kg** of Low-Osmolarity ORS over **4 hours** at the primary health center.
- **Alternative Age-Based ORS Guide (if weight unknown)**:
    - **<4 months (<5 kg)**: **200–400 mL**
    - **4–11 months (5–7.9 kg)**: **400–700 mL**
    - **12–23 months (8–10.9 kg)**: **700–900 mL**
    - **2–4 years (11–15.9 kg)**: **900–1400 mL**
    - **5–14 years (16–29.9 kg)**: **1400–2200 mL**
- Reassess after 4 hours:
    - If no dehydration → Switch to **Plan A**.
    - If still some dehydration → Repeat **Plan B** for 4 hours.
    - If severe dehydration → Switch to **Plan C**.

#### C. PLAN C: Emergency IV Rehydration (Severe Dehydration) [⭐ High-Yield]

- **Indication**: Severe dehydration (Pink classification) or inability to drink.
- **Fluid Choice**: **Ringer's Lactate (RL)** (preferred) or **0.9% Normal Saline (NS)**.
- **Total Dose**: **100 mL/kg** IV divided into two consecutive phases:

|Age Group|First Phase: **30 mL/kg**|Second Phase: **70 mL/kg**|Total Duration|
|:--|:--|:--|:--|
|**Infants (<1 year)**|Give over **1 hour**|Give over **5 hours**|**6 hours**|
|**Children (≥1 year)**|Give over **30 minutes**|Give over **2.5 hours**|**3 hours**|

- Reassess every 15–30 minutes until strong radial pulse returns.
- Give ORS orally (**5 mL/kg/hour**) as soon as the child can drink while IV infusion continues.

#### D. Pharmacological Treatment & Dosage Rule Table [⭐ High-Yield]

|Drug|Dose|Route|Frequency|Duration|Key Indications / Features|
|:--|:--|:--|:--|:--|:--|
|**Zinc Sulfate**|**10 mg/day** (<6 months)**20 mg/day** (>6 months)|Oral|Once daily|**14 days**|Promotes GI re-epithelialization; mandatory for all acute diarrhea cases.|
|**Low-Osmolarity ORS**|**245 mOsm/L** (Na⁺ 75, Glucose 75, K⁺ 20, Cl⁻ 65, Citrate 10 mEq/L)|Oral|As per Plan A/B|During diarrhea|Optimizes **SGLT-1** co-transport of sodium and water in enterocytes.|
|**Ciprofloxacin**|**15 mg/kg/dose**|Oral|Twice daily|**3 days**|**First-line for Dysentery** (blood in stool).|
|**Ondansetron**|**0.15 mg/kg**|Oral|Single dose|Single dose|Anti-emetic used if intractable vomiting prevents oral rehydration.|

---

### 9. Complications

- **Hypovolemic Shock & Death**.
- **Prerenal Acute Kidney Injury (AKI)** secondary to tubular hypoperfusion.
- **Electrolyte Imbalances**: Severe hypokalemia (paralytic ileus, weakness) and hypernatremic / hyponatremic dehydration.
- **Secondary Lactose Intolerance** and persistent diarrhea.

---

### 10. Prognosis

- **Excellent (>99% survival)** when low-osmolarity ORS and Zinc are initiated early under Plan A or B.
- High mortality if severe dehydration (Plan C) is unrecognized, leading to cardiac arrest from hypovolemic shock.

---

### 11. Mnemonic / Memory Palace

#### Mnemonic: S-U-N-K

- **S** - **Skin pinch test**: Goes back **>2 seconds** in severe dehydration
- **U** - **Unable to drink / Unconscious**: Critical signs of **PINK (Severe)** classification
- **N** - **No antibiotics for watery diarrhea**: Reserved strictly for **Dysentery** (blood in stool) or Cholera
- **K** - **KCl & Zinc 14 Days**: Essential micronutrient and electrolyte replacement

---

### Clinical Pearl

> **Zinc supplementation for 14 days is non-negotiable in childhood diarrhea.** Even if diarrhea stops within 2–3 days, continuing Zinc for the full 14 days reduces the duration and severity of the current episode and prevents future diarrhea episodes for up to 3 months.

---

### Exam Trap

- **The Mix-up**: Confusing the IV rehydration timelines for infants vs. older children under **Plan C**.
- **Distinguishing Fact**: Under Plan C, infants (**<1 year**) take **6 hours total** (30 mL/kg in 1 hour + 70 mL/kg in 5 hours). Older children (**≥1 year**) take **3 hours total** (30 mL/kg in 30 min + 70 mL/kg in 2.5 hours).

---

### Diagram 1: Skin Pinch Test & Dehydration Assessment Guide

- **Type**: Labeled instructional clinical diagram.
- **Outline shape to draw**: Abdominal wall fold held between thumb and index finger.
- **Labels in order**:
    1. **Anatomical Site**: Abdomen wall, halfway between umbilicus and lateral border.
    2. **Technique**: Pinch skin and subcutaneous tissue vertically for 1 second, then release.
    3. **Interpretation 1 (Very Slow)**: Takes **>2 seconds** → **Pink (Severe Dehydration)**.
    4. **Interpretation 2 (Slow)**: Takes **≤2 seconds** → **Yellow (Some Dehydration)**.
    5. **Interpretation 3 (Immediate)**: Takes **<1 second** → **Green (No Dehydration)**.
- **Arrows/connections**: Pinch Skin → Release → Observe Rebound Time → Classify into Pink / Yellow / Green.
- **Extra Mark Annotation**: Skin pinch test is unreliable in children with **Severe Acute Malnutrition (SAM)** due to loss of subcutaneous fat.

---

### Quick Revision

- **Classification Categories**: **Severe Dehydration** (Pink), **Some Dehydration** (Yellow), **No Dehydration** (Green).
- **Plan A (No Dehydration)**: Extra fluids + ORS + **Zinc (10–20 mg/day for 14 days)** + continued feeding.
- **Plan B (Some Dehydration)**: Low-osmolarity ORS **75 mL/kg over 4 hours** at facility.
- **Plan C (Severe Dehydration)**: **RL / NS 100 mL/kg IV** (Infants: 1h + 5h = 6h; Children ≥1y: 30m + 2.5h = 3h).
- **Dysentery**: Diarrhea + visible blood → Oral Ciprofloxacin for 3 days.

---

### One-Line Exam Opener

- **The IMNCI strategy for acute diarrhea systematically triages children into Severe, Some, or No Dehydration using four standardized clinical signs to deliver targeted Plan C (IV fluids), Plan B (facility ORS), or Plan A (home care with Zinc and ORS) therapy.**