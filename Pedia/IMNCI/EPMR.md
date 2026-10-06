[[PMR]]
#(Mark-Weightage Calibration: Defaulting to 10 Marks / Long Answer Depth)

# Extended Perinatal Mortality Rate (EPMR) & Measures for Reduction in India [⭐ High-Yield]

### 1. Definition [⭐ High-Yield]

- **Perinatal Period**: Standardly extends from the **22nd completed week of gestation** (154 days, fetal weight **≥500 g**) to **less than 7 completed days of life** (<168 hours post-delivery).
- **Extended Perinatal Mortality Rate (EPMR)**: Defined as the total number of late fetal deaths (stillbirths occurring at **≥22 or ≥28 weeks of gestation**) PLUS total neonatal deaths occurring during the **entire 28 completed days of neonatal life** (early <7 days + late 7–28 days), expressed per **1000 total births** (live births + stillbirths).
- **Core Distinction from Standard PNMR**: Standard Perinatal Mortality Rate (**PNMR**) includes early neonatal deaths occurring only within the first week of life (**<7 days**). EPMR extends the observation window to include late neonatal deaths (**7 to 28 days**), offering a broader metric that evaluates both intrapartum care and post-discharge community/facility newborn care quality.

\[\text{Extended Perinatal Mortality Rate (EPMR)} = \frac{\text{Stillbirths } (\ge 28 \text{ wks}) + \text{ Total Neonatal Deaths } (<28 \text{ days})}{\text{Total Births } (\text{Live Births} + \text{Stillbirths})} \times 1000\]

- **Current Epidemiological Indices in India (SRS Data)**:
    - **Under-5 Mortality Rate (U5MR)**: **32 per 1000 live births**.
    - **Infant Mortality Rate (IMR)**: **28 per 1000 live births**.
    - **Neonatal Mortality Rate (NMR)**: **20 per 1000 live births** (accounts for **63%** of U5MR and **71%** of infant deaths).
    - **Early Neonatal Mortality Rate (ENMR)**: **15 per 1000 live births** (**75%** of NMR).
    - **Late Neonatal Mortality Rate (LNMR)**: **5 per 1000 live births** (**25%** of NMR).

---

### 2. Etiology / Causes / Risk Factors [⭐ High-Yield]

EPMR encompasses the combined etiologies of stillbirths, early neonatal deaths, and late neonatal deaths:

#### A. Antepartum and Intrapartum Fetal Factors (Stillbirths)

- **Maternal Anemia & Undernutrition**: Over **57%** of pregnant women in India are anemic, leading to severe Intrauterine Growth Restriction (**IUGR**) and fetal hypoxia.
- **Hypertensive Disorders of Pregnancy**: Pre-eclampsia and eclampsia cause acute/chronic placental insufficiency, abruptio placentae, and intrauterine fetal death.
- **Intrapartum Complications**: Prolonged/obstructed labor, cord prolapse, and uterine rupture leading to birth asphyxia.

#### B. Early Neonatal Factors (<7 Days) [⭐ High-Yield]

- **Prematurity & Low Birth Weight (LBW)** (**44%** of neonatal deaths): Causes **Respiratory Distress Syndrome (RDS)**, **Intraventricular Hemorrhage (IVH)**, and severe **hypothermia**.
- **Birth Asphyxia & Trauma** (**19%** of neonatal deaths): Failure to initiate breathing at birth leading to **Hypoxic Ischemic Encephalopathy (HIE)**.
- **Early-Onset Sepsis (EOS)** (**20%** of neonatal deaths): Occurs within **72 hours** of birth due to maternal chorioamnionitis or unsterile delivery.

#### C. Late Neonatal Factors (7 to 28 Days)

- **Late-Onset Sepsis (LOS)**: Hospital or community-acquired bacterial infections (predominantly _**Klebsiella pneumoniae**_, _Acinetobacter_, and _Staphylococcus aureus_).
- **Neonatal Pneumonia & Severe Diarrhea**: Secondary to unhygienic feeding, bottle feeding, or lack of early exclusive breastfeeding.
- **Unsafe Home Practices**: Application of cow dung/surma to the umbilical cord stump and failure to maintain the **Warm Chain**.

#### D. Health System & Social Factors ("The Three Delays Model")

1. **First Delay**: Delay in deciding to seek care due to poverty, illiteracy, and lack of awareness of danger signs.
2. **Second Delay**: Delay in reaching a health facility due to inadequate emergency transport and geographic barriers.
3. **Third Delay**: Delay in receiving quality emergency obstetric and newborn care (**EmONC**) at the facility.

