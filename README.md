# TaletrectinibPBPK

# A Physiologically Based Pharmacokinetic Model of the ROS1/NTRK Inhibitor Taletrectinib in Dogs and Humans

Please refer to the manuscript for additional details once it is published. 

Wu PY, Wang L, Lin Z. (2026). A physiologically based pharmacokinetic model of the ROS1/NTRK inhibitor taletrectinib in dogs and humans. Under review.

## Overview

This repository contains the model and data files supporting the development and evaluation of physiologically based pharmacokinetic (PBPK) models for taletrectinib in dogs and humans.

## Repository Contents

### Dog PBPK Model

- `Dog_10kg` – dog physiology file used for PBPK simulations.
- `Zhu et al. (2024) Dogs_IV_10mg.ipd` – dog IV dataset used for model development.
- `Zhu et al. (2024) Dogs_PO_50mg.opd` – dog PO dataset used for oral absorption calibration.
- `Taletrectinib Dog PBPK.mdb` – GastroPlus PBPK model file for dogs.

### Human PBPK Model

- `HumAmeMalHlthy50YO_89.02kg_28.86BMI` – human physiology file used for model development and internal validation.
- `HumJpMalHlthy51YO_58.41kg_21.97BMI` – Japanese human physiology file used for external validation.
- `Papadopoulos et al. 2020 PO 400 fasted.opd` – 400-mg fasted dataset used for model development.
- `Papadopoulos et al. 2020 PO 400 fed.opd` – 400-mg fed dataset used for internal validation.
- `Fujiwara et al. 2018 PO 400mg.opd` – 400-mg once-daily external validation dataset.
- `Fujiwara et al. 2018 PO 600mg.opd` – 600-mg once-daily external validation dataset.
- `Fujiwara et al. 2018 PO 800mg.opd` – 800-mg once-daily external validation dataset.
- `Taletrectinib Human PBPK.mdb` – GastroPlus PBPK model file for humans.

### Compound Information

- `Structure2D_COMPOUND_CID_72202474` – 2D chemical structure file for taletrectinib.

## Software

- GastroPlus v9.9 – PBPK model development and simulation
- ADMET Predictor v11.2.0.0 – prediction of selected model parameters
- WebPlotDigitizer v5.2 – digitization of published pharmacokinetic data
- R v4.3.2 and RStudio v2026.8.0.187 – model evaluation and statistical analyses
