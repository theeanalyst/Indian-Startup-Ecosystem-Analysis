# Indian-start-up-funding-ecosystem-analysis

## Business Understanding
### Objectives

The primary aim of this analysis is to gain a comprehensive understanding of the Indian startup ecosystem. It involves identifying pivotal funding trends and delving into the critical factors that influence a startup's funding prospects. Ultimately, the knowledge acquired through this study will be applied to boost our own startup's likelihood of securing funding.

### Data Understanding

The dataset encompasses valuable information pertaining to the Indian startup ecosystem, covering the years 2018, 2019, 2020, and 2021. It comprises essential data such as funding stages, company details, founding year, funding amounts, investors, industry sectors, company descriptions, founder information, and headquarters location. Our objective is to delve into the dataset to uncover and analyze funding trends and the influential factors that determine a startup's capacity to secure funding.

### Data Preparation

Our next step involves the meticulous cleaning and preprocessing of the dataset, ensuring its suitability for analysis. This process entails eliminating any missing or duplicated data, transforming the existing data into an appropriate format for analysis, and generating new variables as necessary to address our research questions effectively.

### Hypothesis 
Null hypothesis(Ho): There is no significant relationship between a startup's sector and amount of funding secured.

Alternative hypothesis(Ha) There is a significant relationship between a startup's sector and amount of funding secured.

### Questions
1. Which companies received the highest amount of funding? 
2. What is the trend in startup funding in India over the years?
3. At what funding stage did investors fund the highest?
4. Which cities received the highest amount of funding ?
5. Which sectors received the highest amount of funding? 

### Information Needed/To work on
1. Information on year of funding
2. Information on Location
3. Information on Stage of Development
4. Information on Sector of Operation
5. Information on Amount of Funding

### Types of data-related issues:

1. The column names in Data18 are different from the other datasets.
2. Data20 contains an unnecessary column named 'unnamed: 9'.
3. Data18 is missing columns for founders, investors, and the year founded.
4. The 'amount' column in all datasets includes currency symbols, commas, and is stored as a string.
5. Null values are present in the 'founded', 'headquarter', 'sector', and 'stage' columns.
6. The 'headquarter' column in Data18 contains additional information compared to other datasets.
7. The values in the 'sector' column differ among all datasets.
8. The 'amount' column has null values.
9. The data types are mostly represented as objects.

### Planned solutions to address the issues:

1. Rename the column names in Data18 to match the other datasets.
2. Remove the unnecessary 'unnamed: 9' column from Data20.
3. Add missing columns with null values for founders, investors, and the year founded in Data18.
4. Convert all amounts in all datasets to dollars as floating-point numbers.
5. Modify the 'headquarter' column in Data18 by separating values with commas and keeping only the first word.
6. Standardize sector values
7. Drop all null values in amount column
8. Adjust the data types of each column accordingly.
