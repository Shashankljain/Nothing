[[C16-Cardiology]]
# Acute Pulmonary Edema

## 1. Definition [⭐ High-Yield]

**Acute Pulmonary Edema** is a life-threatening medical emergency characterized by the rapid, abnormal accumulation of transudative or exudative fluid within the pulmonary interstitial spaces and alveoli. This fluid inundation severely impairs alveolar gas exchange, leading to acute respiratory failure, profound hypoxemia, and cellular hypoxia.

---

## 2. Etiology / Causes / Risk Factors

1. **Cardiogenic Causes (Increased Capillary Hydrostatic Pressure >20–25 mmHg):**
    
    - **Acute Myocardial Infarction / Severe Myocardial Ischemia:** Sudden left ventricular systolic failure and myocardial stunning.
    - **Acute Decompensated Heart Failure:** Exacerbation of pre-existing dilated or ischemic cardiomyopathy.
    - **Acute Valvular Incompetence:** Ruptured chordae tendineae causing acute mitral regurgitation, or acute aortic regurgitation.
    - **Severe Systemic Hypertension:** Hypertensive crisis / accelerated hypertension with increased left ventricular afterload.
    - **Severe Tachyarrhythmias or Bradyarrhythmias:** Loss of diastolic filling time or loss of atrial kick.
2. **Non-Cardiogenic Causes (Increased Permeability / ARDS / Other):**
    
    - **Acute Respiratory Distress Syndrome (ARDS):** Sepsis, severe acute pancreatitis, major trauma, blood transfusion (TRALI).
    - **Fluid Overload:** Acute Kidney Injury (AKI) or Chronic Kidney Disease with excessive IV fluid administration relative to renal output.
    - **Neurogenic:** Severe central nervous system trauma, intracerebral hemorrhage, or status epilepticus.
    - **Drug-Induced / Toxins:** Opioid overdose (heroin, morphine), aspirin toxicity, hydrochlorothiazide, or smoke inhalation.
    - **High Altitude Pulmonary Edema (HAPE):** Rapid ascent above 2500 meters triggering severe hypoxic pulmonary vasoconstriction.

---

## 3. Pathophysiology (with Flowchart) [⭐ High-Yield]

### Pathogenetic Sequence

1. **Primary Insult:** Acute left ventricular dysfunction raises left ventricular end-diastolic pressure (LVEDP), transmitting high backward pressure to the left atrium and pulmonary veins.
2. **Hydrostatic Transudation:** When pulmonary capillary hydrostatic pressure exceeds plasma oncotic pressure (typically >20–25 mmHg), fluid is forced across the capillary endothelium into the lung interstitium (interstitial edema).
3. **Alveolar Inundation:** As interstitial capacity is overwhelmed, fluid ruptures through alveolar epithelial junctions into the airspaces.
4. **Surfactant Inactivation & Shunting:** The fluid dilutes surfactant, causing alveolar collapse, extensive ventilation-perfusion (V/Q) mismatch, right-to-left intrapulmonary shunting, severe arterial hypoxemia, and acute respiratory acidosis.

### Pathophysiology Flowchart

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px

A[Acute LV Dysfunction / Severe Hypertension / ARDS]:::primary --> B[Elevated Pulmonary Capillary Hydrostatic Pressure >25 mmHg]:::primary
B --> C[Extravasation of Fluid into Interstitium → Interstitial Edema]:::warning
C --> D[Alveolar Inundation with Proteinaceous Fluid & Surfactant Inactivation]:::danger

D --> E[Alveolar Collapse, Severe V/Q Mismatch & Intrapulmonary Shunting]:::danger
E --> F[Acute Severe Hypoxemia PaO₂ <60 mmHg & Air Hunger]:::danger

