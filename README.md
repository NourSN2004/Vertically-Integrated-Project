# Vertically-Integrated-Project
# SOC Wireless Transceiver Design Automation

This repository contains the work conducted for the development and optimization of SOC wireless transceivers, focusing on automating the design of critical circuit blocks using tools such as **Cadence Virtuoso**, **Ocean Script**, and **Skill**.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Key Features](#key-features)
3. [Files and Structure](#files-and-structure)
4. [Methodology](#methodology)
5. [Results](#results)
6. [Future Work](#future-work)
7. [Acknowledgments](#acknowledgments)

## Project Overview
This project explores automated design solutions for SOC wireless transceivers operating in the RF frequency range of 2.5–7 GHz. The focus was on optimizing three key circuit blocks:
- **Current Mirror**: Ensures the output current matches the reference current with minimal variation.
- **Second-Order Low-Pass Filter (LPF)**: Tuned to achieve specific frequency response characteristics.
- **Differential Amplifier**: Optimized to maximize gain while adhering to design constraints.

The project leverages optimization algorithms, scripting for automation, and advanced simulation techniques to enhance efficiency and performance.

## Key Features
- **Automation Tools**: Integrated Ocean Script and Skill for automated design and optimization.
- **Optimization Algorithms**: Employed Gradient Descent and Newton's Method to fine-tune component values.
- **Data-Driven Design**: Utilized CSV-based data analysis to refine results and guide future optimizations.
- **Design Compliance**: Ensured adherence to constraints such as gain, cutoff frequency, and SNR for RF circuits.

## Files and Structure
- **`current_mirror/`**: Contains the current mirror design and optimization scripts.
- **`low_pass_filter/`**: Includes LPF schematics, simulations, and Ocean Script files.
- **`differential_amplifier/`**: Holds design files and optimization results for the amplifier.
- **`scripts/`**: Automation scripts for running simulations and exporting results.
- **`results/`**: CSV files and logs documenting simulation outputs and optimization progress.

## Methodology
1. **Simulation Setup**:
   - Designed schematics using Cadence Virtuoso.
   - Configured global variables and test setups for DC, AC, and noise analyses.

2. **Optimization**:
   - Applied iterative techniques to fine-tune component values.
   - Exported Ocean Script files for automation and executed SKILL scripts for variable substitution.

3. **Data Analysis**:
   - Processed simulation results in CSV format for systematic evaluation and refinement.

4. **Performance Evaluation**:
   - Compared outputs against target metrics such as cutoff frequency, gain, and signal-to-noise ratio (SNR).

## Results
- Achieved:
  - Precise current matching for the current mirror.
  - Targeted frequency response for the LPF with high SNR and rejection.
  - Maximum gain for the differential amplifier within specified constraints.

- Tools and methods proved effective in enhancing design automation and reducing manual intervention.

## Future Work
- Explore advanced optimization techniques like Accelerated Proximal Gradient Descent (APGD).
- Integrate machine learning models to predict optimal configurations and streamline the design process.
- Expand the scope to include additional circuit blocks and higher frequency ranges.

## Acknowledgments
This project was developed under the guidance of **Prof. Louay Bazzi** and **Prof. Issam Lakkis** and with support from **Ubilite**. Contributions were made by:
- **Nour Shammaa**  
- **Hadi Dayeh**
-  **Riwa El Kari**  
- **Shafik Houeidi**  
- **Tamer Slim**  
- **Mahdi Zwain**

