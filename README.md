# 📚 Pure Mathematics Notes

A structured collection of **theorems, definitions, and proofs** that I’ve learned in pure mathematics.  
Organized by topic, this repository serves as both a personal reference and a learning resource for others interested in rigorous mathematics. Note that this is an **exposition** - I claim no originality on any of the content. 

It contains my organized notes on key areas of pure mathematics. Some of the topics I covered are included below: 

| Branch | Topics Covered |
|---------|----------------|
| **Foundations** | Set Theory, Number Systems |
| **Algebra** | Groups and Rings, Linear Algebra, Rings and Modules |
| **Analysis** | Real Analysis, Metric Spaces, Multivariable Calculus |
| **Topology & Geometry** | Point Set Topology, Geometry |

---

## 🏗️ Notes Structure
```mermaid
---
config:
  layout: dagre
---
flowchart BT
    A("Set Theory") --> B("Number Systems")
    B --> C("Real Analysis") & D("Groups and Rings")
    C --> E("Metric Spaces")
    D --> F("Linear Algebra")
    E --> G("Multivariable Calculus") & H("Point Set Topology") & I("Geometry") & S("Algebraic Geometry 1")
    F --> G & I & J("Rings and Modules") & K("Advanced Group Theory") & L("Field and Galois Theory")
    G --> N("Complex Analysis 1")
    H --> M("Algebraic Topology 1") & N & R("Bundle Structures in Topology")
    I --> M
    J --> O("Category Theory") & P("Commutative Algebra 1")
    K --> M
    M --> Q("Algebraic Topology 2")
    O --> T("Homological Algebra")
    P --> T

     A:::None
     B:::None
     C:::Analysis
     D:::Algebra
     E:::Analysis
     F:::Algebra
     G:::Analysis
     H:::TopGeo
     I:::TopGeo
     J:::Algebra
     K:::Algebra
     L:::Algebra
     M:::AlgTopGeo
     N:::Analysis
     O:::Algebra
     P:::Algebra
     Q:::AlgTopGeo
     R:::TopGeo
     S:::AlgTopGeo
     T:::Algebra
    classDef AlgTopGeo stroke:#AA00FF, fill:#FFFFFF
    classDef TopGeo stroke:#2962FF, fill:#FFFFFF
    classDef Analysis stroke:#FFD600, fill:#FFFFFF
    classDef Algebra stroke:#D50000, fill:#FFFFFF
    classDef None fill:#FFFFFF
    click A "https://github.com/Labix-Liu/Notes/blob/main/Sets%20and%20Numbers/Set%20Theory/Set%20Theory.pdf"
    click D "https://github.com/Labix-Liu/Notes/blob/main/Algebra/Groups%20and%20Rings/Groups%20and%20Rings.pdf"
    click F "https://github.com/Labix-Liu/Notes/blob/main/Algebra/Linear%20Algebra/Linear%20Algebra.pdf"
    click H "https://github.com/Labix-Liu/Notes/blob/main/Geometry%20and%20Topology/Point%20Set%20Topology/Point%20Set%20Topology.pdf"
    click J "https://github.com/Labix-Liu/Notes/blob/main/Algebra/Rings%20and%20Modules/Rings%20and%20Modules.pdf"
    click M "https://github.com/Labix-Liu/Notes/blob/main/Geometry%20and%20Topology/Algebraic%20Topology%201/Algebraic%20Topology%201.pdf"





```
