[[C16-Cardiology]]
# Acute Myocardial Infarction & Cardiogenic Shock

## 1. Definition [⭐ High-Yield]

**Acute Myocardial Infarction (AMI)** is defined as the death (necrosis) of cardiac muscle resulting from severe, prolonged myocardial ischaemia caused by an abrupt reduction or cessation of coronary blood flow.

According to the **Fourth Universal Definition of Myocardial Infarction**, AMI is diagnosed when there is clinical evidence of acute myocardial ischaemia accompanied by a detection of a rise and/or fall of cardiac biomarker values—preferably **cardiac troponin (cTn I or T)**—with at least one value above the 99th percentile upper reference limit (URL).

---

## 2. Etiology / Causes / Risk Factors [⭐ High-Yield]

### A. Primary Etiology

- **Coronary Atherothrombosis (Dominant Cause - >90%):** Acute disruption (rupture, erosion, or fissuring) of a vulnerable atherosclerotic plaque in an epicardial coronary artery, triggering immediate platelet adhesion, aggregation, and activation of the coagulation cascade, leading to an occlusive thrombus.
- **Non-Atherothrombotic Causes (<10%):**
    - **Coronary Artery Spasm:** Prinzmetal variant angina or cocaine/ephedrine ingestion.
    - **Coronary Embolism:** Left atrial thrombus in Atrial Fibrillation, infective endocarditis vegetations, or prosthetic valve thrombi.
    - **Coronary Vasculitis:** Kawasaki disease, Takayasu arteritis, or Polyarteritis nodosa.
    - **Spontaneous Coronary Artery Dissection (SCAD)** or severe oxygen supply/demand mismatch (e.g., severe shock, thyrotoxicosis, tachyarrhythmia).

### B. Cardiovascular Risk Factors [⭐ High-Yield]

#### Non-Modifiable (Constitutional) Risk Factors

- **Age:** Risk increases progressively with age (peak incidence >45 years in men, >55 years in women).
- **Gender:** Males have a higher incidence through middle age; post-menopausal females lose estrogenic protection and reach equal risk.
- **Family History / Genetics:** First-degree male relative with premature CAD (<55 years) or female relative (<65 years).

#### Modifiable Risk Factors

- **Cigarette Smoking:** Most crucial preventable cause; accelerates endothelial injury, promotes platelet aggregation, and induces coronary vasospasm.
- **Systemic Hypertension (BP ≥140/90 mmHg):** Promotes shear-stress endothelial dysfunction, left ventricular hypertrophy (LVH), and increases myocardial O₂ demand.
- **Dyslipidaemia:** Elevated Low-Density Lipoprotein (LDL-C), elevated Lipoprotein(a), reduced High-Density Lipoprotein (HDL-C <40 mg/dL), and oxidized LDL accumulation.
- **Diabetes Mellitus & Insulin Resistance:** Accelerates advanced glycation end-product formation, endothelial dysfunction, and diffuse multi-vessel CAD.
- **Obesity & Physical Inactivity:** Centripetal obesity (Metabolic Syndrome).
- **Inflammatory Markers:** Elevated High-Sensitivity C-Reactive Protein (hs-CRP >3 mg/L) indicates chronic atheromatous inflammation.

---

## 3. Classification

### A. Clinical & Electrocardiographic Classification

1. **ST-Segment Elevation Myocardial Infarction (STEMI):** Complete occlusive thrombus causing transmural (full-thickness) myocardial necrosis; characterized by persistent ST-segment elevation on 12-lead ECG.
2. **Non-ST-Segment Elevation Myocardial Infarction (NSTEMI):** Subtotal / incomplete coronary occlusion causing partial-thickness (subendocardial) necrosis; characterized by ST-segment depression or T-wave inversion on ECG with elevated serum troponins.

### B. Fourth Universal Definition Clinical Classification (Types 1–5)

- **Type 1:** Spontaneous MI secondary to acute atherothrombotic plaque rupture or erosion.
- **Type 2:** MI secondary to ischaemic imbalance (oxygen supply/demand mismatch, e.g., severe anaemia, vasospasm, acute hypertension).
- **Type 3:** Cardiac death with symptoms of myocardial ischaemia before biomarkers could be obtained.
- **Type 4a:** Percutaneous Coronary Intervention (PCI)-related MI (troponin >5× 99th percentile URL).
- **Type 4b:** Stent thrombosis-associated MI detected by angiography or autopsy.
- **Type 5:** Coronary Artery Bypass Grafting (CABG)-related MI (troponin >10× 99th percentile URL).

---

## 4. Pathophysiology (with Flowchart) [⭐ High-Yield]

