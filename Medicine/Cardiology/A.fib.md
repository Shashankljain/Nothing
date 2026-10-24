[[C16-Cardiology]]

# Atrial Fibrillation

## 1. Definition

**Atrial Fibrillation (AF)** is a supraventricular tachyarrhythmia characterized by rapid, uncoordinated, and chaotic atrial electrical activation at a rate of 350–600 bpm. This leads to total loss of effective atrial mechanical contraction ("atrial kick") and a characteristically "irregularly irregular" ventricular response (typically 100–160 bpm).

On 12-lead ECG, AF is diagnosed by the complete absence of distinct P waves, which are replaced by irregular, low-amplitude fibrillatory waves (f-waves), alongside irregularly irregular R-R intervals.

---

## 2. Etiology / Causes / Risk Factors [⭐ High-Yield]

AF can result from intrinsic cardiac pathology, systemic illness, or occur spontaneously in an otherwise normal heart.

### A. Cardiac Causes

1. **Coronary Artery Disease (CAD):** Acute myocardial infarction (MI) or chronic ischaemic heart disease.
2. **Valvular Heart Disease:** Rheumatic Mitral Valve Disease (Mitral Stenosis / Mitral Regurgitation) causes severe left atrial dilatation, making it the most potent structural trigger.
3. **Hypertension:** Long-standing elevated systemic pressure causing Left Ventricular Hypertrophy (LVH) and left atrial stretch.
4. **Sinoatrial Node Disease:** Sick Sinus Syndrome (Tachy-Brady Syndrome).
5. **Cardiomyopathies:** Dilated, Hypertrophic, or Restrictive Cardiomyopathy.
6. **Pericardial Disease:** Acute pericarditis or constrictive pericarditis.
7. **Congenital Heart Disease:** Atrial Septal Defect (ASD).

### B. Non-Cardiac / Systemic Causes

1. **Hyperthyroidism / Thyrotoxicosis:** Excess thyroid hormone increases automaticity and atrial sensitivity to catecholamines; AF occurs in ~10% of thyrotoxic patients.
2. **Alcohol Excess:** Acute heavy binge drinking ("Holiday Heart Syndrome") or chronic alcoholism.
3. **Acute Respiratory Pathology:** Pneumonia, Chronic Obstructive Pulmonary Disease (COPD), or Pulmonary Embolism.
4. **Obstructive Sleep Apnoea (OSA), Chronic Kidney Disease (CKD), and Psoriasis.**
5. **Electrolyte Disturbances:** Hypokalaemia and Hypomagnesaemia.

### C. Lone Atrial Fibrillation

- Defined as AF occurring in patients <60 years of age without clinical or echocardiographic evidence of structural cardiac or cardiopulmonary disease. Accounts for ~50% of paroxysmal and ~20% of persistent AF cases.

---

## 3. Classification

```
                          ┌──────────────────────────────────────────┐
                          │    ATRIAL FIBRILLATION CLASSIFICATION    │
                          └────────────────────┬─────────────────────┘
                                               │
             ┌─────────────────────────────────┼─────────────────────────────────┐
             ▼                                 ▼                                 ▼
┌──────────────────────────┐      ┌──────────────────────────┐      ┌──────────────────────────┐
│      PAROXYSMAL AF       │      │      PERSISTENT AF       │      │       PERMANENT AF       │
│ Self-terminating <7 days │      │ Lasts >7 days; requires  │      │ Accepted by patient/MD;  │
│  (usually within 48 hrs) │      │ cardioversion to restore │      │ rate control accepted    │
└──────────────────────────┘      └──────────────────────────┘      └──────────────────────────┘
```

- **Paroxysmal AF:** Recurrent episodes that terminate spontaneously or with intervention within 7 days (most commonly <48 hours).
- **Persistent AF:** Continuous AF that sustained >7 days, requiring electrical or pharmacological cardioversion for termination. (_Long-standing persistent AF:_ continuous AF >1 year).
- **Permanent AF:** Continuous AF in which cardioversion has failed or is not attempted by mutual agreement; management focuses strictly on rate control.
- **Valvular vs Non-Valvular AF:**
    - _Valvular AF:_ AF secondary to moderate-to-severe rheumatic mitral stenosis or in the presence of mechanical heart valves.
    - _Non-Valvular AF:_ AF in the absence of severe rheumatic mitral stenosis or mechanical prosthetic valves.

