<img src="https://github.com/user-attachments/assets/ef0a5280-7030-472e-a53d-5d9b2288d830" alt="Header"/>


# **Data-Visualization-with-Python-IBM**


  # 📄 Summary
  This course teaches how to present and visualize complex data in a manner that makes sense to people, and allows for insights to be easily seen and derived. This course makes use of several Python data visualization libraries such as Matplotlib, Seaborn, Plotly, and Folium, to explore Canadian immigration data. It also covers dashboard creation using Plotly Dash, with a Peer graded assignment combining the skills learned to analyse and report US domestic airline flights performance in a dashboard.
  
  📑 Main Topics
  
  - Introduction to Data Visualization Tools
  - Basic and Specialized Visualization Tools
  - Advanced Visualizations and Geospatial Data
  - Dashboard creation using Plotly Dash.

🔑 Key Skills Learned

-  Using Matplotlib to create various plots, including line plots, area plots, histograms, bar charts, and more.
- Applying advanced visualization tools to create waffle charts and word clouds.
- Using Seaborn with Matplotlib to generate attractive regression plots.
- Creating maps and visualizing geospatial data, using Folium.
- Using Plotly, Plotly.graph_objects, and Plotly express commands.
- Using Dash and basic Dash components (core and HTML).

## 🛠️ Tools
The following tools were used to complete this certification: <br> <br>
  <img src="https://user-images.githubusercontent.com/84391594/152705364-f16bb223-41aa-4510-8113-51171dfe9953.png" height="75">
  <img src="https://user-images.githubusercontent.com/84391594/152705271-083f8784-b3c9-4065-9733-ea3fa8ad5a7a.png" height="75">
  <img src="https://user-images.githubusercontent.com/84391594/152705273-adffe1bf-b509-44d0-b3ac-671cce5071df.svg" height="75">
  <img src="https://user-images.githubusercontent.com/84391594/152705324-68f777a0-3875-4b65-ae96-646643284541.png" height="75">
  <img src="https://user-images.githubusercontent.com/84391594/152705298-bb170d32-3dd0-4ad4-8221-8b7b029116b4.png" height="75">
</p>
(Python, Jupyter, GitHub, IBM Watson Studio, IBM Cloud Pak)

## 📖 Libraries
The following Python libraries were used throughout the certification: <br> 
<p align="left">
  <img  src="https://user-images.githubusercontent.com/84391594/152706127-ce41990f-2588-472a-b5df-6b403a5947e6.png" height="35">
  <img  src="https://user-images.githubusercontent.com/84391594/152706130-5577011e-ecb3-47aa-af73-f6bd1bda05bc.png" height="35">
  <img  src="https://user-images.githubusercontent.com/84391594/152706132-5939da7e-7d1e-43b8-9c46-2d3fe5198dda.png" height="35">
  <img  src="https://user-images.githubusercontent.com/84391594/152706135-85cdd35e-922a-414a-a198-c670fbf8fb25.svg" height="35">
  <img  src="https://user-images.githubusercontent.com/84391594/152706148-36f27f03-1967-45d1-82d8-f6c149c6f21c.svg" height="35">
  <img  src="https://user-images.githubusercontent.com/84391594/152706211-7966848a-a2e1-4c4a-bc08-594a4ca6ff07.png" height="35">
 <img  src="https://user-images.githubusercontent.com/84391594/152706214-d018bc5e-1477-4de2-94d7-5c0886e0477d.png" height="35">
 <img  src="https://user-images.githubusercontent.com/84391594/152706217-c0cfd9d8-22ad-4c3b-9ac7-70a6cf2799f7.png" height="35"> <br>
</p>


Issued by Coursera
Authorized by IBM
This badge earner has a good understanding of what data visualization is, uses of data visualization, and best practices when creating plots and visuals. The individual has the skills to use different Python Libraries, mainly Matplotlib and Seaborn to generate different types of visualization tools such as line plots, scatter plots, bubble plots, area plots, histograms, and bar charts. The earner is able to use the Folium library to visualize geospatial data and to create choropleth maps.




