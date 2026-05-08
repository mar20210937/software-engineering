# Software Engineering Project - Group #5

## 1. Group Info

- **Group Number:** 5
- **Case Study:** Parking Management and Guidance System
- **Members:**
  - Maryam Abualia - 20210937
  - Joud Quteifan - 20221073
  - Ali Ziadeh - 20210870
  - Zaid Alsaleh - 20220126
- **Course:** Software Engineering
- **Instructor:** Dr. Samer Elkababji

## 2. Overview

The Parking Management and Guidance System is an embedded and database-driven system that monitors parking occupancy, guides drivers to available spaces, supports reservations, and manages parking payments in real time. It integrates user interfaces, IoT sensors, cameras, a central database, and an external payment gateway.

**Tools used:** Visual Studio Code, PlantUML, Draw.io, GitHub, Markdown, PDF generation tools.

## 3. Diagrams

- **C4 Level 1 - Context Diagram:** Shows the system boundary and the main external actors, including drivers, admins, sensors/cameras, and the payment gateway.
- **C4 Level 2 - Container Diagram:** Shows the main internal containers: user interface, admin dashboard, backend services, integration layer, and database.
- **Use Case Diagram:** Shows the functional services provided to drivers, admins, sensors/cameras, and the payment gateway.
- **High-Level Sequence Diagram:** Shows stakeholder-level flow for checking availability, reserving a spot, receiving guidance, paying, and viewing occupancy.
- **Detailed Sequence Diagram:** Shows developer-level component interactions between the UI, backend, database, sensor/camera system, and payment gateway.
- **Class Diagram:** Shows main system classes with attributes, operations, inheritance, associations, aggregation, and composition.
- **Activity Diagram with Swimlanes:** Shows the parking workflow across the driver, parking system, sensor/camera system, and payment gateway.
- **DFD Level 0:** Shows the data-driven behavior of availability, reservation, payment, occupancy, pricing, and reporting processes.

## 4. Repo Structure

```text
software-engineering/
├── docs/
│   ├── report.md
│   ├── report.pdf
│   ├── se_report_group_05.pdf
│   └── images/
│       ├── c4_context.png
│       ├── c4_container.png
│       ├── use_case_diagram.png
│       ├── sequence_high_level.png
│       ├── sequence_detailed.png
│       ├── class_diagram.png
│       ├── activity_diagram.png
│       └── dfd_level_0.png
├── uml/
│   ├── c4_context.puml
│   ├── c4_container.puml
│   ├── use_case_diagram.puml
│   ├── sequence_high_level.puml
│   ├── sequence_detailed.puml
│   ├── class_diagram.puml
│   ├── activity_diagram.puml
│   └── dfd_level_0.puml
└── README.md
```

## 5. Contributions

- **Maryam Abualia:** Initial repository setup, project structure, README, report sections, use case descriptions, and diagram organization. **Commits:** 9
- **Joud Quteifan:** Reviewed and contributed to final project content. **Commits:** 1
- **Ali Ziadeh:** Reviewed and contributed to final project content. **Commits:** 1
- **Zaid Alsaleh:** Added member information, completed missing deliverables, updated diagrams, finalized report, and prepared final PDF. **Commits:** 2