---

## 4. Pathophysiology (with Flowchart) [⭐ High-Yield]

### Pathogenetic Sequence

1. **Ectopic Triggers:** Episodes are initiated by rapid, spontaneous bursts of ectopic impulses originating from myocardial muscle sleeves surrounding the **pulmonary veins** or diseased atrial tissue.
2. **Multiple Re-entry Circuits:** Sustained re-entry occurs as multiple wavelets loop simultaneously around electrophysiologically inhomogeneous atrial tissue.
3. **Electrical and Structural Remodelling:**
    - _Electrical Remodelling:_ Within hours of AF onset, short-term electrical changes cause progressive shortening and spatial dispersion of atrial refractory periods ("AF begets AF").
    - _Structural Remodelling:_ Sustained AF over months induces atrial dilatation, cell hypertrophy, and interstitial fibrosis, locking the atria into permanent AF.
4. **Hemodynamic Compromise:**
    - **Loss of Atrial Kick:** Loss of coordinated atrial contraction reduces ventricular end-diastolic filling and decreases cardiac output by 20–30%.
    - **Rapid Ventricular Rate:** Irregular, fast impulse transmission through the AV node shortens diastolic filling time, further lowering stroke volume and aggravating heart failure.
    - **Stasis & Thromboembolism:** Uncoordinated atrial quivering leads to blood stasis, particularly within the **left atrial appendage**, promoting mural thrombus formation.

### Pathophysiology Flowchart

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px

A[Etiological Triggers: HTN, CAD, Mitral Stenosis, Thyrotoxicosis]:::primary --> B[Atrial Stretch, Dilatation & Interstitial Fibrosis]:::primary
B --> C[Ectopic Firing from Pulmonary Veins + Multiple Re-entry Circuits]:::warning
C --> D[Chaotic Uncoordinated Atrial Activation: 350-600 bpm]:::danger

D --> E[Loss of Atrial Kick & Rapid Irregular AV Nodal Conduction]:::danger
E --> F[Reduced Diastolic Filling & Decreased Cardiac Output]:::danger

F -->|Atrial Stasis in Appendage| G[Left Atrial Thrombus Formation → Systemic Embolism / Stroke]:::danger
F -->|Persistent Tachycardia| H[Tachycardiomyopathy & Acute / Chronic Heart Failure]:::danger

G --> I{Triple Management Strategy}:::warning
H --> I