### Pathogenetic Sequence & Temporal Progression

1. **Plaque Disruption & Thrombus Formation:** Rupture or erosion of a thin-cap fibroatheroma exposes subendothelial collagen and von Willebrand factor, triggering platelet aggregation and fibrin-rich thrombus deposition.
2. **Biochemical Progression of Ischaemia:**
    - **Within 8–10 seconds:** Oxygen deprivation stops aerobic metabolism; ATP levels drop rapidly, and intracellular lactate accumulates.
    - **Within 1–2 minutes:** Loss of myocardial contractility occurs.
    - **Within 20–30 minutes:** Irreversible necrotic cell death initiates in the subendocardium.
3. **The Wavefront Hypothesis of Infarction:** Cardiomyocyte necrosis progresses as a wave from the vulnerable subendocardium outward toward the subepicardium. The wave is complete by **6 to 12 hours** ("time is myocardium").
4. **Microscopic Histopathological Evolution:**
    - _1–3 hours:_ Wavy myocardial fibers, subtle cellular edema.
    - _4–12 hours:_ Coagulative necrosis, contraction band necrosis, early neutrophilic infiltrate.
    - _1–3 days:_ Dense neutrophilic infiltrate, loss of cardiomyocyte nuclei and striations.
    - _3–7 days:_ Macrophage phagocytosis of necrotic debris (maximum tissue friability; peak risk of mechanical myocardial rupture!).
    - _7–10 days:_ Early granulation tissue formation with capillary neocanalization.
    - _7 weeks onward:_ Dense collagenous fibrous scar replacement.

### Pathophysiology Flowchart

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px

A[Atherosclerotic Plaque Rupture / Erosion]:::primary --> B[Platelet Adhesion & Activation of Coagulation Cascade]:::primary
B --> C{Degree of Thrombus Occlusion}:::warning

C -->|Complete Occlusive Thrombus| D[Transmural Subepicardial Ischaemia - STEMI]:::danger
C -->|Subtotal / Transient Thrombus| E[Subendocardial Ischaemia - NSTEMI / Unstable Angina]:::danger

D --> F[Depletion of ATP & Intracellular Lactate Accumulation within 10 mins]:::danger
F --> G[Irreversible Myocyte Necrosis Initiates within 20–30 mins]:::danger
G --> H[Wavefront Progression: Complete Transmural Necrosis in 6–12 Hours]:::danger

