[[C6 - Hemorrhage and blood transfusion]]
# Hemorrhagic Shock

### Definition [⭐ High-Yield]

**Hemorrhagic shock** is a life-threatening form of hypovolemic shock resulting from rapid intravascular blood loss leading to severe systemic tissue hypoperfusion, inadequate cellular oxygen delivery, and a mandatory shift from aerobic to anaerobic metabolism, which—if uncorrected—causes progressive multi-organ dysfunction syndrome (MODS) and death.

---

### Etiology & Types of Hemorrhage [⭐ High-Yield]

#### 1. Anatomical Classification of Bleeding

- **Overt / Revealed Hemorrhage**: Obvious external blood loss (e.g., open arterial wound, massive hematemesis from peptic ulcer).
- **Concealed Hemorrhage**: Hidden internal blood loss occurring into major body compartments ("one on the floor and four more"):
    1. _Chest_ (Massive hemothorax)
    2. _Abdomen & Retroperitoneum_ (Ruptured spleen/liver, ruptured AAA)
    3. _Pelvis_ (Unstable pelvic ring fractures)
    4. _Long Bones / Extremities_ (Femur or multiple humerus/tibia fractures)

#### 2. Temporal Classification

- **Primary Hemorrhage**: Bleeding occurring at the immediate time of injury or surgery.
- **Reactionary Hemorrhage**: Delayed bleeding within 24 hours of injury/surgery, caused by dislodgement of a clot or slippage of a ligature as blood pressure normalizes during resuscitation.
- **Secondary Hemorrhage**: Bleeding occurring 7–14 days post-injury/surgery due to infection, pressure necrosis (from drains), or erosion/sloughing of a vessel wall.

---

### Classification of Hemorrhagic Shock (ATLS Staging) [⭐ High-Yield]

|Parameter|Class I (Minimal)|Class II (Mild / Compensated)|Class III (Moderate / Decompensated)|Class IV (Severe / Irreversible)|
|:--|:--|:--|:--|:--|
|**Approximate Blood Loss (%)**|<15%|15%–30%|30%–40%|>40%|
|**Approximate Blood Loss (mL)**|<750 mL (<0.5 L)|750–1500 mL (1.0 L)|1500–2000 mL (1.5 L)|>2000 mL (>2.0 L)|
|**Heart Rate (bpm)** [⭐ High-Yield]|Normal (<100)|**↑ Tachycardia (>100)**_(Earliest sign)_|↑↑ Marked (>120)|↑↑ Severe (>140) / Non-recordable|
|**Systolic Blood Pressure (SBP)**|Normal|**Normal** _(Compensated)_|**↓ Decreased (SBP drops)**|↓↓ Severely decreased / Non-recordable|
|**Pulse Pressure (SBP - DBP)**|Normal|**Narrowed**|Markedly narrowed|Severely reduced / Absent|
|**Respiratory Rate (per min)**|Normal (14–20)|Normal / Mildly elevated|↑ Increased (20–30)|↑↑ Tachypnea / Labored (>35)|
|**Urine Output (mL/h)**|Normal (>30)|Normal (20–30)|**↓ Decreased (5–15)**|**Anuria (<5)**|
|**Mental Status / CNS**|Normal / Mild anxiety|Anxious, thirsty|Drowsy, confused|Comatose / Lethargic|
|**Base Deficit (mEq/L)**|Normal (0 to -2)|-2 to -6 mEq/L|-6 to -10 mEq/L|> -10 mEq/L|
|**Initial Resuscitation Fluid**|Crystalloid / Oral|IV Crystalloids|IV Crystalloids + Blood / Colloid|**Massive Transfusion Protocol (MTP)**|

---

### Pathophysiology [⭐ High-Yield]

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[Acute Intravascular Blood Loss]:::primary --> B[Baroreceptor & Atrial Volume Receptor Activation]:::primary
B --> C[Sympathetic Nervous System & RAAS Activation: Catecholamines, ADH, Cortisol]:::primary
C --> D[Systemic Vasoconstriction + Tachycardia ↑ HR & Increased SVR]:::warning

