🌍 Global Terrorism Analysis  
📌 Project Overview  
This project investigates the Global Terrorism dataset to uncover recurring patterns in terrorist incidents worldwide. The dataset includes attributes such as year, country, region, attack type, target type, weapon type, casualties, and other related details.

The aim is to clean the dataset, highlight significant trends, and build visualizations that make terrorism dynamics easier to understand across time and geography.

📌 Project Summary  
The analysis centers on Exploratory Data Analysis (EDA) of the United Nations Global Terrorism Analysis (UNGTA) dataset, which documents terrorist incidents globally from 1970 to 2017. With more than 180,000 events recorded, the dataset offers a comprehensive foundation for studying terrorism trends and characteristics.

The project’s main objective is to derive insights through systematic data exploration and visualization. Using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn, the analysis examines temporal shifts, geographic hotspots, and operational methods of terrorist groups.

The workflow begins with data preprocessing—resolving missing values, correcting inconsistencies, and engineering useful features. This step ensures the dataset is reliable for deeper analysis.

Subsequent exploration focuses on:

Temporal trends: How attack frequency has evolved over decades, including spikes and declines.

Geographic distribution: Identifying regions, countries, and cities most impacted, and mapping terrorism intensity across continents.

Attack characteristics: Studying attack types, weapons used, and target categories to reveal common strategies and vulnerabilities.

Impact assessment: Measuring casualties (killed and wounded) to evaluate severity and highlight destructive incidents.

Visualizations—line charts, bar plots, heatmaps, and distribution graphs—are employed to simplify complex findings and make them accessible.

Overall, this project demonstrates how structured analysis of large datasets can provide actionable insights into terrorism dynamics, supporting researchers, policymakers, and security agencies.

🎯 Objectives

📂 Load and inspect the dataset

🧹 Handle missing values and duplicates

🔄 Correct inconsistent data types

➕ Create derived columns (e.g., casualties)

📊 Perform exploratory analysis

📈 Visualize trends with charts

💡 Generate stakeholder-relevant insights

🧹 Study terrorism trends from 1970–2017

📊 Identify most affected regions and countries

💣 Understand attack types and weapons used

☠️ Assess casualties and impacts

🛠️ Tools Used

🐍 Python

🐼 Pandas

🔢 NumPy

📉 Matplotlib

🎨 Seaborn

🧼 Data Cleaning Steps

🗑️ Removed duplicates

⚠️ Handled missing values in key fields

🔧 Converted incorrect data types

➕ Created a casualties column (nkill + nwound)

📅 Added year, decade, and month_name columns

📌 Key Columns Used

📅 iyear

📆 imonth

📍 iday

🌎 country_txt

🗺️ region_txt

🏙️ city

💣 attacktype1_txt

🎯 targtype1_txt

👥 gname

🔫 weaptype1_txt

☠️ nkill

🤕 nwound

✅ success

⚔️ suicide

📊 casualties

📊 Exploratory Data Analysis  
Focus areas include:

📈 Attacks by year

🌍 Countries with highest attack counts

💣 Frequency of attack types

🎯 Target categories

☠️ Casualty distribution

📦 Outliers in impact

🔗 Correlations among numerical variables

📉 Visualizations

📈 Line chart: yearly attacks

📊 Bar chart: top affected countries

💣 Bar chart: attack type frequency

🥧 Pie chart: target type distribution

📉 Histogram: casualties

📦 Box plot: casualty outliers

🔥 Heatmap: correlations

💡 Key Insights

🌍 Terrorism is unevenly distributed across time and geography

📍 Certain regions face disproportionate attack volumes

💣 Bombings and explosives dominate attack methods

🎯 Civilian and public targets are most vulnerable

📊 Casualty distribution is skewed—few events cause extreme losses

🧠 Dataset insights can guide risk assessment and security planning

👥 Stakeholder Usefulness

🏛️ Governments for counter-terrorism planning

🛡️ Security agencies monitoring risks

🎓 Researchers studying terrorism

📜 Policymakers allocating resources

🌐 International organizations evaluating threats

🏁 Conclusion  
This project illustrates how data cleaning, exploration, and visualization can uncover terrorism patterns and support informed decision-making.

✍️ Author  
Avinav Singh
