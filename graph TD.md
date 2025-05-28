graph TD
    U[U (30V)] -->|I_A (5A)| R1[R1 (6Ω)]
    U -->|I_B (3A)| XL1[XL1 (10Ω)]
    U -->|I_C (3.75A)| R3[R3 (8Ω)]

    subgraph "Токи"
        I_A(I_A)
        I_B(I_B)
        I_C(I_C)
    end
    
    U --> I_A
    U --> I_B
    U --> I_C
    
    style U fill:#fff,stroke:#000,stroke-width:2px
    style R1 fill:#0f0,stroke:#000,stroke-width:2px
    style XL1 fill:#00f,stroke:#000,stroke-width:2px
    style R3 fill:#ff0,stroke:#000,stroke-width:2px
    
    classDef active fill:#0f0;
    classDef reactive fill:#00f;