D --> E[Compensated Phase: Blood Shunted to Heart & Brain; Peripheries Cool]:::warning
E --> F[Continued Bleeding >30% Blood Volume Loss]:::danger

F --> G[Tissue Hypoxia & Anaerobic Metabolism → Lactic Acidosis]:::danger
G --> H[Capillary Endothelial Breakdown & Endogenous Fibrinolysis ATC]:::danger

H --> I[Deadly Triad: Hypothermia <34°C + Acidosis pH <7.2 + Coagulopathy]:::danger
I --> J[Damage Control Resuscitation DCR: Permissive Hypotension + 1:1:1 MTP + TXA]:::success
```

- **Neuroendocrine Response**: Acute volume reduction activates carotid/aortic baroreceptors and atrial volume receptors. This triggers sympathetic nerve discharge and massive release of catecholamines (adrenaline/noradrenaline), ACTH, cortisol, aldosterone, and ADH (vasopressin).
- **Compensatory Mechanism**: Selective arteriolar vasoconstriction shunts blood away from non-essential capillary beds (skin, skeletal muscle, splanchnic circulation) to preserve central perfusion to the heart, brain, and lungs.
- **Cellular & Microvascular Damage**: Persistent hypoperfusion depletes intracellular ATP, causing sodium-potassium pump failure, cellular swelling, lysosomal membrane disruption, and lactic acidosis. Acidosis and tissue trauma induce **Acute Traumatic Coagulopathy (ATC)** characterized by systemic hyperfibrinolysis and endothelial capillary leak.
- **The Deadly Triad (Lethal Triad)** [⭐ High-Yield]: The combined cascade of **Hypothermia (<34 °C)**, **Acidosis (pH <7.2 / Lactate >5 mmol/L)**, and **Coagulopathy** leads to physiological exhaustion and rapid cardiac arrest if not interrupted by damage control principles.

---

### Clinical Features [⭐ High-Yield]

#### Symptoms

- **Thirst & Anxiety**: Early compensatory signs driven by hyperosmolar and sympathetic tone.
- **Dizziness, Confusion & Drowsiness**: Indicates deteriorating cerebral perfusion.
- **Dyspnea & Air Hunger**: Compensatory respiratory response to metabolic lactic acidosis.

#### Signs

- **Cardiovascular**: Tachycardia (**earliest clinical sign**, HR >100 bpm), narrow pulse pressure, cold/clammy/pale peripheries with delayed capillary refill time (>2 seconds), and hypotension (a **late sign** appearing only after >30% blood volume loss).
- **Renal**: Oliguria (urine output <0.5 mL/kg/h in adults; <1 mL/kg/h in children).

---

### Assessment of Dynamic Fluid Response [⭐ High-Yield]

The physiological response to an initial fluid bolus (500–1000 mL warm crystalloid) classifies patients into three critical operational categories:

|Category|Pulse Rate & Blood Pressure|Clinical Implication|Action Required|
|:--|:--|:--|:--|
|**Responders**|Normalizes (HR ↓↓, SBP ↑↑); changes remain persistent|Bleeding has stopped; total blood loss <20%|Monitor; cross-match blood; conservative work-up|
|**Transient Responders**|Initial improvement, but parameters deteriorate after 15–20 min|Ongoing active bleeding (bleeding rate ≈ fluid infusion rate)|**Major Transfusion Protocol (MTP)**; urgent surgical/radiological hemostasis|
|**Non-Responders**|No improvement in HR or SBP despite fluid bolus|Massive ongoing exsanguination (bleeding rate > fluid infusion rate)|**Immediate operative/interventional control**; emergency O-negative blood transfusion|

---

### Investigations & Monitoring [⭐ High-Yield]

#### 1. Point-of-Care & Diagnostic Panel

- **Bedside Venous Lactate & Base Deficit [Best Measure of Tissue Perfusion]** [⭐ High-Yield]: Serum lactate >3–5 mmol/L or base deficit > -6 mEq/L reflects the severity of tissue debt and guides resuscitation.
- **Hemoglobin & Hematocrit**: Initial Hb may be falsely normal in acute bleeding prior to hemodilution; serial Hb measurements are mandatory.
- **Thromboelastography (TEG) / Rotational Thromboelastometry (ROTEM)**: Point-of-care coagulation assessment to target specific factor replacement.
- **Bedside Imaging**: **eFAST** (extended Focused Assessment with Sonography for Trauma) and chest/pelvic X-rays to locate occult bleeding in unstable patients.
- **Whole-Body Contrast CT (WBCT)**: Gold-standard anatomical mapping tool for hemodynamically stable or stabilized trauma patients.

#### 2. Monitoring Metrics

- **Urine Output [Best Clinical Indicator of Resuscitation Success]** [⭐ High-Yield]: Target **>0.5 mL/kg/h in adults** (>1 mL/kg/h in children) via an indwelling Foley catheter.
- **Shock Index (SI)**: Heart Rate ÷ Systolic BP. Normal = 0.5–0.7; **SI >0.9 indicates severe shock and high mortality risk**.
- **Modified Shock Index (MSI)**: Heart Rate ÷ Mean Arterial Pressure (MAP) _(most sensitive marker)_.

---

### Treatment / Management (Damage Control Resuscitation - DCR) [⭐ High-Yield]

Resuscitation of active hemorrhagic shock prioritizes rapid hemostasis and prevention of coagulopathy over simple blood pressure normalization.

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[Active Hemorrhagic Shock Identified]:::primary --> B[1. Immediate Hemostasis: Direct Pressure + Tourniquets + Pelvic Binder]:::danger
B --> C[2. Activate Major Hemorrhage Protocol MHP]:::danger
C --> D[3. Administer Tranexamic Acid TXA 1 g IV over 10 min within 3 hours]:::success
D --> E[4. Permissive Hypotension: Target SBP 70–90 mmHg / Central Pulse]:::warning
E --> F[5. Balanced Transfusion: PRBC : FFP : Platelets in 1:1:1 Ratio]:::success
F --> G{Physiological Stability vs Deadly Triad}:::warning

G -->|Stable / Responded| H[Early Total Care ETC: Definitive Surgical Reconstruction]:::success
G -->|Deadly Triad Present: Temp <34°C, pH <7.2, Coagulopathy| I[Damage Control Surgery DCS: Abbreviated Laparotomy + Packing + ICU Warm Resuscitation]:::danger
```

