# solar-mix-mast-scheduling-project

## 📌 Project Overview

Solar Mix Inc. requires the urgent replacement of a mast divided into four major components:

* **Lower Mast**
* **Middle Mast**
* **Upper Mast**
* **Crown**

The project contract was awarded to **Horse Leg Inc.** effective **01/04/2021**, with the kick-off meeting scheduled one week later. This repository demonstrates a **professional construction scheduling setup** suitable for **Primavera P6**, focusing on **WBS structure, cost loading, resource hours, and phased execution (Shop & Field)**.

This project is designed as a **portfolio-quality example** for project controls, planning, and scheduling roles.

---

## 🧱 Work Breakdown Structure (WBS)

| WBS Element | Non-Labor Cost ($) | Labor Hours |
| ----------- | ------------------ | ----------- |
| Lower Mast  | 75,000.00          | 2,500       |
| Middle Mast | 85,450.00          | 3,120       |
| Upper Mast  | 65,750.00          | 2,200       |
| Crown       | 55,480.00          | 1,250       |
| **Total**   | **281,680.00**     | **9,070**   |

---

## 🏭 Project Phases

The schedule is divided into **two major execution phases**:

### Phase 1: Shop (Fabrication)

| Activity    | Duration           | Cost % | Labor % |
| ----------- | ------------------ | ------ | ------- |
| Engineering | 20 days            | 10%    | 0%      |
| Procurement | 10 days            | 15%    | 0%      |
| Fitting     | As driven by labor | 20%    | 30%     |
| Welding     | As driven by labor | 25%    | 35%     |
| FAT         | 5 days             | 5%     | 0%      |
| Paint       | 5 days             | 5%     | 0%      |

> Activities without fixed durations are calculated based on assigned labor hours and calendar work hours.

---

### Phase 2: Field (Installation & Closeout)

| Activity       | Duration           | Cost % | Labor % |
| -------------- | ------------------ | ------ | ------- |
| Final Assembly | As driven by labor | 10%    | 35%     |
| Final Testing  | 5 days             | 5%     | 0%      |
| Inspection     | 3 days             | 2%     | 0%      |
| Shipping       | 2 days             | 3%     | 0%      |

---

## ⏱️ Scheduling Assumptions

* **Calendar**: 5 days/week, 8 hours/day
* **Activity relationships**: Finish-to-Start (FS)
* **Cost loading** based on percentage allocation per activity
* **Labor hours** distributed proportionally across WBS components
* **Shop activities precede Field activities**

---

## 🛠 Tools & Skills Demonstrated

* Primavera P6 Scheduling
* WBS & Activity Structuring
* Cost Loading & Resource Allocation
* Labor Hour Distribution
* Shop vs Field Phasing
* Project Controls Documentation

---

## 📂 Recommended Repository Structure

```
solar-mix-mast-project/
│
├── README.md
├── p6-files/
│   └── SolarMix_Mast_Schedule_XER.xer
├── schedules/
│   └── baseline_schedule.pdf
├── cost/
│   └── cost_loading_breakdown.xlsx
├── resources/
│   └── labor_resource_plan.xlsx
└── docs/
    └── project_assumptions.md
```

---

## 🧾 Sample Commit Messages

* `Initial project setup and README documentation`
* `Added WBS structure and cost summary`
* `Uploaded Primavera P6 schedule file`
* `Included cost and labor resource breakdown`
* `Finalized baseline schedule and assumptions`

---

## 👤 Author

**Isaac Olaleye**
Project Scheduler | Construction Planning Engineer

---

## ⭐ Notes

This repository is intended for **demonstration and portfolio purposes** and reflects realistic industry scheduling practices.
