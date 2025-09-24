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

---

<table>
<tr>
<td width="30%" valign="middle">

**Distribution of the Data**  
- Even distribution in age  
- BMI: Gauss curve  
- Charges: great left skew  

</td>
<td width="70%" align="center">

<img src="images/AGE_BOXPLOT_BMI_BOXPLOT_CHARGES_BOXPLOT.png" alt="Age, BMI, Charges Boxplots" width="600"/>  
<img src="images/AGE_DISTRIBUTION_BMI_DISTRIBUTION_CHARGES_DISTRIBUTION.png" alt="Age, BMI, Charges Distributions" width="600"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Outliers in the Data**  
- 9 Outliers at BMI  
- Over 100 Outliers at Charges  

</td>
<td width="70%" align="center">

<img src="images/AGE_BOXPLOT_BMI_BOXPLOT_CHARGES_BOXPLOT.png" alt="Age, BMI, Charges Boxplots" width="600"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Distribution of Sex, Regions, Smokers and Children**  
- Relatively even distribution between sex and region  
- Uneven distribution between  
  - Smokers  
  - Children (w/ has a far higher concentration)  

</td>
<td width="35%" align="center">

<img src="images/DISTRIBUTION_OF_SEX_DISTRIBUTION_OF_REGIONS_DISTRIBUTION_OF_SMOKERS_DISTRIBUTION_OF_CHILDREN.png" alt="Distribution of Sex, Regions, Smokers, Children" width="600"/>  

</td>
<td width="35%" align="center">

<img src="images/SEX_DISTRIBUTION_REGION_DISTRIBUTION_SMOKER_DISTRIBUTION_CHILDREN_DISTRIBUTION.png" alt="Sex, Region, Smoker, Children Distributions" width="600"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Distribution of Smokers per Region**  
- No great variation of smokers by region  
- Small outlier: Southeast  

</td>
<td width="70%" align="center">

<img src="images/SMOKERS_AT_NORTHEAST_SMOKERS_AT_NORTHWEST_SMOKERS_AT_SOUTHEAST_SMOKERS_AT_SOUTHWEST.png" alt="Smokers by Region" width="400"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Distribution of Smokers per Sex**  
- Relatively even distribution of smokers at a certain sex  
- Males slightly higher than females  

</td>
<td width="35%" align="center">

<img src="images/SMOKERS_AT_MALES_SMOKERS_AT_FEMALES.png" alt="Smokers at Males / Females" width="600"/>  

</td>
<td width="35%" align="center">

<img src="images/DISTRIBUTION_OF_SMOKERS_BY_SEX.png" alt="Distribution of Smokers by Sex" width="600"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Correlation Heatmaps**  
Look on heatmap → lowest horizontal line  
- Greatest impact by age and BMI  
- Low impact by number of children  

</td>
<td width="45%" align="center">

<img src="images/CORRELATION_HEATMAP.png" alt="Correlation Heatmap" width="600"/>  

</td>
<td width="35%" align="center">

<img src="images/CORRELATION_HEATMAP_GRAPHS.png" alt="Correlation Heatmap (Graphs)" width="600"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Charges per Sex**  
- Impact by sex is evenly distributed by male and female  
- Age is a higher impact  

</td>
<td width="70%" align="center">

<img src="images/RELATIONSHIP_-_CHARGES_PER_SEX.png" alt="Relationship - Charges per Sex" width="600"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Charges per smokers / non-smokers**  
- Critical impact by smoking  
- Age has an impact, too  

</td>
<td width="70%" align="center">

<img src="images/RELATIONSHIP_-_CHARGES_OF_SMOKERS_&_CHARGES_OF_NON-SMOKERS.png" alt="Relationship - Charges of Smokers & Non-Smokers" width="600"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Charges per Number of Children**  
- Number of children has almost no impact until a number of 3  
- Great decrease at 4 and 5 children  
- Great impact by smoking  

</td>
<td width="70%" align="center">

<img src="images/CHARGES_BY_NUMBER_OF_CHILDREN.png" alt="Charges by Number of Children" width="600"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Clustering of BMI according to current standards:**  
- BMI > 18.5 → Underweight  
- 18.5 < BMI < 25 → Normal Weight  
- 25 =< BMI < 30 → Overweight  
- 30 < BMI → Obesity  

**Observation**  
- High percentage of obesity and overweight  
- Keep in mind: BMI one of the highest impacts on charges  

</td>
<td width="70%" align="center">

<img src="images/Distribution_of_BMI_Type.png" alt="Distribution of BMI Type" width="400"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Charges by BMI and Region**  
- No underweight people in southeast  
- Highest charges for obesity  
- Tie 2nd highest charges for normal and overweight  
  - Assumption: affect by smokers  

</td>
<td width="70%" align="center">

<img src="images/CHARGES_BY_BMI_AND_REGION.png" alt="Charges by BMI and Region" width="600"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Clustering - Risk Level & Age**  
- Clustering to risk level:  
  - High risk: Obesity + Smoker  
  - Moderate risk: normal/overweight + smoker  
  - Else: low risk  
    
- Clustering by age:  
  - Age < 30 years  
  - 30 years < Age < 50 years  
  - Age > 50 years  

</td>
<td width="70%" align="center">

<img src="images/DISTRIBUTION_OF_RISK_TYPE.png" alt="Distribution of Risk Type" width="400"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Charges per Age Type & Risk**  
- Charges increase with risk level  
- Age has greater impact  

</td>
<td width="70%" align="center">

<img src="images/CHARGES_BY_AGE_TYPE_AND_RISK.png" alt="Charges by Age Type and Risk" width="600"/>  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="50%" valign="middle">

**KEY FINDINGS**  

*Findings (Data Distribution)*  
- Outliers:  
  - BMI: 9  
  - Charges: > 100 + Skew to the right  

- More or less balanced distribution per  
  - Age  
  - Sex  
  - Smokers  
  - Region  

</td>
<td width="50%" valign="middle">

*Insights*  
- Smoking has a high impact on charges  
- Also, obesity affects charges heavily  
- Charges rise continuously per age  
- Regional distribution of the factors including the sex mentioned above is relatively evenly done  
- Low impact on charges by the number of children  

</td>
</tr>
</table>

---

<table>
<tr>
<td width="30%" valign="middle">

**Linear Regression**  

*Key Points*  
- Mean Squared Error: 0.285
- R-squared (R²) on Test Set: 0.715

</td>
<td width="70%" align="center">

<img src="images/PREDICTED_VS._ACTUAL_VALUES.png" alt="Predicted vs. Actual Values" width="600"/>  

</td>
</tr>
</table>

---

## Acknowledgements
- Dataset: [Kaggle – US Health Insurance Dataset](https://www.kaggle.com/datasets/teertha/ushealthinsurancedataset/data)  
- Inspired by FreeCodeCamp guide on [writing good READMEs](https://www.freecodecamp.org/news/how-to-write-a-good-readme-file/)  

---

## License
MIT License – free to use, modify, and distribute.