#### 1. Pillars of Damage Control Resuscitation (DCR) [⭐ High-Yield]

1. **Immediate Hemostasis**: Application of direct pressure, tourniquets for limb exsanguination, pelvic binder at the greater trochanters for open-book pelvic fractures, or endovascular balloon occlusion (REBOA).
2. **Permissive Hypotension**: Maintaining a target **systolic blood pressure of 70–90 mmHg** (or Mean Arterial Pressure ~50 mmHg; target SBP >90 mmHg if co-existing traumatic brain injury is present) until bleeding is controlled. This prevents dislodging fresh vascular clots ("popping the clot") and limits dilutional coagulopathy.
3. **Balanced Hemostatic Transfusion (1:1:1 Ratio)** [⭐ High-Yield]: Avoiding crystalloid/colloid overload; transfusing **Packed Red Blood Cells (PRBC), Fresh Frozen Plasma (FFP), and Platelets in an equal 1:1:1 ratio**using blood warmers.
4. **Early Antifibrinolytic Administration**: **Tranexamic Acid (TXA)** given within 3 hours of injury.

#### 2. Damage Control Surgery (DCS) vs. Early Total Care (ETC) [⭐ High-Yield]

- **Damage Control Surgery (DCS)** [⭐ High-Yield]: Abbreviated, life-saving surgery limited strictly to **arresting hemorrhage** and **controlling gastrointestinal contamination** (e.g., liver packing, temporary bowel stapling, temporary vascular shunts) followed by temporary abdominal closure. Indicated in the presence of the **Deadly Triad** (Temp <34 °C, pH <7.2, Lactate >5 mmol/L, or massive transfusion >10 units).
- **ICU Phase**: The patient is transferred to ICU for active rewarming, correction of acidosis, and reversal of coagulopathy.
- **Definitive Reconstruction**: Delayed until 24–72 hours later when physiology is restored.