I -->|Ventricular Rate Control| J[Beta-Blocker / Verapamil / Diltiazem / Digoxin]:::success
I -->|Rhythm Restoration| K[Cardioversion / Flecainide / Amiodarone / Catheter Ablation]:::success
I -->|Stroke Prevention| L[NOACs: Dabigatran / Rivaroxaban OR Warfarin]:::success
```

---

## 5. Clinical Features

### A. Symptoms

- **Palpitations:** Sensation of rapid, fluttering, or irregular heart beat.
- **Exertional Dyspnoea & Fatigue:** Caused by loss of atrial kick and elevated left atrial pressure.
- **Lightheadedness, Dizziness, or Syncope:** Secondary to transient reduction in cerebral perfusion from rapid ventricular rate.
- **Angina / Chest Discomfort:** Induced by increased myocardial oxygen demand in patients with underlying CAD.
- **Asymptomatic:** Common in elderly individuals; often discovered incidentally or presenting directly with an embolic stroke.

### B. Physical Signs

- **Pulse:** "Irregularly irregular" rhythm with variable pulse volume.
- **Pulse Deficit:** Difference between apical heart rate (auscultated) and radial pulse rate >10 beats/min, because premature, poorly-filled ventricular contractions fail to generate a palpable peripheral pulse wave.
- **Jugular Venous Pulse (JVP):** Absence of the normal 'a' wave (due to loss of presystolic atrial contraction).
- **Heart Sounds:** Variable intensity of the First Heart Sound (S₁).

---

## 6. Diagnosis / Investigations

1. **12-Lead Electrocardiogram (ECG) [Gold Standard]:**
    - Absence of discrete P waves.
    - Presence of rapid, irregular fibrillatory f-waves (variable amplitude and shape).
    - Irregularly irregular QRS complexes.
    - _6-Second Marker Rule:_ Heart Rate = Number of QRS complexes in 30 large ECG boxes × 10.
2. **Transthoracic Echocardiography (TTE):**
    - Evaluates left atrial size (LA diameter >4 cm predicts chronicity/poor cardioversion success), Left Ventricular Ejection Fraction (LVEF), and valvular lesions (mitral stenosis).
3. **Transoesophageal Echocardiography (TEE):**
    - High sensitivity to detect or rule out left atrial appendage thrombus prior to planned cardioversion.
4. **Thyroid Function Tests (Serum TSH, Free T₃, T₄):** Mandatory in all new-onset AF cases to exclude occult thyrotoxicosis.
5. **Serum Electrolytes, Renal Function & Blood Count:** Identifies hypokalaemia, hypomagnesaemia, renal impairment (guides anticoagulant dosing), and anaemia.

---

## 7. Differential Diagnosis

|Feature|Atrial Fibrillation (AF)|Atrial Flutter (AFl)|Multifocal Atrial Tachycardia (MAT)|AVNRT / PSVT|
|:--|:--|:--|:--|:--|
|**Atrial Rate**|350–600 bpm|250–350 bpm|100–150 bpm|150–250 bpm|
|**Rhythm**|Irregularly irregular|Regularly irregular or regular|Irregular|Strictly regular|
|**P Wave Morphology**|Absent (replaced by f-waves)|"Saw-tooth" flutter waves|≥3 distinct P-wave morphologies|Hidden or retrogradely inverted|
|**Primary Association**|HTN, CAD, Valvular Disease|Right atrial macro-reentry|Severe COPD / Theophylline toxicity|Re-entry in AV node|

---

## 8. Treatment / Management (Rationale & Specific Drug Details) [⭐ High-Yield]

Management revolves around three primary pillars: **(1) Rate vs Rhythm Control**, **(2) Hemodynamic Stabilization**, and **(3) Stroke Thromboprophylaxis**.

```
                     ┌──────────────────────────────────────────────┐
                     │     ACUTE / NEW-ONSET ATRIAL FIBRILLATION    │
                     └──────────────────────┬───────────────────────┘
                                            │
               ┌────────────────────────────┴────────────────────────────┐
               ▼                                                         ▼
┌──────────────────────────────┐                          ┌──────────────────────────────┐
│   HEMODYNAMICALLY UNSTABLE   │                          │    HEMODYNAMICALLY STABLE    │
│  (BP <90 mmHg, Angina, HF)   │                          │  (Select Rate vs Rhythm Rx)  │
└──────────────┬───────────────┘                          └──────────────┬───────────────┘
               │                                                         │
               ▼                                    ┌────────────────────┴────────────────────┐
┌──────────────────────────────┐                    ▼                                         ▼
│  Synchronised DC Cardioversion │      ┌───────────────────────────┐             ┌───────────────────────────┐
│     (Start 100 J → 200 J)    │      │       RATE CONTROL        │             │      RHYTHM CONTROL       │
└──────────────────────────────┘      │  Target Rest HR 60-80 bpm │             │ (Paroxysmal / Young / HF) │
                                      │ Beta-Blocker / Verapamil /│             │ Cardioversion / Flecainide│
                                      │    Diltiazem / Digoxin    │             │   Amiodarone / Ablation   │
                                      └───────────────────────────┘             └───────────────────────────┘