F -->|LMNOP Protocol: Oxygen + CPAP + GTN + Furosemide| G[Reduction of Preload & Capillary Hydraulic Gradient]:::success
G --> H[Resorption of Alveolar Fluid & Restoration of Gas Exchange]:::success
```

---

## 4. Clinical Features

- **Symptoms:**
    
    - Sudden, excruciating, rapidly worsening breathlessness (air hunger) occurring at rest.
    - Marked anxiety, extreme agitation, restlessness, and fear of impending death.
    - Cough producing profuse, frothy, pink or blood-streaked sputum.
    - Inability to lie flat (severe orthopnea).
- **Physical Signs:**
    
    - **General Appearance:** Patient sits bolt upright, pale, sweaty, clammy, with central cyanosis.
    - **Respiratory System:** Tachypnea (>30 breaths/min), recruitment of accessory respiratory muscles, extensive fine inspiratory crepitations/crackles audible throughout both lung fields, and diffuse wheeze ("cardiac asthma").
    - **Cardiovascular System:** Tachycardia, elevated Jugular Venous Pressure (JVP), **Third Heart Sound (S₃ gallop)**, and hypertension (or hypotension/shock in cardiogenic failure).

---

## 5. Diagnosis / Baseline Investigations

1. **Arterial Blood Gas (ABG):** Severe arterial hypoxemia (PaO₂ <60 mmHg / 8 kPa). Initially shows hyperventilation with respiratory alkalosis, progressing to severe hypercapnia (PaCO₂ >45 mmHg) and combined metabolic/respiratory acidosis in extremis.
2. **Chest X-Ray [⭐ High-Yield]:**
    - Prominence of upper lobe blood vessels (upper lobe diversion).
    - Enlarged hilar shadow ("bat-wing" or "butterfly" distribution of alveolar edema).
    - **Kerley B lines** (horizontal septal lines at the lung bases reflecting interstitial fluid accumulation).
    - Cardiomegaly (dilated cardiac silhouette in underlying chronic heart failure).
3. **12-Lead ECG:** Evaluates for underlying acute myocardial infarction, ischemic ST-T changes, left ventricular hypertrophy, or tachyarrhythmias.
4. **Echocardiography:** Gold-standard bedside test to assess left ventricular ejection fraction (LVEF), regional wall motion abnormalities, and acute valvular dysfunction.
5. **Serum Biomarkers:** B-type Natriuretic Peptide (BNP >400 pg/mL or NT-proBNP >450–900 pg/mL) confirms cardiogenic etiology.

---

## 6. Treatment / Management [⭐ High-Yield]

Acute pulmonary edema is a critical medical emergency requiring immediate, step-wise resuscitative measures and targeted pharmacotherapy.

```
                     ┌──────────────────────────────────────────────┐
                     │   MANAGEMENT OF ACUTE PULMONARY EDEMA        │
                     └──────────────────────┬───────────────────────┘
                                            │
               ┌────────────────────────────┴────────────────────────────┐
               ▼                                                         ▼
┌──────────────────────────────┐                          ┌──────────────────────────────┐
│  A. RESUSCITATIVE & NON-     │                          │   B. PARANTERAL              │
│     PHARMACOLOGICAL (LMNOP)  │                          │      PHARMACOTHERAPY         │
│ • Sit Patient Upright (90°)  │                          │ • IV Nitrates (GTN Infusion) │
│ • High-Flow Oxygen (100%)    │                          │ • IV Loop Diuretic           │
│ • Non-Invasive Ventilation   │                          │   (Furosemide)               │
│   (CPAP 5–10 cmH₂O)          │                          │ • IV Morphine (Sparingly)    │
└──────────────────────────────┘                          └──────────────┬───────────────┘
                                                                         │
                                                                         ▼
                                                          ┌──────────────────────────────┐
                                                          │   C. INOTROPIC / MECHANICAL  │
                                                          │ • IV Dobutamine (If Shocked) │
                                                          │ • Intra-Aortic Balloon Pump │
                                                          └──────────────────────────────┘
