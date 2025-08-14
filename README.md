# hackthon1 Retail Sales Data Analysis

**hackthon1 Retail Sales Data Analysis** is aim to analyze historical retail sales data along with store, promotional, and economic information to uncover patterns, identify key sales drivers, and generate actionable insights that can improve revenue forecasting, optimize promotions, and enhance inventory management.


# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


## Dataset Content
* Dataset used in this anaylsis is the historical sales data from 10/2/2010 to 26/10/2012 for 45 stores located in different regions - each store contains a number of departments.The company also runs several promotional markdown events throughout the year. These markdowns precede prominent holidays, the four largest of which are the Super Bowl, Labor Day, Thanksgiving, and Christmas. The weeks including these holidays are weighted five times higher in the evaluation than non-holiday weeks. 

* There are 3 datasets – Stores, Features and Sales. For more details please visit https://www.kaggle.com/datasets/manjeetsingh/retaildataset


## Business Requirements
* Sales Performance Analysis

    * Compare performance across stores, departments to identify top- and low-performing stores/departments.

* Promotion Effectiveness

    * Measure the impact of markdowns, holidays, and seasonal promotions on weekly sales and recommend optimal promotion strategies.


* Seasonality & Trend Detection

    * Identify sales patterns by week, month, quarter, and year to determine holiday season trends.

* Operational Planning

    * Support inventory and staffing decisions with accurate demand insights.


## Hypothesis and how to validate?
1. Weekly Sales Are Significantly Higher During Holidays
    * **Assessment:** Partially valid

    * **Details:** Not all holiday weeks show higher sales volumes. Peak sales occur mainly in November and December, near holiday weeks (Graph 10).

2. Promotions/Markdowns Positively Impact Sales
    * **Assessment:** Valid

    * **Details:** Graph 6 shows that higher markdowns can boost sales. Markdown3 demonstrates the strongest positive effect on sales.

3. Larger Stores Generate Higher Sales
    * **Assessment:** Valid

    * **Details:** Graph 9 shows a strong positive correlation between store size and sales. Store type A tends to be larger and achieves higher sales performance.

4. Economic Factors (Fuel Price, CPI, Unemployment) Influence Sales
    * **Assessment:** Invalid

    * **Details:** Graph 5’s heatmap indicates limited and minimal correlation between economic factors and sales.

5. Sales Follow Seasonal Patterns with Specific Quarterly/Monthly Peaks
    * **Assessment:** Valid

    * **Details:** Quarter 2 and 3 show higher average weekly sales (Graph 4), while peak weekly sales occur in December (Graph 10).

## Project Plan

1. Collection:
    * Data was gathered from Kaggle and downloaded as CSV files in the local environment.

2. Processing:

    * Missing or inconsistent values were handled using appropriate methods (e.g., imputation).

    * Data types were standardized (dates converted to datetime, categorical variables encoded where necessary).

    * Aggregation was performed to analyze trends at the store-week level, and holiday flags were combined across departments.

3. Analysis:

    * Exploratory Data Analysis (EDA) was performed using descriptive statistics and visualizations to understand patterns, seasonality, and anomalies.

    * Correlation analysis and grouping operations were used to identify relationships between store size, promotions, holidays, and sales.

    * Trend and seasonal pattern analysis helped identify peak periods and key sales drivers.

4. Interpretation:

    * Insights were derived by comparing sales patterns across stores, quarters, and holiday periods.

    * Hypotheses were tested against observed data trends to validate assumptions about sales drivers.

## Choice of Methodology:

* Exploratory Data Analysis (EDA): To identify patterns, trends, and anomalies in weekly sales data.

* Aggregation and Grouping: Used to summarize sales at the store and week level, allowing comparisons across time and stores. It allow focusing on top-performing stores, which is essential for strategic business decisions.

* Visualization (Line Charts, Heatmaps): To clearly communicate trends, seasonal effects, and correlations, making findings actionable.

* Correlation Analysis: To evaluate the influence of store size, promotions, and economic factors on sales performance.


## Ethical considerations
Although there were no data privacy (PII), bias, or fairness issues with the dataset, the following principles were always followed:

* Data Privacy: Any personally identifiable information (PII) was anonymized or removed to protect individual privacy.

* Bias and Fairness: The dataset was reviewed for representation bias, and adjustments were made to prevent disadvantaging any group.

* Legal Compliance: Data collection and processing adhered to all applicable regulations (e.g., GDPR, HIPAA).

* Societal Impact: Potential misuse or negative consequences were considered, and safeguards were implemented to mitigate risks.

source: ChatGPT


## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
    *  Time Management
        *   Completing a project within a short timeframe is always challenging. Effective preparation before project handoff greatly improves workflow efficiency. Setting clear time limits for each task, coupled with prioritization based on importance and dependencies, ensures that critical milestones are met. Utilizing project management tools—such as a Kanban board—helps track progress, visualize workload, and maintain focus. These strategies helped me a lot on delivering quality results within the deadline.
    * Technical Deficiency and Limited Experience
        * Limited technical expertise or lack of familiarity can slow down progress and reduce the depth of analysis. Gaps in knowledge of programming, statistical modeling, or data visualization may require extra time for research, trial-and-error, and troubleshooting. To address these challenges, I sought assistance from generative AI tools such as ChatGPT and GitHub Copilot, which helped debug faulty code and turn ideas into workable solutions. While it sometimes took time to understand, review, and test the suggested code to ensure smooth execution, the process contributed to valuable skill-building. This experience supports my long-term goal of continuous learning and technical growth.


* What new skills or tools do you plan to learn next based on your project experience? 
    *  Regarding the demand forecasting, it is essential to  develop models to predict future sales using historical data and external features (temperature, fuel prices, CPI, unemployment, etc.). Further ML techniques for forecasting are to be developed.


## Main Data Analysis Libraries
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Plotly



## Credits 
- The LMS from the course Data Analytics with AI by Code Institutes provides all the foundamental knowledge building up this project.

- Retail Sales Dataset from Kaggle is used. For more details please visit https://www.kaggle.com/datasets/manjeetsingh/retaildataset

- The texts and codes from this project is reviewed and proofread by ChatGTP and Co-pilot.


## Acknowledgements

* Many thanks to the course masters, Mark and Neil, the facilitators, Vasi and Roman, and all my classmates for the support and inspiration through the journey of learning.