```

---

### A. Emergency Management (Unstable Patient)

- **Indication:** AF with hemodynamic instability (Systolic BP <90 mmHg, acute pulmonary oedema, severe angina, or rapid ventricular response in WPW syndrome).
- **Action:** Immediate **Synchronised DC Cardioversion** starting at 100 J (up to 200 J) under short intravenous anaesthesia.

---

### B. Pharmacotherapy: Rate Control vs Rhythm Control

#### 1. Rate Control Drugs (First-Line for Permanent / Elderly AF)

##### a. Beta-Adrenoceptor Blockers (Metoprolol / Bisoprolol / Propranolol)

- **Mechanism of Action:** (KDT Textbook p. 145, 573; Davidson p. 479). Selective β₁ or non-selective β-blockade → depresses SA node automaticity and slows AV nodal conduction velocity, prolonging the AV effective refractory period (ERP).
- **Dose & Route:**
    - **Metoprolol:** 25–100 mg PO BD (or 5 mg IV over 2 mins up to 15 mg).
    - **Bisoprolol:** 2.5–10 mg PO OD.
    - **Propranolol:** 10–40 mg PO TDS (or 1 mg IV over 2 mins up to 5 mg).
- **Frequency:** OD to TDS.
- **Features:** First-line rate control agent during exertion, sympathetic stress, CAD, or hypertension.
- **Side Effects:** Bradycardia, hypotension, bronchospasm, fatigue, cold extremities.
- **When to Start / Stop:** Avoid in active asthma or acute uncompensated heart failure.

##### b. Non-Dihydropyridine Calcium Channel Blockers (Verapamil / Diltiazem)

- **Mechanism of Action:** (KDT Textbook p. 580; Davidson p. 480). Inhibits L-type Ca²⁺ channels in AV nodal tissue → depresses Ca²⁺-dependent slow-channel conduction and extends AV nodal ERP.
- **Dose & Route:**
    - **Verapamil:** 40–120 mg PO TDS (or 5–10 mg slow IV over 2 mins).
    - **Diltiazem:** 30–60 mg PO TDS/QID (or 25 mg slow IV infusion).
- **Frequency:** TDS / QID.
- **Features:** Highly effective rate control in non-HF patients.
- **Side Effects:** Constipation (verapamil), bradycardia, hypotension, aggravation of HF.
- **When to Start / Stop:** **Contraindicated in HFrEF (LVEF <35%)** and in combination with IV β-blockers (risk of fatal AV block/asystole).

##### c. Cardiac Glycoside (Digoxin)

- **Mechanism of Action:** (KDT Textbook p. 559, 560; Davidson p. 481). Direct and vagomimetic activation → slows AV conduction and prolongs AV nodal ERP; weakly inhibits Na⁺/K⁺-ATPase.
- **Dose & Route:** Maintenance 0.125–0.25 mg PO OD (IV loading 0.5–1.0 mg).
- **Frequency:** Once daily.
- **Features:** Rate control drug of choice when **AF co-exists with Heart Failure** or hypotension. Poor at controlling heart rate during exercise.
- **Side Effects:** Anorexia, nausea, vomiting, xanthopsia (yellow-green vision), AV block, ventricular arrhythmias.
- **When to Start / Stop:** Reduce dose in renal impairment and elderly.

---

#### 2. Rhythm Control Drugs (For Paroxysmal / Persistent AF)

##### a. Flecainide / Propafenone (Class Ic Antiarrhythmics)

- **Mechanism of Action:** (KDT Textbook p. 573; Davidson p. 481). Potent open-state Na⁺ channel blockers → markedly depresses Phase 0 upstroke velocity (dV/dt) and slows intra-atrial conduction.
- **Dose & Route:**
    - **Flecainide:** 50–100 mg PO BD (or 2 mg/kg IV over 10–30 mins).
    - **Propafenone:** 150 mg PO TDS to 300 mg PO BD.
- **Features:** Drug of choice for pharmacological cardioversion and "Pill-in-the-pocket" strategy in patients **without structural heart disease**.
- **Side Effects:** Proarrhythmic risk, conversion to 1:1 conducted atrial flutter, dizziness.
- **When to Start / Stop:** **Strictly contraindicated in CAD, previous MI, or LV dysfunction** (increases mortality).

##### b. Amiodarone (Class III Antiarrhythmic) - rate + rhythm control

- **Mechanism of Action:** (KDT Textbook p. 578; Davidson p. 480). Multichannel blocker (K⁺, Na⁺, Ca²⁺) and non-competitive α/β-blocker → prolongs action potential duration and effective refractory period across all cardiac tissues.
- **Dose & Route:**
    - **IV Loading:** 150 mg IV over 10 mins, then 1 mg/min for 6 hours, then 0.5 mg/min for 18 hours.
    - **Oral Maintenance:** 100–200 mg PO OD (after loading with 600–1200 mg/day for 1–2 weeks).
- **Frequency:** Once daily.
- **Features:** Most effective rhythm control drug in patients with **structural heart disease or heart failure**.
- **Side Effects:** Corneal microdeposits, pulmonary fibrosis, hypo/hyperthyroidism, photosensitivity, hepatotoxicity, peripheral neuropathy.
- **When to Start / Stop:** Monitor LFTs, TFTs, and CXR baseline and periodically.

---

### C. Anticoagulation & Stroke Prevention (Thromboprophylaxis) [⭐ High-Yield]

#### 1. Stroke Risk Stratification: CHA₂DS₂-VASc Score

Indicated for all non-valvular AF cases.

|Parameter|Condition|Points|
|:--|:--|:--|
|**C**|Congestive Heart Failure / LV dysfunction|1 point|
|**H**|Hypertension history|1 point|
|**A₂**|Age ≥75 years|**2 points**|
|**D**|Diabetes Mellitus|1 point|
|**S₂**|Stroke / TIA / Thromboembolism history|**2 points**|
|**V**|Vascular Disease (prior MI, PAD, aortic plaque)|1 point|
|**A**|Age 65–74 years|1 point|
|**Sc**|Sex category Female|1 point|

- **Treatment Threshold:** Score = 0 (males) / 1 (females) → No anticoagulation. **Score ≥2 (males) / ≥3 (females) → Mandatory long-term oral anticoagulation**.

#### 2. Bleeding Risk Assessment: HAS-BLED Score

- Parameters: **H**ypertension (>160 mmHg), **A**bnormal Liver/Renal function (1 pt each), **S**troke history, **B**leeding history, **L**abile INR, **E**lderly (>65 yrs), **D**rugs/Alcohol (1 pt each).
- Score ≥3 indicates high bleeding risk, requiring correction of modifiable risk factors and frequent monitoring.

#### 3. Choice of Anticoagulant Agents

1. **Non-Vitamin K Oral Anticoagulants (NOACs / DOACs): First-Line for Non-Valvular AF**.
    - **Dabigatran:** Direct Thrombin Inhibitor — 150 mg PO BD.
    - **Rivaroxaban:** Factor Xa Inhibitor — 20 mg PO OD.
    - **Apixaban:** Factor Xa Inhibitor — 5 mg PO BD.
2. **Vitamin K Antagonist (Warfarin):**
    - Mandatory choice for **Valvular AF** (Mitral Stenosis / Mechanical Valves) and AF with End-Stage Renal Disease (ESRD).
    - Dose: 2–5 mg PO OD, adjusted to maintain **Target INR 2.0–3.0**.
3. _Aspirin / Clopidogrel:_ **Not recommended** for stroke prophylaxis in AF due to inferior efficacy and comparable major bleeding risk.

---

## 9. Complications [⭐ High-Yield]

1. **Thromboembolism & Ischaemic Stroke:** Blood stasis in left atrial appendage leads to mural thrombus formation → dislodges to produce embolic stroke (15% of all strokes), transient ischaemic attack (TIA), or systemic visceral/limb embolism.
2. **Tachycardiomyopathy & Heart Failure:** Sustained fast, uncoordinated ventricular response causes LV systolic dysfunction and dilated cardiomyopathy.
3. **Acute Pulmonary Oedema:** Sudden onset of AF in Mitral Stenosis abruptly shortens diastolic filling time, causing massive left atrial pressure spike and pulmonary capillary flooding.
4. **Anticoagulation-Induced Major Bleeding:** Intracranial haemorrhage or severe gastrointestinal bleeding.

---

## 10. Mnemonic / Memory Palace

### Mnemonic for Etiology: "PIRATES"

- **P** — **P**ericarditis / **P**ulmonary Embolism
- **I** — **I**schaemic Heart Disease (MI / CAD)
- **R** — **R**heumatic Valvular Disease (Mitral Stenosis)
- **A** — **A**lcohol excess ("Holiday Heart")
- **T** — **T**hyrotoxicosis
- **E** — **E**lectrolyte imbalance (Hypokalaemia)
- **S** — **S**ick Sinus Syndrome / Systemic Hypertension

---

## 11. Clinical Pearl

> **Clinical Pearl:** In patients presenting with persistent AF >48 hours duration, **NEVER attempt elective cardioversion** without prior 3 to 4 weeks of continuous effective oral anticoagulation (Target INR 2.0–3.0) or a Transoesophageal Echo (TEE) excluding a left atrial thrombus! Reversion to sinus rhythm restores mechanical atrial contraction, which can instantly dislodge a stagnant atrial appendage clot into the systemic circulation, causing a massive embolic stroke.

---

## 12. Exam Trap

### Exam Trap

- **The Mix-Up:** Choosing Digoxin for rapid rate control in young active patients or during acute exertional AF episodes.
- **Distinguishing Fact:** Digoxin slows AV conduction primarily by boosting central vagal tone. During exercise or acute adrenergic stress, elevated sympathetic tone completely overrides vagal activity, rendering digoxin ineffective for exertional rate control. **Beta-blockers or Diltiazem/Verapamil** are far superior for controlling exertional heart rate in AF.

---

## 13. Diagram Guide

### Diagram 1 : ECG Features of Atrial Fibrillation

_(Reference in text: See Section 1 & Section 6)_

- **Type:** Labeled Rhythm Strip Diagram.
- **Outline Shape to Draw:** Standard single-channel ECG strip baseline showing QRS complexes.
- **Labels in Order:**
    1. **Absence of P waves:** Flat or wavy baseline preceding QRS complexes.
    2. **Fibrillatory waves (f-waves):** Rapid, low-amplitude, chaotic baseline oscillations (350–600/min).
    3. **Irregularly Irregular R-R Intervals:** Variable spacing between consecutive R wave spikes.
    4. **Narrow QRS Complexes:** Normal ventricular depolarization architecture (<0.12s) unless bundle branch block co-exists.
- **Extra Mark Annotation:** _"Irregularly irregular R-R intervals with absence of P waves and presence of fibrillatory waves are pathognomonic for Atrial Fibrillation."_.

```
  f-waves (no P waves)     QRS            QRS                   QRS
   /\/\/\/\/\/\/\/\/\/\ ┌───┐            ┌───┐                 ┌───┐
  ─┴────────────────────┤   ├────────────┤   ├─────────────────┤   ├─
                        └───┘            └───┘                 └───┘
  │← ── Short R-R ── →│← ───── Long R-R ───── →│← ─ Medium R-R ─ →│
