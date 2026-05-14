# Governance Effectiveness and Control of Corruption in Global Society (2013-2023)

Academic machine learning project by **Soledad Yash** exploring how governance quality and human development interact across countries from 2013 to 2023.

## Overview

This repository contains a historical academic submission originally developed for the **Machine Learning for Business** module at **CCT College Dublin**. The project combines:

- governance indicators from the **World Governance Indicators**
- human development indicators from the **Human Development Report**
- clustering methods to identify structural country groupings
- time-series forecasting to examine future HDI trajectories

The analytical framing connects data science with questions relevant to governance, risk, compliance, institutional performance, and long-term development outcomes.

## Research Question

The central question is whether stronger institutions consistently lead to better human development outcomes, or whether deeper historical, geopolitical, and structural factors continue to shape that relationship.

## Methods

The notebook applies a workflow that includes:

- data reshaping, cleaning, and panel-style merging
- exploratory data analysis
- feature scaling and comparative clustering
- **K-Means**
- **Agglomerative Clustering**
- cluster validation using **Silhouette Score** and **Davies-Bouldin Index**
- governance-development incongruence interpretation
- **ARIMA / time-series forecasting** for HDI trend analysis

## Repository Contents

- [MachineLearning_SoledadYash.ipynb](./MachineLearning_SoledadYash.ipynb): main notebook
- [CA1_Report_SoledadYash_GRC_Final.docx](./CA1_Report_SoledadYash_GRC_Final.docx): written report
- [HDR_2013_2023.csv](./HDR_2013_2023.csv): Human Development Report source data
- [WGI_Data_2013_2023.csv](./WGI_Data_2013_2023.csv): processed World Governance Indicators data
- [f70b79f5-0f3c-4a25-86e6-dd846374fe51_Series - Metadata.csv](./f70b79f5-0f3c-4a25-86e6-dd846374fe51_Series%20-%20Metadata.csv): metadata reference
- [P_Data_Extract_From_Worldwide_Governance_Indicators.zip](./P_Data_Extract_From_Worldwide_Governance_Indicators.zip): original archive source

## Environment

The notebook uses Python libraries including:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `scipy`
- `statsmodels`
- `pmdarima`
- `geopandas`
- `pycountry-convert`

See [requirements.txt](./requirements.txt) for a lightweight environment list.

## Reproducibility Notes

- This repository is published as a **historical academic work**, not as a newly rebuilt production project.
- The notebook reflects the state of the submission at the time of the assignment, with light repository cleanup for portfolio presentation.
- Some outputs, formatting artefacts, and notebook execution traces may remain consistent with an academic workflow.

## Academic and IP Statement

This repository contains academic work authored by **Soledad Yash**. It is shared for portfolio, research communication, and professional visibility purposes.

- The analytical framing, interpretation, and project assembly are presented as the author's academic work.
- Source datasets come from external public or institutional data sources and remain subject to their own usage terms.
- The university or module context is acknowledged, but publication here does **not** imply endorsement by the institution.
- If any institution-specific material requires removal or adjustment, the repository should be updated accordingly.

See [ACADEMIC_USE_AND_IP.md](./ACADEMIC_USE_AND_IP.md) for the longer statement.

## AI Use Disclosure

AI-assisted support may have been used in limited ways during the broader research and documentation process, including drafting support, restructuring ideas, or code explanation. Final responsibility for verification, interpretation, submission, and publication remains with **Soledad Yash**.

See [AI_USE_DISCLOSURE.md](./AI_USE_DISCLOSURE.md) for a fuller note on boundaries, limitations, and security awareness.

## Portfolio Intent

This project is relevant to roles and themes such as:

- data analytics
- GRC-adjacent analysis
- public policy and governance analysis
- risk and institutional performance
- socially grounded data storytelling

## Author

**Soledad Yash**  
Dublin, Ireland  
[LinkedIn](https://www.linkedin.com/in/soledad-yash)  
[GitHub](https://github.com/asolyash)
