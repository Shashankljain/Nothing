[[C33-DISEASES OF THE FETUS AND THE NEWBORN]]
# Neonatal Resuscitation Protocol [⭐ High-Yield]

### Mark Weightage

- **5 Marks**

---

### 1. Definition [⭐ High-Yield]

- **Neonatal Resuscitation**: A standardized, time-critical sequence of life-support interventions performed immediately at birth to establish effective alveolar ventilation, gas exchange, and cardiac output in a newborn experiencing birth asphyxia or failure to transition to extrauterine life.
- **Birth Asphyxia Diagnostic Criteria**:
    1. **Umbilical Cord Blood Acidemia**: Umbilical arterial blood pH <7.0 or base deficit ≥12 mmol/L.
    2. **Depressed Apgar Score**: Persistent Apgar score <5 at 5 minutes and 10 minutes.
    3. **Neurological Manifestations**: Development of **Hypoxic Ischemic Encephalopathy (HIE)** (hypotonia, altered sensorium, neonatal seizures within 12–24 hours).
    4. **Multiorgan Dysfunction**: Evidence of acute hypoxic injury in cardiovascular, renal, gastrointestinal, or hematological systems.

---

### 2. Indications & Assessment at Birth [⭐ High-Yield]

#### A. Initial Rapid Assessment (First Few Seconds)

Every newborn is evaluated immediately at birth by asking **3 primary questions**:

1. **Is the baby term gestation?**
2. **Does the baby have good muscle tone?**
3. **Is the baby breathing or crying?**

- If **YES** to all three: The baby stays with the mother for routine care (warmth, positioning airway, clearing secretions if needed, drying, and skin-to-skin contact).
- If **NO** to any question: The baby is shifted under a pre-heated radiant warmer to initiate the Resuscitation Protocol.

#### B. Apgar Scoring System (Dr. Virginia Apgar, 1953) [⭐ High-Yield]

Evaluated at **1 minute** and **5 minutes** after birth (repeated at 10, 15, and 20 minutes if depressed):

|Apgar Parameter|Score 0|Score 1|Score 2|
|:--|:--|:--|:--|
|**A - Appearance (Color)**|Blue, pale completely|Body pink, extremities blue (Acrocyanosis)|Completely pink|
|**P - Pulse (Heart Rate)**|Absent|<100 bpm|>100 bpm|
|**G - Grimace (Reflex Irritability)**|No response|Slight grimace|Cough, sneeze, or cry|
|**A - Activity (Muscle Tone)**|Flaccid / Limp|Some flexion of extremities|Active movements, well-flexed|
|**R - Respiration (Breathing Effort)**|Absent (Apnea)|Slow, irregular, shallow|Good, strong crying|

- **Score Interpretation**:
    - **8–10**: Normal (no depression).
    - **5–7**: Mild depression.
    - **3–4**: Moderate depression.
    - **0–2**: Severe depression / Severe Birth Asphyxia.
- _Crucial Rule_: **NEVER delay resuscitation to calculate the 1-minute Apgar score!**

---

