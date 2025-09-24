# HealthInsuranceDataUS

## Table of Contents
1. [Description](#description)
2. [Motivation](#motivation)
3. [Dataset](#dataset)
4. [Files in Repository](#files-in-repository)
5. [Features](#features)
6. [Installation](#installation)
7. [Usage](#usage)
8. [Visualizations & Images](#visualizations--images)
9. [Reports & Presentations](#reports--presentations)
10. [Acknowledgements](#acknowledgements)
11. [License](#license)

---

## Description
This repository explores the **U.S. Health Insurance dataset** through **data analytics and linear regression**.  
It includes:
- A Jupyter Notebook (`project_insurance_analysis.ipynb`)
- The raw dataset (`insurance.csv`)
- A PDF report and PowerPoint presentation
- A set of exported images and plots

---

## Motivation
Health insurance data reveals relationships between **age, BMI, number of children, smoking habits, and insurance costs**.  
This project demonstrates:
- Data cleaning
- Exploratory analysis
- Regression modeling
- Communicating results via slides, reports, and visuals

---

## Dataset
- **Source**: [Kaggle – US Health Insurance Dataset](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset/data)  
- **File**: `insurance.csv`  
- Contains demographic and lifestyle factors with insurance charges.  
- Key columns: `age`, `sex`, `bmi`, `children`, `smoker`, `region`, `charges`.

---

## Files in Repository
- `insurance.csv` → dataset  
- `project_insurance_analysis.ipynb` → Jupyter notebook with code & analysis  
- `Analysis of US Health Insurance data.pdf` → written report  
- `Analysis of US Health Insurance data.pptx` → presentation slides  
- `images/` → exported plots and figures  
- `README.md` → project description  

---

## Features
- Linear regression to predict insurance charges  
- Exploratory visualizations (BMI vs charges, smoker impact, region analysis)  
- Correlation and statistical insights  
- Reports and slides summarizing results  

---

## Installation
Clone the repo:
```bash
git clone https://github.com/BjoernMueller13/HealthInsuranceDataUS.git
cd HealthInsuranceDataUS
```

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

---

## Usage
- Open the Jupyter Notebook:
```bash
jupyter notebook project_insurance_analysis.ipynb
```
- Run cells to reproduce analysis and plots  
- Review the PDF / PPTX for presentation of results  

---

## Reports & Presentations
The full results are also available as downloadable files:

- 📄 [Analysis of US Health Insurance data (PDF)](presentations/_Analysis%20of%20US%20Health%20Insurance%20data.pdf)  
- 📊 [Analysis of US Health Insurance data (PPTX)](presentations/_Analysis%20of%20US%20Health%20Insurance%20data.pptx)  

These documents provide a structured overview of methodology, findings, and conclusions.

---

## Visualizations & Images
The following images are included in the repository. Each one can be described in more detail:

*Distribution*
- Even distribution in age
- BMI: Gauss curve
- Charges: great left skew

*Outliers*
- 9 Outliers at BMI
- Over 100 Outliers at Charges

![Age, BMI, Charges Boxplots](images/_AGE%20BOXPLOT_BMI%20BOXPLOT_CHARGES%20BOXPLOT.png)  
![Age, BMI, Charges Distributions](images/_AGE%20DISTRIBUTION_BMI%20DISTRIBUTION_CHARGES%20DISTRIBUTION.png) 

*Observation*
- Relatively even distribution between sex and region
- Uneven distribution between
  - Smokers
  - Children (w/ has a far higher concentration)

![Sex, Region, Smoker, Children Distributions](images/_SEX%20DISTRIBUTION_REGION%20DISTRIBUTION_SMOKER%20DISTRIBUTION_CHILDREN%20DISTRIBUTION.png)  
![Distribution of Sex, Regions, Smokers, Children](images/_DISTRIBUTION%20OF%20SEX_DISTRIBUTION%20OF%20REGIONS_DISTRIBUTION%20OF%20SMOKERS_DISTRIBUTION%20OF%20CHILDREN.png) 

*Observation*
- No great variation of smokers by region
- Small outlier: Southeast

![Smokers by Region](images/_SMOKERS%20AT%20NORTHEAST_SMOKERS%20AT%20NORTHWEST_SMOKERS%20AT%20SOUTHEAST_SMOKERS%20AT%20SOUTHWEST.png)  

*Observation*
- Relatively even distribution of smokers at a certain sex
- Males slightly higher than females

![Smokers by Males/Females](images/_SMOKERS%20AT%20MALES_SMOKERS%20AT%20FEMALES.png)  
![Distribution of Smokers by Sex](images/DISTRIBUTION%20OF%20SMOKERS%20BY%20SEX.png)  

*Observation*
Look on heatmap → lowest horizontal line
- Greatest impact by age and BMI
- Low impact by number of children

![Correlation Heatmap](images/CORRELATION%20HEATMAP.png)  

Observation
 Impact by sex is evenly distributed by male and female
 Age is a higher impact
* IMAGE "RELATIONSHIP: CHARGES PER SEX" TO BE UPLOADED *


![Charges by Age Type and Risk](images/CHARGES%20BY%20AGE%20TYPE%20AND%20RISK.png)  
![Charges by BMI and Region](images/CHARGES%20BY%20BMI%20AND%20REGION.png)  
![Charges by Number of Children](images/CHARGES%20BY%20NUMBER%20OF%20CHILDREN.png)  


 
![Distribution of BMI Type](images/_Distribution%20of%20BMI%20Type.png)  
![Distribution of Risk Type](images/_DISTRIBUTION%20OF%20RISK%20TYPE.png)  
 




---

## Acknowledgements
- Dataset: [Kaggle – US Health Insurance Dataset](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset/data)  
- Inspired by FreeCodeCamp guide on [writing good READMEs](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)  

---

## License
MIT License – free to use, modify, and distribute.
