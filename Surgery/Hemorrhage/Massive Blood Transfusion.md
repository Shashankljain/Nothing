[[C6 - Hemorrhage and blood transfusion]]
# Massive Blood Transfusion

### Definition [⭐ High-Yield]

**Massive blood transfusion** is defined clinically as meeting any **one** of the following criteria:

1. Transfusion / replacement of the **entire circulating blood volume** (~5 L or 70 mL/kg in a 70-kg adult) within **24 hours**.
2. Administration of **>10 units of packed red blood cells (PRBCs)** or whole blood within **24 hours**.
3. Administration of **>4 units of PRBCs within 1 hour**. _(In pediatric practice, it is defined as loss/replacement of >50% total blood volume in <3 hours, 100% replacement in 24 hours, or >20% loss/replacement in <1 hour)._

---

### Etiology / Causes / Indications [⭐ High-Yield]

Massive blood transfusion is indicated in life-threatening exsanguinating hemorrhage:

- **Major Trauma & Polytrauma**: Massive hemothorax, severe pelvic ring fractures, complex liver/splenic lacerations, and major vascular injuries.
- **Gastrointestinal Hemorrhage**: Ruptured esophageal varices, massive peptic ulcer bleeding, or aortoenteric fistulae.
- **Obstetric Emergencies**: Ruptured ectopic pregnancy, severe postpartum hemorrhage (PPH), placenta accreta spectrum, and placental abruption.
- **Ruptured Aortic Aneurysms**: Ruptured abdominal or thoracic aortic aneurysms (AAA).
- **Major Intraoperative Surgical Hemorrhage**: Cardiac surgery on cardiopulmonary bypass, liver transplantation, or extensive oncological resections.

---

### Pathophysiology [⭐ High-Yield]

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[Exsanguinating Hemorrhage / Massive Blood Loss]:::primary --> B[Activation of Major Hemorrhage Protocol MHP]:::primary
B --> C{Physiological Hazards of Rapid Stored Blood Transfusion}:::warning

C -->|Infusion of Cold Stored Blood 2–6°C| D[Hypothermia <34°C → 10% Drop in Coagulation Factor Activity per 1°C Fall]:::danger
C -->|Citrate Anticoagulant Accumulation| E[Citrate Toxicity → Ca²⁺ & Mg²⁺ Chelation → Severe Hypocalcemia & Metabolic Alkalosis]:::danger
C -->|Efflux from Lysed Stored Red Cells| F[Extracellular Potassium Shift → Marked Hyperkalemia]:::danger
C -->|PRBC & Crystalloid Excess| G[Dilutional Coagulopathy + Acidosis + Hypothermia = Lethal Triad]:::danger

D & E & F & G --> H[Damage Control Resuscitation DCR: Balanced 1:1:1 Ratio + Blood Warming + TXA]:::success
```

- **Vicious Cycle of Coagulopathy**: Massive hemorrhage triggers acute traumatic coagulopathy (ATC). Rapid transfusion of stored PRBCs lacking functional platelets and clotting factors induces dilutional coagulopathy, compounding hypothermia and lactic acidosis to form the **Deadly Triad** (Hypothermia <34 °C, Acidosis pH <7.2, and Coagulopathy).

---

### Complications [⭐ High-Yield]

#### 1. Metabolic & Electrolyte Complications

- **Hypothermia** [⭐ High-Yield]: Infusion of cold stored blood (2–6 °C) drops core body temperature. For each 1 °C fall in temperature, coagulation factor activity decreases by 10%, provoking cardiac dysrhythmias, impaired platelet aggregation, and worsening coagulopathy.
- **Citrate Toxicity (Hypocalcemia & Hypomagnesemia)** [⭐ High-Yield]: Citrate anticoagulant in blood bags chelates ionized serum calcium (Ca²⁺) and magnesium (Mg²⁺). Causes perioral numbness, tingling, carpopedal spasm (Trousseau's sign), facial twitching (Chvostek's sign), myocardial depression, and prolonged QT interval.
- **Metabolic Alkalosis**: Hepatic conversion of transfused citrate into bicarbonate (HCO₃⁻) produces delayed metabolic alkalosis.
- **Hyperkalemia (>> Hypokalemia)** [⭐ High-Yield]: Extracellular leakage of potassium (K⁺) from aging/lysed stored red blood cells during storage elevates serum K⁺ levels, risking lethal cardiac arrest.

#### 2. Hematological & Vascular Complications

- **Dilutional Coagulopathy** [⭐ High-Yield]: **Most common cause of death in massive transfusion/hemorrhagic shock**. Results from excessive PRBC and crystalloid administration without adequate plasma and platelet replacement.
- **Transfusion-Related Acute Lung Injury (TRALI)**: Non-cardiogenic pulmonary edema occurring within 6 hours, mediated by donor anti-HLA antibodies.
- **Transfusion-Associated Circulatory Overload (TACO)**: Hydrostatic volume overload presenting with hypertension, elevated JVP, and cardiogenic pulmonary edema.
- **Hemolytic & Febrile Reactions**: ABO mismatch (intravascular hemolysis) or Febrile Non-Hemolytic Transfusion Reactions (FNHTR, prevented by leukoreduction filters).

---

### Treatment / Management (Major Hemorrhage Protocol) [⭐ High-Yield]

```
                     MAJOR HEMORRHAGE PROTOCOL (MHP)
                                    |
     +------------------------------+------------------------------+
     |                                                             |
