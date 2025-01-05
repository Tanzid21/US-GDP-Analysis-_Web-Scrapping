# US-GDP-Analysis-Web-Scrapping
Used web scraping to extract US GDP data, growth rates, GDP per capita, and population trends from Worldometers. The scraped data was cleaned using Pandas and analyzed to uncover key economic trends. Visualizations created with Matplotlib showcase growth patterns, recessions, and the impact of population changes from 1993 to 2022.

# Context:

The overarching objective of this project is to create a fully automated pipeline for extracting, processing, and analyzing United States GDP data sourced from the Worldometers website. This initiative involves leveraging web scraping techniques to dynamically retrieve tabular GDP data embedded within HTML pages and transforming it into a structured, machine-readable format using Python.
The project will utilize libraries like BeautifulSoup or Selenium for efficient web scraping and HTML parsing. Once extracted, the data will be cleaned, formatted, and organized into a tabular structure using the Pandas library, enabling seamless data manipulation. The structured data will then be subjected to basic exploratory data analysis (EDA) to identify trends, insights, and patterns in GDP growth over time.In addition to data processing, the project aims to incorporate visualizations using tools such as Matplotlib and Seaborn, providing graphical representations of GDP trends and contributions. The ultimate goal is to streamline the data extraction-to-analysis workflow, reducing manual intervention and ensuring accuracy, efficiency, and repeatability in GDP data processing. This pipeline can serve as a foundation for more advanced analytics or integration into larger economic research initiatives.

# Web Scraping:

Web scraping will involve the use of Python libraries such as requests and BeautifulSoup to programmatically access and extract relevant content from the Worldometers website. The requests library will be used to send HTTP GET requests to the target webpage and retrieve the raw HTML content of the page. After retrieving the HTML, the BeautifulSoup library will parse the content, enabling easy navigation and searching of the document tree to locate the specific data table containing GDP information. By analyzing the webpage structure (via browser developer tools or inspecting the source code), unique identifiers such as class names, IDs, or tag hierarchies will be identified to precisely locate the table of interest. Once the table is located, the script will extract both the column headers (e.g., year, GDP value, percentage change, etc.) and the rows of data using HTML tags like <table>, <tr>, and <td>. This process ensures the desired data is isolated and prepared for further processing.

# Data Cleaning and Structuring:

The raw data extracted from the webpage may contain irregularities such as missing values, unnecessary symbols (e.g., commas, dollar signs), or inconsistencies in formatting. To address this, the extracted data will be cleaned and structured using the Pandas library. First, the data will be converted into a Pandas DataFrame, where meaningful and intuitive column names (e.g., "Year", "GDP in Trillions", "Annual Growth Rate") will be assigned. Any redundant or irrelevant columns will be removed to streamline the dataset. Special characters or formatting issues, such as commas in numeric values or trailing spaces, will be stripped using string manipulation techniques or Pandas' built-in functions. Missing or null values will be handled appropriately, either by imputing them with relevant statistical measures (e.g., mean, median) or by removing the corresponding rows if they do not significantly impact the dataset. The result will be a clean, well-structured DataFrame, ready for exploratory analysis and visualization, ensuring the data is accurate, consistent, and suitable for deeper insights.


# Data Source: 
https://www.worldometers.info/gdp/us-gdp/

# Data Analysis Result: 

