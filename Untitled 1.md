
 flowchart TD
    A[Step 1] --> B[Step 2]
    B --> C{Decision point?}
    C -->|Yes| D[Outcome A]
    C -->|No| E[Outcome B] 

flowchart TD
    A[Insulin deficiency] --> B[Increased lipolysis]
    A --> C[Decreased glucose uptake by cells]
    B --> D[Free fatty acids to liver]
    D --> E[Ketogenesis]
    E --> F[Ketoacidemia]
    C --> G[Hyperglycemia]
    G --> H[Osmotic diuresis]
    H --> I[Dehydration and electrolyte loss]
    F --> J{pH less than 7.3?}
    J -->|Yes| K[Diagnosis: DKA confirmed]
    J -->|No| L[Reassess - consider other cause]

```mermaid
flowchart TB
    %% Outer Fence
    subgraph Outer [<b>Outer Process</b>]
        A[Start] --> B[Step 1]
        
        %% Inner Fence 1
        subgraph Inner1 [<i style='color:red;'>Inner Priority Box</i>]
            B --> C[Step 2]
        end
        
        %% Inner Fence 2
        subgraph Inner2 [<b>Inner Review Box</b>]
            C --> D[Step 3]
        end
        
    end
    
    D --> E[Finish]

    %% --- STYLING THE FENCES ---
    %% Outer Fence: Light gray background, dark gray border
    style Outer fill:#f5f5f5,stroke:#333,stroke-width:2px
    
    %% Inner Fence 1: Very light red background, red dashed border
    style Inner1 fill:#ffebee,stroke:#ef5350,stroke-width:2px,stroke-dasharray: 5 5
    
    %% Inner Fence 2: Very light blue background, blue border
    style Inner2 fill:#e3f2fd,stroke:#42a5f5,stroke-width:2px
```
