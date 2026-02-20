### 📊 Flow of project

- Dataset is downloaded from Maven Analytics Hospital Patient Record [Link here](https://mavenanalytics.io/data-playground/hospital-patient-records)
- From this, you get [encounters.csv](https://github.com/akmalbakeri/SQL/blob/main/Hospital_record/encounters.csv) and also [hospital_analytics_questions.sql](https://github.com/akmalbakeri/SQL/blob/main/Hospital_record/hospital_analytics_questions.sql)
- From hospital_analytics_questions.sql, Maven posed some query to answer like below, than I already query in MySQL in [questionbased.sql](https://github.com/akmalbakeri/SQL/blob/main/Hospital_record/questionbased.sql)
- This visualization produced same result as MySQL query in questionbased.sql but 2 parts objective only.

 
### 🏥 Hospital Records Dashboard — encounters Overview
-- OBJECTIVE 1: ENCOUNTERS OVERVIEW

 a. How many total encounters occurred each year?  
 b. For each year, what percentage of all encounters belonged to each encounter class (ambulatory, outpatient, wellness, urgent care, emergency, and inpatient)?  
 c. What percentage of encounters were over 24 hours versus under 24 hours?  

-- OBJECTIVE 2: COST & COVERAGE INSIGHTS

 a. How many encounters had zero payer coverage, and what percentage of total encounters does this represent?  
 b. What are the top 10 most frequent procedures performed and the average base cost for each?  
 c. What are the top 10 procedures with the highest average base cost and the number of times they were performed?  
 d. What is the average total claim cost for encounters, broken down by payer?  


### 📈 VISUALIZATION BY TABLEAU
- Visualization of query answer is separated into 2 dashboards.

- Dashboard 1 (OBJECTIVE 1: ENCOUNTERS OVERVIEW)
 [View interactively on Tableau Public](https://public.tableau.com/app/profile/akmal.bakeri/viz/hospitalrecord_17715959336800/Dashboard1)
 ![Hospitalrecord1.jpg](https://github.com/akmalbakeri/Visualization/blob/main/Hospital_record/Hospitalrecord1.jpg)

- Dashboard 2 ( OBJECTIVE 2: COST & COVERAGE INSIGHTS)
[View interactively on Tableau Public](https://public.tableau.com/app/profile/akmal.bakeri/viz/hospitalrecord-2/Dashboard2)
  ![Hospitalrecord2.jpg](https://github.com/akmalbakeri/Visualization/blob/main/Hospital_record/Hospitalrecord2.jpg)



