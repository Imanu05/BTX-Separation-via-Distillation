 ## Overview
This project focuses on the simulation and optimization of a distillation system used to separate a BTX mixture containing **benzene, toluene, and p-xylene**. The objective is to achieve the required product purities while ensuring the desired downstream pressures and minimizing energy consumption.

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

## Important Results
- Boiling Points at 1.3 bar:  
  - Benzene: ~88.4 °C  
  - Toluene: ~119.6 °C  
  - p-Xylene: ~147.9 °C  
- Relative Volatility (avg): **~2.19**  
- Minimum number of stages: **~7**  
- Final simulation meets required product purities and pressures.  

## Tools Used
- **DWSIM / Aspen Plus** Distillation Models  
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
