# Patient Data with Lithium Concentration Levels
<div style="text-align: center;">
  <img src="images/Lithium-carbonate.png" alt="Lithium Carbonate" width="400" style="display:inline-block; margin-right:20px;"/>
  <img src="images/Lithium-carbonate-form.png" alt="Lithium Carbonate Formula" width="400" style="display:inline-block;"/>
</div>

## Description
This dataset contains information on <span style="color:blue;">**236 patients**</span>, including various clinical and demographic variables. The dataset is designed for use in training machine learning models to <span style="color:blue;">**predict lithium concentration levels**</span> based on patient data.

<div style="text-align: center;">
  <img src="images/lithium-pills.jpg" alt="Lithium pills" width="400" style="display:inline-block; margin-right:20px;"/>
</div>

## Dataset Structure
The dataset is provided as a CSV file (`patients_data.csv`) with the following columns:

- **Patient_ID**: Unique identifier for each patient.
- **Daily_Dose**: Daily dose of medication (in mg). Lithium doses typically range from <span style="color:blue;">**300 to 900 mg per day**</span>, but higher doses (up to <span style="color:blue;">**1200 mg/day**</span>) are sometimes prescribed.
- **Age**: Age of the patient (in years). Patients' ages can realistically range from <span style="color:blue;">**18 to 65 years old**</span>.
- **ALT**: Alanine aminotransferase levels (in U/L). Normal range is typically <span style="color:blue;">**7-56**</span>.
- **AST**: Aspartate aminotransferase levels (in U/L). Normal range is typically <span style="color:blue;">**10-40**</span>.
- **ALB**: Albumin levels (in g/dL). Normal range is typically <span style="color:blue;">**3.5-5.0**</span>.
- **TBIL**: Total bilirubin levels (in mg/dL). Normal range is typically <span style="color:blue;">**0.1-1.2**</span>.
- **Cr**: Creatinine levels (in µmol/L). Normal range for creatinine is typically <span style="color:blue;">**60-110**</span> for women and <span style="color:blue;">**70-120**</span> for men.
- **Zopiclone**: Binary indicator **(0 or 1)** if Zopiclone is co-administered.
- **Quinine**: Binary indicator **(0 or 1)** if Quinine is co-administered.
- **Tipine**: Binary indicator **(0 or 1)** if Tipine is co-administered.
- **Lorazepam**: Binary indicator **(0 or 1)** if Lorazepam is co-administered.
- **Olanzapine**: Binary indicator **(0 or 1)** if Olanzapine is co-administered.
- **Valproate**: Binary indicator **(0 or 1)** if Valproate is co-administered.
- **Metoprolol**: Binary indicator **(0 or 1)** if Metoprolol is co-administered.
- **Statins**: Binary indicator **(0 or 1)** if Statins are co-administered.
- **Li_Concentration**: Lithium concentration levels (in mmol/L). Therapeutic range for lithium is typically <span style="color:blue;">**0.6-1.2 mmol/L**</span>.

## Data Summary
- **Number of Entries**: 236
- **Lithium Concentration Range**: 0.6 to 2.0 mmol/L
- **Higher-than-Typical Lithium Concentrations**: Approximately <span style="color:blue;">**20%**</span> of the entries have lithium concentrations above the typical therapeutic range (1.2 to 2.0 mmol/L).

## Usage
<div style="text-align: center;">
  <img src="images/chart.jpeg" alt="Lithium pills" width="400" style="display:inline-block; margin-right:20px;"/>
</div>

This dataset can be used for various machine learning tasks, including but not limited to:
- Predicting lithium concentration levels based on patient clinical and demographic data.
- Studying the relationship between lithium concentration and various clinical variables.
- Evaluating the performance of regression models in predicting lithium levels.

## License
This dataset is provided for <span style="color:blue;">**educational and research purposes**</span>. Proper attribution should be given if the dataset is used in any publications or presentations.