### 3. Resuscitation Algorithm (AHA / AAP / NNF Guidelines) [⭐ High-Yield]

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[Birth of Neonate -> Term? Good Tone? Breathing/Crying?]:::primary --> B{All Yes?}:::warning
B -->|Yes| C[Routine Care: Warm, Maintain Temp, Position Airway, Dry, Stay with Mother]:::success
B -->|No| D[Initial Steps - 30 Sec: Radiant Warmer, Position Sniffing Position, Clear Airway if needed, Dry & Stimulate]:::primary
D --> E{Apnea / Gasping OR HR <100 bpm?}:::warning
E -->|No| F[Observe, Position Airway, SpO2 Monitor, CPAP if labored breathing]:::primary
E -->|Yes| G[Start Positive Pressure Ventilation PPV with Bag & Mask for 30 Sec + SpO2 Monitor]:::danger
G --> H{Check HR: Is HR <60 bpm?}:::warning
H -->|HR 60-100| I[Check Chest Movement, Ventilation Corrective Steps MR. SOPA, ETT if needed]:::warning
H -->|HR <60 bpm| J[Intubate ETT + Chest Compressions 3:1 ratio + 100% O2 for 60 Sec]:::danger
J --> K{Check HR: Is HR still <60 bpm?}:::warning
K -->|Yes| L[Administer IV Epinephrine 1:10,000 0.1-0.3 mL/kg via UVC + Consider Vol. Expansion]:::danger
K -->|No HR >60| M[Discontinue Compressions, Continue PPV until HR >100 bpm]:::success
```

---

### 4. Step-by-Step Resuscitation Protocol (T-ABC Steps) [⭐ High-Yield]

#### Step 1: Initial Steps (First 30 Seconds) [⭐ High-Yield]

1. **T - Thermoregulation**: Place the infant under a preheated (36.5°C) **radiant warmer**. For extremely preterm babies (<28 weeks), wrap in a polyethylene plastic bag/wrap without drying to prevent hypothermia.
2. **A - Airway Positioning**: Place the baby in a supine position with the neck slightly extended in the **"sniffing position"** (avoid hyperextension or hyperflexion).
3. **Suctioning**: Suction the **mouth first, then the nose** using a bulb syringe or mucus sucker **ONLY if secretions obstruct the airway** or if meconium is present in a non-vigorous infant.
4. **Dry & Stimulate**: Thoroughly dry the infant with warm towels and provide tactile stimulation (rubbing the back or flicking soles).

#### Step 2: Positive Pressure Ventilation (PPV - Breathing) [⭐ High-Yield]

- **Indications**: Apnea, gasping respiration, or **Heart Rate <100 bpm** after initial steps.
- **Technique**:
    - Deliver PPV using a self-inflating bag (Ambu bag) with a well-fitting cushioned face mask covering the nose and chin.
    - **Ventilation Rate**: **40–60 breaths/minute**.
    - **Oxygen Concentration (FiO₂)**: Start with **0.21 (21% room air)** for term infants (≥32 weeks) and **0.30 (30% O₂)** for preterm infants (<28 weeks), titrating with a blender to match target preductal SpO₂.
- **Ventilation Corrective Steps (MR. SOPA)** (If chest is not rising):
    - **M**: Mask readjustment.
    - **R**: Reposition head (sniffing position).
    - **S**: Suction mouth and nose.
    - **O**: Open mouth slightly.
    - **P**: Pressure increase (by 5 cm H₂O up to 30–40 cm H₂O).
    - **A**: Alternate airway (Endotracheal intubation - ETT or Laryngeal Mask Airway).

#### Step 3: Chest Compressions (Circulation) [⭐ High-Yield]

- **Indication**: **Heart Rate <60 bpm** despite **30 seconds of effective PPV** that moves the chest.
- **Technique**:
    - **Two-Thumb Technique**: Thumbs placed over the lower third of the sternum (just below the intermammary line) with fingers encircling the torso supporting the back.
    - **Depth**: Compress the sternum to **one-third of the anteroposterior diameter** of the chest.
    - **Compression-to-Ventilation Ratio**: **3:1 ratio** (3 compressions to 1 ventilation = 90 compressions + 30 breaths = 120 events/minute).
    - Increase FiO₂ to **1.00 (100% Oxygen)** when chest compressions begin.
    - Re-evaluate heart rate after **60 seconds** of coordinated chest compressions.

#### Step 4: Medications & Volume Expansion [⭐ High-Yield]

- **Indication**: **Heart Rate <60 bpm** persisting despite 60 seconds of chest compressions and 100% O₂ PPV.
- **Epinephrine (Adrenaline)**:
    - **1:10,000 dilution** (0.1 mg/mL) given via Umbilical Venous Catheter (UVC) at a dose of **0.1 to 0.3 mL/kg**(0.01 to 0.03 mg/kg) IV or endotracheal tube. Repeat every **3–5 minutes** if HR remains <60 bpm.
- **Volume Expansion**:
    - **Normal Saline (0.9% NaCl)** given at **10 mL/kg** IV over 5–10 minutes via UVC for acute blood loss, shock, or poor perfusion.

---

### 5. Equipment & Targeted SpO₂ Values [⭐ High-Yield]

#### A. Targeted Preductal SpO₂ (Right Hand) After Birth

- **1 Minute**: 60–65%
- **2 Minutes**: 65–70%
- **3 Minutes**: 70–75%
- **4 Minutes**: 75–80%
- **5 Minutes**: 80–85%
- **10 Minutes**: 85–95%

#### B. Essential Resuscitation Equipment Checklist

- **Thermoregulation**: Pre-heated radiant warmer, warm towels, plastic wrap (<28 wks), hat.
- **Airway & Ventilation**: Suction bulb/catheter, self-inflating Ambu bag, cushioned face masks, oxygen blender, CPAP circuit, laryngoscope (blades 00, 0, 1), Endotracheal Tubes (sizes 2.5, 3.0, 3.5 mm).
- **Medications & Access**: Epinephrine (1:10,000), Normal Saline 0.9%, Umbilical Venous Catheterization (UVC) tray, 3-way stopcocks.

---

### 6. Differential Diagnosis

#### Comparison of Causes of Depressed Neonate at Birth

|Parameter|Birth Asphyxia|Maternal Narcotic Depression|Preterm Severe RDS|Early-Onset Neonatal Sepsis|
|:--|:--|:--|:--|:--|
|**Primary History**|Intrapartum distress, cord prolapse, abruption.|Maternal Opioid/Pethidine within 4 hours.|Preterm birth (<34 wks), lack of surfactant.|Maternal fever, PROM >18 hrs, chorioamnionitis.|
|**Cord Blood pH**|**Acidemic (pH <7.0)**.|Normal (>7.20–7.25).|Normal or mild mixed acidosis.|Normal or variable.|
|**Heart Rate**|**Bradycardia (<100 bpm)**.|Normal (>100 bpm).|Variable.|Tachycardia or normal.|
|**Naloxone Reversal**|No response.|**Prompt reversal of respiratory depression**.|No response.|No response.|
|**CXR / Workup**|Normal or patchy opacities.|Normal lung fields.|**Ground-glass opacities + Air bronchograms**.|Raised CRP, positive blood culture.|

---

### 7. Complications of Perinatal Asphyxia [⭐ High-Yield]

|System|Acute Complications|Long-Term Sequelae|
|:--|:--|:--|
|**CNS**|Cerebral edema, HIE, neonatal seizures, intracranial hemorrhage.|**Spastic/Choreoathetoid Cerebral Palsy (CP)**, epilepsy (30%), intellectual disability.|
|**Cardiovascular**|Cardiogenic shock, myocardial ischemia, papillary muscle dysfunction, hypotension.|Chronic heart failure (rare).|
|**Pulmonary**|Meconium Aspiration Syndrome (MAS), Persistent Pulmonary Hypertension (PPHN), pulmonary hemorrhage.|Bronchopulmonary Dysplasia (BPD), chronic lung disease.|
|**Renal**|Acute Tubular Necrosis (ATN), oliguria, hematuria.|Chronic renal impairment.|
|**GI & Metabolic**|Necrotizing Enterocolitis (NEC), stress ulcers, hypoglycemia, hypocalcemia.|Intestinal strictures.|
|**Hematology**|Disseminated Intravascular Coagulation (DIC), thrombocytopenia.|Anemia.|

---

### 8. Drug Dosage Table (DOSAGE RULE) [⭐ High-Yield]

|Name|Mechanism of Action|Dose|Dosage / Route|Frequency|Features & Precautions|Side Effects|When to Start / Stop|
|:--|:--|:--|:--|:--|:--|:--|:--|
|**Epinephrine (Adrenaline)**|Direct α and β-adrenergic agonist; increases systemic vascular resistance, aortic diastolic BP, and coronary/cerebral perfusion.|**0.1–0.3 mL/kg**of 1:10,000 solution (0.01–0.03 mg/kg)|Intravenous (IV) via UVC or Endotracheal (ET) tube|Repeat every **3–5 minutes** as needed|**Drug of choice in NRP**; use 1:10,000 dilution only; flush IV line with 3 mL NS.|Severe tachycardia, cardiac arrhythmias, hypertension.|Start if HR remains <60 bpm after 60s chest compressions + 100% O₂ PPV; stop when HR >60 bpm.|
|**Normal Saline (0.9% NaCl)**|Isotonic crystalloid; expands intravascular volume and restores organ perfusion.|**10 mL/kg**|Intravenous (IV) infusion via UVC|Single bolus over **5–10 minutes**|Volume expander of choice for acute hypovolemia, pallor, or shock.|Hyperchloremic acidosis, fluid overload, intraventricular hemorrhage in preterms.|Start in suspected hypovolemia or shock with poor perfusion; repeat once if shock persists.|
|**Naloxone**|Pure competitive opioid receptor antagonist; reverses narcotic-induced respiratory depression.|**10 μg/kg**(0.01 mg/kg)|Intramuscular (IM) or IV|Single stat dose; repeat if needed|**Indicated ONLY for severe respiratory depression secondary to maternal opioid administration**within 4 hours of birth.|May precipitate acute withdrawal seizures in neonates of opioid-addicted mothers.|Start after establishing effective PPV in documented maternal narcotic depression; stop once spontaneous breathing returns.|

---

### 9. Clinical Pearl & Exam Trap

### Clinical Pearl

- **Effective Ventilation is the Single Most Important Step**: The vast majority of asphyxiated neonates respond promptly to effective **Positive Pressure Ventilation (PPV)** alone. Chest compressions and epinephrine are rarely required (<1% of deliveries) if mask ventilation achieves adequate chest rise.

### Exam Trap

- **The Mix-Up**: Delaying Resuscitation to Obtain a 1-Minute Apgar Score.
- **Distinguishing Fact**: **NEVER wait for the 1-minute Apgar score to initiate neonatal resuscitation!**Resuscitation begins immediately within the first 30 seconds based on initial rapid assessment (gestational age, tone, breathing/crying, and heart rate). Apgar scores are calculated retrospectively at 1 and 5 minutes while resuscitation is actively ongoing.

---

### 10. Diagram Guides

### Diagram 1: Correct Positioning of Neonatal Head (Sniffing Position)

- **Type**: Procedural anatomical schematic diagram.
- **Outline shape to draw**: Lateral view of neonatal head and neck on a flat surface with a shoulder roll.
- **Labels in order**:
    1. **Shoulder Roll (Towel)** — placed under upper back/shoulders to elevate chest slightly.
    2. **Sniffing Position** — neck in slight extension aligning pharyngeal and tracheal axes.
    3. **Incorrect Extension / Flexion** — shows airway occlusion from hyperextension or chin-on-chest flexion.
- **Annotation**: _"The sniffing position with slight neck extension aligns the airway axes and optimizes patency for bag-and-mask ventilation."_

---

### Diagram 2: Two-Thumb Technique for Neonatal Chest Compressions

- **Type**: Clinical procedural diagram.
- **Outline shape to draw**: Frontal view of infant chest encircled by examiner's hands.
- **Labels in order**:
    1. **Lower Third of Sternum** — compression site directly below intermammary line.
    2. **Two Thumbs Side-by-Side** — compressing sternum to 1/3rd AP chest depth.
    3. **Encircle Fingers Behind Back** — supporting the spine.
- **Arrows/connections**: Downward Compression (1/3rd AP Depth ↓) ↔ Complete Recoil (Upward Release ↑).
- **Annotation**: _"The two-thumb technique provides superior coronary and cerebral perfusion pressure compared to the two-finger technique."_

---

### 11. Mnemonic / Memory Palace

#### Mnemonic: T-A-B-C-D (Neonatal Resuscitation Steps)

- **T**: **Temperature control** (Radiant warmer, drying, plastic wrap for preterms <28 wks).
- **A**: **Airway position & clearance** (Sniffing position, suction mouth then nose only if needed).
- **B**: **Breathing / PPV** (Bag-and-mask ventilation for 30s if HR <100 bpm or apnea; MR. SOPA if no chest rise).
- **C**: **Circulation / Compressions** (Chest compressions at 3:1 ratio with 100% O₂ for 60s if HR <60 bpm).
- **D**: **Drugs & Volume** (IV Epinephrine 1:10,000 and Normal Saline 10 mL/kg bolus via UVC).

---

### Quick Revision

- **Initial Assessment**: Term? Good tone? Breathing/crying? If NO → shift under radiant warmer.
- **Indication for PPV**: Apnea, gasping, or **HR <100 bpm** after initial steps.
- **Indication for Compressions**: **HR <60 bpm** despite 30 seconds of effective PPV.
- **Compressions Ratio**: **3:1 ratio** (90 compressions + 30 breaths = 120 events/minute) with 100% O₂.
- **Epinephrine Dose**: **0.1–0.3 mL/kg of 1:10,000 dilution IV** via Umbilical Venous Catheter.

---

### One-Line Exam Opener

- **Neonatal resuscitation is a time-critical clinical protocol (T-ABC) designed to treat birth asphyxia and respiratory failure at birth by establishing rapid alveolar aeration, effective positive pressure ventilation, coordinated 3:1 chest compressions, and parenteral epinephrine administration.**

---

💡 _Would you like me to generate practice MCQs, clinical case scenarios, or flashcards on Neonatal Resuscitation & Perinatal Asphyxia to test your recall before the exam?_