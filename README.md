
# Adaptive PID, Fuzzy Logic, Neural Network, and Neuro-Fuzzy Controller Simulation

This repository contains a MATLAB/Simulink implementation and comparison of four control strategies:

- Adaptive PID Controller
- Fuzzy Logic Controller
- Neural Network Controller
- Neuro-Fuzzy Controller

## Software Used

- MATLAB/Simulink R2024a

## Files

| File | Description |
|---|---|
| `Final_Completed_Assignment_Model_Zeeshan_Jamil_F25711009.slx` | Simulink model containing the four controller implementations |
| `Final_Assignment_Report_Zeeshan_Jamil.docx` | Final assignment report with theory, results, discussion, and references |
| `Closed_Loop_Output_Comparison.png` | MATLAB-generated closed-loop output comparison plot |

## How to Run the Simulink Model

Open MATLAB, set the current folder to this repository, and run:

```matlab
open_system('Final_Completed_Assignment_Model_Zeeshan_Jamil.slx')
out = sim('Final_Completed_Assignment_Model_Zeeshan_Jamil');

*.log

# OS files
.DS_Store
Thumbs.db
