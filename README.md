Project Workflow / Process

1. Data Collection
The project uses a Shark Tank India startup investment dataset containing information
about startup pitches, investor participation, deal amounts, equity offered, founder details,
and business performance metrics.

3. Data Cleaning and Preprocessing (Python)
Python and Pandas were used to prepare the dataset for analysis.

Steps performed:

* Loaded the dataset using Pandas
* Checked dataset structure, data types, and missing values
* Cleaned column names and removed inconsistencies
* Converted financial fields such as deal amount, equity, revenue, and valuation into numeric format
* Created a Funding Success column to identify startups that received investment
* Exported the cleaned dataset into a CSV file for dashboard development

3. Data Transformation (Power Query)
The cleaned dataset was imported into Power BI.

Key transformations included:

* Removing unnecessary fields
* Handling null values
* Converting columns into appropriate data types
* Unpivoting investor investment columns to restructure the dataset into an investor-wise format for easier analysis
* Preparing data for efficient dashboard visualization
  
4. Data Modeling
Relationships and measures were created to support analytical insights.

Important calculated metrics included:

* Total Startups
* Funded Startups
* Funding Success Rate
* Total Investment
* Average Deal Amount
* Investor-wise Capital Deployment

DAX formulas were used to generate these KPIs.

5. Dashboard Development (Power BI)
An interactive Power BI dashboard was created consisting of three analytical sections:

# Investment Overview
Provides a high-level summary of startup funding including total startups, funding distribution by 
industry, geographic distribution, and season-wise investment trends.

# Investor Investment Analysis
Analyzes investor behavior by ranking investors based on total capital deployment, deal participation 
frequency, and average investment per deal.

# Founder & Business Performance Analysis
Explores relationships between funding outcomes and founder characteristics such as team size,
gender distribution, revenue performance, and patent ownership.

6. Insight Generation
The dashboard was designed to identify key investment patterns such as:

* Industry sectors attracting the highest funding
* Investor strategies based on deal participation and capital deployment
* Impact of founder team composition on funding success
* Relationship between startup revenue and investment size

7. Visualization & Storytelling
The final dashboard was structured to provide a clear analytical narrative, enabling users to
interactively explore startup investment trends and investor decision patterns.

# Tools Used #

* Python (Pandas, NumPy)
* Power BI
* Power Query
* DAX
* Data Visualization Techniques
  
