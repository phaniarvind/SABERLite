This document will analyze a residential building in Lakewood, CO using the SABER tool. The details of the building are given in the .pdf document in this folder. SABER will be used to analyze the building and provide recommendations for energy efficiency improvements. First the table below provides the inputs required for the analysis. The description of the each of the inputs is provided in the DetailedDocumentation.md file in the docs folder of this repository.  The screenshots of the various input screens are also provided in the ***DetailedDocumentation.md*** file.

# Inputs

| Input Parameter               | Value                     |
|-------------------------------|---------------------------|
| Project Name                  | LakewoodResidentialBuilding|
| Building Type                 | Single Family Residential Building              |
| Location                      | Denver, CO             |
| Floor Plan                    | Rectangle                 |
| Orientation                   | East                     |
| Floor Area (sqft)            | 1800                      |
| Floor Quantity                | 2                         |
| Wall Height (ft)              | 8                         |
| x1 (ft)                       | 36                        |
| x2 (ft)                       | 0                         |
| y1 (ft)                       | 24                        |
| y2 (ft)                       | 0                         |
| Exterior Wall Construction    | 2x4 insulated wood stud with brick finish                |
| Exterior Wall Insulation Level | R-7 Fiberglass                     |
| Exterior Roof Construction    | Asphalt shingles                |
| Exterior Roof Insulation Level | R-30 Fiberglass                     |
| Foundation Type               | Slab on Grade             |
| Infiltration Air Leakage Rate (ACH50) | 4.0                       |
| Window Material              | Single Pane Clear    |
| WWR Front (%)                | 5.5%                        |
| WWR Back (%)                 | 5.5%                        |
| WWR Left (%)                 | 8.3%                        |
| WWR Right (%)                | 0.1%                        |
| Shading Overhang Depth (ft)     | 0                         |
| Window Height (ft)          | 3                         |
| Number of windows per wall     | 2                         |
| Cooling Equipment Type        | Air Conditioner                |
| SEER        | Other.. - 11               |
| Cooling Setpoint Temperature (°F) | 74                        |
| Cooling Setback (°F)          | 0                         |
| Heating Equipment Type        | Gas Furnace                |
| AFUE                          | 92.5%                       |
| Heating Setpoint Temperature (°F) | 65                        |
| Night Setback (°F)          | 0                        |
| Hot Water Equipment Type     | Gas Boiler                |
| Tank Size (gallons)            | 40                        |
| Cooking Range Type          | Range-Radiant; Not Energy Star Certified;                   |
| Refrigerator Type           | Small; Not Energy Star Certified;                   |
| Dishwasher Type            | None                   |
| Clothes Washer Type         | Medium; Not Energy Star Certified;                   |
| Clothes Dryer Type          | Medium; Not Energy Star Certified;                   |
| Miscellaneous Plug Loads | None                    |
| Interior Lighting | #26 Fluorescent; #20CFL |
| Exterior Lighting | #5 Fluorescent |
| Daylight Controls | No |
| Occupancy Controls | No |

# Outputs

## Pre-Calibration
  <p align="center">
    <img src="./images/1-PreCalkWhResults.png" alt="fig1" width="70%">
    <img src="./images/2-PreCalThermResults.png" alt="fig2" width="70%">
    <img src="./images/3-PreCalEndUseBreakDown.png" alt="fig3" width="70%">
    <img src="./images/4-PreCalFuelUseBreakDown.png" alt="fig4" width="70%">
  </p>

## Post-Calibration
  <p align="center">
    <img src="./images/5-PostCalkWhResults.png" alt="fig5" width="70%">
    <img src="./images/6-PostCalThermResults.png" alt="fig6" width="70%">
    <img src="./images/7-PostCalEndUseBreakDown.png" alt="fig7" width="70%">
    <img src="./images/8-PostCalFuelUseBreakDown.png" alt="fig8" width="70%">
    </p>

# Measure Evaluation
The calibration model can now be used to evaluate various energy efficiency measures. The following measures were evaluated for this building:
## Infiltration Level
Reduce infiltration from 4.0 ACH50 to 2.0 ACH50
  <p align="center">
    <img src="./images/9-InfiltrationMeasure.png" alt="fig9" width="70%">
    </p>


## Insulation Level
Increase wall insulation from R-7 to R-19
  <p align="center">
    <img src="./images/10-InsulationMeasure.png" alt="fig10" width="70%">
    </p>

## Night Setback
Implement a night setback of 10°F for heating
  <p align="center">
    <img src="./images/11-NightSetbackMeasure.png" alt="fig11" width="70%">
    </p>

## Cooling Equipment
Replace existing AC with a SEER 13 unit
  <p align="center">
    <img src="./images/12-CoolingEquipmentMeasure.png" alt="fig12" width="70%">
    </p>

## Measure Package
Combine all the above measures into a single package
  <p align="center">
    <img src="./images/13-MeasurePackage.png" alt="fig13" width="70%">
    </p>