---

### 3. Classification / Components of EPMR [⭐ High-Yield]

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[Extended Perinatal Mortality EPMR]:::primary --> B1[Fetal Deaths / Stillbirths]:::warning
A --> B2[Total Neonatal Deaths <28 Days]:::danger

B1 --> C1[Antepartum Stillbirths: Macerated death before labor]:::warning
B1 --> C2[Intrapartum Stillbirths: Fresh death during labor]:::danger

B2 --> C3[Early Neonatal Deaths: Days 0 to 6 <168 hours]:::danger
B2 --> C4[Late Neonatal Deaths: Days 7 to 28 of life]:::danger
```

---

### 4. Pathophysiology [⭐ High-Yield]

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[Maternal Risk Factors: Anemia, PIH, Infection, Lack of SBA]:::primary --> B[Placental Insufficiency & Intrapartum Hypoxia]:::warning
B --> C{Delivery Event & Resuscitation}:::warning
C -->|Failed Resuscitation| D[Intrapartum Stillbirth OR Severe HIE]:::danger
C -->|Preterm Delivery <37 Wks| E[Surfactant Deficiency RDS & Hypothermia]:::danger
C -->|Unsterile Care / Pathogens| F[Early or Late Neonatal Sepsis]:::danger

D --> G1[Early Neonatal Collapse <7 Days]:::danger
E --> G2[Multi-organ Failure & IVH]:::danger
F --> G3[Septic Shock & Refractory Acidosis <28 Days]:::danger

G1 & G2 & G3 --> H[Extended Perinatal Death]:::danger
```

- **Pathophysiological Triad**: Hypoxia-ischemia, cold stress (hypothermia), and invasive bacterial sepsis act synergistically in neonates, depleting glycogen stores and triggering severe metabolic acidosis, multiorgan dysfunction, and cardiac arrest.

---

### 5. Clinical Features / Key Surveillance Indicators

#### A. Fetal & Intrapartum Danger Markers

- Decreased fetal movements, non-reassuring fetal heart rate (bradycardia **<110 bpm**), thick meconium-stained amniotic fluid (**MSL**).

#### B. Neonatal Danger Signs (0 to 28 Days) [⭐ High-Yield]

- **Respiratory**: Fast breathing (**≥60 breaths/min**), severe chest indrawing, grunting, or central cyanosis.
- **Neurological**: Convulsions, lethargy, poor feeding/inability to suck, hypotonia.
- **Thermal**: Cold extremities and body (**axillary temperature <35.5°C**) or fever (**>37.5°C**).
- **Sepsis Signs**: Umbilical redness extending to skin, severe skin pustules, abdominal distension, yellow soles.

---

### 6. Diagnosis / Investigations & Surveillance

- **Antenatal Screening**:
    - Ultrasonography (USG) for fetal growth, gestational age, and biophysical profile.
    - Maternal blood pressure, Hb, random blood sugar, and TORCH/VDRL/HIV serology.
- **Neonatal Investigations**:
    - **APGAR Score**: Evaluated at **1 and 5 minutes** post-delivery.
    - **Sepsis Screen**: Total Leukocyte Count (**TLC <5000/mm³**), Absolute Neutrophil Count (**ANC <1800/mm³**), Immature to Total ratio (**I/T ratio >20%**), **CRP >1 mg/dL**, micro-ESR **≥15 mm in 1st hour**.
    - **Blood Culture**: Gold standard for confirming neonatal sepsis.
- **Death Surveillance**: **Maternal and Perinatal Death Surveillance and Response (MPDSR)** audits to identify and fix systemic care gaps.

---

### 7. Differential Diagnosis / Comparison Table

|Parameter|**Standard PNMR**|**Extended Perinatal Mortality Rate (EPMR)** [⭐ High-Yield]|**Neonatal Mortality Rate (NMR)**|**Infant Mortality Rate (IMR)**|
|:--|:--|:--|:--|:--|
|**Fetal Component**|Stillbirths (**≥28 wks**)|Stillbirths (**≥28 wks**)|None|None|
|**Postnatal Component**|Early Neonatal Deaths (**<7 days**)|**Total Neonatal Deaths (<28 days)**|Total Neonatal Deaths (**<28 days**)|Deaths in **1st year of life (<365 days)**|
|**Denominator**|Total Births (per 1000)|Total Births (per 1000)|Live Births (per 1000)|Live Births (per 1000)|
|**Scope of Assessment**|Evaluates antenatal & intrapartum care|Evaluates antenatal, intrapartum **& 28-day postnatal care**|Evaluates newborn care quality|Evaluates overall infant health & immunization|