H -->|Urgent Reperfusion <120 mins| I[Primary PCI / Thrombolysis: Myocardial Salvage & Survival]:::success
H -->|Delayed / Failed Reperfusion| J[Ventricular Remodeling, Heart Failure & Cardiogenic Shock]:::danger
```

---

## 5. Clinical Features

### A. Symptoms

- **Cardio-Specific Pain Character:**
    - **Site:** Substernal, retrosternal, or precordial.
    - **Quality:** Heavy, crushing, squeezing, band-like constriction, or "an elephant standing on the chest".
    - **Radiation:** Radiates along C8–T4 nerve roots to the **left arm, shoulder, neck, jaw, epigastrium, or back**.
    - **Duration:** Prolonged pain lasting **>20–30 minutes**; NOT relieved by rest or sublingual nitrates.
- **Autonomic Disturbance & Angor Animi:**
    - **Sympathetic Activation:** Profuse cold sweating (diaphoresis), pallor, anxiety, and a feeling of impending doom (_angor animi_).
    - **Vagal Activation:** Nausea, vomiting, and sinus bradycardia (especially in inferior MI secondary to vagal afferent stimulation).
- **Breathlessness & Collapse:** Sudden dyspnoea caused by acute left ventricular failure/pulmonary congestion, or syncope/collapse caused by fatal arrhythmias or severe hypotension.
- **Silent / Painless MI:** Occurs in up to 25% of cases; most common in **elderly patients** (presenting as acute delirium, falls, or weakness) and **diabetic patients** (due to autonomic neuropathy).

### B. Physical Signs

- **General:** Patient appears grey, pale, diaphoresis present, anxious, and tossing restlessly.
- **Cardiovascular:**
    - **Pulse & BP:** Tachycardia or bradycardia; narrow pulse pressure; hypotension indicates cardiogenic shock or RV infarction.
    - **Auscultation:** Soft First Heart Sound (S₁), **Third Heart Sound (S₃ gallop)** indicating acute LV failure, **Fourth Heart Sound (S₄)** due to stiff non-compliant LV, and transient apical pansystolic murmur if papillary muscle dysfunction causes acute Mitral Regurgitation.
- **Respiratory:** Bi-basal fine inspiratory crackles (crepitations) indicating acute pulmonary edema.

---

## 6. Diagnosis / Investigations [⭐ High-Yield]

### A. Cardiac Biomarkers [⭐ High-Yield]

1. **Cardiac Troponins (cTnI and cTnT) [Gold Standard]:**
    - **Rise:** Detectable within **2–4 hours** (using high-sensitivity assays).
    - **Peak:** 24–48 hours.
    - **Duration:** Remains elevated for **7–14 days**.
    - _Diagnostic Threshold:_ Elevation >99th percentile URL with a characteristic rise and/or fall pattern.
2. **Creatine Kinase-MB (CK-MB):**
    - Rises within 4–6 hours, peaks at 24 hours, normalizes within 48–72 hours.
    - Useful primarily for detecting **early re-infarction** (within 28 days).
3. **Inflammatory & General Bloods:** Full blood count shows leukocytosis (peak on day 1); elevated CRP/ESR; serum lipids measured within 24 hours.

### B. 12-Lead Electrocardiogram (ECG) [⭐ High-Yield]

1. **Sequential ECG Evolution in STEMI:**
    - **Hyperacute Phase (Minutes):** Tall, broad, peaked T waves.
    - **Acute Phase (Hours):** Convex-upward **ST-segment elevation** merging with T waves ("current of injury").
    - **Subacute Phase (Days):** Loss of R wave height, development of **pathological Q waves** (width ≥0.04s and depth >25% R wave height), and T-wave inversion.
    - **Late / Old Infarct (Weeks to Months):** Q waves tend to persist indefinitely; ST segments return to baseline.
2. **ECG Lead Anatomical Localization:**
    - **Anteroseptal:** V₁–V₄ (Left Anterior Descending - LAD).
    - **Anterolateral:** V₄–V₆, I, aVL (Left Circumflex / LAD).
    - **Inferior:** II, III, aVF (Right Coronary Artery - RCA).
    - **Right Ventricular (RVMI):** ST elevation in right-sided chest leads (V₃R, V₄R).
    - **Posterior:** Dominant tall R wave and horizontal ST depression in V₁–V₃.

### C. Imaging

- **Transthoracic Echocardiography:** Bedside test detecting **Regional Wall Motion Abnormalities (RWMA)**, measuring LVEF, and diagnosing complications (mural thrombus, VSD, papillary muscle rupture, pericardial effusion).
- **Chest X-Ray:** Assesses cardiomegaly and detects pulmonary alveolar congestion/edema.
- **Invasive Coronary Angiography (CAG):** Visualizes the culprit vessel thrombus and guides immediate percutaneous revascularization.

---

## 7. Differential Diagnosis

|Feature|Acute Myocardial Infarction|Acute Pericarditis|Acute Pulmonary Embolism|Acute Aortic Dissection|
|:--|:--|:--|:--|:--|
|**Pain Character**|Heavy, crushing, retrosternal pain (>20 mins)|Sharp, pleuritic pain, relieved sitting forward|Sudden pleuritic chest pain + severe dyspnoea|Sudden "tearing" or "ripping" interscapular pain|
|**ECG Features**|Regional ST elevation / depression with reciprocal changes|Diffuse concave (saddle-shaped) ST elevation, PR depression|Sinus tachycardia, S₁Q₃T₃ pattern, RBBB|Normal ECG or inferior ST elevation (if RCA dissected)|
|**Biomarkers**|Sharp rise and fall of Troponin I/T|Mild Troponin elevation|Elevated D-Dimer, mild Troponin elevation|Normal Troponins, markedly elevated D-Dimer|
|**Definitive Diagnostic Test**|Emergency Coronary Angiography|Echocardiography (Pericardial effusion)|CT Pulmonary Angiography (CTPA)|Contrast-Enhanced CT Aorta / Transoesophageal Echo|

---

## 8. Treatment / Management in the First 24 Hours [⭐ High-Yield]

```
                     ┌──────────────────────────────────────────────┐
                     │    ACUTE STEMI MANAGEMENT (FIRST 24 HOURS)   │
                     └──────────────────────┬───────────────────────┘
                                            │
               ┌────────────────────────────┴────────────────────────────┐
               ▼                                                         ▼