# Australian Wildfire Data Analysis and Visualization
[Analyzing wildfire activities in Australia](https://github.com/dattesh2507/Data-Visualization-with-Python-IBM/blob/main/Analyzing%20wildfire%20activities%20in%20Australia.ipynb)


Wildfire Dataset Analysis and Visualization using Matplotlib, Seaborn, Pandas, Folium, Plotly, and Dash

**Description**

This project analyzes and visualizes wildfire activities in Australia using a historical dataset. By exploring patterns, trends, and creating visualizations, the project aims to gain insights into wildfire behavior across different regions of Australia. The analysis is split into two parts: Part 1 focuses on analyzing wildfire data, and Part 2 involves creating an interactive dashboard for visualizing the findings.

**Dataset**

This dataset includes data on wildfire activities in Australia from 2005 onwards. It provides information on estimated fire areas, fire brightness, radiative power, and more, categorized by region and date.

Variables:
- Region: The seven regions affected by wildfires.
- Date: Dates in UTC, providing data for 24 hours ahead.
- Estimated_fire_area: Daily sum of estimated fire area for presumed vegetation fires with a confidence > 75% (in km²).
- Mean_estimated_fire_brightness: Daily mean of estimated fire brightness for presumed vegetation fires with a confidence > 75% (in Kelvin).
- Mean_estimated_fire_radiative_power: Daily mean of estimated radiative power for presumed vegetation fires with a confidence > 75% (in megawatts).
- Mean_confidence: Daily mean confidence for presumed vegetation fires with a confidence > 75%.
- Std_confidence: Standard deviation of estimated fire radiative power (in megawatts).
- Var_confidence: Variance of estimated fire radiative power (in megawatts).
- Count: Daily number of pixels for presumed vegetation fires with a confidence level > 75% for a given region.
- Replaced: Indicates with a "Y" if the data has been replaced with standard quality data (usually with a 2-3 month lag).

**Project Tasks completed:**
- Part 1: Analyzing Wildfire Activities in Australia
- Task 1.1: Plot a line chart showing the change in average estimated fire area over time.
- Task 1.2: Plot the estimated fire area over the months to identify seasonal patterns.
- Finding: The plot shows a significant peak in fire activity between 2010 to 2013, with a notable rise in fire area after April 2011 and before 2012, correlating with a period of intense wildfires in Australia.
- Task 1.3: Create a bar plot displaying the distribution of mean estimated fire brightness across different regions.
- Task 1.4: Develop a pie chart showing the portion of pixel counts for presumed vegetation fires across regions.
- Task 1.5: Customize the pie plot for better visual representation.
- Task 1.6: Develop a histogram of mean estimated fire brightness to observe the distribution.
- Task 1.7: Create a scatter plot to show the distribution of estimated fire brightness across regions, using the region as a hue.
- Task 1.8: Develop a scatter plot to show the correlation between mean estimated fire radiative power and mean confidence level.
- Task 1.9: Mark all seven regions affected by wildfires on a map of Australia using Folium.
- Part 2: Dashboard for Interactive Visualization
- Task 2.1: Add a title to the dashboard.
- Task 2.2: Add radio items and a dropdown menu for region and year selection.
- Task 2.3: Create two empty divisions for output within the dashboard.
- Task 2.4: Link the output and input components inside the app.callback decorator.
- Task 2.5: Implement the callback function to update the visualizations based on user selections.

**Dashboard Functionality:**

The dashboard allows users to select a specific region and year to dynamically update the visualizations.
- Visualization 1: A pie chart displaying the monthly average estimated fire area for the selected region and year.
- Visualization 2: A bar chart showing the average count of pixels for presumed vegetation fires across months for the selected region and year.
This interactive dashboard provides an intuitive way to explore wildfire data across different regions and years, enabling users to gain deeper insights into seasonal and regional wildfire patterns.

**Findings**
- Seasonal Trends: The peak wildfire activities were observed between 2010 and 2013, with a notable rise in fire area after April 2011, aligning with historical records of severe wildfires in Australia during this period.
- Regional Differences: The distribution of fire brightness and pixel counts varied significantly across regions, highlighting regional vulnerability.
- Correlation Insights: There is a noticeable correlation between fire radiative power and confidence levels, suggesting that areas with higher radiative power are more likely to be accurately detected.

**Requirements**

Python 3.6+
Pandas
Matplotlib
Seaborn
Folium
Dash
Plotly







