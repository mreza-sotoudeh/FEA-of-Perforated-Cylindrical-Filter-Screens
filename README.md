# Mesh Filter FEA – Scrubber Device

Finite Element Analysis (FEA) and stress evaluation of a perforated cylindrical mesh filter used in an industrial gas scrubber.

The study investigates the mechanical behavior of the filter under 7 bar working pressure using SolidWorks Simulation. Two different perforation patterns are compared to assess the effect of hole diameter and pitch on the maximum von Mises stress and to identify critical stress-concentration regions.

## Project Objectives

- Model a cylindrical mesh filter with two different perforation patterns in SolidWorks
- Perform linear static Finite Element Analysis under 7 bar internal pressure
- Evaluate von Mises stress distribution for each geometry
- Compare maximum stresses between the two designs
- Identify critical regions (stress concentrations around the holes)
- Provide a basis for geometric optimization of the filter

## Analysis Conditions

| Parameter              | Value                          |
| ---------------------- | ------------------------------ |
| Filter shape           | Cylindrical                    |
| Diameter               | 100 mm                         |
| Height                 | 300 mm                         |
| Sheet thickness        | 0.8 mm                         |
| Material               | Galvanized Carbon Steel        |
| Working pressure       | 7 bar                          |
| Analysis type          | Linear Static FEA              |
| Software               | SolidWorks + SolidWorks Simulation |
| Stress criterion       | von Mises Equivalent Stress    |

Two perforation cases were studied under identical material, thickness, overall dimensions and loading conditions:

| Parameter       | Case 1     | Case 2     |
| --------------- | ---------- | ---------- |
| Hole diameter   | 3 mm       | 5 mm       |
| Pitch (center-to-center) | 5 mm | 8 mm |
| Maximum von Mises stress | **52 MPa** | **72 MPa** |

## Key Results

The maximum von Mises stress increased by approximately **38.5 %** when moving from the finer perforation pattern (Case 1) to the coarser pattern (Case 2):

```
Percentage Increase = [(72 − 52) / 52] × 100 ≈ 38.5 %
```

Main observations:

| Operating Condition | Main Observation |
| ------------------- | ---------------- |
| Case 1 (Ø3 mm / Pitch 5 mm) | Lower peak stress (52 MPa) – more uniform load distribution |
| Case 2 (Ø5 mm / Pitch 8 mm) | Higher peak stress (72 MPa) – increased stress concentration around larger holes |
| Stress concentration | Highest stresses occur at the edges of the perforations |
| Geometry effect | Hole diameter and pitch significantly influence residual ligament strength and force-flow paths |
| Design implication | Perforation pattern must be chosen considering both flow area and mechanical integrity |

Both designs remain well below the typical yield strength of galvanized carbon steel, but Case 1 exhibits a more favorable stress distribution under the examined working pressure.

## Results

The `Images/` directory contains the stress contour plots obtained from SolidWorks Simulation:

- von Mises stress distribution – Case 1 (Ø3 mm / Pitch 5 mm)
- von Mises stress distribution – Case 2 (Ø5 mm / Pitch 8 mm)

## Repository Contents

- `Models/` — SolidWorks part/assembly files of the two filter geometries (to be added)
- `Images/` — Stress contour plots from SolidWorks Simulation
- `Report/The_Project.docx` — Full internship project report (Persian)

## Requirements

- SolidWorks (2018 or later recommended)
- SolidWorks Simulation (for FEA)

## Internship

**Company:** Andisheh Shomal Machinery
**Period:** Summer 1405 (2026)  
**Supervisors:**  
- Eng. Hosseinpour  
- Eng. Nasiri  

## Author

**Mohammadreza Sotoudeh**  
B.Sc. Student in Mechanical Engineering  
Internship Project – Finite Element Analysis of Scrubber Mesh Filter