┌──────────────────────────────┐                          ┌──────────────────────────────┐
│  1. EMERGENCY INITIAL CARE   │                          │  2. REPERFUSION STRATEGY     │
│ • IV Morphine + Antiemetic   │                          │ • Primary PCI (<120 mins)    │
│ • Oxygen (only if SpO₂ <90%) │                          │            OR                │
│ • SL / IV Nitrates           │                          │ • Thrombolysis (<12 hours)   │
│ • DAPT: Aspirin + Ticagrelor │                          │   (Tenecteplase / Stk)       │
│ • High-Dose Statin           │                          └──────────────┬───────────────┘
└──────────────────────────────┘                                         │
                                                                         ▼
                                                          ┌──────────────────────────────┐
                                                          │ 3. CCU MAINTENANCE THERAPY   │
                                                          │ • Parenteral Anticoagulant   │
                                                          │ • Oral Beta-Blocker (24 hrs) │
                                                          │ • ACE-Inhibitor (24 hrs)     │
                                                          └──────────────────────────────┘
```

### A. Immediate Emergency & Resuscitation Measures (Pre-CCU / ER)

1. **Airway & Oxygenation:** Supplemental oxygen administered **ONLY if SpO₂ <90%** or if the patient exhibits hypoxaemia/respiratory distress.
2. **Analgesia & Sedation:** Intravenous Opiates—**Morphine Sulfate 3–5 mg IV** slow injection (repeated as needed) plus Metoclopramide 10 mg IV—to relieve pain, lower sympathetic adrenergic drive, and reduce vascular resistance. _(Avoid IM injections due to painful hematoma formation after antithrombotics!)_
3. **Sublingual Nitrates:** Glyceryl Trinitrate (GTN 0.5 mg SL or spray) for pain relief and preload reduction. _(Do NOT administer if Systolic BP <90 mmHg, HR <50 or >100 bpm, RV infarction, or PDE-5 inhibitor taken within 24h)_.

---

### B. Reperfusion Therapy (Emergency Door-to-Balloon / Door-to-Needle) [⭐ High-Yield]

Immediate reperfusion is mandatory for all STEMI patients presenting within **12 hours** of symptom onset.

1. **Primary Percutaneous Coronary Intervention (PCI) [Gold Standard]:**
    - Recommended if the target **First Medical Contact (FMC) to wire-crossing time is <120 minutes**.
    - Restores epicardial vessel patency (TIMI 3 flow) using balloon angioplasty and Drug-Eluting Stent (DES) placement.
2. **Fibrinolytic / Thrombolytic Therapy (If Primary PCI unavailable within 120 mins):**
    - Must be administered within **12 hours** of onset (door-to-needle time **<30 minutes**).
    - **Tenecteplase (TNK-tPA):** Fibrin-specific single IV bolus over 10 seconds: **0.5 mg/kg IV** (maximum 50 mg).
    - **Streptokinase:** 1.5 million Units IV in 100 mL 0.9% Normal Saline infused over 1 hour. _(Contraindicated if used within prior 6 months due to neutralizing antibodies!)_
    - _Post-Thrombolysis Management:_ Check ECG at 60–90 mins. If <70% ST-segment resolution occurs → perform immediate **Rescue PCI**; if >70% resolution occurs → perform routine **Pharmaco-invasive PCI within 2–24 hours**.

---

### C. Antiplatelet & Anticoagulant Dosing Protocols (First 24 Hours)

1. **Dual Antiplatelet Therapy (DAPT) Loading:**
    - **Aspirin:** **300–325 mg PO** chewable non-enteric tablet immediately.
    - **P2Y₁₂ Inhibitor Choice:**
        - **Ticagrelor:** **180 mg PO** loading dose (preferred).
        - **Prasugrel:** **60 mg PO** loading dose (for primary PCI).
        - **Clopidogrel:** **300–600 mg PO** loading dose (if Ticagrelor/Prasugrel unavailable or patient receiving thrombolysis).
2. **Parenteral Anticoagulation:**
    - **Enoxaparin (LMWH):** **30 mg IV bolus**, followed 15 mins later by **1 mg/kg SC twice daily**.
    - **Fondaparinux:** 2.5 mg SC once daily.
    - **Unfractionated Heparin (UFH):** IV bolus 60 U/kg (max 4000 U) followed by infusion.
3. **Glycoprotein IIb/IIIa Inhibitors (In Cath Lab):**
    - **Abciximab, Eptifibatide, or Tirofiban** IV infusion reserved as downstream "bailout" therapy in PCI for high thrombus burden.

---

### D. Core Disease-Modifying Drugs Initiated in First 24 Hours

1. **High-Intensity Statin:** **Atorvastatin 80 mg PO OD** (or Rosuvastatin 40 mg PO OD) initiated immediately in all patients regardless of baseline lipid levels.
2. **Beta-Adrenoceptor Blockers:** Oral **Metoprolol 25–50 mg PO BD** (or Bisoprolol 2.5–5 mg PO OD) initiated within the first 24 hours in hemodynamically stable patients. _(Hold if pulmonary edema, hypotension SBP <102 mmHg, or bradycardia present!)_
3. **ACE Inhibitors / ARBs:** **Enalapril 2.5–5 mg PO BD** (or Ramipril 2.5 mg PO OD) started within 24 hours once hemodynamically stable to prevent acute ventricular remodeling and heart failure.

---

## 9. Management of Cardiogenic Shock [⭐ High-Yield]

### A. Definition & Diagnostic Criteria

**Cardiogenic Shock** is defined as a state of critical end-organ hypoperfusion resulting from primary cardiac pump failure.

- **Hemodynamic Criteria:**
    - Persistent **Systolic Blood Pressure <90 mmHg** (or Mean Arterial Pressure <65 mmHg) for >30 minutes.
    - **Cardiac Index <2.2 L/min/m²** in the presence of elevated left ventricular filling pressure (Pulmonary Capillary Wedge Pressure - PCWP >18 mmHg).
- **Clinical End-Organ Hypoperfusion Signs:** Oliguria (urine output <0.5 mL/kg/hr), cold, clammy, cyanotic extremities, altered mental status, and metabolic lactic acidosis.

### B. Pathophysiology of the "Downward Spiral"

Extensive myocardial necrosis (affecting **>40% of Left Ventricular mass**, usually proximal LAD occlusion) depresses LV systolic and diastolic function.

1. **↓ Stroke Volume & ↓ Cardiac Output** → Severe systemic hypotension → **↓ Coronary Perfusion Pressure** → Worsening myocardial ischaemia.
2. **↑ LVEDP & PCWP (>18 mmHg)** → Severe pulmonary venous congestion & alveolar edema → Hypoxaemia → Exacerbation of myocardial hypoxia.
3. Compensatory intense peripheral vasoconstriction raises afterload, increasing myocardial work without improving perfusion, driving a self-perpetuating **vicious cycle / downward spiral** culminating in multi-organ dysfunction syndrome (MODS). (See **Diagram 2**).

### C. Hemodynamic Subsets & Killip Classification

- **Killip Class I:** No signs of heart failure (Mortality ~5%).
- **Killip Class II:** Crackles halfway up chest, S₃ gallop (Mortality ~10%).
- **Killip Class III:** Overt acute pulmonary edema; crackles all over lung fields (Mortality ~20%).
- **Killip Class IV:** **Cardiogenic Shock** (Mortality 50–80%).

---

### D. Stepwise Management Protocol for Cardiogenic Shock

```
                     ┌──────────────────────────────────────────────┐
                     │    CARDIOGENIC SHOCK MANAGEMENT ALGORITHM    │
                     └──────────────────────┬───────────────────────┘
                                            │
               ┌────────────────────────────┴────────────────────────────┐
               ▼                                                         ▼
