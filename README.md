# US-GDP-Analysis-_Web-Scrapping
Used web scraping to extract US GDP data, growth rates, GDP per capita, and population trends from Worldometers. The scraped data was cleaned using Pandas and analyzed to uncover key economic trends. Visualizations created with Matplotlib showcase growth patterns, recessions, and the impact of population changes from 1993 to 2022.

# Objective
The primary goal of this project is to automate the extraction, processing, and analysis of United States GDP data from the Worldometers website. The project will involve web scraping techniques to retrieve tabular data from HTML pages, structuring it into a readable format using Python, and conducting basic data analysis using Pandas.

# Web Scraping
Use Python libraries (requests and BeautifulSoup) to retrieve the HTML content of the webpage. Locate the desired data table by analyzing the webpage structure and identifying unique class names or IDs. Extract both column headers and rows of data from the table.

# Data Cleaning and Structuring:
Clean and format the extracted data using Pandas. Organize the data into a DataFrame with meaningful column names. Handle missing or improperly formatted data, if any.

# Data Source: 
https://www.worldometers.info/gdp/us-gdp/

# Result: 

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



