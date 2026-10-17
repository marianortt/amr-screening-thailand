# AMR Screening Cost Analysis – Thailand

## Overview

This repository contains an Excel-based pilot cost analysis model developed to evaluate the costs of preoperative screening for antimicrobial-resistant bacteria in patients undergoing elective colorectal surgery in Thailand.

The model accompanies the manuscript:

**Evaluating screening-based interventions for controlling WHO-priority bacteria in Thai hospitals: a review of evidence and a pilot cost analysis**

## Model description

The model compares two strategies:

1. **No screening (standard care):** Patients receive standard antibiotic prophylaxis without prior screening.
2. **Screening:** Patients are screened for resistant bacteria before surgery. Antibiotic prophylaxis is selected according to the screening results.

The screening strategy considers three mutually exclusive patient groups:

- Non-carriers
- Third-generation cephalosporin-resistant Enterobacterales (3GCR) carriers
- Carbapenem-resistant Gram-negative bacteria (CR) carriers

For each group, the model evaluates three possible clinical outcomes:

- No surgical site infection (N-SSI)
- Surgical site infection caused by susceptible bacteria (S-SSI)
- Surgical site infection caused by resistant bacteria (R-SSI)

## Model inputs

The Excel workbook includes:

- Prevalence of antimicrobial-resistant bacterial carriage
- Probabilities of surgical site infections
- Antibiotic prophylaxis and treatment costs
- Screening and diagnostic costs
- Length of antibiotic treatment
- Length of hospital stay
- Antimicrobial-associated societal cost components

Base-case parameters were selected for the modelled scenario using published evidence and modelling assumptions.

## Sensitivity analysis

The model supports deterministic one-way sensitivity analysis.

In the associated study, 16 input parameters were independently varied by ±10% around their base-case values to assess their influence on the incremental cost of screening.

## Repository contents

- `[Public] SSI Cost Analysis v09(2).xlsx` – Excel cost analysis model.

The workbook includes the model calculations, input parameters, and supporting price information.

## How to use

1. Download the Excel workbook.
2. Open it using Microsoft Excel.
3. Navigate to the `Cost Model` worksheet.
4. Review the base-case parameters and calculated costs.
5. Modify the unlocked input parameters to explore alternative scenarios.
6. Review the updated model outputs.

The workbook contains protected cells to prevent accidental modification of formulas.

## Limitations

This is an exploratory cost analysis model, not a validated clinical decision-support tool.

The model incorporates simplifying assumptions, including mutually exclusive carriage groups, perfect screening accuracy, and predefined treatment pathways.

Parameter values are informed by published literature but do not necessarily represent directly observed clinical estimates.

The model evaluates costs rather than cost-effectiveness and should not be used to guide individual patient treatment decisions.

## Citation

If you use this model, please cite the associated manuscript:

Ratto M, et al. Evaluating screening-based interventions for controlling WHO-priority bacteria in Thai hospitals: a review of evidence and a pilot cost analysis.

Full publication details and DOI will be added when available.

## Contact

For questions regarding the model, please refer to the corresponding author of the associated manuscript.
