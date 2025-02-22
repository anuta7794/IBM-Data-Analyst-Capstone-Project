# IBM Data Analyst Capstone Project: Exploring the Developer Landscape

## Overview:

This capstone project, part of the **IBM Data Analyst Professional Certificate** course, demonstrates proficiency in data analysis tools and techniques, including **_Excel_**, **_Python_**, **_SQL_**, and **_Looker Studio_**. The project involves tasks such as data collection, wrangling, exploratory analysis, statistical analysis, data visualization, and creating interactive dashboards. 

## Scenario:

I have recently been hired as a Data Analyst by a global IT and business consulting firm renowned for its expertise in IT solutions and highly experienced consultants. To stay competitive in the rapidly evolving technology landscape, my organization regularly analyzes data to identify emerging and future skill requirements. As a Data Analyst, you wll contribute to this initiative by collecting data from diverse sources and identifying trends for this year's report on in-demand skills. 

## Tools and Technologies:

In this project, I utilized the following tools:

- **_Microsoft Excel:_** For initial data exploration and manipulation.

- **_Jupyter Notebook:_** As an interactive environment for writing and running Python code.

 - **_Python Libraries:_**
     - **_Pandas:_** Data manipulation and analysis.
     - **_NumPy:_** Numerical computing.
     - **_Matplotlib_** and **_Seaborn:_** Data visualization.

- **_SQLite:_** To manage and query relational databases.

- **_Google Looker Studio:_** For creating interactive dashboards and reports.

- **_PowerPoint:_** To compile and present findings effectively.

## Dataset:

One key source for this project is the latest **Stack Overflow Developer Survey**, a comprehensive dataset offering insights into the global developer community. It consists of responses from developers with different professional backgrounds, educational levels and geographic locations. The dataset is available at [link](https://stackoverflow.blog/2024/08/06/2024-developer-survey/).

## Steps:

### 1. Collecting Data Using APIs.

I began by analyzing HTTP requests and utilizing the GitHub REST API to retrieve and paginate job postings for various technologies. Next, I collected job data from the GitHub Jobs API.

### 2. Collecting Data Using Webscraping.

In this section, I employed web scraping techniques to collect data by downloading webpages, extracting links and images, and parsing HTML tables, subsequently saving the data into a CSV file.

### 3. Exploring Data.

After collecting sufficient data, I analyzed it to summarize key dataset characteristics and identify common data types used in data analysis.

### 4. Data Wrangling.

In this module, I applied essential data-wrangling techniques to clean and prepare datasets for analysis, including:

- Identifying and handling missing values;

- Removing duplicate entries;

- Imputing missing data;

- Normalizing data.

### 5. Exploratory Data Analysis.

In this module, I applied essential exploratory data analysis (EDA) techniques to extract meaningful insights from the dataset:
  
- Data distribution analysis;

- Outlier detection and removal;

- Correlation exploration;

- DataFrame creation.

### 6. Data Vizualization.

Next, I applied essential data visualization techniques to extract meaningful insights from the Stack Overflow survey dataset:

- Visualizing data distribution: utilized **_histograms_** and **_box plots_** to understand the spread and central tendency of various features;

- Exploring feature relationships: employed **_scatter_** and **_bubble plots_** to examine potential correlations between different variables;

- Analyzing data composition: created **_pie charts_** and **_stacked charts_** to assess the proportional makeup of categorical data;

- Comparing categorical data: used **_line_** and **_bar charts_** to compare metrics across different categories effectively.

### 7. Building a Dashboard.

After identifying key trends and insights, I synthesized my findings by creating a comprehensive dashboard using Google Looker Studio. The dashboard is structured into three main sections:

- **_Current Technology Usage:_** This section visualizes the prevalent technologies among respondents, highlighting popular programming languages, tools, and platforms.

  ![1 Current Technology Use](https://github.com/user-attachments/assets/3d43a817-ba92-4600-b99c-6046eec11268)

- **_Future Technology Trends:_** Here, I present data on emerging technologies and respondents' intentions to adopt new tools, offering insights into future industry directions.

 ![2 Future Technology Trends](https://github.com/user-attachments/assets/aa1c505f-ed2c-4e11-8604-a7daa62038ec)

- **_Demographics:_** This part provides an overview of respondent profiles, including factors such as geographic distribution, experience levels, and educational backgrounds.

![3 Demographics](https://github.com/user-attachments/assets/8507e6c8-139e-49b8-8559-bd9a8c024964)

### 8. Final Presentation.

After deriving key insights from the Stack Overflow Developer Survey data, I synthesized the findings into a comprehensive **_PowerPoint presentation_**. This presentation highlights the most significant trends and patterns identified during the analysis, providing a clear and concise overview of the data's implications.

## Key Findings and Insights:

1. **_Most Desired Programming Languages & Technologies:_**

•	The Top 10 languages developers want to work with next year include Python, JavaScript, and TypeScript.

•	Emerging trends show increasing interest in Rust, Go, and Kotlin.

2. **_Most Desired Databases & Platforms:_**

•	PostgreSQL and MySQL remain the most desired databases, while MongoDB is gaining popularity.

•	The Top 10 desired platforms include Linux, AWS, and Docker, indicating a preference for cloud-based and containerized environments.

3. **_Web Framework Preferences:_**

•	React.js and Node.js are the most sought-after frameworks.

•	Backend frameworks like Django and Spring Boot are also in high demand.

4. **_Developer Demographics & Education:_**

•	A majority of developers fall into the 25-34 age range, followed by younger professionals under 24.

•	Bachelor’s degrees are the most common education level, but a significant portion of respondents are self-taught or have taken online courses.

5. **_Gender Distribution in Development:_**

•	The survey reflects a male-dominated industry, though representation of women and non-binary developers is increasing.

6. **_Geographic Distribution of Respondents:_**

•	The highest number of respondents come from the United States, India, and Germany.

•	Developing tech hubs in Latin America and Southeast Asia are showing growth.

7. **_Age vs. Education Level Trends:_**

•	Younger developers (18-24) often rely on online learning, bootcamps, and self-teaching.

•	More experienced developers (35+) tend to have formal computer science degrees.
