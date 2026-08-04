# Equipment Maintenance Management System (SAP Framework)

An equipment maintenance and tracking system designed to consistiantly maintenance, standardize field SOPs, and track service schedules for utility and heavy agricultural equipment.

---

## 1. System Overview

* **Primary Workbook:** [`SAP-vehicle-schedule.csv`](./SAP-vehicle-schedule.csv)
* **Framework:** SAP Maintenance Plan Model (Equipment ID -> Maintenance Task -> SOP -> Schedule)
* **Target Machinery:** Utility vehicles (UTVs), heavy tractors, and lawn care power equipment.

---

## 2. Asset Inventory

| Asset ID | Equipment Name | Category | Model | Serial Number |
| :--- | :--- | :--- | :--- | :--- |
| **EQ-001** | Polaris Ranger XP (PROSTAR) | UTV | Ranger Fullsize | 46240 |
| **EQ-002** | Kubota L3901 | Heavy Tractor | LA525 | W0202 |
| **EQ-003** | Kubota Zero-Turn Mower | Lawn Mower | Z726XKW | 12359 |

---

## 3. Maintenance Tasks & Standard Operating Procedures (SOPs)

### Task ID: TA-001 | Polaris Ranger XP
* **Target Vehicle:** Polaris Ranger XP (PROSTAR)
* **Tasks:** Oil change & fuel line replacement
* **Interval:** 200 Hours / 4 Months
* **SOP Protocol:**
  1. Move vehicle to a flat/level surface and engage **Park**.
  2. Disconnect the negative battery terminal before performing service.
  3. Allow the engine to cool completely before proceeding.
  4. Carefully drain old oil, replace filter, inspect/replace fuel lines, and dispose of fluid following proper environmental guidelines.

---

### Task ID: TA-002 | Kubota L3901 Tractor
* **Target Vehicle:** Kubota L3901
* **Tasks:** Transmission fluid change & hydraulic filter replacement
* **Interval:** 1000 Hours / 12 Months
* **SOP Protocol:**
  1. Park tractor on a flat/level surface, lower all attachments, engage parking brake, and shut off engine.
  2. Allow engine to cool for 5–10 minutes until normal operating temp drops.
  3. Place drain pan under transmission and remove drain plug.
  4. Remove current hydraulic filter and clean the mounting surface thoroughly.
  5. Lightly lubricate the gasket on the new hydraulic filter and install it.
  6. Reinstall drain plug securely to prevent leaks.
  7. Refill system with **Kubota Super UDT2** until it reaches the full mark.
  8. Start and warm up the engine; operate steering and hydraulic functions to circulate fluid.
  9. Shut off engine, check fluid levels (top off if needed), and inspect for leaks around drain plug and filter.

---

### Task ID: TA-003 | Kubota Zero-Turn Mower
* **Target Vehicle:** Kubota Zero-Turn Mower
* **Tasks:** Engine oil & filter replacement, grease pump into blade spindles
* **Interval:** 250 Hours / 5 Months
* **SOP Protocol:**
  1. Park mower on a flat/level surface, engage parking brake, shut off engine, and remove key.
  2. Allow engine to cool completely.
  3. Drain old engine oil and remove oil filter.
  4. Lubricate new filter gasket before installation and install new filter.
  5. Reinstall drain plug and fill with **SAE 10W-30** engine oil to full mark.
  6. Start engine and inspect for active leaks.
  7. Shut off engine and recheck oil level.
  8. Use a grease gun to lubricate all blade spindle fittings until a small amount of grease exits the fitting.
  9. Clean any spills and dispose of used oil and filter properly.

---

## 4. Maintenance Execution Logs

| Plan ID | Equipment | Task Performed | Service Date | Status |
| :--- | :--- | :--- | :--- | :--- |
| **P-001** | Polaris Ranger XP (PROSTAR) | Oil change; fuel lines replaced | 2026-05-05 | `Completed` |
| **P-002** | Kubota L3901 | Change transmission fluid; replace hydraulic filter | 2025-06-10 | `Completed` |
| **P-003** | Kubota Zero-Turn Mower | Change oil; replace filter; grease blade spindles | 2025-05-25 | `Completed` |

---

## 5. Key System Outcomes

* **Downtime Prevention:** Standardizes service intervals based on usage hours and calendar limits to prevent premature equipment failure.
* **Safety & Regulatory Compliance:** Embeds detailed safety steps (power isolation, fluid cooling, environmental waste disposal) into every task list.
* **Traceability:** Pairs unique equipment serial identifiers with task logs to maintain full service history.
