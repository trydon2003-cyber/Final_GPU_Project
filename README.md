# Final_GPU_Project
Final Project: High-Performance Image Pipeline
Hardware Used for this project:
  NVIDIA RTX 4070 TI Super w/ 8448 CUDA cores. More information found here:https://www.asus.com/us/motherboards-components/graphics-cards/tuf-gaming/tuf-rtx4070tis-o16g-gaming/techspec/

  Enviroment Setup:
    1. Create a new folder for your project.
    2. Hit control + Shift + P to open the command pallet
    3. Enter Python Create Enviroment, and click Venv.
    4. Select Python 3.11.9, make sure to close current terminal and opening a new one.

Performance Table Summary:
Gaussian Blur table
--- PERFORMANCE RESULTS ---
CPU Blur Time: 24.841272 seconds

--- GPU TIMINGS ---
H2D Transfer Time: 0.006025 seconds
D2H Transfer Time: 0.009031 seconds

--- KERNEL TIMES ---
GPU Global Memory Time: 0.000243 seconds
GPU Shared Memory Time: 0.000213 seconds

--- SPEEDUPS ---
Shared vs Global Speedup: 1.139256x
CPU vs Shared Speedup: 116490.059312x  