![image](https://github.com/user-attachments/assets/11a27fb5-2e7d-4aed-be9f-64bbaefe2394)
The pie chart illustrates the percentage contribution of GDP from 2011 to 2022, showcasing economic fluctuations and resilience over time. The highest contribution occurred in 2011 (10.9%), signaling strong economic performance at the start of the period. However, from 2012 to 2014, there was a noticeable dip, with contributions ranging from 6.7% to 7.5%, likely reflecting the lingering effects of the 2008 financial crisis on global economies. Starting in 2015, the percentage steadily increased, indicating a phase of recovery and growth, reaching a consistent rise through 2018 (8.8%) and 2019 (9.1%). The year 2020 saw a decline to 9.0%, which can likely be attributed to the global economic disruption caused by the COVID-19 pandemic. However, the subsequent years, 2021 (9.9%) and 2022 (10.0%), show signs of recovery, reflecting efforts to stabilize economies through stimulus measures and the reopening of global markets. This chart provides a clear narrative of economic challenges and recoveries, emphasizing the resilience and adaptability of economies in response to both external shocks and internal growth strategies over the 12-year period.

# US GDP Trend Over Time (1993-2022)
![image](https://github.com/user-attachments/assets/3e5b47a3-73cd-46b8-aa38-6e7a293f6861)

The United States' GDP has experienced consistent growth over the past three decades, reaching a remarkable $25.46 trillion in 2022. This steady rise reflects the strength and dynamism of the US economy, which has shown resilience in the face of global and domestic challenges. Periods such as the late 1990s and mid-2000s were characterized by strong economic expansion fueled by technological advancements, market growth, and policy reforms. However, the data also highlights key moments of economic vulnerability, such as the global financial crisis of 2008-2009, which led to a temporary dip in GDP, and the COVID-19 pandemic in 2020, which caused a contraction of -2.77%. Despite these setbacks, the GDP has rebounded strongly each time, showcasing the country’s ability to recover quickly through innovation, fiscal stimulus, and monetary policies. The long-term upward trajectory underscores the importance of strategic investments and economic reforms to sustain this growth.

# GDP Growth Rate Trend
![image](https://github.com/user-attachments/assets/aeb89246-6eba-49c0-86b6-7878b6e4a37a)

The GDP growth rate has exhibited significant variability, highlighting the cyclical nature of economic performance. Periods of robust growth, such as the 4.79% in 1999 and 3.48% in 2005, reflect a thriving economy fueled by favorable market conditions, technological breakthroughs, and consumer confidence. Conversely, the data also underscores periods of decline, such as the -2.6% during the 2009 financial crisis and the -2.77% contraction in 2020 due to the pandemic. These downturns underline the impact of global financial instability, policy decisions, and unforeseen events on economic performance. The sharp rebound in 2021, with a growth rate of 5.95%, demonstrates the economy's capacity for recovery through stimulus measures and adaptive industries. The fluctuations in growth rates serve as a reminder of the need for balanced policies that address vulnerabilities while promoting sustained development in both stable and volatile periods.

# GDP Per Capita Over Time
![image](https://github.com/user-attachments/assets/e5f726dd-c91a-4578-9504-4ad5af738979)

The GDP per capita has shown consistent improvement, reflecting enhanced productivity, technological advancements, and better living standards for individuals.In 1993, 39,693 to $61,349 in 2022, this upward trend highlights how economic growth has translated into greater wealth for the average citizen. Despite challenges such as the global financial crisis and the COVID-19 pandemic, GDP per capita continued to rise in the long term, indicating the resilience of the US economy in maintaining individual prosperity. This growth can be attributed to factors such as increased workforce efficiency, investment in high-value industries, and the expansion of the service sector. The consistent increase, even with population growth, underscores the ability of the US economy to adapt and ensure equitable distribution of wealth across its citizens. However, this trend also highlights the importance of addressing income inequality to ensure that these gains benefit all segments of society.

# Population Trend Over Time
![image](https://github.com/user-attachments/assets/031e2946-e1ec-4704-86cc-21cfd5052ff7)

The US population has grown steadily, increasing from approximately 262 million in 1993 to over 341 million in 2022. This growth reflects both natural population increases and sustained immigration, which has contributed to economic diversification and expansion. A larger population often leads to greater economic output, as seen in the corresponding rise in GDP. However, population growth also presents challenges such as increased demand for resources, infrastructure, and social services. Despite these challenges, the consistent rise in GDP per capita indicates that economic growth has outpaced population increases, ensuring improved living standards. The data also suggests that careful policy planning, particularly in education, healthcare, and infrastructure, is essential to sustain this balance. As the population continues to grow, it will be crucial to invest in workforce development and innovation to maintain economic productivity and competitiveness on a global scale.