Immediate Hemostatic Resuscitation                Balanced Component Therapy (1:1:1)
* Activate Major Hemorrhage Protocol              * Packed Red Blood Cells (PRBC) : 1 Unit
* Administer Tranexamic Acid (TXA) 1 g IV         * Fresh Frozen Plasma (FFP) : 1 Unit
* Use Blood Warmers & Rapid Infusers              * Platelet Concentrate : 1 Unit
* Target Permissive Hypotension (SBP 70–90 mmHg)  * Cryoprecipitate (if Fibrinogen <1.5 g/L)
```

1. **Activation of Major Hemorrhage Protocol (MHP)**: Automatic, coordinated release of pre-matched blood products from the blood bank.
2. **Balanced Component Resuscitation (1:1:1 Ratio)** [⭐ High-Yield]: Transfuse **PRBCs, Fresh Frozen Plasma (FFP), and Platelets in an equal 1:1:1 ratio** to mimic whole blood and prevent dilutional coagulopathy.
3. **Hypothermia Prevention**: All transfused fluids and blood products MUST pass through active blood warmers / rapid infusers.
4. **Antifibrinolytic Therapy**: **Tranexamic Acid (TXA)** administered as 1 g IV over 10 minutes, followed by 1 g IV over 8 hours (must be given within 3 hours of injury).
5. **Targeted Factor Replacement**: Administer **Cryoprecipitate** if serum fibrinogen falls <1.5 g/L.

---

### Dosage Rule

#### 1. Tranexamic Acid (TXA)

- **Name**: Tranexamic Acid
- **Mechanism of Action**: Synthetic lysine-analog antifibrinolytic; competitively inhibits plasminogen activation to prevent hyperfibrinolysis and clot breakdown.
- **Dose**: **1 g loading dose** over 10 minutes, followed by **1 g IV infusion** over 8 hours.
- **Dosage / Route**: Intravenous infusion.
- **Frequency**: Single loading dose + 8-hour continuous maintenance infusion.
- **Features**: Must be given as early as possible (ideally within 1 hour; ineffective/harmful if given >3 hours post-injury).
- **Side Effects**: Hypotension (if injected rapidly IV), nausea, thrombosis.
- **When to Start / Stop**: Start immediately upon activating MHP; stop after 8-hour infusion completes.

#### 2. Calcium Gluconate (10%)

- **Name**: 10% Calcium Gluconate
- **Mechanism of Action**: Directly replaces ionized calcium (Ca²⁺) chelated by citrate anticoagulant, restoring cardiac excitation-contraction coupling and neuromuscular stability.
- **Dose**: 10 mL of 10% Calcium Gluconate IV over 10–15 minutes (or 10 mL per 4–6 units of transfused PRBCs).
- **Dosage / Route**: Slow Intravenous injection.
- **Frequency**: Repeat based on serial ionized calcium monitoring (<0.9–1.0 mmol/L).
- **Side Effects**: Bradycardia, hypotension (if rapid IV push), tissue necrosis if extravasated.
- **When to Start / Stop**: Start upon clinical or biochemical evidence of citrate-induced hypocalcemia (tetany, QTc prolongation, ionized Ca²⁺ <0.9 mmol/L).

---

### Clinical Pearl

During massive blood transfusion, **never rely on routine standard laboratory coagulation panels (PT/aPTT)** to guide active resuscitation, as turn-around times take 45–60 minutes. Use **point-of-care viscoelastic testing—Rotational Thromboelastometry (ROTEM) or Thromboelastography (TEG)**—at the bedside to receive real-time functional assessment of clot initiation, clot strength, and hyperfibrinolysis within 10 minutes.

---

### Exam Trap

- **The Mix-up**: Treating citrate-induced hypocalcemia during massive transfusion with **Calcium Chloride via a peripheral IV line** or mixing calcium directly into the blood bag.
- **The Distinguishing Fact**: **NEVER add calcium solutions directly into a blood bag or blood tubing**, as it overcomes the citrate anticoagulant and causes immediate, catastrophic clotting inside the line! Furthermore, **10% Calcium Gluconate is preferred for peripheral IV lines**, whereas 10% Calcium Chloride is extremely sclerotic and requires central venous access.

---

### Diagram Guide

### Diagram 1: Complications of Massive Blood Transfusion

(Number sequentially within the answer — Diagram 1)

- **Type**: Mind-map / Etiological classification diagram.
- **Outline shape to draw**: Central box labeled "Massive Blood Transfusion" branching into 4 physiological complication quadrants.
- **Labels in order**:
    1. _Hypothermia (2–6°C Blood)_ → Inactivates clotting cascades & causes dysrhythmias.
    2. _Citrate Toxicity_ → Chelates Ca²⁺/Mg²⁺ → Hypocalcemia, tetany & QTc prolongation.
    3. _Hyperkalemia (Lysed RBCs)_ → Extracellular K⁺ accumulation → Risk of cardiac arrest.
    4. _Coagulopathy (1:1:1 Ratio needed)_ → Dilutional loss of platelets and factors + hyperfibrinolysis.
- **Annotation worth extra marks**: _"Dilutional coagulopathy combined with hypothermia and acidosis constitutes the Lethal Triad of massive transfusion."_

---

### Diagram 2: Damage Control Resuscitation & 1:1:1 Transfusion Strategy

(Number sequentially within the answer — Diagram 2)

- **Type**: Schematic flow diagram.
- **Outline shape to draw**: Three equal blood component bags feeding into a rapid blood warmer.
- **Labels in order**:
    1. _Packed Red Blood Cells (1 Unit)_ — oxygen-carrying capacity.
    2. _Fresh Frozen Plasma (1 Unit)_ — coagulation factors.
    3. _Platelet Concentrate (1 Unit)_ — primary hemostatic plug.
    4. _Inline Fluid / Blood Warmer_ — delivers 37 °C blood to prevent hypothermia.
    5. _Tranexamic Acid (TXA 1 g IV)_ — prevents hyperfibrinolysis.
- **Annotation worth extra marks**: _"Resuscitation in a 1:1:1 ratio mimics whole blood, preventing dilutional coagulopathy and optimizing survival."_

---

### Mnemonic / Memory Palace

#### Topic Mnemonic: C-O-A-G-U-L-A-T-E

- **C** – **C**itrate toxicity causing severe hypocalcemia and hypomagnesemia.
- **O** – **O**verload (TACO - Transfusion-Associated Circulatory Overload).
- **A** – **A**cidosis and **A**lkalosis (Lactic acidosis initially; Citrate → Bicarbonate alkalosis later).
- **G** – **G**iving blood via a blood warmer to prevent hypothermia (<34 °C).
- **U** – **U**nits criteria (>10 units PRBCs in 24 hours or >4 units in 1 hour).
- **L** – **L**ethal Triad: Hypothermia, Acidosis, and Coagulopathy.
- **A** – **A**ntifibrinolytic: Tranexamic Acid (TXA 1 g IV within 3 hours).
- **T** – **T**RALI (Transfusion-Related Acute Lung Injury via donor anti-HLA antibodies).
- **E** – **E**lectrolyte shift: Hyperkalemia from stored lysed RBCs.

---

### Quick Revision

- **Diagnostic Criteria**: Replacement of total blood volume in 24h, >10 units PRBCs in 24h, or >4 units PRBCs in 1h.
- **Major Complications**: Hypothermia, Citrate-induced Hypocalcemia, Hyperkalemia, and Dilutional Coagulopathy.
- **Primary Resuscitation Strategy**: Damage Control Resuscitation with **1:1:1 ratio (PRBC : FFP : Platelets)**.
- **Essential Drug**: **Tranexamic Acid (TXA) 1 g IV** loading dose over 10 min + 1 g IV over 8h (administered within 3 hours).
- **Bedside Monitoring**: ROTEM / TEG point-of-care testing to guide targeted factor replacement.

---

### One-Line Exam Opener

_Massive blood transfusion is the rapid replacement of a patient's total blood volume (>10 units PRBCs in 24 hours or >4 units in 1 hour) in exsanguinating hemorrhage, associated with life-threatening hypothermia, citrate hypocalcemia, hyperkalemia, and dilutional coagulopathy, managed via a Major Hemorrhage Protocol delivering a balanced 1:1:1 ratio of PRBCs, FFP, and platelets alongside tranexamic acid and active blood warming._

---

💡 _Since we have completed this comprehensive review, would you like to explore **Trauma-Induced Coagulopathy (TIC) & ROTEM/TEG Interpretation**, **Damage Control Surgery (DCS) & The Open Abdomen**, or **Postoperative Fluid Management Protocols** next?_