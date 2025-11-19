## Abstract

This project focuses on the separation of a ternary BTX mixture—benzene (400 kg/h), toluene (600 kg/h), and p-xylene (100 kg/h)—at 30 °C and 1.3 bar using both shortcut and rigorous distillation methods in Aspen Plus. The separation target is to obtain benzene and toluene with purities of at least 95%, with final product pressures of 6 bar (benzene), 3 bar (toluene), and 4 bar (p-xylene).

The workflow begins with verification of component boiling points and vapour–liquid equilibrium through Flash calculations. K-value analysis confirms the volatility order benzene > toluene > p-xylene, enabling correct identification of light and heavy keys. The average relative volatility for the first column (benzene/toluene) is approximately 2.19.

Shortcut column design is performed using the Fenske–Underwood–Gilliland method. Fenske’s equation gives a minimum of about 6.92 theoretical stages. Underwood’s method determines the minimum reflux ratio, while Gilliland’s correlation relates operating reflux to actual stage count. These estimates are implemented using Aspen Plus’s DSTWU block, which predicts a benzene purity of roughly 96.13% in the distillate.

A rigorous column model (Distl/RADFRAC) is then developed using stagewise mass and energy balances, tray efficiencies, and condenser/reboiler specifications. The rigorous simulation yields a practical benzene purity of approximately 95.2%, which is expected to be slightly lower than DSTWU due to real-stage inefficiencies and non-ideal VLE behavior.

The second column (toluene/p-xylene) includes the effects of benzene carryover, requiring iterative optimization of reflux and feed stage location. Final purities and recoveries are validated using rigorous simulation.

This combination of shortcut estimation and detailed modelling provides an efficient and accurate design approach for BTX separation, highlighting best practices for multicomponent distillation workflows.
The study uses rigorous distillation modeling, flash calculations, relative volatility estimation, and optimization of reflux ratios and number of stages.

## Feed Composition
- Benzene: 400 kg/h  
- Toluene: 600 kg/h  
- p-Xylene: 100 kg/h  
- Feed Conditions: 30 °C, 1.3 bar  
- Product Purity Targets:  
  - Benzene ≥ **95%**  
  - Toluene ≥ **97%**  
- Downstream product pressures:  
  - Benzene: 6 bar  
  - Toluene: 3 bar  
  - p-Xylene: 4 bar  

## Key Steps Performed
- Verified boiling points using **Pure Component** and **PT Envelope** tools.  
- Estimated **K-values** and **relative volatilities** using flash simulations.  
- Identified benzene as **light key** and toluene as **heavy key**.  
- Calculated minimum number of stages using **Fenske equation**.  
- Found minimum reflux ratio using **DSTWU** shortcut distillation model.  
- Built rigorous simulation using **Distillation Column (Dist1)** block.  
- Verified product purities, flowrates, and exit conditions.  
- Ensured no azeotropes in the operating temperature range.  



## Tools Used
- ** Aspen Plus** Distillation Models  
- Pure Component & PT Envelope Analysis  
- K-value and Flash calculations  
- DSTWU Shortcut Design  
- Rigorous RadFrac/Dist Column Simulation  

## Applications
- Industrial separation of aromatics  
- Refinery / petrochemical distillation design  
- Teaching and training in separation processes  
- Optimization of multicomponent distillation columns  

## Contact
For discussions, improvements, or academic use:  
**anuragy24@iitk.ac.in**
