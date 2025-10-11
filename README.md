# 📚 Pure Mathematics Notes

A structured collection of **theorems, definitions, and proofs** that I’ve learned in pure mathematics.  
Organized by topic, this repository serves as both a personal reference and a learning resource for others interested in rigorous mathematics.

It contains my organized notes on key areas of pure mathematics — from foundational set theory to abstract algebra, topology, and analysis. It is still a massive work in progress! Get in touch with me if you find corrections. 

---

## 🧮 Table of Contents

| Branch | Topics Covered |
|---------|----------------|
| **Foundations** | Set Theory, Number Systems |
| **Algebra** | Groups and Rings, Linear Algebra, Rings and Modules |
| **Analysis** | Real Analysis, Metric Spaces, Multivariable Calculus |
| **Topology & Geometry** | Point Set Topology, Geometry |

---

## 🏗️ Notes Structure
```mermaid
flowchart BT
    A("Set Theory") --> B("Number Systems")
    B --> C("Real Analysis") & D("Groups and Rings")
    C --> E("Metric Spaces")
    D --> F("Linear Algebra")
    E --> G("Multivariable Calculus") & H("Point Set Topology") & I("Geometry")
    F --> G & I & J("Rings and Modules") & K("Advanced Group Theory") & L("Field and Galois Theory")
    H --> M("Algebraic Topology 1")
    I --> M
    K --> M

     A:::None
     B:::None
     C:::Analysis
     D:::Algebra
     E:::Analysis
     F:::Algebra
     G:::Analysis
     H:::Class_01
     H:::TopologyGeometry
     H:::TopGeo
     I:::Class_01
     I:::TopologyGeometry
     I:::TopGeo
     J:::Algebra
     K:::Algebra
     L:::Algebra
     M:::AlgTopGeo
    classDef AlgTopGeo stroke:#AA00FF, fill:#FFFFFF
    classDef TopGeo stroke:#2962FF, fill:#FFFFFF
    classDef Analysis stroke:#FFD600, fill:#FFFFFF
    classDef Algebra stroke:#D50000, fill:#FFFFFF
    classDef None fill:#FFFFFF
    click A "https://github.com/Labix-Liu/Notes/blob/main/Sets%20and%20Numbers/Set%20Theory/Set%20Theory.pdf"
    click D "https://github.com/Labix-Liu/Notes/blob/main/Algebra/Groups%20and%20Rings/Groups%20and%20Rings.pdf"
    click F "https://github.com/Labix-Liu/Notes/blob/71f4c7cc4b1cd6b5f67829805c8c9747846c6a3a/Algebra/Linear%20Algebra/Linear%20Algebra.pdf"
    click J "https://github.com/Labix-Liu/Notes/blob/71f4c7cc4b1cd6b5f67829805c8c9747846c6a3a/Algebra/Rings%20and%20Modules/Rings%20and%20Modules.pdf"
    click M "https://github.com/Labix-Liu/Notes/blob/71f4c7cc4b1cd6b5f67829805c8c9747846c6a3a/Geometry%20and%20Topology/Algebraic%20Topology%201/Algebraic%20Topology%201.pdf"





```
