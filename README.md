# Governance Effectiveness and Control of Corruption in Global Society (2013-2023)

There are moments when the official story of a country and the lived conditions of its people no longer move together. Institutions look solid on paper. Indicators suggest order, control, procedure. And yet development stalls, or arrives unevenly, or never quite reaches those who are meant to benefit from it. This project begins in that fracture.

Built as an academic machine learning project by **Soledad Yash**, the work examines how governance quality and human development relate across countries from 2013 to 2023. It uses governance indicators from the **World Governance Indicators** together with the **Human Development Report** to study whether stronger institutional performance actually travels alongside better human outcomes, or whether deeper structural forces continue to shape the distance between the two.

## What this project does

The notebook moves through the problem in stages:

- it reshapes and aligns governance and development datasets across country and year
- it examines the structure of the combined panel through exploratory analysis
- it applies clustering methods to identify country groupings and structural divergence
- it uses time-series forecasting to extend HDI trajectories beyond the observed period

The result is not a claim of final truth. It is a disciplined attempt to read the relationship between institutional form and social outcome without treating either one as self-explanatory.

## Main analytical components

- data cleaning and panel-style merging
- exploratory data analysis
- feature scaling
- **K-Means clustering**
- **Agglomerative clustering**
- validation with **Silhouette Score** and **Davies-Bouldin Index**
- interpretation of governance-development incongruence
- **ARIMA / time-series forecasting** for HDI trends

## Repository contents

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

## Why it matters

This project speaks to themes that return often in my work:

- analytics used to read institutions rather than decorate them
- governance and risk seen through outcomes, not only frameworks
- public-interest analysis grounded in structure, asymmetry, and historical constraint

## Reproducibility notes

- This repository is shared as a **historical academic work**.
- The notebook reflects the original assignment-era workflow, with light cleanup for portfolio publication.
- Some formatting traces and execution artefacts remain consistent with that academic context.

## Academic and IP statement

This repository contains academic work authored by **Soledad Yash** and is shared for portfolio, research communication, and professional visibility.

- The framing, interpretation, and assembly of the project are presented as the author's work.
- Source datasets remain subject to the terms of their original owners.
- The academic context is acknowledged for transparency and context only.

See [ACADEMIC_USE_AND_IP.md](./ACADEMIC_USE_AND_IP.md) for the longer statement.

## AI use disclosure

AI-assisted support may have been used in limited surrounding tasks such as drafting support, structural editing, or explanation. Final responsibility for validation, interpretation, submission, and publication remains with **Soledad Yash**.

See [AI_USE_DISCLOSURE.md](./AI_USE_DISCLOSURE.md) for a fuller note on limitations, boundaries, and security awareness.

## Author

**Soledad Yash**  
Dublin, Ireland  
[LinkedIn](https://www.linkedin.com/in/soledad-yash)  
[GitHub](https://github.com/moonexca)