---

### 8. Measures to Reduce EPMR in India [⭐ High-Yield]

Reducing EPMR requires a continuum-of-care approach across four healthcare domains:

```
flowchart TD

classDef primary fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
classDef danger fill:#ffebee,stroke:#c62828,stroke-width:2px
classDef success fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
classDef warning fill:#fff8e1,stroke:#f57f17,stroke-width:2px

A[National Strategy to Reduce EPMR in India]:::primary --> B1[Antenatal Interventions]:::success
A --> B2[Intrapartum Care & Resuscitation]:::success
A --> B3[Facility & Community Newborn Care]:::success
A --> B4[Public Health & Systemic Programs]:::success

B1 --> C1[PMSMA: Min 4 ANC visits, IFA for Anemia 57%, HTN/GDM screening, Antenatal Steroids <34w]:::success
B2 --> C2[Institutional Delivery 89% JSY/LaQshya, NSSK Golden Minute training, Delayed Cord Clamping 30-60s]:::success
B3 --> C3[Warm Chain, KMC for LBW <2000g, Tiered Care NBCC/NBSU/SNCU, M-NICU, HBNC ASHA visits]:::success
B4 --> C4[IMNCI training, UIP Immunization, RBSK 4Ds screening, HBYC home visits]:::success
```

#### A. Antenatal Care Measures

- **Quality Antenatal Visits**: Minimum 4 ANC visits under **Pradhan Mantri Surakshit Matritva Abhiyan (PMSMA)**.
- **Anemia Control**: Iron-Folic Acid (**IFA**) supplementation and IV iron sucrose infusion for severe anemia.
- **Antenatal Corticosteroids**: Administration of **IV Dexamethasone / Betamethasone** to mothers in preterm labor (**<34 weeks**) to accelerate lung maturation and reduce RDS and IVH.
- **Screening & Control**: Early detection of gestational hypertension, pre-eclampsia, and gestational diabetes.

#### B. Intrapartum Care Measures

- **Institutional Deliveries**: Promoting births at health facilities (achieved **89%** coverage) via **Janani Suraksha Yojana (JSY)** and **LaQshya** labor room quality standards.
- **Navjat Shishu Suraksha Karyakram (NSSK)**: Training birth attendants in basic newborn resuscitation to master the **"Golden Minute"** (initiating positive pressure ventilation within 60 seconds of birth).
- **Delayed Cord Clamping (DCC)**: Delaying clamping for **30–60 seconds** in un-asphyxiated infants to increase iron stores and reduce IVH.

#### C. Postnatal & Neonatal Care Measures [⭐ High-Yield]

- **Essential Newborn Care (ENC)**: Immediate drying, maintaining the **Warm Chain**, early skin-to-skin contact, and initiating exclusive breastfeeding within **1 hour of birth**.
- **Kangaroo Mother Care (KMC)**: Continuous skin-to-skin contact and exclusive breastfeeding for low birth weight (**<2000 g**) and preterm infants to prevent hypothermia and sepsis.
- **Tiered Facility Infrastructure**:
    - **Newborn Care Corner (NBCC)**: Available at all delivery points for immediate drying and resuscitation.
    - **Newborn Stabilization Unit (NBSU)**: Available at CHCs for stabilizing sick neonates **>1800 g**.
    - **Special Newborn Care Unit (SNCU)**: 12–16 bedded units at district hospitals for neonates **<1800 g** or severe sickness.
    - **Mother-Neonatal Intensive Care Unit (M-NICU)**: Keeping mothers and sick neonates together to improve KMC and breastfeeding.
- **Home-Based Newborn Care (HBNC)**: ASHA home visits on days **1, 3, 7, 14, 21, 28, and 42** to identify danger signs and refer sick newborns.

#### D. Systemic & Community Public Health Interventions

- **IMNCI Implementation**: Training healthcare providers in Integrated Management of Neonatal and Childhood Illness algorithms.
- **Universal Immunization Program (UIP)**: Administering **OPV zero dose, BCG, and Hepatitis B** at birth.
- **Rashtriya Bal Swasthya Karyakram (RBSK)**: Screening newborns and children for **4Ds** (Defects at birth, Deficiencies, Diseases, Developmental delays).
- **Home-Based Care for Young Child (HBYC)**: Extended ASHA home visits at **3, 6, 9, 12, and 15 months** to ensure adequate complementary feeding and growth.