```

---

### A. Immediate First-Line Resuscitative Measures (LMNOP Protocol)

1. **Positioning (Upright Posture):**
    - **Sit the patient completely upright (90° angle)** with legs dangling over the side of the bed.
    - _Mechanism:_ Decreases venous return (preload) to the heart and reduces pulmonary capillary hydraulic pressure.
2. **High-Flow Oxygen Therapy:**
    - Administer high-flow 100% oxygen via a tight-fitting mask with a rebreather reservoir bag to achieve a target saturation of **94–98%**.
3. **Continuous Positive Airway Pressure (CPAP / NIV):**
    - Apply CPAP at **5 to 10 cmH₂O (mmHg)** via a tight-fitting facial mask.
    - _Mechanism:_ Recruits collapsed alveoli, enhances clearance of alveolar fluid into lymphatics, reduces the pulmonary capillary hydraulic gradient, and decreases the work of breathing.

---

### B. Pharmacotherapy & Dosage Rules [⭐ High-Yield]

#### 1. Glyceryl Trinitrate (GTN / Nitrates) [⭐ High-Yield]

- **Mechanism of Action:** (KDT Textbook p. 586, 619; Davidson p. 525). Nitrates are converted in vascular smooth muscle cells to release **Nitric Oxide (NO)** → activates soluble guanylyl cyclase → increases intracellular cGMP → produces potent relaxation of venous capacitance vessels (venodilation) and systemic arterioles. Venodilation pooling reduces central venous return (preload) and left ventricular end-diastolic volume, while arteriolar dilation reduces afterload.
    
    ```
    GTN → Releases Nitric Oxide (NO) → ↑ cGMP in Vascular Smooth Muscle → Venodilation → Preload ↓ & Capillary Pressure ↓
    ```
    
- **Dose:**
    - **IV Infusion:** **10 to 200 μg/min** continuous infusion, titrated upward by 10 μg/min every 5–10 minutes according to clinical response and blood pressure.
    - **Buccal / Sublingual:** **2 to 5 mg** buccal GTN or sublingual spray (400 μg per spray) as an immediate initial measure.
- **Dosage / Route:** Intravenous infusion or buccal/sublingual.
- **Frequency:** Continuous IV infusion.
- **Features:** Primary fast-acting drug of choice in acute hypertensive/cardiogenic pulmonary edema; rapidly lowers pulmonary capillary hydraulic gradient.
- **Side Effects:** Severe throbbing headache, flushing, symptomatic hypotension, reflex tachycardia, pharmacological tolerance (>12–24 hours).
- **When to Start / Stop:** Start immediately if **Systolic BP is ≥110 mmHg**. **Stop or titrate downward if SBP drops below 90–100 mmHg**.

#### 2. Furosemide (High-Ceiling Loop Diuretic) [⭐ High-Yield]

- **Mechanism of Action:** (KDT Textbook p. 563, 630; Davidson p. 525). Inhibits the Na⁺/K⁺/2Cl⁻ cotransporter in the thick ascending Limb of Henle. Intravenous furosemide produces a **biphasic response**: (a) _Immediate Venodilator Action (Pre-diuretic):_ Increases systemic venous capacitance within 5–15 minutes, promptly reducing right atrial and pulmonary capillary wedge pressures. (b) _Diuretic Action:_ Induces rapid diuresis, reducing total circulating blood plasma volume and combating systemic volume overload.
- **Dose:** **40 to 80 mg IV** (or 50–100 mg IV) as a slow bolus over 2 minutes.
- **Dosage / Route:** Intravenous slow injection.
- **Frequency:** Single stat dose; can be repeated or given as a continuous infusion (5–10 mg/hr) if diuresis is inadequate.
- **Features:** Combats systemic fluid overload; rapid onset of symptomatic relief.
- **Side Effects:** Hypokalemia, hyponatremia, hypovolemia, prerenal azotemia, ototoxicity (if high IV bolus rates used).
- **When to Start / Stop:** Start immediately in volume-overloaded acute left ventricular failure. Avoid in severely hypovolemic patients.

#### 3. Morphine Sulphate (Opioid Analgesic - Selective Use)

- **Mechanism of Action:** (KDT Textbook p. 506; Davidson p. 525). Binds to central and peripheral μ-opioid receptors: (a) Induces peripheral venodilation, pooling blood in systemic capacitance vessels and reducing cardiac preload. (b) Depresses the medullary respiratory center, allaying severe dyspnea and "air hunger". (c) Suppresses sympathetic discharge, calming patient anxiety and reducing myocardial oxygen demand.
- **Dose:** **2.5 to 5.0 mg IV** slow injection.
- **Dosage / Route:** Intravenous slow injection.
- **Frequency:** Single stat dose, repeated sparingly as necessary.
- **Features:** Dramatically relieves extreme patient distress, panic, and pain.
- **Side Effects:** Respiratory depression, CO₂ retention, severe hypotension, nausea, vomiting, bradycardia.
- **When to Start / Stop:** Use sparingly in highly distressed or anxious patients with stable blood pressure. **Contraindicated** in severe hypotension, hypercapnic respiratory failure, or COPD overlap.

#### 4. Inotropic Support (In Cardiogenic Shock Cases)

- **Dobutamine (2.5 to 10 μg/kg/min IV infusion):** Indicated when acute pulmonary edema is complicated by cardiogenic shock and severe hypotension (Systolic BP <90 mmHg) to augment cardiac output.

---

## 7. Complications

1. **Acute Type I or Type II Respiratory Failure:** Requiring urgent endotracheal intubation and mechanical ventilation.
2. **Cardiogenic Shock:** Severe systemic hypoperfusion due to primary pump failure.
3. **Severe Mixed Metabolic and Respiratory Acidosis:** Leading to fatal ventricular arrhythmias.
4. **Cardiorenal Syndrome / Acute Kidney Injury (AKI):** Secondary to low cardiac output and high renal venous congestion.
5. **Cardiogenic Cardiac Arrest:** Secondary to fatal ventricular fibrillation or pulseless electrical activity.

---

## 8. Diagram Guide

### Diagram : Mechanism of Alveolar Fluid Accumulation in Cardiogenic Pulmonary Edema

_(Reference in text: See Section 3 - Pathophysiology)_

- **Type:** Labeled Micro-Anatomical Diagram.
- **Outline Shape to Draw:** Dual alveoli alongside a pulmonary capillary bed.
- **Labels in Order:**
    1. **Pulmonary Capillary Bed:** Showing elevated hydrostatic pressure (>25 mmHg).
    2. **Endothelial-Epithelial Barrier:** Interstitial swelling and fluid transudation.
    3. **Alveolar Space:** Filled with proteinaceous fluid, sloughed debris, and diluted surfactant layer.
    4. **CPAP / PEEP Vector:** Inward airway pressure arrow resisting fluid transudation.
- **Extra Mark Annotation:** _"CPAP exerts a positive end-expiratory pressure (5–10 cmH₂O) that mechanically opposes hydrostatic fluid transudation across the alveolar-capillary membrane."_.

---

## 9. Mnemonic / Memory Palace

### Mnemonic for Emergency Management: "L M N O P"

- **L** — **L**asix (Furosemide IV 40–80 mg)
- **M** — **M**orphine Sulphate (IV 2.5–5 mg sparingly)
- **N** — **N**itrates (IV GTN 10–200 μg/min or Buccal GTN 2–5 mg)
- **O** — **O**xygen (High-flow rebreather mask / CPAP 5–10 cmH₂O)
- **P** — **P**ositioning (Sitting upright 90° with legs dangling)

### Memory Palace: "The Flooded Engine Room"

Visualize walking through 4 loci in a flooded engine room:

1. **Loci 1 (The Vertical Chair at the Entrance):** A mechanic sitting in a tall 90° chair with legs hanging down (**Sitting upright to reduce preload**).
2. **Loci 2 (The Pressure Valve Fan):** A high-pressure air mask blowing air to push rising water back out of the pipes (**CPAP ventilation 5–10 cmH₂O**).
3. **Loci 3 (The Red Nitro Tank):** Opening a red Nitric Oxide valve (**IV GTN infusion**) which expands the large drain pipes (**Venodilation**).
4. **Loci 4 (The Blue Lasix Sump Pump):** Switching on a blue high-capacity pump (**IV Furosemide 40–80 mg**) to rapidly pump excess fluid out of the building (**Diuresis**).

---

## 10. Clinical Pearl

> **Clinical Pearl:** Always sit the patient **bolt upright (90°) with legs dangling over the edge of the bed**immediately upon arrival! This simple non-pharmacological maneuver uses gravity to pool blood in the lower extremity capacitance veins, instantly reducing venous return (preload) and lowering pulmonary capillary hydrostatic pressure before any intravenous drug takes effect.

---

## 11. Exam Trap

### Exam Trap

- **The Mix-Up:** Administering **high-dose IV Morphine or Beta-Blockers** to a patient in acute pulmonary edema who is hypotensive, drowsy, or has a history of severe COPD.
- **Distinguishing Fact:** Morphine depresses the medullary respiratory center and can precipitate severe CO₂ retention, obtundation, and respiratory arrest in patients with hypercapnia or hypotension. Beta-blockers possess negative inotropic actions that further collapse left ventricular cardiac output during acute pump failure.
- **Resolution:** Use morphine sparingly **only in highly anxious patients with adequate blood pressure**, and **strictly avoid β-blockers** until the patient is euvolaemic and fully compensated.

---

### Quick Revision

- **Hallmark Definition:** Rapid fluid accumulation in lung alveoli due to pulmonary capillary pressure >20–25 mmHg.
- **Classic Signs:** Severe air hunger, orthopnea, frothy pink sputum, bilateral crepitations, S₃ gallop.
- **Diagnostic Imaging:** Chest X-ray showing upper lobe diversion, Kerley B lines, bat-wing hilar infiltrates, and cardiomegaly.
- **LMNOP Treatment Protocol:** **L**asix (Furosemide IV 40–80 mg), **M**orphine (IV 2.5–5 mg sparingly), **N**itrates (IV GTN infusion), **O**xygen (CPAP 5–10 cmH₂O), **P**ositioning (Sit upright 90°).
- **Nitrates Rule:** Titrate GTN IV infusion (10–200 μg/min); stop if Systolic BP drops below 90–100 mmHg.

---

### One-Line Exam Opener

> **Acute pulmonary edema is a catastrophic medical emergency characterized by the rapid transudation of fluid into the alveolar airspaces secondary to acute left ventricular failure or capillary leak, requiring immediate upright positioning, non-invasive positive pressure ventilation, IV nitrates, and loop diuretics.**

---

🫁 _Would you like to explore the step-by-step management of cardiogenic shock complicating acute pulmonary edema, or review a set of practice clinical case scenarios on acute left ventricular failure?_