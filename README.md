*Healthcare*

**Objective**

Your mission is to utilize Tableau's robust capabilities to craft a compelling narrative from the provided datasets. This task will encompass thorough data preparation, intelligent data modeling, and the skillful application of calculated fields and Tableau functions for sophisticated analysis. The ultimate aim is to construct an interactive and intuitive dashboard in Tableau that showcases your key discoveries, offering concise, actionable insights into the optimization of hotel operations and performance.

**Data Source**
**HealthcareDataset1 This dataset contains the following columns:**

PatientID: A unique identifier for each patient. (Primary Key)
PatientName: Name of the patient.
Age: Age of the patient.
Gender: Gender of the patient.
BloodType: Blood type of the patient.
Diagnosis: The diagnosis given to the patient.
Treatment: The treatment provided to the patient.
AdmissionDate: Date when the patient was admitted.
DischargeDate: Date when the patient was discharged.
TotalBill: The total bill amount for the patient's treatment.
Full Prescription Details: Detailed prescription information including medication names, dosages, frequency, and duration.
HealthcareDataset2 This dataset contains the following columns:

PatientID: A unique identifier for each patient, corresponding to 'PatientID' in HealthcareDataset1.xlsx. (Foreign Key)
Hospital: The name of the hospital where the patient was treated.
DoctorName: Name of the doctor who treated the patient.
RoomNumber: The room number assigned to the patient.
DailyCost: The daily cost of the patient's treatment.
TreatmentType: Type of treatment provided.
RecoveryRating: A rating of the patient's recovery (out of 10).

**Dashboards:**

![Tb1](https://github.com/Saniyashakur22/Tableau_Project/assets/112815736/70554f47-a916-46c0-ae63-9dd6d771e204)
![Tb2](https://github.com/Saniyashakur22/Tableau_Project/assets/112815736/7b53656c-7d58-4d93-98f4-590b3c338d51)
![Tb3](https://github.com/Saniyashakur22/Tableau_Project/assets/112815736/a4213806-c680-4772-a2d4-7a26eb58aec6)
![TB4](https://github.com/Saniyashakur22/Tableau_Project/assets/112815736/2e8bc103-7185-4e26-8157-52a62137f19e)


**Task Performed**

- Correlation Analysis between Stay Duration and Recovery Rating: Investigate if there's a correlation between the duration of hospital stay and recovery ratings.
- Clustering for Patient Treatment Patterns: Use clustering to group patients based on treatment patterns and recovery outcomes.
- Advanced Calculations for Prescription Analysis: Analyze the 'Full Prescription Details' to identify the most commonly prescribed medications for each diagnosis.
- Hospital Efficiency Analysis: Measure hospital efficiency based on average stay duration, recovery ratings, and total bill.
- Custom Date Parsing for Admission Trends: Analyze admission trends by parsing 'AdmissionDate' into day of the week and month.
- Dynamic Filters for Patient Demographics: Create dynamic filters to explore data based on patient demographics like age, gender, and blood type.
- Time-Series Forecasting for Hospital Admissions: Use Tableau's forecasting features to predict the number of hospital admissions for the next 6 months. Base your forecast on  trends observed in 'AdmissionDate' and various diagnoses.


**Key Insights**
- The total number of female patients were 337, male patients were 329 and other patients 334 in 3 years.

- The recovery rating for Diabetes is increasing over the years.

- Using the time series forecasting I forcasted the no. of patients for each diagnosis.

- David Moore checks the maximum no. of patients.

- Cedar Senai Clinic is the most expensive hospital followed by Green Valley Medical Center and the least expensive hospital is Silver Oak Medical Plaza.

- Meple Groove Health Facility has the overall highest recovery rating.

- For Diabetes the Cedar Sanai Clinic's Doctor Elizabeth Davis has the highest recovery rating.

- The number patients going for Mental Therapy as treatment type are also increasing over years.