```

---

### Quick Revision

- **Definition & ECG:** Supraventricular tachyarrhythmia with chaotic atrial rate (350–600 bpm), irregularly irregular R-R intervals, and absence of P waves.
- **Etiology:** Hypertension, CAD, Rheumatic Mitral Stenosis, Thyrotoxicosis, Alcohol ("PIRATES").
- **Rate Control:** Beta-blockers or Verapamil/Diltiazem (first-line); Digoxin preferred only in co-existing heart failure.
- **Rhythm Control:** Flecainide/Propafenone (no structural disease) or Amiodarone (structural heart disease/HF).
- **Thromboembolism Risk:** Evaluated by **CHA₂DS₂-VASc Score** (Score ≥2 in males, ≥3 in females requires NOACs or Warfarin).

---

### One-Line Exam Opener

> **Atrial fibrillation is a common supraventricular tachyarrhythmia characterized by chaotic uncoordinated atrial activation and an irregularly irregular ventricular response, whose primary clinical dangers stem from tachycardiomyopathy-induced heart failure and left atrial appendage thromboembolism causing ischaemic stroke.**

---

🧭 _Would you like to explore the step-by-step catheter ablation procedure for pulmonary vein isolation, or review the detailed management algorithm for Wolff-Parkinson-White (WPW) syndrome presenting with pre-excited atrial fibrillation?_