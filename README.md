```mermaid
---
config:
  theme: neutral
---
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
    classDef Algebra stroke:#D50000
    classDef AlgTopGeo stroke:#AA00FF
    classDef TopGeo stroke:#2962FF
    classDef Analysis stroke:#FFD600

```
