# Healthcare Appointments Dashboard

## Project Overview
This project aims to create an interactive dashboard for visualizing healthcare appointment data, helping healthcare providers optimize scheduling and improve service delivery. The dashboard was developed using **Power BI** and is based on the **Healthcare Appointment Dataset** available on Kaggle. The goal is to identify trends, appointment status distributions, and demographics, ultimately improving healthcare efficiency and patient care.

Dataset Source: [Healthcare Appointment Dataset on Kaggle](https://www.kaggle.com/datasets/wajahat1064/healthcare-appointment-dataset)

## Purpose
The primary purpose of this project is to create an insightful dashboard that can:
- Track appointment scheduling trends.
- Analyze appointment statuses (e.g., completed, canceled).
- Visualize patient demographics and appointment types.
- Identify patterns like missed appointments (no-shows) and cancellations.
- Forecast future appointment trends to assist in resource planning.

## Tools Used
- **Power BI**: For creating the interactive dashboard, visualizing the data, and generating key insights.
- **Kaggle Dataset**: The raw data used for this project comes from Kaggle's **Healthcare Appointment Dataset**.
- **Excel/CSV**: Data was imported into Power BI from CSV files and processed as required.

## Dataset Details
The dataset comes from a healthcare system and contains data related to patient appointments. Key attributes include:
- **Patient ID**: Unique identifier for each patient.
- **Appointment ID**: Unique identifier for each appointment.
- **Scheduled Day**: The date when the appointment was scheduled.
- **Appointment Day**: The date of the actual appointment.
- **Age**: The age of the patient.
- **Gender**: The gender of the patient.
- **Neighbourhood**: The location of the healthcare center.
- **Scholarship**: Whether the patient is enrolled in a government scholarship program.
- **Hypertension**: Whether the patient has hypertension.
- **Diabetes**: Whether the patient has diabetes.
- **Alcoholism**: Whether the patient has an alcohol-related condition.
- **Handicap**: Whether the patient has any physical disabilities.
- **No-Show**: Indicates whether the patient showed up for the appointment (1 for no-show, 0 for attended).

You can download the dataset from Kaggle using the link provided above.

## Data Preprocessing
Before creating the dashboard, the data underwent several preprocessing steps:
1. **Handling Missing Values**: Missing or null values were handled by either imputing data or removing the rows.
2. **Date Formatting**: The appointment dates and scheduled days were standardized.
3. **Categorization**: Numeric fields like age were categorized into groups (e.g., child, adult, senior).
4. **Data Aggregation**: Data was aggregated to provide insights at various levels, such as by patient demographics, appointment status, and time periods.
5. **Data Transformation**: Some variables were transformed into Boolean or categorical data types to enhance clarity in visualizations.

## Dashboard Features
The dashboard includes the following key features:

### 1. **Appointment Trends Over Time**
   - A **line chart** visualizing appointment trends over time, broken down by different periods (daily, weekly, monthly).
   - This helps identify peak periods and trends in appointment scheduling.

### 2. **Appointment Status Breakdown**
   - A **pie chart** or **bar chart** showing the distribution of appointment statuses (attended vs. no-show).
   - Helps track the effectiveness of appointment reminders and identify patterns in missed appointments.

### 3. **Patient Demographics**
   - **Bar charts** and **pie charts** visualizing patient demographics based on age, gender, and location (neighbourhood).
   - This helps healthcare providers understand patient composition and allocate resources accordingly.

### 4. **Health Conditions and Appointment Status**
   - **Stacked bar charts** or **heatmaps** displaying the relationship between patient conditions (e.g., hypertension, diabetes) and appointment statuses.
   - Identifies if patients with specific conditions are more likely to miss appointments.

### 5. **No-Show Analysis**
   - **Heatmap** visualizing the frequency of no-shows across different days of the week and times of day.
   - This helps to identify patterns and optimize appointment scheduling.

### 6. **Forecasting Future Appointments**
   - Using historical data, the dashboard includes **forecasting models** that predict the number of upcoming appointments.
   - Helps healthcare providers plan for periods of high demand.

## Steps Taken to Build the Dashboard

1. **Data Collection**: 
   - The dataset was downloaded from Kaggle and loaded into Power BI.

2. **Data Cleaning**:
   - Missing data and anomalies were handled through cleaning techniques, including filling missing values or removing rows with critical missing information.
   - Variables were converted into appropriate data types.

3. **Data Transformation**:
   - Key transformations included aggregating data by different time periods and categories to generate useful insights, such as appointment trends by neighbourhood, age, and health conditions.

4. **Creating Visualizations**:
   - Different types of charts were created, including line charts for trends, bar charts for distributions, and heatmaps for appointment status analysis.
   - Filters and slicers were added to allow users to interact with the dashboard and filter data based on variables like time range, health conditions, or demographic characteristics.

5. **Dashboard Design**:
   - The layout was optimized for readability and ease of use, with a clear flow from trends to specific insights.
   - Interactivity was built in, allowing users to drill down into specific data points and adjust the visualizations to suit their needs.

6. **Testing and Refining**:
   - The dashboard was tested with stakeholders to ensure it provided the necessary insights and that all filters and visualizations worked as expected.
   - Feedback was incorporated to improve the design and functionality.

