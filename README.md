# Battery Pack Optimization - Siemens Design Challenge
### 1st Place Winner ($10,000 Award)

## Challenge Overview

Design and optimize a compact battery enclosure focused on minimizing volume while maintaining thermal performance of 140°F  maximum temperature and manufacturability requirements.

The final design achieved the smallest package volume among competitors while satisfying thermal constraints.

---

## Judging 
1. Smallest internal enclosure volume
2. Lowest Enclosure Mass (tie-breaker)
3. Lowest Maximum Battery Temperature (tie-breaker)
---

## Design Rules and Requirements

- All walls must maintain 0.5 in. thickness
- No single cell exceeds 140°F 
- Design must contain 6 modules of 7 cells each minimum
- Maintain cell temperatures below competition limits
- Maintain mesh size >0.1 in.
- Outlets (Fans) can only be of the following

| Size | Diameter (in) | Airflow (CFM) | Power (W) | Mass (g)|
|---|---|---|---|---|
| Large | 3.2 | 35 | 2.0 | 80 |
| Medium | 2.4 | 20 | 1.5 | 50 |
| Small | 1.6 | 8 | 1.0 | 25 |

- Total fan power consumption must not exceed 10 W
  - Note: my iteration used only 2 small fans, consuming only 2 out of the 10 allocated Watts and adding just 50 grams
- Inlet holes (Forced-Air) can only be placed up to a maximum of 4 with a fixed diameter of 2.5 in. with uniform 25 mph and an ambient temperature of 80°F
- Design needs exactly 1 passive vent with 1.0 in. diameter with ambient pressure only
- These are the only openings allowed, and they must be placed on the sides only
- Enclosure must be reasonably manufacturable (no organic structures)
- Internal volume cannot exceed 3,000 in³
- Battery cells themselves cannot be modified
- Battery cells must emit 15 W of thermal power each
---

## Design Objectives

- Create a manufacturable modular battery layout
- Optimize packaging efficiency
- Minimize battery enclosure volume
- Maintain cell temperatures below competition limits

---

## Final Design Results

| Parameter                |                Result                |
|--------------------------|--------------------------------------|
| Award                    | 1st Place - Siemens Design Challenge |
| Cell Count               | 42 cylindrical cells                 |
| Module Configuration     | 6 modules × 7 cells                  |
| Enclosure Volume         | 132.378 in³                          |
| Battery Mass             | 6055.56 g                            |
| Maximum Cell Temperature | 108.7°F                              |
| Temperature Requirement  | <140°F                               |

---

## Battery Architecture

The battery given parameters consist of 42 individual cells arranged into six custom-designed modules with 7 cells each minimum.

The module layout was optimized to balance:
- packaging density
- thermal performance
- structural integration

<img width="1905" height="798" alt="Screenshot 2026-07-31 160531" src="https://github.com/user-attachments/assets/7aac8b3a-3723-4341-91be-7df721cddbf1" />

## Mechanical Design and Methods

Our overall method revolved around consuming as much negative volume as possible by placing each cell 0.1 in. away from each other as close as possible. We "wrapped" the walls into the negative volume while maintaining a 0.5 in thickness. Our strategy revolved entirely around minimizing volume even if it starts adding to mass.

Designed:
- Battery enclosure geometry
- Inlet/Outlet placements

Tools:
- SolidWorks CAD
- Altair Inspire Simulations

<img width="1440" height="978" alt="Screenshot 2026-07-31 160220" src="https://github.com/user-attachments/assets/13f36026-75e3-4806-b0d8-2b5db6b64e5c" />
<img width="1689" height="1113" alt="Screenshot 2026-07-31 163638" src="https://github.com/user-attachments/assets/24a80016-0347-41a8-bd96-9f9b5987c20a" />


---

## Thermal Performance

Thermal analysis was performed to evaluate heat management under operating conditions.

Final design achieved:

**Maximum temperature: 108.7°F**

compared to the required limit:

**140°F maximum**

<img width="1076" height="560" alt="Screenshot 2026-07-22 134302" src="https://github.com/user-attachments/assets/b8bdb58b-6561-4582-8289-016023fa4f21" />

---

## Design Report

Full project documentation:

[CalSol Siemens Challenge Writeup.pdf](https://github.com/user-attachments/files/30607577/CalSol.Siemens.Challenge.Writeup.pdf)


---

## Contributors
Teddy Mendonca, Yashil Trivedi, William Preston, Sadiq Khan

Team project completed for the 2026 Siemens Design Challenge.
