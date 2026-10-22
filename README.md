# Data and Code for Safety-Filtered DQN Microclimate Control in a 10-ft Container Vertical Farm

This repository provides the dataset, sanitized source code, and reproducibility materials associated with the IEEE Access manuscript:

**Safety-Filtered Deep Q-Network Microclimate Control in a 10-ft Container Vertical Farm: Real-Plant Deployment and Distributed-Sensor Validation**

## Authors

- Albert — Institut Teknologi Bandung / Institut Teknologi Del — ORCID: 0000-0003-2174-7595
- Good Fried Panggabean — Institut Teknologi Del
- Rahmat Romadhon — Institut Teknologi Bandung
- Endra Joelianto — Institut Teknologi Bandung — ORCID: 0000-0003-4496-6301

## Contents

- `data/IEEE_Access_DQN_Dataset.zip` — DQN deployment logs, sensor exports, rule-based comparison records, and processed summaries.
- `code/IEEE_Access_DQN_Source_Code_SANITIZED.zip` — DQN training, Jetson Nano deployment, rule-based controller, reward, action masking, and supporting code. Private credentials and local-network addresses have been removed/replaced with placeholders for public release.
- `reproducibility/IEEE_Access_DQN_Reproducibility_Package.zip` — synchronized spatial-audit data, 27-node temperature/humidity records, energy measurements, analysis scripts, derived tables, and reproduction notes used for the manuscript results.

## Key experimental context

The DQN was trained in a simplified stochastic environment and deployed on an NVIDIA Jetson Nano in a physical 10-ft container vertical farm. The real plant included a 1-PK air conditioner, humidifier, compressed-gas CO2 supply with solenoid control, artificial lighting, hydroponic circulation, and a distributed low-cost sensor network. The public dataset includes controller logs, microclimate measurements, actuator states, and measured electrical power used in the manuscript analyses.

## Reproducibility

Start with the reproducibility package. It contains the synchronized and derived data together with the scripts used to reproduce the spatial-compliance, runtime-mask, actuator-utilization, and energy-analysis results reported in the manuscript.

## Security and privacy note

The public source-code archive is sanitized. Deployment credentials, API/database tokens, and private local-network addresses are intentionally excluded. The control logic, DQN architecture, reward design, and analysis logic are unchanged by the sanitization.

## Citation

If you use these materials, please cite the associated IEEE Access article once published. A machine-readable citation record is provided in `CITATION.cff`.

## DOI / archival release

GitHub does not assign a DOI by itself. For a persistent DOI suitable for a data-availability statement, archive a tagged GitHub release with Zenodo (or another DOI-issuing research repository) and update `CITATION.cff` and the manuscript Data Availability statement with the resulting DOI.
