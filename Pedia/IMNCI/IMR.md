[[C32-IMNCI]]
#(Mark-Weightage Calibration: 5 Marks)

# Infant Mortality Rate (IMR) — Definition, Factors & Reduction Measures [⭐ High-Yield]

### 1. Definition [⭐ High-Yield]

- **Infant Mortality Rate (IMR)** is defined as the total number of deaths of infants under **1 year of age** (<365 days) per **1000 live births** in a given population during a specific year.
- It serves as the single most sensitive demographic indicator of a nation's overall health status, socioeconomic development, quality of maternal-child healthcare, and environmental sanitation.

\[\text{Infant Mortality Rate (IMR)} = \frac{\text{Number of deaths of infants } <1 \text{ year of age in a given year}}{\text{Total number of live births in the same year}} \times 1000\]

- **Current Epidemiological Indices in India (SRS Data)**:
    - **Infant Mortality Rate (IMR)**: **28 per 1000 live births**.
    - **Under-5 Mortality Rate (U5MR)**: **32 per 1000 live births** (IMR accounts for **~87%** of total under-5 deaths).
    - **Neonatal Mortality Rate (NMR)**: **20 per 1000 live births** (accounts for **71%** of total infant deaths).
    - **Early Neonatal Mortality Rate (ENMR)**: **15 per 1000 live births** (accounts for **75%** of NMR).
    - **Late Neonatal Mortality Rate (LNMR)**: **5 per 1000 live births** (accounts for **25%** of NMR).
    - **Post-Neonatal Mortality Rate (PNMR)**: **8 per 1000 live births** (accounts for **29%** of total infant deaths).

---

### 2. Classification / Sub-Components [⭐ High-Yield]

Infant mortality is divided chronologically into two distinct anatomical time-windows:

1. **Neonatal Mortality (Birth to 28 Days)** [⭐ High-Yield]:
    - **Early Neonatal Period (0 to 6 Days)**: **40% of all neonatal deaths occur within the first 24 hours of life**, and **75%** occur within the first week.
    - **Late Neonatal Period (7 to 28 Days)**: Accounts for the remaining **25%** of neonatal deaths.
2. **Post-Neonatal Mortality (28 Days to 1 Year)**:
    - Deaths occurring between **29 days and 365 days** of life, predominantly driven by environmental, nutritional, and infectious etiologies.

---

### 3. Etiology / Factors Affecting IMR [⭐ High-Yield]

Infant mortality in India is multifactorial, resulting from a interplay of direct medical, maternal, nutritional, and socioeconomic risk factors:

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[Determinants & Risk Factors of IMR]:::primary --> B1[Neonatal Causes 71% of IMR]:::danger
A --> B2[Post-Neonatal Causes 29% of IMR]:::warning
A --> B3[Maternal & Environmental Factors]:::primary

B1 --> C1[Prematurity & LBW 44%, Infections/Sepsis 20%, Birth Asphyxia 19%, Anomalies 11%]:::danger
B2 --> C2[Pneumonia 11%, Diarrhea 9%, Measles, Malaria, Malnutrition]:::warning
B3 --> C3[Maternal Anemia 57%, Young Age, Lack of SBA, Poverty, Unsafe Water]:::primary