┌──────────────────────────────┐                          ┌──────────────────────────────┐
│ 1. AIRWAY & OXYGENATION      │                          │ 2. FLUID CHALLENGE           │
│ • Intubation & Invasive MV   │                          │ • 0.9% Normal Saline 10 mL/kg│
│ • Target SpO₂ 94–98%         │                          │   bolus (if PCWP not elevated)│
└──────────────┬───────────────┘                          └──────────────┬───────────────┘
               │                                                         │
               └────────────────────────────┬────────────────────────────┘
                                            │
                                            ▼
                               ┌──────────────────────────────┐
                               │ 3. INOTROPES & VASOPRESSORS  │
                               │ • Noradrenaline (0.05-0.5 µg)│
                               │ • Dobutamine (2.5-10 µg/kg/m)│
                               └────────────┬─────────────────┘
                                            │
               ┌────────────────────────────┴────────────────────────────┐
               ▼                                                         ▼
┌──────────────────────────────┐                          ┌──────────────────────────────┐
│ 4. EMERGENCY REPERFUSION     │                          │ 5. MECHANICAL CIRCULATORY    │
│ • Immediate Emergency        │                          │    SUPPORT                   │
│   Primary PCI (Culprit lesion)│                         │ • Intra-Aortic Balloon Pump  │
└──────────────────────────────┘                          │ • VA-ECMO / Impella          │
                                                          └──────────────────────────────┘
