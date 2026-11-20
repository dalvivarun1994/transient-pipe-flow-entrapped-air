# transient-pipe-flow-entrapped-air
1D finite-volume model for transient liquid flow with entrapped air, valve dynamics and pressure-surge validation
## Overview
1D finite-volume model to study what happens when a valve is opened rapidly in a liquid-filled pipeline with a finite pocket of air trapped at the closed end.

## Physical System
<img width="1752" height="897" alt="Transient Pipe Flow with Entrapped Air" src="https://github.com/user-attachments/assets/fae404f7-2343-4b8b-9301-77de946f585b" />


## Model
- 1D finite-volume formulation
- Liquid mass conservation
- Liquid momentum conservation
- Entrapped-air energy equation
- Pressure-dependent water density
- Pipe friction
- Time-dependent valve resistance

## Numerical Method
Implicit Newton-Raphson solution of the coupled equations.

## Validation
<img width="1256" height="706" alt="image" src="https://github.com/user-attachments/assets/8e1e5729-e93f-4e1d-829e-40b13e490957" />

The experimental configuration and measured pressure data used for model validation were reproduced from the doctoral thesis by Nahm Ho Lee, Effect of Pressurization and Expulsion of Entrapped Air in Pipelines, Georgia Institute of Technology, 2005.

## Parametric Study
<img width="1722" height="1288" alt="graphic3_complete_matrix_plot" src="https://github.com/user-attachments/assets/2a65ecb3-b64f-445d-841d-1974f39ab1ac" />


## Key Findings
- Entrapped air provides system compliance
- Initial Air volume and reservoir pressure strongly affects peak pressure
- Valve opening affects first peak magnitude/timing
- Heat transfer affects oscillation frequency/phase
- Friction damps subsequent oscillations

## Limitations
Not currently included:
- Unsteady friction
- Gas dissolution
- Cavitation
- Flashing / phase change

## Future Work
Extension to LN2 using drift-flux and two-fluid models.