C1 & C2 & C3 --> D[Infant Death <1 Year]:::danger
```

#### A. Direct Neonatal Causes (0 to 28 Days) — Contributes 71% to IMR [⭐ High-Yield]

1. **Prematurity & Low Birth Weight (LBW)** (**44%** of neonatal deaths):
    - LBW infants (<2500 g) constitute nearly one-third of all births in India but account for **three-fourths of total neonatal deaths**.
    - Preterm infants (<37 weeks) succumb to **Respiratory Distress Syndrome (RDS)** due to surfactant deficiency, **Intraventricular Hemorrhage (IVH)**, and severe **hypothermia**.
2. **Neonatal Sepsis & Infections** (**20%** of neonatal deaths):
    - Early-onset sepsis (<72 hours) and late-onset sepsis (>72 hours) caused by _**Klebsiella pneumoniae**_, _Acinetobacter_, and _Staphylococcus aureus_.
3. **Perinatal / Birth Asphyxia & Trauma** (**19%** of neonatal deaths):
    - Hypoxic Ischemic Encephalopathy (HIE) resulting from failure to establish spontaneous respiration within the **"Golden Minute"** of birth.
4. **Congenital Anomalies** (**11%** of neonatal deaths):
    - Neural tube defects (NTDs), congenital heart diseases (VSD, TGV), and structural malformations.

#### B. Direct Post-Neonatal Causes (28 Days to 1 Year) — Contributes 29% to IMR

1. **Acute Respiratory Infections (Pneumonia)** (**11%** of under-5 mortality).
2. **Diarrheal Diseases & Dehydration** (**9%** of under-5 mortality).
3. **Vaccine-Preventable Diseases (VPDs)**: Measles, pertussis, diphtheria, and Hib meningitis.
4. **Underlying Undernutrition**: An underlying contributing factor associated with **45% of all under-5 deaths**.

#### C. Maternal, Socioeconomic & Environmental Factors

- **Maternal Anemia & Malnutrition**: Over **57%** of pregnant women in India suffer from anemia, leading to intrauterine growth restriction (IUGR) and LBW.
- **Maternal Age & Parity**: High risk in teenage pregnancies (<18 years) and elderly multiparas.
- **Delivery Circumstances**: Home deliveries without Skilled Birth Attendants (SBA) and lack of emergency obstetric care.
- **Socio-cultural Determinants**: Female gender bias, illiteracy, poverty, lack of exclusive breastfeeding, early introduction of diluted top feeds, and poor environmental sanitation.

---

### 4. Pathophysiology [⭐ High-Yield]

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[Maternal Anemia / Poverty / Unsafe Delivery]:::primary --> B[LBW <2.5 kg / Prematurity <37 wks]:::warning
B --> C{Exposure to Postnatal Insults}:::warning
C -->|Inadequate Resuscitation| D[Hypoxic Ischemic Encephalopathy HIE]:::danger
C -->|Cold Exposure / Lack of KMC| E[Severe Hypothermia & Acidosis]:::danger
C -->|Pathogen Ingress / Poor Hygiene| F[Sepsis, Pneumonia & Severe Diarrhea]:::danger

D --> G1[Multiorgan Failure & Brain Death]:::danger
E --> G2[Sclerema, Hypoglycemia & Collapse]:::danger
F --> G3[Septic / Hypovolemic Shock & Apnea]:::danger

G1 & G2 & G3 --> H[Infant Collapse & Death <1 Year]:::danger
```

---

### 5. Clinical Features / Early Danger Signs in Infants

- **Respiratory Distress**: Tachypnea (respiratory rate >60 breaths/min in neonates, >50 in infants 2–12 months), severe chest indrawing, grunting, and central cyanosis.
- **Neurological Depression**: Lethargy (no movement or movement only when stimulated), inability to suck or feed, convulsions, and abnormal tone (hypotonia).
- **Thermal Instability**: Cold stress / hypothermia (axillary temperature <35.5°C) or fever (>37.5°C).
- **Infection Markers**: Umbilical redness/pus, severe skin pustules, abdominal distension, and persistent vomiting.

---

### 6. Diagnosis / Surveillance & Audit

- **Sample Registration System (SRS)**: Primary national demographic survey tracking IMR trends in India.
- **Child Death Review (CDR) / MPDSR**: Mandatory verbal autopsy and facility-based audits to identify cause of death and rectify health-system delays.
- **Sepsis Screen & Cultures**: Micro-ESR ≥15 mm in 1st hr, CRP >1 mg/dL, TLC <5000/mm³, ANC <1800/mm³, and blood culture.

---

### 7. Differential Diagnosis

