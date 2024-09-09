# Call Center Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning and Preparation](#data-cleaning)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Results and Findings](#results)
- [Key Insights & Recommendations](key-insights-and-recommendations)
- [Limitations](#limitations)
- [References](#references)

## Project Overview


This section focuses on evaluating the performance and efficiency of a call center. By analyzing key metrics such as average response times, customer sentiment, and call volumes across different communication channels, the goal is to identify areas for operational improvement. Data insights are drawn using Excel for data cleaning and pivot tables, helping to visualize patterns and trends. Recommendations for optimizing service levels and enhancing the customer experience are provided based on the findings.

## Data Sources

**Call Center Data:** The primary dataset used for this analysis is the "call_center.csv" file, which contains detailed records of customer interactions. The dataset includes fields such as call timestamps, agent IDs, customer sentiment ratings, call duration, resolution time, and the communication channel used (call center, email, chatbot, etc.). This data is essential for understanding call center performance and identifying trends in customer service.

## Tools

- **Excel:** The primary tool used for data analysis in this project. Excel features were extensively utilized for various tasks:
    - **Conditional Formatting:** Applied to highlight key data trends and anomalies during the data cleaning process.

    - **Pivot Tables:** Utilized for summarizing and analyzing data, allowing for in-depth exploration of metrics such as call durations, response times, and sentiment.

    - **Slicers:** Used to filter and interact with data dynamically in pivot tables, making it easier to analyze specific segments and trends.

    - **Visualizations:** Created charts and graphs to represent data insights clearly. This included a map visualization to display call volumes by state, providing a geographical perspective on call distribution.
 
## Data Cleaning

**1. Initial Data Review:** Examined the raw data from "call_center.csv" to understand its structure and identify inconsistencies or missing values.

**2. Conditional Formatting:** Applied to highlight anomalies and missing values, making it easier to address data quality issues.

**3. Data Transformation:** Adjusted and standardized columns for consistency, such as converting timestamps to a uniform format and standardizing categorical data.

**4. Handling Missing Values:** Addressed missing values by filling them with appropriate defaults or removing incomplete records as necessary.

**5. Data Filtering:** Removed irrelevant data to focus on key metrics pertinent to the analysis.

**6. Data Aggregation:** Used pivot tables to summarize call metrics, such as call durations and response times, by various dimensions.

## Exploratory Data Analysis 

EDA involved exploring the call center data to answer questions, such as: 
1. What is the total number of inbound calls?
2. How does customer sentiment vary by call type or channel?
3. What are the most common reasons for call escalation or call-back requests?
4. Are there any significant differences in call volume or resolution times between different agents or teams?

## Data Analysis

**1. Aggregated Insights:** Utilized pivot tables to summarize key metrics such as total call volume, average call duration, and resolution times across different dimensions.

**2. Trend Analysis:** Analyzed trends over time with line charts to observe changes in call volumes and response times.

**3. Geospatial Analysis:** Created a map visualization to show call volumes by state, revealing geographical patterns and concentrations.

**4. Comparative Analysis:** Compared metrics across agents and teams using bar charts to identify performance variations.

**5. Sentiment Analysis:** Evaluated customer sentiment ratings across different call types and channels using box plots and scatter plots.

**6. Visualization of Key Metrics:** Developed histograms and pie charts to illustrate call duration distribution and call type proportions.

**7. Actionable Recommendations:** Provided recommendations for optimizing operations based on the analysis, such as staffing adjustments and addressing common issues.

## Results

**1. Call Volume Patterns:** The analysis revealed distinct patterns in call volumes, with peak periods occurring during mid-morning and late afternoon. Los Angeles (CA) received the highest number of calls at 3,631, followed by Texas (3,572). The lowest volume was in Wyoming, with significantly fewer calls. This suggests that staffing adjustments are needed to better handle these peaks.

**2. Call Sentiments:** The analysis showed that negative sentiments were the most frequent among all calls. Los Angeles received the highest negative sentiments among the call centers, followed by Baltimore. This highlights potential issues with customer service quality in these regions.

**3. Top Call Reasons:** The most common reason for calls was related to billing questions, indicating a frequent need for clarity or resolution in this area.

**4. Call Response Times:** Most calls were answered within the Service Level Agreement (SLA), showing a general adherence to expected response times.

**5. Geographical Insights:** Los Angeles, California, had the highest call volume, while Denver, Colorado, had the lowest. The differences in regional call activity suggest the need for more resources or region-specific strategies to manage calls efficiently.

**6. Call Channels:** A breakdown of the communication channels showed that 32% of total calls were handled via the call center, 25% through the chatbot, 23% via email, and 20% via the web. This distribution highlights the importance of maintaining and optimizing multiple channels to handle customer inquiries effectively.

**7. Customer Sentiment and Channel Analysis:** Although the call center handled the highest proportion of calls, the overall customer sentiment was negative, particularly in regions like Los Angeles and Baltimore. This suggests potential issues with service quality or the complexity of issues being addressed through this channel.

## Key Insights & Recommendations

**1. Staffing Adjustments:** With the highest call volumes occurring in Los Angeles (3,631 calls) and Texas (3,572 calls), and peak periods during mid-months, it's recommended to adjust staffing levels to handle these surges more efficiently. Additional resources should also be allocated to regions with consistently high call volumes.

**2. Addressing Negative Sentiments:** Los Angeles and Baltimore had the highest negative sentiment scores, indicating dissatisfaction with the service in these areas. It is recommended to conduct further analysis to identify specific causes and provide targeted training or resources to agents in these locations to improve service quality and customer satisfaction.

**3. Billing Procedure Improvements:** Billing questions were the most common reason for calls, suggesting that the current billing system or communication around billing may need improvement. Streamlining the billing process and providing clearer instructions or self-service options could reduce the number of calls related to this issue.

**4. Response Time Optimization:** Although most calls were handled within the Service Level Agreement (SLA), there may be opportunities to improve response times during peak periods to maintain high performance. Monitoring response times more closely in high-volume regions like California and Texas could prevent future delays.

**5. Channel Optimization:** The majority of calls (32%) were handled by the call center, but given the high negative sentiment, improving the call center’s performance is critical. Exploring ways to optimize other channels like the chatbot (25%) and email (23%) could reduce the load on the call center, improving overall efficiency and customer experience.

**6. Geographical Strategy:** Since California and Texas had the highest call volumes, but regions like Denver and Wyoming had significantly lower activity, the strategy could be adjusted to allocate resources based on call volume needs. This might involve re-distributing staff or investing in automation solutions in low-call-volume regions.

**7. Sentiment Monitoring:** Regular sentiment analysis, especially for regions like Los Angeles and Baltimore, should be implemented to track changes and address issues early. Automated feedback systems could help flag negative experiences in real time, allowing for immediate resolution.

## Limitations

**1. Data Scope and Quality:** The analysis was based solely on the "call_center.csv" file, which may not capture all relevant variables. Additionally, potential data quality issues, such as missing or inaccurate entries, could have influenced the results.

**2. Geographical and Channel Bias:** The dataset showed significant regional imbalances, with states like California and Texas dominating. Similarly, channel usage data lacked details on effectiveness, limiting deeper insights.

**3. Sentiment Accuracy:** Customer sentiment may be influenced by external factors not related to the call center's service, affecting the reliability of sentiment analysis.

## References

**1. Microsoft Excel Documentation:** Detailed instructions on using pivot tables and conditional formatting can be found [here](https://support.microsoft.com/en-gb/excel)
