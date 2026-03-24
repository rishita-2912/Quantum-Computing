# Grover's Algorithm — 10-Qubit Qiskit Implementation

## Marked States
- `0110011010`
- `1101010001`

## Requirements
pip install qiskit qiskit-aer matplotlib numpy

## How to Run
1. Open `grover_10qubit.ipynb` in Jupyter Notebook or JupyterLab
2. Run all cells in order (Cell → Run All)
3. Circuit diagrams appear inline after each stage
4. Histograms display inline and are saved as PNG files

## Circuit Diagrams Generated
| File | Contents |
|------|----------|
| stage1_superposition.png | Hadamard layer |
| stage2_oracle_4bit.png | Oracle (4-qubit readable example) |
| stage2_oracle_10bit.png | Oracle (full 10-qubit) |
| stage3_diffusion_4bit.png | Diffusion (4-qubit readable example) |
| stage3_diffusion_10bit.png | Diffusion (full 10-qubit) |
| stage4_one_iteration.png | One Grover iteration (no measurement) |
| stage5_full_circuit_Xiter.png | Full circuit for X = 1,3,5,10 iterations |
| grover_histograms.png | Results for all iteration counts |
| grover_optimal_circuit.png | Circuit at optimal (~18) iterations |
| grover_optimal_histogram.png | Results at optimal iterations |

## Expected Output
The two marked states appear with the highest bars (crimson) in all histograms.