|Feature|**Neonatal Mortality (<28 Days)** [⭐ High-Yield]|**Post-Neonatal Mortality (28 Days to 1 Year)**|
|:--|:--|:--|
|**Contribution to IMR**|**71%** (NMR = 20 per 1000)|**29%** (PNMR = 8 per 1000)|
|**Primary Causes**|Prematurity (44%), Birth Asphyxia (19%), Neonatal Sepsis (20%)|Pneumonia (11%), Diarrheal diseases (9%), Malnutrition, VPDs|
|**Primary Underlying Factor**|Maternal anemia, pre-eclampsia, lack of EmONC|Unsafe water, poor feeding practices, unimmunized status|
|**Main Health Interventions**|NSSK (Golden Minute), KMC, SNCU / NBSU, FBNC|UIP Immunization, IMNCI, IYCF, ORS + Zinc, POSHAN Abhiyaan|

---

### 8. Treatment / Measures to Reduce IMR in India [⭐ High-Yield]

The Government of India implements an integrated continuum-of-care framework across reproductive, maternal, newborn, and child health domains:

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[National Package to Reduce IMR]:::primary --> B1[Antenatal & Intrapartum Interventions]:::success
A --> B2[Facility-Based Newborn Care FBNC]:::success
A --> B3[Community-Based Newborn & Child Care]:::success
A --> B4[National Public Health Programs]:::success

