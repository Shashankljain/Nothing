### Pathophysiology Flowchart of Renal Failure

```mermaid
flowchart TB
    A[Renal insult / Hypoperfusion or Nephrotoxin] --> B[Decline in Glomerular Filtration Rate]
    B --> Outer

    subgraph Outer [<b>Pathophysiological Pathways in Renal Dysfunction</b>]
        subgraph Ischemia [<i style='color:red;'>Ischemic & Inflammatory Pathway</i>]
            C[Tubular epithelial cell hypoxia] --> D[Apoptosis & shedding of tubular cells]
            D --> E[Intratubular obstruction & back-leak of filtrate]
        end

        subgraph Compensate [<b style='color:#1565c0;'>Compensatory Pathway</b>]
            F[Renin-Angiotensin System activation] --> G[Efferent arteriolar vasoconstriction & Hyperfiltration]
            G --> H[Progressive glomerulosclerosis in surviving nephrons]
        end
    end

    E --> I{Duration & Chronicity of Insult?}
    H --> I
    I -->|Transient < 48 hrs| J[Pre-Renal Azotemia]
    I -->|Persistent tubular damage| K[Acute Tubular Necrosis / Intrinsic AKI]
    I -->|Progressive > 3 months| L[Chronic Kidney Disease / Stage 5 ESRD]

    style Outer fill:#f5f5f5,stroke:#333,stroke-width:2px
    style Ischemia fill:#ffebee,stroke:#ef5350,stroke-width:2px,stroke-dasharray: 5 5
    style Compensate fill:#e3f2fd,stroke:#42a5f5,stroke-width:2px
```

- **Trigger & Initial Insult**: **Renal hypoperfusion** or **nephrotoxic exposure** causes an immediate decrease in **Glomerular Filtration Rate (GFR)**.
- **Ischaemic & Inflammatory Pathway**: Severe tubular hypoxia leads to **cell apoptosis**, detachment, and **shedding into the luminal space**, causing **intratubular obstruction** and **back-leak of filtrate**.
- **Compensatory Pathway**: Activation of the **Renin-Angiotensin System** leads to **angiotensin II-mediated efferent arteriolar vasoconstriction** to maintain intraglomerular pressure, which over time drives **hyperfiltration** and secondary **glomerulosclerosis** in surviving nephrons.
- **Outcome Stratification**: Transient hypoperfusion resolves as **Pre-Renal Azotemia**, persistent tubular injury manifests as **Acute Tubular Necrosis (Intrinsic AKI)**, and long-standing nephron loss over > 3 months progresses to **Chronic Kidney Disease / Stage 5 ESRD**.