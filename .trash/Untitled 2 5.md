### Pathophysiology Flowchart of Acute Pancreatitis

```mermaid
flowchart TB
    A[Acinar cell injury or Ductal obstruction] --> B[Intra-acinar zymogen activation]
    B --> Outer

    subgraph Outer [<b>Mechanisms of Pancreatic Injury & Inflammation</b>]
        subgraph Autodigestion [<i style='color:red;'>Autodigestive Pathway</i>]
            C[Trypsinogen converted to active Trypsin] --> D[Cascade activation of Elastase, Lipase, Phospholipase A2]
            D --> E[Parenchymal necrosis, fat necrosis, vascular haemorrhage]
        end

        subgraph Inflammatory [<b style='color:#1565c0;'>Systemic Inflammatory Pathway</b>]
            F[Pro-inflammatory cytokine release IL-1, IL-6, TNF-alpha] --> G[Capillary leak & neutrophil infiltration]
            G --> H[Systemic Inflammatory Response Syndrome SIRS]
        end
    end

    E --> I{Organ Failure / Necrosis persistent > 48 hrs?}
    H --> I
    I -->|No organ failure| J[Mild Acute Pancreatitis]
    I -->|Transient failure < 48 hrs| K[Moderately Severe Pancreatitis]
    I -->|Persistent failure > 48 hrs| L[Severe Acute Pancreatitis]

    style Outer fill:#f5f5f5,stroke:#333,stroke-width:2px
    style Autodigestion fill:#ffebee,stroke:#ef5350,stroke-width:2px,stroke-dasharray: 5 5
    style Inflammatory fill:#e3f2fd,stroke:#42a5f5,stroke-width:2px
```

- **Initiating Insult**: **Gallstone ampullary obstruction** or **alcohol toxicity** leads to impaired zymogen exocytosis and intracellular fusion of zymogen granules with lysosomes.
- **Intra-Acinar Enzyme Activation**: Lysosomal **cathepsin B** converts **trypsinogen to active trypsin**, triggering cascade activation of **elastase**, **lipase**, and **phospholipase A2**.
- **Autodigestion & Tissue Injury**: Activated enzymes digest pancreatic tissue, producing **parenchymal necrosis**, **retroperitoneal fat saponification**, and **vascular hemorrhage**.
- **Systemic Cytokine Release**: Pro-inflammatory cytokines (**TNF-α**, **IL-1**, **IL-6**) induce endothelial injury, capillary permeability, and **Systemic Inflammatory Response Syndrome (SIRS)**.
- **Severity Stratification**: Categorized into **Mild** (no organ failure), **Moderately Severe** (transient organ failure < 48 hours), or **Severe Acute Pancreatitis** (persistent organ failure > 48 hours).