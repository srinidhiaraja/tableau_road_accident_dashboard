### Data Analysis Project Report: Road Accidents Dashboard

#### **Project Overview**
This project involved developing an interactive Tableau dashboard to analyze road accidents data comprehensively. The dashboard enables users to explore various aspects of road accidents, focusing on factors such as vehicle type, weather conditions, and road surface. Additionally, it provides insights into year-over-year (YOY) changes in casualties.

#### **Objectives**
1. **Visualize Road Accidents Data:** Provide insightful visualizations to understand patterns and trends in road accidents.
2. **Enable Interactive Exploration:** Allow users to interactively filter and analyze data based on various parameters.
3. **Highlight Key Insights:** Focus on critical findings, including trends in casualties and the impact of different factors on accident severity.

#### **Data Preparation and Preprocessing**
- **Data Collection:** Compiled data on accident locations, dates, times, vehicle types, weather conditions, road surfaces, and casualty details.
- **Data Cleaning:** Addressed missing values, corrected inconsistencies, and formatted data for analysis.
- **Data Transformation:** Created calculated fields and parameters for advanced analysis.

#### **Dashboard Components**

1. **Interactive Filters:**
   - **Date Range:** Filter data by specific date ranges to analyze trends over different periods.
   - **Casualty Type:** View data based on casualty severity (fatal, serious, slight).

2. **Visualizations:**
   - **Casualties by Weather and Road Surface:**
     - **Donut Chart:** Displays the distribution of casualties by different weather conditions and road surface types, providing a clear view of how these factors impact casualty rates.
   - **Casualties by Road Type:**
     - **Horizontal Bar Chart:** Shows the number of casualties by different road types, making it easy to compare the impact of various road types on accident severity.
   - **Year-Wise Casualties:**
     - **Line Chart:** Illustrates the trend of casualties over different years, highlighting increases or decreases in accident severity over time.
   - **Key Performance Indicators (KPIs) with Sparklines:**
     - **KPIs:** Present key metrics such as total accidents, total casualties, and casualties by severity.
     - **Sparklines:** Provide a compact view of trends for KPIs over time, helping to quickly identify patterns and trends in the data.

3. **Advanced Calculations and Parameters:**
   - **Year-Over-Year (YOY) Casualties Calculation:**
     - **Current Year Casualties:** Calculated using a parameter to select the current year and summing casualties for that year.
     - **Previous Year Casualties:** Calculated by shifting the parameter to the previous year and summing casualties.
     - **YOY Change:** A calculated field that computes the difference between current year and previous year casualties to assess trends.
   - **Casualties by Vehicle Type:**
     - **Grouping:** Combined similar vehicle types into broader categories (e.g., "Mini Bus" and "Bus/Coach" grouped as "Bus").
     - **Calculation:** Custom calculated fields determine the number of casualties for each vehicle type category, allowing for comparison and trend analysis.

4. **Dynamic Interactions:**
   - **Real-Time Updates:** Visuals update dynamically based on selected filters, providing an interactive user experience.
   - **Comparative Analysis:** Enables comparison of different time periods, vehicle types, and other categories.

#### **Findings and Insights**

1. **Accident Trends:**
   - The dashboard reveals trends in total accidents and casualties over time, with YOY trends highlighting periods of increase or decrease.

2. **Impact of Weather:**
   - Analysis by weather conditions shows their impact on accident rates and severity.

3. **Vehicle Type Analysis:**
   - Grouped vehicle types provide a clearer picture of casualty distribution and highlight which vehicle categories are most frequently involved in accidents.

4. **Road Surface and Accident Severity:**
   - Insights into how different road surfaces affect accident frequency and severity, aiding in road safety improvements.

5. **Casualty Breakdown:**
   - The breakdown of casualties by severity offers a detailed view of accident seriousness and helps in prioritizing safety measures.

6. **Year-Over-Year (YOY) Trends:**
   - YOY analysis provides insights into changes in casualty numbers and highlights trends in road safety over time.

#### **Conclusion**
The interactive Tableau dashboard effectively visualizes and analyzes road accidents data, providing valuable insights into accident patterns, vehicle involvement, and the impact of various factors. The use of parameters and custom calculated fields enhances the analysis, allowing for detailed YOY comparisons and a better understanding of casualty trends.

#### **Next Steps**
1. **User Feedback:** Obtain feedback from users to refine and enhance the dashboard's functionality.
2. **Data Updates:** Regularly update the dashboard with new data to maintain accuracy and relevance.
3. **Further Analysis:** Explore additional metrics or dimensions that could provide deeper insights into road safety.

The dashboard serves as a comprehensive tool for analyzing road accidents, facilitating data-driven decisions to improve traffic safety and reduce casualties.