---

### Complications [⭐ High-Yield]

- **Systemic**: Multi-Organ Dysfunction Syndrome (MODS), Acute Respiratory Distress Syndrome (ARDS) secondary to aggressive crystalloids or transfusion, Acute Kidney Injury (AKI / ATN), Disseminated Intravascular Coagulation (DIC).
- **Resuscitation-Related**: Abdominal Compartment Syndrome (ACS) from massive bowel edema, hypothermia, citrate toxicity (hypocalcemia), hyperkalemia from stored lysed RBCs, and Transfusion-Related Acute Lung Injury (TRALI).

---

### Dosage Rule

#### 1. Tranexamic Acid (TXA)

- **Name**: Tranexamic Acid (CRASH-2 trial protocol).
- **Mechanism of Action**: Synthetic lysine-analog antifibrinolytic; competitively inhibits plasminogen activation, preventing clot lysis and reducing traumatic bleeding.
- **Dose**: **1 g loading dose** over 10 minutes, followed by **1 g IV infusion** over 8 hours.
- **Route**: Intravenous.
- **Timing**: **MUST be administered within 3 hours of trauma** (administration after 3 hours increases mortality).

#### 2. Initial Fluid Bolus (Crystalloids)

- **Name**: Warmed Isotonic Crystalloid (Hartmann's solution / 0.9% Normal Saline).
- **Dose**:
    - _Adults_: **500 mL to 1000 mL bolus** (judicious trial).
    - _Pediatrics_: **10 mL/kg bolus** of warmed isotonic fluid.
- **Route**: Intravenous via two short, large-bore peripheral cannulae (14G / 16G).
- **When to Stop**: Limit crystalloids immediately once blood products are available.

---

### Exam Trap

### Exam Trap

- **The Mix-up**: Relying on Systolic Blood Pressure (SBP) or Capillary Refill Time as an early indicator to rule out hemorrhagic shock in young, healthy trauma victims.
- **The Distinguishing Fact**: Young, fit individuals possess immense vascular compensatory reserve and can maintain a completely normal SBP until **more than 30%–40% of circulating blood volume is lost (Class III/IV shock)**. **Tachycardia (HR >100 bpm) and a narrowing pulse pressure are the EARLIEST clinical indicators of compensated hemorrhagic shock**.

---

### Clinical Pearl

In a severely injured trauma patient, **isolated closed head injury NEVER causes hypovolemic hemorrhagic shock**. If a patient with a traumatic brain injury presents with hypotension and tachycardia, **always search for an occult source of systemic hemorrhage** (chest, abdomen, pelvis, retroperitoneum, or long bones) or consider neurogenic shock if spinal cord injury above T6 is present.

---

### Diagram Guide

### Diagram 1: Traditional ATLS Classification of Hemorrhagic Shock

(Number sequentially within the answer — Diagram 1)

- **Type**: Tabular & clinical comparative schematic.
- **Outline shape to draw**: A 4-column progression box representing Class I to Class IV shock.
- **Labels in order**:
    1. _Class I (<15% loss)_ — Normal HR, Normal SBP, Normal Urine Output (>30 mL/h).
    2. _Class II (15–30% loss)_ — Tachycardia (>100 bpm), Normal SBP, Narrow Pulse Pressure.
    3. _Class III (30–40% loss)_ — Marked Tachycardia (>120 bpm), **Dropped SBP**, Oliguria (5–15 mL/h).
    4. _Class IV (>40% loss)_ — Severe Tachycardia (>140 bpm), Severe Hypotension, Anuria (<5 mL/h).
- **Annotation worth extra marks**: _"Blood pressure drops only in Class III shock; tachycardia is the earliest physical compensatory sign of Class II shock."_

---

### Diagram 2: Damage Control Resuscitation (DCR) Protocol

(Number sequentially within the answer — Diagram 2)

- **Type**: Procedural algorithm flowchart.
- **Outline shape to draw**: Dual-phase timeline box showing "Prioritize Coagulation (Active Bleeding)" transitioning to "Prioritize Perfusion (Post-Hemostasis)".
- **Labels in order**:
    1. _Active Bleeding Phase_ → Permissive Hypotension (SBP 70–90 mmHg) + Balanced Transfusion (1:1:1 PRBC:FFP:Platelets) + TXA 1 g IV.
    2. _Damage Control Surgery (DCS)_ → Rapid bleeding/contamination control → Temporary abdominal closure.
    3. _ICU Resuscitation Phase_ → Normalization of temp, pH, and coagulation.
    4. _Definitive Surgery Phase_ → Planned re-exploration and anatomical repair at 24–72 hours.
- **Annotation worth extra marks**: _"Damage control resuscitation aims to restore physiological stability over anatomical perfection in exsanguinating trauma."_

---

### Mnemonic / Memory Palace

#### Topic Mnemonic: D-E-A-D-L-Y

- **D** – **D**amage Control Resuscitation (Permissive hypotension SBP 70–90 mmHg + 1:1:1 blood ratio).
- **E** – **E**arliest sign of compensated shock is **tachycardia** (HR >100 bpm).
- **A** – **A**utologous / Balanced blood products over crystalloids to prevent dilutional coagulopathy.
- **D** – **D**eadly Triad: Hypothermia (<34 °C), Acidosis (pH <7.2), Coagulopathy.
- **L** – **L**actate (>3–5 mmol/L) and Urine Output (>0.5 mL/kg/h) serve as the best indicators of organ perfusion.
- **Y** – **Y**ield to surgery (DCS) when non-responders or transient responders exhibit persistent bleeding.

---

### Quick Revision

- **Core Definition**: State of inadequate tissue perfusion secondary to blood loss, forcing anaerobic metabolism and lactic acidosis.
- **Earliest Sign**: Tachycardia (HR >100 bpm) and narrowed pulse pressure; SBP drops late (Class III, >30% blood loss).
- **Deadly Triad**: Hypothermia (<34 °C), Acidosis (pH <7.2), and Coagulopathy.
- **Damage Control Resuscitation (DCR)**: Permissive hypotension (SBP 70–90 mmHg) + 1:1:1 balanced transfusion (PRBC:FFP:Platelets) + Tranexamic acid (1 g IV).
- **Best Monitor of Perfusion**: Hourly urine output (>0.5 mL/kg/h in adults) and serial venous lactate.

---

### One-Line Exam Opener

_Hemorrhagic shock is a life-threatening form of hypovolemic shock caused by rapid intravascular blood loss resulting in tissue hypoperfusion and anaerobic metabolism, classified into four ATLS stages, monitored via urine output and serum lactate, and managed urgently through Damage Control Resuscitation and balanced 1:1:1 blood product transfusion._

---

💡 _I have grounded this comprehensive exam response strictly in your uploaded textbook sources. Would you like to review **Damage Control Surgery (DCS) & The Open Abdomen**, **Massive Transfusion Protocol (MTP)**, or **Assessment & Initial Management of Major Trauma (ATLS Primary Survey)** next?_