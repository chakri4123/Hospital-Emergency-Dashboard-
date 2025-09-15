# Hospital-Emergency-Dashboard
## 🎯 Project Objectives
Developed an interactive Power BI dashboard to monitor and analyze monthly hospital emergency room performance, enabling data-driven decisions through KPIs like patient admissions, wait times, demographic trends, department referrals, and time-based resource planning.

The primary business requirements for this dashboard are to:

Measure and track the total number of patients visiting the ER daily.

Calculate and monitor the average patient wait time.

Analyze the average patient satisfaction score to evaluate service quality.

Track the number of patients admitted to the hospital from the ER.

Monitor the volume of departmental referrals to understand specialty demand.

## 📊 Dataset
The analysis is based on the Hospital ER_Data.csv file. This dataset contains transactional records for each patient visit to the ER.

Data Dictionary
The key fields used in this analysis are defined in the Data Terminology.docx file and include:

Patient ID: A unique identifier for each patient.

Patient Admission Date: The date and time of admission to the ER.

Patient Gender: The gender of the patient.

Patient Age: The age of the patient at the time of admission.

Patient Race: The self-reported racial or ethnic identity.

Department Referral: The specialty department the patient was referred to.

Patient Admin Flag: A flag indicating if the patient was admitted to the hospital.

Patient Satisfaction Score: A score (1-10) reflecting the patient's experience.

Patient Wait Time: The time (in minutes) from arrival to being seen by medical staff.

## 🛠️ Tools Used
Power BI: For data modeling, DAX calculations, visualization, and dashboard creation.

Microsoft PowerPoint: For outlining business requirements and project structure.

Microsoft Word: For documenting the data terminology.

## 📁 Project Files
Hospital ER_Data.csv: The raw dataset containing ER patient information.

Hospital Emergency room.pbix: The Power BI project file with the complete report and data model.

Hopital Emergency Room PPT.pptx: A presentation outlining the business requirements and dashboard structure.

Data Terminology.docx: A document defining the fields in the dataset.

## 📈 Dashboard Features
The Power BI report is structured into four main dashboards, as specified in the business requirements:

Monthly View: Provides a snapshot of key performance indicators (KPIs) for the selected month, including daily trends for patient volume, wait times, and satisfaction scores.

Consolidated View: Offers a holistic summary of hospital performance over a customizable date range, allowing for broader trend analysis.

Patient Details: A detailed grid view that allows for granular analysis of individual patient records, including demographics, wait times, and admission status.

Key Takeaways: A summary dashboard that presents descriptive analysis and actionable insights derived from the other dashboards to guide decision-making.

## 🚀 How to Use
Prerequisites: Ensure you have Power BI Desktop installed on your machine.

Open the Report: Open the Hospital Emergency room.pbix file in Power BI Desktop.

Interact with the Dashboards:

Use the slicers and filters (e.g., for date ranges, departments) to explore the data.

Navigate between the four dashboard pages (Monthly View, Consolidated View, etc.) using the tabs at the bottom.

Hover over visuals to see detailed tooltips and click on data points to cross-filter other charts on the page.