```

#### Step 1: Airway, Oxygenation & Ventilation

- Secure airway with endotracheal intubation and mechanical ventilation (with PEEP) for hypoxaemic patients to reduce the work of breathing and oxygen consumption.

#### Step 2: Judicious Fluid Challenge

- In patients without severe pulmonary congestion (or suspecting RV infarction), administer a **10 mL/kg fluid challenge** of 0.9% Normal Saline over 15–30 mins. _(Avoid excessive fluid overloading as starch solutions cause renal damage)_.

#### Step 3: Vasoactive Inotropic & Vasopressor Support

- **Noradrenaline (Norepinephrine):** First-line vasopressor of choice for profound hypotension (SBP <80 mmHg). Promotes α₁-mediated vasoconstriction to restore Mean Arterial Pressure (MAP >65 mmHg) with minimal tachycardia. Infusion rate: 0.05–0.5 μg/kg/min IV.
- **Dobutamine:** First-line inotropic agent for low cardiac output with SBP 80–90 mmHg. Stimulates β₁-receptors to increase myocardial contractility and cardiac output. Infusion rate: **2.5–10 μg/kg/min IV**.
- **Adrenaline (Epinephrine):** Reserved for refractory shock as combined inotrope/vasopressor.

#### Step 4: Emergency Revascularization

- **Immediate Primary PCI** of the culprit occluded coronary artery is the **definitive therapy** that breaks the downward spiral and improves survival in cardiogenic shock.

#### Step 5: Mechanical Circulatory Support (MCS)

- **Intra-Aortic Balloon Pump (IABP):** Placed in descending thoracic aorta via femoral artery. Inflates in diastole (augmenting coronary perfusion) and deflates in systole (reducing LV afterload).
- **Veno-Arterial Extracorporeal Membrane Oxygenation (VA-ECMO) or Impella:** Provides full mechanical cardiac and respiratory support in refractory cardiogenic shock.

---

## 10. Complications [⭐ High-Yield]

### A. Electrical Complications (Arrhythmias)

- **Ventricular Fibrillation (VF) & Ventricular Tachycardia (VT):** Occurs in 5–10% of patients within the first 48 hours; primary cause of out-of-hospital death. Requires immediate unsynchronized DC defibrillation.
- **Atrial Fibrillation (AF):** Secondary to atrial stretch or LV failure.
- **Sinus Bradycardia & AV Block:** Common in Inferior MI (RCA involvement). Complete AV block in Anterior MI reflects extensive dual bundle branch destruction (poor prognosis; requires temporary cardiac pacing).

### B. Mechanical Complications (Typically Days 3–7) [⭐ High-Yield]

1. **Free Wall Rupture:** Produces acute hemopericardium and cardiac tamponade with electromechanical dissociation (pulseless electrical activity). Rapidly fatal.
2. **Ventricular Septal Defect (VSD) Rupture:** Produces acute biventricular failure, a harsh new pansystolic murmur with thrill at the lower left sternal border.
3. **Papillary Muscle Rupture:** Acute destruction of posteromedial papillary muscle (RCA supply) causing severe acute Mitral Regurgitation and sudden pulmonary edema.

### C. Hemodynamic & Inflammatory Complications

- **Right Ventricular Infarction (RVMI):** Characterized by hypotension, clear lung fields, and markedly elevated JVP.
- **Early Pericarditis:** Positional friction rub occurring on Days 2–3.
- **Dressler Syndrome:** Autoimmune pericarditis, pleuritis, and fever occurring 2–10 weeks post-MI.
- **Ventricular Aneurysm:** Persistent ST elevation >6 weeks post-MI with mural thrombus formation.

---

## 11. Prognosis

Overall hospital mortality for AMI is ~7–8% (higher in STEMI than NSTEMI). One-third of STEMI patients die out-of-hospital within 1 hour due to VF. In-hospital 28-day survival for patients reaching medical care exceeds 85%.

---

## 12. Dosage Rule (Core Pharmacotherapy in First 24 Hours)

### 1. Tenecteplase (TNK-tPA)

- **Mechanism of Action:** (KDT Textbook p. 675). Recombinant fibrin-specific plasminogen activator. Catalyzes the conversion of fibrin-bound plasminogen into active plasmin, dissolving the occlusive intravascular thrombus.
- **Dose:** **0.5 mg/kg** single IV bolus (maximum 50 mg) based on body weight.
- **Dosage / Route:** Intravenous bolus injected over 10 seconds.
- **Frequency:** Single administration.
- **Features:** Highest fibrin selectivity; rapid onset; drug of choice for pre-hospital/emergency department thrombolysis when primary PCI is unavailable.
- **Side Effects:** Major systemic hemorrhage, intracranial hemorrhage (~0.5–1%), hypotension.
- **When to Start / Stop:** Administer within 12 hours of STEMI onset (door-to-needle <30 mins). Contraindicated in active internal bleeding, prior hemorrhagic stroke, recent major surgery (<3 weeks), or aortic dissection.

### 2. Aspirin (Acetylsalicylic Acid)

- **Mechanism of Action:** (KDT Textbook p. 680). Irreversibly acetylates COX-1 enzyme in platelets, blocking Thromboxane A₂ (TXA₂) synthesis and platelet aggregation.
- **Dose:** Loading dose **300–325 mg PO** (chewable non-enteric); maintenance **75–100 mg PO OD**.
- **Dosage / Route:** Oral (swallowed/chewed).
- **Frequency:** Single loading dose, then once daily.
- **Features:** Reduces relative 30-day mortality by 25%.
- **Side Effects:** Dyspepsia, gastric ulceration, bleeding.
- **When to Start / Stop:** Start immediately at presentation; continue maintenance indefinitely.

### 3. Ticagrelor

- **Mechanism of Action:** (KDT Textbook p. 676). Cyclopentyltriazolopyrimidine that reversibly binds and blocks the platelet P2Y₁₂ ADP purinergic receptor, preventing ADP-mediated platelet activation.
- **Dose:** Loading dose **180 mg PO**; maintenance **90 mg PO BD**.
- **Dosage / Route:** Oral.
- **Frequency:** Twice daily maintenance.
- **Features:** Faster, more potent, and more consistent P2Y₁₂ inhibition than Clopidogrel; reduces overall mortality (PLATO trial).
- **Side Effects:** Bleeding, dyspnoea, ventricular pauses, hyperuricaemia.
- **When to Start / Stop:** Start immediately at presentation alongside Aspirin (DAPT) for up to 12 months.

### 4. Atorvastatin

- **Mechanism of Action:** (KDT Textbook p. 682). Competitive HMG-CoA reductase inhibitor; upregulates hepatic LDL receptors and stabilizes vulnerable atheromatous plaques.
- **Dose:** **80 mg PO OD**.
- **Dosage / Route:** Oral.
- **Frequency:** Once daily at night.
- **Features:** High-intensity statin therapy reduces major adverse cardiac events (MACE).
- **Side Effects:** Myalgia, raised liver transaminases, rhabdomyolysis.
- **When to Start / Stop:** Start high-dose within 24 hours of admission; continue indefinitely.

---

## 13. Diagram Guides

### Diagram 1 : Progression of Infarction & Myocardial Salvage Window

_(Reference in text: See Section 4 - Pathophysiology & Reperfusion)_

- **Type:** Line Graph / Time-Course Diagram.
- **Outline Shape to Draw:** Plot axes (Y-axis: Extent of Myocardial Salvage / Necrosis %; X-axis: Time from Ischaemia Onset in Hours).
- **Labels in Order:**
    1. **Reversible Ischaemic Phase (0–30 mins):** 100% salvageable myocardium.
    2. **Irreversible Phase Onset (30 mins):** Cardiomyocyte necrosis initiates in subendocardium.
    3. **Golden Hours (1–2 hours):** Steep decline in salvageable myocardium (Primary PCI / Thrombolysis yields >80% salvage).
    4. **Completed Transmural Infarct (6–12 hours):** Only 1/6th of myocardium remains salvageable.
- **Extra Mark Annotation:** _"Reperfusion within the 'golden hour' (first 60 minutes) achieves maximum myocardial salvage and dramatically reduces cardiogenic shock mortality."_.

---

### Diagram 2 : The Downward Spiral of Cardiogenic Shock

_(Reference in text: See Section 9 - Cardiogenic Shock)_

- **Type:** Interconnected Cyclic Flowchart.
- **Outline Shape to Draw:** Circular loop of connected boxes showing positive feedback worsening.
- **Labels in Order:**
    1. **Severe LV Systolic Damage (>40% Loss):** Depressed Cardiac Output & Stroke Volume.
    2. **Systemic Hypotension (SBP <90 mmHg):** Impaired Coronary Perfusion Pressure.
    3. **Elevated LVEDP / PCWP (>18 mmHg):** Pulmonary Capillary Congestion & Alveolar Edema.
    4. **Severe Hypoxaemia & Compensatory Vasoconstriction:** Increased Afterload & Worsening Myocardial Ischaemia.
- **Connections:** Arrows connecting Box 4 back into Box 1 forming a closed vicious cycle.
- **Extra Mark Annotation:** _"Emergency Primary PCI breaks the downward spiral by restoring coronary arterial flow to viable stunned myocardium."_.

---

## 14. Mnemonic / Memory Palace

### Mnemonic for Emergency STEMI Management: "MONA BASH"

- **M** — **M**orphine (3–5 mg IV for pain and anxiety)
- **O** — **O**xygen (Supplemental only if SpO₂ <90%)
- **N** — **N**itrates (Sublingual GTN 0.5 mg)
- **A** — **A**spirin (300 mg chewable loading dose)
- **B** — **B**eta-Blocker (Metoprolol within 24h)
- **A** — **A**CE Inhibitor (Enalapril/Ramipril within 24h)
- **S** — **S**tatin (Atorvastatin 80 mg)
- **H** — **H**eparin / LMWH (Enoxaparin 30 mg IV bolus)

### Memory Palace: "The Emergency Cardiac Resuscitation Bay"

Visualize walking through a hospital trauma room:

1. **The Entrance Door (Aspirin & Ticagrelor):** A paramedic handing two tablets (**Aspirin 300 mg + Ticagrelor 180 mg**) to a sweating patient clutching his chest (**DAPT Loading**).
2. **The Oxygen Mask & Syringe (Morphine):** A nurse attaching an oxygen monitor (**SpO₂ <90%**) and injecting a **Morphine 3 mg syringe** to quiet a roaring alarm (**Adrenergic drive reduction**).
3. **The Cath Lab Clock (Primary PCI <120 mins):** A massive digital wall clock counting down **120 minutes** as the patient is wheeled directly to the angiography suite (**Door-to-balloon target**).
4. **The Fibrinolytic Hose (Tenecteplase):** In a rural bay without PCI, a doctor injects a single 10-second bolus of **Tenecteplase (0.5 mg/kg)** to dissolve a red arterial clot.
5. **The Pressure Monitor & Noradrenaline Pump (Cardiogenic Shock):** In a hypotensive patient (BP 70/40 mmHg), a central line infusion of **Noradrenaline** and **Dobutamine** is started alongside an **IABP console** pulsing in time with the ECG.

---

## 15. Clinical Pearl

> **Clinical Pearl:** In any patient presenting with acute inferior wall STEMI (ST elevation in II, III, aVF), **ALWAYS record right-sided ECG leads (V₃R and V₄R) before administering Nitrates or Morphine!**Right Ventricular Infarction (RVMI) co-exists in ~30–50% of inferior MIs and creates strict preload dependency. Administering GTN or Morphine drops preload abruptly, precipitating severe, life-threatening hypotension and collapse. RV infarction requires aggressive **IV Normal Saline fluid loading** instead.

---

## 16. Exam Trap

### Exam Trap

- **The Mix-Up:** Administering Nitrates to a patient with chest pain who has taken a Phosphodiesterase-5 (PDE-5) inhibitor like **Sildenafil** within the past 24 hours.
- **Distinguishing Fact:** Nitrates stimulate cGMP synthesis while Sildenafil inhibits cGMP breakdown. Combining them causes massive cGMP accumulation, resulting in catastrophic, refractory hypotension, severe coronary hypoperfusion, and fatal cardiac collapse. Nitrates are **STRICTLY CONTRAINDICATED** within 24 hours of Sildenafil ingestion.

---

### Quick Revision

- **Definition & Biomarker:** Myocardial necrosis secondary to occlusive atherothrombosis; diagnosed by rise/fall of Cardiac Troponin I/T >99th percentile URL + ischaemic symptoms/ECG changes.
- **STEMI Reperfusion Target:** Primary PCI within 120 minutes (door-to-balloon) OR Thrombolysis with Tenecteplase (0.5 mg/kg) within 12 hours (door-to-needle <30 mins).
- **Core First 24-Hour Drugs:** Aspirin 300 mg + Ticagrelor 180 mg + Atorvastatin 80 mg + Enoxaparin + Beta-blocker + ACE Inhibitor.
- **Cardiogenic Shock Criteria:** Cardiac Index <2.2 L/min/m², SBP <90 mmHg, PCWP >18 mmHg; managed with fluid challenge, Noradrenaline, Dobutamine, and immediate Emergency PCI.
- **Mechanical Complications:** Free wall rupture, VSD, and Papillary muscle rupture occur typically between Days 3–7 when tissue friability is maximal.

---

### One-Line Exam Opener

> **Acute myocardial infarction is a life-threatening acute coronary syndrome triggered by atherothrombotic epicardial coronary occlusion, where rapid cardiomyocyte necrosis initiates within 20 minutes and demands immediate emergency reperfusion therapy via primary percutaneous coronary intervention or fibrinolysis to prevent acute heart failure, cardiogenic shock, and fatal ventricular arrhythmias.**

---

🧭 _Would you like to explore the step-by-step ECG localization criteria for specific coronary artery territories, or detail the diagnostic workup and surgical management for acute post-MI papillary muscle rupture?_