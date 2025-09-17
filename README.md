CAPSTONE PROJECT

SHARK ATTACKS ANALYSIS – DOCUMENTATION

Project Overview:

This project analyses over 6,094 recorded shark attacks spanning the past 100+ years.

The goal was to clean, transform, and visualise the data to uncover trends, identify high-risk areas, and provide actionable insights for decision-makers.

I worked through data cleaning, transformation, exploratory analysis, and visualisation using Power Query (Power BI) and applied best practices for building an interactive dashboard.

Objectives & Business Questions

The analysis focused on answering these key questions:

1.	Annual Trends: How have shark attacks changed over time since 1900?
   
2.	High-Risk Countries & Locations: Which countries report the most attacks, and which locations are most dangerous?
   
3.	Body Parts Injured: What body parts are most frequently affected?
   
4.	Time of Day Analysis: Are attacks more common in the morning, afternoon, evening, or night?
   
5.	Shark Species: Which species are involved in most attacks?
  
6.	Fatality Analysis: What percentage of attacks are fatal?
   
7.	Additional Insights:
    
o	Age distribution of victims.

o	Gender distribution of victims.

Data Quality Considerations

The original dataset contained 6,094 rows, but after data cleaning and validation:

•	Only 1,474 rows were sufficiently complete for reliable analysis.

•	The remaining rows were excluded due to missing or invalid key fields such as Year, Country, Location, or Attack Type.

Implication:

The results reflect trends in well-documented, high-quality cases, not every single recorded attack.

This improves insight accuracy but should be kept in mind when interpreting the findings.

Process & Approach

1. Data Cleaning & Preparation (Power Query)
   
•	Removed unnecessary columns (like duplicates, irrelevant metadata).

•	Handled missing data

•	Created new columns:

o	Time of Day (Morning, Afternoon, Evening, Night) from messy text/time data.

o	Fatal Boolean (TRUE/FALSE) for better filtering and aggregation.

o	Body Part classification from injury descriptions (text search using if/else logic).

•	Trimmed and standardised text columns to remove trailing spaces and inconsistencies.

2. Data Modelling
   
•	Species Mapping Table: Created and merged to standardise species names.

•	Ensured proper data types for Year, Time of Day, and Fatal Boolean.

3. Analysis & Visualisation (Power BI)
   
•	KPIs:

o	Total Attacks

o	Total Fatal Attacks

o	Fatality Rate (%)

o	Most Affected Country

o	Shark Species Count

•	Other Visuals:

o	Annual trend of shark attacks since 1900.

o	Shark attacks by Country.

o	Top 10 most dangerous locations.

o	Most Often Injured Body Parts.

o	Shark Attacks by Species.

o	Shark Attacks by Time of Day.

o	Shark Attacks by Age and Gender.

o	Slicers: Year, Country, Species, Fatality, Time of Day, Activity.

Insights

•	Shark attacks have generally increased over the last century, likely due to improved reporting and increased human interaction with oceans.

•	Top countries: USA, Australia, South Africa, and Brazil report the highest number of attacks, with the USA being the most affected Country.

•	Body parts affected: Legs and feet are most commonly injured.

•	Peak attack times: The majority of records had incomplete or missing time-of-day data, which were grouped as “Unknown”. As a result, “Unknown” appears as the largest category in the analysis. Among records with valid time-of-day information, “Afternoon” attacks were the most frequently reported, suggesting that shark activity or human presence in the water may peak during this period.

Recommendation: Future reporting should aim to capture complete time information to improve the accuracy of trend analysis and enhance safety planning.

•	Species: The majority of shark attack records lacked detailed species identification and were grouped as “Others”, which also turned out to be the largest category in the analysis. Among the records with identified species, Great White Sharks were responsible for the most attacks, followed by Tiger Sharks.

Recommendation: Enhancing species reporting during shark attack documentation would improve the accuracy of species-specific risk analysis, which is critical for targeted public safety campaigns and conservation efforts.

Tools & Skills Used

•	Power BI (Data modelling, DAX, Visualisations)

•	Power Query (ETL: Extract, Transform, Load)

•	Data Cleaning (Handling nulls, text standardisation, custom column logic)

•	Exploratory Data Analysis (Trend and distribution insights)

Deliverables

•	Interactive Power BI Dashboard (with slicers for exploration)

•	Dashboard Screenshot: <img width="665" height="776" alt="Shark_Attacks_Dashboard" src="https://github.com/user-attachments/assets/be524250-3ae4-4a6d-beac-df91a90e6ac3" />

Dashboard PDF: [Shark_Attacks_Project.pdf](https://github.com/user-attachments/files/22385034/Shark_Attacks_Project.pdf)

