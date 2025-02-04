# Healthcare-Management-Optimization-Analysis-Dashboard-Creation

<h1>Project Background</h1>
The Healthcare Management Optimization project leverages data from 2019 to May 2024 across multiple hospitals to provide critical insights into hospital operations, patient care, and financial management. This project aims to assist hospital administrators and healthcare providers in making data-driven decisions to improve efficiency, optimize resources, and enhance patient care.


With the rising demand for urgent, elective, and emergency care, hospitals face challenges in optimizing patient stay durations, managing billing practices, and ensuring efficient allocation of resources such as blood supply and medical staff. The dataset used in this project provides a comprehensive view of hospital operations, including patient demographics, hospital stay durations, medical conditions, insurance billing, and doctor performance across various facilities.


<h3>Key insights and recommendations are provided across the following areas:</h3>
1. Patient Stay Duration: Evaluation of patient stay lengths across hospitals, aimed at improving capacity management for both short- and long-term care.
2. Billing Practices by Insurance Providers: Analysis of billing discrepancies and trends across different insurance providers, helping to identify areas for cost optimization.
3. Blood Supply Management: Insights into universal blood donor and receiver distributions to ensure timely and efficient transfusions.
4. Doctor Performance: Evaluation of doctors based on the number of patients treated and their associated billing, offering insights into workload and revenue contribution.<br>
5. Medication Trends: An analysis of the most commonly prescribed medications for various medical conditions, guiding pharmacy inventory management.

<h3>Tools Used</h3>
1. An interactive Power BI dashboard accompanies this project to provide a dynamic and visual exploration.
2. Excel is used to inspect, clean, and prepare the data for analysis, ensuring accurate and actionable insights.
3.The SQL queries regarding various business questions and data preparation for the Power BI dashboard.
By harnessing this data, healthcare providers can address key operational challenges, reduce costs, and improve the overall quality of patient care.

<h3>Dataset</h3>
This project utilizes a dataset of 55501 patient records from multiple hospitals, highlighting key metrics such as hospital stay duration, billing amounts, insurance providers, and medical conditions.

<img width="460" alt="image" src="https://github.com/user-attachments/assets/c50c82e5-9eaa-4029-87f2-b7c4d2c2bd33" />

<h2>Executive Summary</h2>
Here the Tableau dashboard is explained in detail, and the SQL business question answers are thoroughly covered.

<h3>Financial & Insurance Dashboard</h3>
The total billing amount reached <b>$1.40B</b> across all hospitals, with significant growth in 2020 before seeing a dip in 2024. However, the data only reflects the numbers up to May 2024, so there is potential for an increase by the end of the year. This downward trend highlights the dynamic nature of healthcare demands and the impact of external factors on revenue, possibly due to operational adjustments post-pandemic.


The average billing per patient is <b>$25.54K</b>, with minor variations between insurance providers. <b>Medicare</b> leads with an average billing of <b>$25.63K</b>, while <b>UnitedHealthcare</b> follows closely at <b>$25.41K</b>, suggesting consistent pricing strategies across the board.


Patients in the <b>30-39</b> age group contributed the highest total billing <b>($208.17M)</b>, followed by those aged <b>40-49</b> with <b>$204.83M</b>, indicating that middle-aged patients are a key demographic for healthcare spending. This also suggests that individuals in these age groups may be more prone to health issues, necessitating higher healthcare expenditures.


Admissions are evenly distributed among <b>Elective (33.70%), Urgent (33.42%)</b>, and <b>Emergency (32.88%)</b> cases, demonstrating that all patient care types are significant contributors to overall billing.


<img width="608" alt="image" src="https://github.com/user-attachments/assets/faa14d26-4025-445e-84fb-68120d951c01" />

<h3>Patient Insight Dashboard</h3>
<b>Low-risk patients</b> contribute the most to total billing <b>($467M)</b>, while <b>high-risk patients</b> account for <b></b>$158M.</b> This indicates that routine monitoring and care for low-risk patients is a critical revenue stream, as they may require frequent checkups and follow-up appointments, even if their conditions are not life-threatening.

The number of patient admissions peaked in <b>2020 at 3,818</b>, followed by a gradual decline. The significant decrease in 2024 can be attributed to external factors like healthcare policies or global events. However, as the data only includes records up to May 2024, there is potential for admission rates to increase by the end of the year.

The gender distribution is nearly balanced, with <b></b>50.02% male</b> and <b>49.98% female</b> patients, indicating equitable access to healthcare services across genders.<br>
Patients aged <b><50-59 years and 30-39 years</b> have the <b>highest admission rates</b>b>, representing critical age groups for hospital resource planning and patient care management. These groups may require urgent care more frequently, highlighting the need for hospitals to prioritize resource availability for these patients.


<img width="604" alt="image" src="https://github.com/user-attachments/assets/525896c9-d137-4589-9826-bc3a42a07932" />


<h3>Hospital & Doctor Dashboard</h3>
<b>LLC Smith hospital</b> leads in overall billing, contributing <b>$423,591</b>, along with the highest elective admissions. Ltd Smith hospital follows closely behind, showcasing their efficiency and revenue generation capabilities. Some refund amounts were also noted, indicating billing adjustments, possibly due to insurance claims or patient refunds.


<b>Michael Smith</b> is the top-performing doctor, generating <b>$201K</b> in billings for high-risk patients. <b>John Smith</b> and Robert Smith significantly contribute with <b>$275K and $186K</b>, respectively. Interestingly, low-risk patients who require discharge and follow-up appointments contribute a substantial portion of the total billing. This suggests that even though these patients are at lower risk, maintaining contact and follow-up with their doctors generates a considerable revenue stream.