B1 --> C1[PMSMA: Min 4 ANC visits, IFA for Anemia, JSY/LaQshya Institutional Births 89%]:::success
B2 --> C2[NSSK Golden Minute Resuscitation, NBCC, NBSU, SNCU for LBW <1800g]:::success
B3 --> C3[HBNC ASHA visits days 1,3,7,14,21,28,42, KMC, Early Exclusive Breastfeeding]:::success
B4 --> C4[UIP 12 VPDs, IMNCI Plan A/B/C, RBSK 4Ds screening, HBYC home visits]:::success
```

#### A. Antenatal & Delivery Interventions

- **Pradhan Mantri Surakshit Matritva Abhiyan (PMSMA)**: Guarantees minimum 4 quality ANC visits, IFA supplementation, and screening for hypertension/diabetes.
- **Promoting Institutional Deliveries**: Achieved **89%** institutional delivery rate through **Janani Suraksha Yojana (JSY)** and **LaQshya** labor room quality guidelines.
- **Navjat Shishu Suraksha Karyakram (NSSK)**: Trains health personnel in basic newborn resuscitation to master the **"Golden Minute"** (initiating positive pressure ventilation within 60 seconds of birth).

#### B. Facility-Based Newborn Care (FBNC) [⭐ High-Yield]

- **Newborn Care Corner (NBCC)**: Established at all delivery points for immediate resuscitation, drying, and warming.
- **Newborn Stabilization Unit (NBSU)**: Established at CHCs for stabilizing sick neonates >1800 g.
- **Special Newborn Care Unit (SNCU)**: Dedicated 12–16 bedded neonatal units at District Hospitals providing round-the-clock specialized care for sick/preterm neonates **<1800 g**.

#### C. Community-Based Interventions

- **Home-Based Newborn Care (HBNC)**: ASHA home visits on days **1, 3, 7, 14, 21, 28, and 42** to promote Kangaroo Mother Care (KMC) for LBW infants, early exclusive breastfeeding, thermal protection, and identification of danger signs.
- **Home-Based Care for Young Child (HBYC)**: Extended ASHA home visits at **3, 6, 9, 12, and 15 months** to ensure appropriate complementary feeding and growth monitoring.

#### D. Preventive & Curative Child Health Initiatives

- **Universal Immunization Program (UIP)**: Free immunization against 12 vaccine-preventable diseases (BCG, OPV, HepB, Pentavalent, Rotavirus, PCV, MR, fIPV).
- **Integrated Management of Neonatal and Childhood Illness (IMNCI)**: Color-coded triage and treatment of pneumonia, diarrhea (Plan A, B, C with ORS and **Zinc for 14 days**), sepsis, and malnutrition.
- **Rashtriya Bal Swasthya Karyakram (RBSK)**: Early screening of children from birth to 6 years for **4Ds** (Defects at birth, Deficiencies, Diseases, Developmental delays).

---

### 9. Complications of Uncontrolled IMR

- High economic and demographic burden on developing health infrastructure.
- High birth rates due to replacement child phenomenon ("insurance effect" in families experiencing infant loss).

---

### 10. Prognosis & National Health Policy Targets

- **National Health Policy (NHP 2017) & SDG 3.2 Goals**:
    - Reduce Under-5 Mortality Rate (U5MR) to **23 per 1000 live births** by 2025.
    - Reduce Neonatal Mortality Rate (NMR) to **16 per 1000 live births** by 2025 (and **≤12 per 1000** by 2030).

---

### 11. Mnemonic / Memory Palace

#### Mnemonic: I-N-F-A-N-T

- **I** - **IMR = 28 per 1000 live births**: Current baseline in India (SRS 2020)
- **N** - **Neonatal period (0–28 days)**: Accounts for **71%** of total infant deaths
- **F** - **Facility-Based Newborn Care**: NBCC, NBSU, and SNCU infrastructure
- **A** - **Asphyxia & Prematurity**: Leading causes of early infant mortality
- **N** - **Navjat Shishu Suraksha Karyakram (NSSK)**: "Golden Minute" resuscitation
- **T** - **Two main components**: Neonatal (<28 days) and Post-neonatal (28 days–1 yr)

---

### Clinical Pearl

> **Reducing IMR requires targeting the first week of life.** Since **71% of infant deaths occur in the neonatal period** (and 75% of those within the first 7 days), health interventions like NSSK "Golden Minute" resuscitation, immediate skin-to-skin contact, early breastfeeding within 1 hour, and KMC for LBW infants yield the maximum reduction in IMR.

---

### Exam Trap

- **The Mix-up**: Confusing the denominator for **Infant Mortality Rate (IMR)** vs. **Perinatal Mortality Rate (PNMR)**.
- **Distinguishing Fact**: **IMR** denominator is strictly **Live Births** (Deaths <1 year ÷ Live births × 1000). **PNMR**numerator includes **Stillbirths (≥28 weeks)** + early neonatal deaths (<7 days), and its standard denominator is **Total Births (Live births + Stillbirths)**.

---

### Diagram 1: Time Distribution Matrix of Infant Mortality

- **Type**: Labeled timeline and component pie-chart diagram.
- **Outline shape to draw**: Horizontal 365-day timeline divided into three segments.
- **Labels in order**:
    1. **Day 0 to Day 7 (Early Neonatal Period)**: **53% of total IMR** (75% of NMR).
    2. **Day 7 to Day 28 (Late Neonatal Period)**: **18% of total IMR** (25% of NMR).
    3. **Day 28 to Day 365 (Post-Neonatal Period)**: **29% of total IMR**.
- **Brackets & Connections**:
    - Combined Bracket (**Day 0 to Day 28**) = **Neonatal Mortality (71% of IMR, Rate = 20)**.
    - Overall Bracket (**Day 0 to Day 365**) = **Infant Mortality Rate (IMR = 28 per 1000 live births)**.
- **Extra Mark Annotation**: Over **40% of all infant deaths occur within the first 24 hours of birth**.

---

### Quick Revision

- **Definition**: Deaths of infants <1 year per 1000 live births. Current Indian IMR = **28 per 1000**.
- **Breakdown**: Neonatal Mortality (**71%**, NMR = 20) + Post-Neonatal Mortality (**29%**, PNMR = 8).
- **Top Causes of Death**: Prematurity/LBW (**44%**), Neonatal Sepsis (**20%**), Birth Asphyxia (**19%**), Pneumonia (**11%**), Diarrhea (**9%**).
- **Key Reduction Programs**: NSSK (Golden Minute), SNCU network, HBNC/HBYC ASHA visits, UIP immunization, and IMNCI strategy.

---

### One-Line Exam Opener

- **The Infant Mortality Rate (IMR) measures the survival of children under 1 year of age per 1000 live births, serving as a pivotal indicator of public health that in India stands at 28 per 1000, driven predominantly by neonatal deaths from prematurity, sepsis, and birth asphyxia.**