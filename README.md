# Project AIM
This is a flow on how a Risk is created.

This is a flow on how a Risk is created. AA

## Actors


User | Designation               | User Group    | Company Name  | Country
-----|---------------------------|---------------|---------------|----------
Sam  | Division CEO              | Local Heads   | Forge Finance | Singapore
Jony | Associate Director, Audit | Risk Managers | Forge Finance | Singapore
Carl | Director, Sale            | Risk Owner    | Forge Finance | Singapore
Lyn  | Associate, Audit          | Contributor   | Forge Finance | Singapore

---

### Risk Creation Overview

([Plantuml Reference](https://www.plantuml.com/plantuml/svg/XLD1Rjj03BplA_Y18dVv52I766XHmEa7Q8cMM5jSTRcEOS2F3vUo9HasqEDIm-5mXj8zou09Uz0EctXYQM671wKGBl0prdY03y86BlRSiExX5mgsbER2xvDSdszHSkBjCSVoVY2erWr9vXsJGiWTGIhjqTj_X5TLRaNlXeGSeKw4cQ3WowTLU1HImPk3T491G6aWKSkQ3N8hXxNiOkenSnHWMS0t3ardew_WawIPkOArmEimfFXbkwmUrxf-jF4liA6_L6SD4xFBjt6hy4pu7smNecrRRnmjoHrcEA46ljdMmFRiQ9yVolpPZbiCrOQ-c4uZBRgfr0I754zAHSQXO_6T3jIQUSvqds2rbk6OHoQXcXJJsHIYTN6ctlpzT-JaikQ5H_5bb1ORmnRhFHGBa-lwZs2U0mh5LDjzsdeXpkF5kgOXc-d9JNTCtQ6qf2N6ESKT2sjdHEF6YndWwiptoOx-6iupnOlWRfgdFMU6aMrn8tv0fi6UU3sZrPE_u-6Ad5AFsvujCxkWRm00))

```plantuml
skinparam shadowing false
skinparam ActivityBorderColor blue



| Local Head |
| Risk Manager |
| Risk Owner |
| Contributor |


| Local Head |
:Identifies 
the risk owner -
Assigns Risk Manager
to create the Risk;

| Risk Manager |
: Creates the Risk 
and register the Risk
Information in the Risk 
Inventory;




| Risk Manager |
:Tags the Risk to 
the owner that was
identified by the Local
Head;

| Risk Owner |
:Reviews the assigned
Risk and assings the
Risk Delegate;

| Contributor |
:Inputs the necesary 
task item required by
the Risk owner and sends
back for review;

| Risk Owner |
:Reviews the information
provided by the Contributor
and accept / reject the changes;

:Sends the finished 
Risk information back to the
Risk manager for review;

| Risk Manager |
:Reviews and sends the
Risk to the Local Head
for final approval;



```

---

### Risk Update Overview

```plantuml
skinparam shadowing false
skinparam ActivityBorderColor blue



| Local Head |
| Risk Manager |
| Risk Owner |
| Contributor |

| Risk Owner |
:Assigns section to delegate ;

| Contributor |
:Makes changes;

:Sends back for approval;

| Risk Owner |
:Reviews and approve;
:Send to Risk Manager;

| Risk Manager |
:Acknowledge;

```

