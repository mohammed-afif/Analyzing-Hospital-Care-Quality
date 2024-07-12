# Analyzing Hospital Care Quality

Project Overview:

Objective:

Analyze the HCAHPS survey results to determine if the initiative has successfully incentivized hospitals to improve their quality of care.


Key Questions:

- Have hospitals' HCAHPS scores improved over the past 9 years?

- Are there specific areas where hospitals have made more progress than others?

- What major areas of opportunity remain?

- What recommendations can be made to hospitals to help them further improve the patient experience?

------------------------------------------------------------------------------------------------------------------

Methodology:

Data Exploration: understanding what the data fields represent and explore the tables and columns of each data set.

Data Cleaning :

1- Rows Removed - 5,772 rows with "Not available" in the "Completed Survey" column were excluded and 2 rows with "Not available" in the "Response Rate" column were removed.

2- Values Replaced - Categories in the "Completed Survey" column with values "Fewer than 50", "Fewer than 100", and "Between 100-299" were replaced with their respective averages.

The averages were calculated using the AVERAGEIF formula, considering only values less than 50, less than 100, and between 100 and 299, respectively.

3- Data Added - I Found that there were States not added to the States Table so I added them using ' Power Query '

4- Fix Date Columns and Scoring Percentage

Data Modeling

Data Analysis: Evaluated trends in HCAHPS scores, identifying areas of progress and opportunity.

------------------------------------------------------------------------------------------------------------------

Key Insights:

- Responses Rate Has declined from 31% in 2015 to 23% in 2023 which indicate Consumers lack of trust in the effectiveness of the Survey

- Discharge Information, Communication with Doctors and with Nurses are Best Performing Measure until the the latest Survey

- Hospital's HCAHPS Positive score improved in 2021 (2020 Survey ), but has since dipped.

- Care Transition and Quietness Environment needs improvement as Patient did NOT give good feedback

- South Dakota and Nebraska have most Satisfied patients


Recommendations:

- Increase the awareness of the completing the survey before the discharge process of patients.

- For effective care transition, establish clear communication protocols between healthcare providers, ensure thorough patient education and facilitate seamless information transfer.

- District of Columbia, Maryland, New Jersey, California, New York, Florida need more improvement in the measures like Care Transition, Cleanliness and Quietness of Hospitals, Communication about Medicine and Hospital Recommendation.

- Communications about Medicines and Quietness of Hospital Environment are major areas for opportunity of growth in the next years.


  
🔗 Explore the detailed findings and recommendations here:  https://app.powerbi.com/view?r=eyJrIjoiMjNkOTU4NWYtZTU1Zi00MGYwLTlmZWItZTg1YWJlOTkzZmI2IiwidCI6ImYwODM1ZmUyLTM5YzEtNDk4ZS1hMTkyLWEzODA2NzFiZDNjYyIsImMiOjl9&pageName=510ec56e8b069403c410


https://github.com/user-attachments/assets/c7a7c46e-c6e5-4024-a6c3-76e6ffc6e696

![Screenshot (376)](https://github.com/user-attachments/assets/7dd4a81b-5812-4eac-a23a-6236a99c9dd6)

![Screenshot (380)](https://github.com/user-attachments/assets/a912c6e3-7c7f-40a1-9bdb-45f821da1963)