The average length of stay varies between doctors, with <b>Jessica Johnson</b> having the shortest average stay of <b>19 days</b> for elective cases, while <b>William Johnson</b> averages <b>26 days</b>, highlighting differences in case complexity and doctor efficiency. Elective cases tend to have shorter average stays compared to emergency and urgent cases, which underscores the need for hospitals to adopt tailored resource management strategies based on admission type.


<img width="610" alt="image" src="https://github.com/user-attachments/assets/edac2c7d-ea39-4631-9807-368f9219293b" />


<h3>Common Medical Conditions and Medications SQL Analysis</h3>
1. Arthritis ranks highest in terms of medication demand, with 9,218 prescriptions recorded, emphasizing the significant pharmaceutical needs for managing chronic pain.
2. Diabetes and Hypertension follow as the next most common conditions, both requiring consistent medication management to prevent long-term complications. These conditions have a high impact on hospital resources and medication supply.
3. Aspirin is the most frequently prescribed medication for multiple conditions such as Arthritis, Asthma, and Cancer, highlighting its importance across treatment categories.
4. Paracetamol and Ibuprofen are widely prescribed for pain and inflammation, while Penicillin is commonly used for managing infections in Obesity and Diabetes patients. Additionally, Lipitor is essential for managing chronic diseases like Diabetes and Obesity, indicating its critical role in long-term treatment plans.

<img width="466" alt="image" src="https://github.com/user-attachments/assets/0f45007f-6ddc-4e01-90f4-aa042b8a5c1f" />


<img width="315" alt="image" src="https://github.com/user-attachments/assets/4bf9aca6-95fd-4377-8f10-2d8fa80fa5e6" />


<h4>Universal Blood Donors and Receivers:</h4>
There are <b>6,804 universal blood donors (O-)</b>, which are crucial for emergency situations, as O- blood can be safely transfused to any patient. This makes it a vital resource for hospitals, especially during shortages or emergencies.


<b>6,882 patients</b> are classified as universal receivers (AB+), which allows them to receive blood from any donor. This flexibility in transfusion provides hospitals with greater options for managing blood supply during critical times.


The near-equal distribution of <b>O- donors and AB+ receivers</b> ensures a balanced potential for blood supply and demand, helping hospitals mitigate shortages and optimize blood bank strategies.


A stored procedure, <b>Blood_Matcher</b>, was created to prioritize matching donors and receivers within the same hospital for faster and more efficient transfusions. For instance, Bobby Harvey, a 79-year-old AB+ patient, was successfully matched with multiple O- donors from different hospitals, ensuring a timely and compatible transfusion at Lester-Rogers hospital.

<img width="416" alt="image" src="https://github.com/user-attachments/assets/9b25c28f-e068-4480-8cd3-959ca11e4cfe" />


<img width="409" alt="image" src="https://github.com/user-attachments/assets/eba2b716-ea2a-4cd3-858c-a7ab43d554ac" />


<img width="419" alt="image" src="https://github.com/user-attachments/assets/c6c31318-cbfb-4e52-9234-df181ca2e6fd" />


<img width="468" alt="image" src="https://github.com/user-attachments/assets/ab0b1bd5-8c27-4835-b7c6-027201ad660a" />

<h2>Recommendations:</h2>
With the majority of patients aged 30-49 years contributing significantly to hospital revenue, target preventive care initiatives and resource allocation for this age group to enhance patient outcomes and reduce long-term healthcare costs.

Prioritize preventive care for high-billing conditions like obesity and diabetes, focusing on early intervention and management to reduce the need for costly treatments later on.

Despite the balance of O- universal donors and AB+ universal receivers, enhance blood bank management by optimizing cross-hospital donor-matching systems to ensure timely and efficient transfusions during emergencies.

Recognize and incentivize top-performing doctors such as Michael Smith and John Smith, who generate substantial revenue through high-risk and follow-up patients. Consider offering incentives and expanding their services to increase patient retention and maximize revenue.

Investigate the decline in total billing in 2024 and address operational inefficiencies or external factors that may have impacted hospital revenue. Adjust financial strategies for the remainder of the year to help recapture potential lost revenue.

To manage high medication demand for chronic conditions like Arthritis, Diabetes, and Hypertension, optimize pharmacy inventory by ensuring a steady supply of key medications, such as Aspirin, Paracetamol, and Lipitor, while minimizing costs through bulk purchasing or supplier negotiations.

Leverage historical data to optimize bed allocation, balancing resources between short- and long-term stays. This will ensure that hospitals can handle both urgent and elective admissions efficiently without overextending resources.

Strengthen relationships with key insurance providers like Cigna and Medicare to ensure steady patient admissions and maintain financial stability. Collaborating with these insurers can help streamline billing practices and reduce discrepancies.

Maintain an optimal inventory of high-demand medications like Aspirin and Paracetamol to ensure consistent pharmaceutical management. Regular audits of inventory can minimize shortages and prevent overstocking, while supplier negotiations can help manage costs.

<h2>Assumptions and Caveats:</h2>
Throughout the analysis, several assumptions were made to address data challenges and ensure the results remained accurate. The following assumptions and caveats are noted below:

The data analyzed includes records only up until May 2024, meaning that trends observed, such as total billing amounts and patient admissions, may change by the end of the year as new data becomes available.

Duplicate records for patient billing were identified and removed to ensure the accuracy of the financial analysis.

Negative and positive billing amounts were categorized into a new column titled "Type of Bill" to differentiate between refunds and normal transactions. Negative amounts were classified as Refund, and positive amounts were classified as Normal.

