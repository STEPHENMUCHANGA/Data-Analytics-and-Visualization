# Social Media Cotegory Content Analysis

Table of Contents 

[Project Overview](#project-overview)

[Data Sources](#data-sources)

[Tools Used](#tools-used)

[Data preparation Modeling and Cleaning](#data-preparation-modeling-and-cleaning)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Data Analysis](#data-analysis)

[Findings](#findings)

[Recommendations](#recommendations)

[References](#references)

### Project Overview

##### The project entailed the extraction, cleaning, analysis, and creation of visuals to reveal the trends in content categories of the social media run by Social Buzz Company.

### Data Sources
##### Social media content information which is in csv files stored by the company's SQL database.

### Tools Used
- Data modeling and cleaning using Microsoft Excel [Download here](https//:microsoft.com)
- Data analysis using Microsoft Excel and SQL
- Data visualization using Microsoft Excel
- Data presentation using Microsoft PowerPoint and recorded using Zoom

### Data Preparation, Modeling and Cleaning 
1. Linked different csv files using common unique identifiers using VLOOKUP
2. Cleaning the data to find distinct content categories 

### Exploratory Data Analysis
1. Matching content categories with content IDs
2. Identification of top-5 most popular social media content categories
3. Identification of bottom-5 least popular social media content categories
### Data Analysis
```sql
SELECT*
FROM reactions
ORDER BY column DESC
LIMIT 5;
```
- Also used MS Excel filter tool to determine and extract the same results of top-5 reaction and other social media content categories
### Findings
- The top-5 categories of social media content in descending order were;
  1. Animal - 68624 reactions (Best category)
  2. Science - 65405 reactions
  3. Health - 63138 reactions
  4. Technology - 63035 reactions
  5. Food - 61598 reactions
### Recommendations 
- The management of Social Buzz should channel more resources and focus them towards these top 5 categories to ensure; 
1. Better and more appealing content
2. Generate more revenue
3. Customer attraction and retention
- Enhance creativity or do away with the bottom-5 content categories to avoid;
1. Resource wastage
2. Focus on the relevant categories
### Limitations
- While cleaning the data, negative reviews (negative) values were eliminated because they could have affected the conclusion of the results.
### References 
1. Basic excel data camp [link](https://www.datacamp.com/tutorial/basic-excel-formulas-for-everyone)
2. SQL Practice Problems [link](https://dl.ebooksworld.ir/books/SQL.Practice.Problems.Sylvia.Moestl.Vasilik.9781520807638.EBooksWorld.ir.pdf) 


