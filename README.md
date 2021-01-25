# Capstone-Diabetes_Readmission: Predicting 30-Day Hospital Readmission for Diabetes Patients


## Basic Explanation
Hospital readmission is considered a key metric in order to assess health center performances. Readmissions involve different consequences such as the patient’s health condition, hospital operational efficiency but also cost burden from a wider perspective. It is important to know if a patient will be readmitted into a hospital within 30-days. The reason is that you can change the treatment, in order to avoid a readmission. Predicting unplanned readmission is of prime interest due to its inherent uncertainty. Unplanned readmission is the most useful type when evaluating the quality of care of a hospital as it highlights a
practitioner’s diagnosis or treatment error. Beyond being a core indicator of the quality of care, unplanned readmissions also constitute a financial problem for nations. Therefore with a predictive model to assess unplanned readmission risk could optimize the quality of hospital services and state Medicare.

The purpose of this project is to propose a prediction model for less than 30-day readmission among diabetes patients in US hospitals. The analysis will be based on risk factors such as a patient’s demographics, admission details, diagnosis, and medical data. The ability to predict readmission in less than 30-days allows health centers to better anticipate and address unplanned readmissions while improving their quality of care and costefficiency.

In this database, you have 3 different outputs:

1. No readmission;
2. A readmission in less than 30 days (this situation is not good, because maybe your treatment was not appropriate);
3. A readmission in more than 30 days (this one is also not so good, however, the reason can be the state of the patient.

In this context, you can see different objective functions for the problem. You can try to figure out situations where the patient will not be readmitted, or if their are going to be readmitted in less than 30 days (because the problem can the the treatment), etc… Make your choice and let's help them creating new approaches for the problem.

## Content
"The data set represents 10 years (1999-2008) of clinical care at 130 US hospitals and integrated delivery networks. It includes over 50 features representing patient and hospital outcomes. Information was extracted from the database for encounters that satisfied the following criteria.

1. It is an inpatient encounter (a hospital admission).
2. It is a diabetic encounter, that is, one during which any kind of diabetes was entered to the system as a diagnosis.
3. The length of stay was at least 1 day and at most 14 days.
4. Laboratory tests were performed during the encounter.
5. Medications were administered during the encounter.

The data contains such attributes as patient number, race, gender, age, admission type, time in hospital, medical specialty of admitting physician, number of lab test performed, HbA1c test result, diagnosis, number of medication, diabetic medications, number of outpatient, inpatient, and emergency visits in the year before the hospitalization, etc.

https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008

## Source
The data are submitted on behalf of the Center for Clinical and Translational Research, Virginia Commonwealth University, a recipient of NIH CTSA grant UL1 TR00058 and a recipient of the CERNER data. John Clore (jclore '@' vcu.edu), Krzysztof J. Cios (kcios '@' vcu.edu), Jon DeShazo (jpdeshazo '@' vcu.edu), and Beata Strack (strackb '@' vcu.edu). This data is a de-identified abstract of the Health Facts database (Cerner Corporation, Kansas City, MO).

## Original source of the data set
https://archive.ics.uci.edu/ml/datasets/Diabetes+130-US+hospitals+for+years+1999-2008