---

### 9. Complications of Perinatal & Neonatal Insults

- **Hypoxic Ischemic Encephalopathy (HIE)**: Seizures, cerebral edema, and severe neurological deficits.
- **Long-term Neurological Impairment**: Dystonic/spastic **Cerebral Palsy**, intellectual disability, and epilepsy.
- **Retinopathy of Prematurity (ROP)**: Uncontrolled vascular proliferation in preterm infants exposed to hyperoxia, leading to retinal detachment and total blindness.

---

### 10. Prognosis & National Targets

- **National Health Policy (NHP 2017) & SDG 3.2 Targets**:
    - Reduce Neonatal Mortality Rate (**NMR**) to **≤12 per 1000 live births** by 2030.
    - Reduce Stillbirth Rate (**SBR**) to **≤12 per 1000 total births** by 2030 under the **India Newborn Action Plan (INAP)**.

---

### 11. Mnemonic / Memory Palace

#### Mnemonic: E-X-T-E-N-D

- **E** - **Entire 28 days**: EPMR tracks stillbirths plus ALL 28 days of neonatal mortality
- **X** - **eXtra late-neonatal tracking**: Captures deaths from Day 7 to Day 28 missed by standard PNMR
- **T** - **Three Delays addressed**: Decision, transport, and facility care bottlenecks
- **E** - **Essential Newborn Care**: Immediate drying, Warm Chain, early exclusive breastfeeding
- **N** - **Navjat Shishu Suraksha Karyakram (NSSK)**: Resuscitation within the Golden Minute
- **D** - **Delayed cord clamping**: 30–60 seconds delay to boost hemoglobin and prevent IVH

---

### Clinical Pearl

> **EPMR provides a complete audit of newborn survival.** While standard PNMR reflects obstetric and immediate delivery room care (<7 days), EPMR extends tracking through the 28th day of life, serving as an indicator of post-discharge newborn care, community infection control, and ASHA home-visit quality.

---

### Exam Trap

- **The Mix-up**: Confusing the denominator and time window for **PNMR** vs. **EPMR**.
- **Distinguishing Fact**: **Standard PNMR** includes stillbirths + early neonatal deaths (**<7 days**). **EPMR** includes stillbirths + total neonatal deaths (**<28 days**). Both use **Total Births (Live births + Stillbirths)** as the denominator.

---

### Diagram 1: Extended Perinatal Period Timeline & Components

- **Type**: Labeled timeline and component diagram.
- **Outline shape to draw**: Horizontal timeline divided into gestational weeks and postnatal days.
- **Labels in order**:
    1. **22 / 28 Weeks Gestation**: Antenatal start boundary (fetal viability).
    2. **Birth Event**: Boundary dividing fetal life from neonatal life.
    3. **Day 7 of Life (<168 hours)**: End of early neonatal period.
    4. **Day 28 of Life**: End of late neonatal period (complete 28 days).
- **Brackets & Connections**:
    - Bracket 1 (**28 Weeks to Birth**) = **Stillbirths / Fetal Deaths**.
    - Bracket 2 (**Birth to Day 7**) = **Early Neonatal Deaths**.
    - Bracket 3 (**Day 7 to Day 28**) = **Late Neonatal Deaths**.
    - Combined Bracket (**28 Weeks to Day 7**) = **Standard PNMR**.
    - Extended Bracket (**28 Weeks to Day 28**) = **Extended Perinatal Mortality Rate (EPMR)**.
- **Extra Mark Annotation**: Late neonatal deaths (days 7–28) account for **25%** of overall neonatal mortality in India.

---

### Quick Revision

- **EPMR Formula**: (Stillbirths ≥28 wks + Total Neonatal Deaths <28 days) ÷ Total Births × 1000.
- **Key Advantage**: Measures intrapartum care AND full 28-day postnatal newborn care quality.
- **Current SRS Rates**: NMR = **20**, ENMR = **15**, LNMR = **5**, U5MR = **32** per 1000 live births.
- **Core Interventions**: PMSMA (antenatal), NSSK Golden Minute resuscitation (intrapartum), KMC + SNCU + HBNC ASHA visits (postnatal).

---

### One-Line Exam Opener

- **The Extended Perinatal Mortality Rate (EPMR) expands standard perinatal surveillance by combining late fetal deaths with total 28-day neonatal deaths per 1000 total births, offering a comprehensive metric to evaluate obstetric quality, immediate resuscitation, and post-discharge neonatal healthcare in India.**