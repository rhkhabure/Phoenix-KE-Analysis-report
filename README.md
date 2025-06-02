# Phoenix Ke Analytics
Phoenix KE Analytics is a technology company that started in 2022. Its goal is to positively impact the lives of five million people. The company aims to have skilled data professionals makeup 40% of the workforce in analytical roles. The founder, Susan Gatura, noticed that women are underrepresented in the data field and that many organizations do not understand how to use data effectively. These observations led to the creation of Phoenix KE Analytics.
This report is based on publicly available data from the Phoenix KE website and a survey completed by participants in data science and analytics. The report's main goal is to evaluate the current state of the data science and analytics sector in Kenya. It will look at which industry sectors are becoming overcrowded, identify the most commonly used technology stacks and their combinations, and explore ways to increase women's representation in this field. This focus is important because there is not enough female participation in the data science industry.
## Objective
The main objective of this report is to evaluate the current state of the data science and analytics sector in Kenya. Specifically, it aims to identify which sectors of the industry are experiencing heightened saturation, ascertain the most frequently utilized technology stacks and their various combinations, and investigate strategies to increase the representation of women within this field. The recognition of insufficient female participation in the data science industry warrants this focus.

## Data Source
Data were collected through a survey that was made accessible to individuals within the data field. The survey comprised twelve questions, incorporating both open-ended and closed-ended formats. The data collection period extended from February 10, 2023, to October 2, 2025. Initially, the information was stored in a spreadsheet and was subsequently converted into a CSV file for analysis.

## Methodology
Tools used 
VS Code's Data Wrangler, 
Pandas
Power BI for data transformation.

### Data Cleaning
To ensure data integrity, duplicates were removed, as they can distort analysis. Missing values in the monthly gross income column were filled with the median income due to significant variations in the data. Rows with null values were deleted in critical columns, specifically the ‘Current Role’ column, essential for understanding participant distribution.
Data types were adjusted accordingly, particularly in the gross salary column, which had inconsistent formats (e.g., ‘80k’, '2.5 M'). Salary figures were standardized and converted to Kenyan Shillings (Ksh) using current exchange rates. The gross salary column was then changed to ‘float64’ for numerical computations. Descriptive analysis revealed a wide salary range, prompting the use of median values for better representation in graphs.

### Data Transformation
Data was imported into Power BI, where transformations began by duplicating the ‘Tech stack’ and ‘Benefits’ columns for individual analysis. Data values were split by commas, and white spaces were removed. The ‘Gross monthly Income’ column was converted to a decimal type, with ‘Ksh’ as the currency format.

## Findings and insights
According to Susan's observations, there exists a pronounced gender disparity within the data sector, particularly in the field of data engineering, which comprises a predominantly male workforce, with women representing only a small fraction. Data analysts constitute the majority of professionals in this field, while data engineers remain the minority; however, they represent the highest-paying roles within the group. The most lucrative work arrangement is characterized by a hybrid model that allows employees the flexibility to determine their office attendance.
Furthermore, it is noted that established companies tend to offer higher salaries than startups. The data sector is relatively small but experiencing growth, with most professionals possessing between three to five years of experience. Notably, data engineers generally have a higher concentration of individuals with seven or more years of experience in the field.
The financial technology (fintech) sector stands out as the leading industry for data professionals, while agriculture, finance, and technology communication are recognized as the highest-paying sectors within this domain.

## Recommnedations
To enhance gender equality, it is recommended that Phoenix KE prioritize the data engineering sector, which currently exhibits a significant underrepresentation of women. This initiative may be realized through the expansion of existing data workshops to include an additional focus on data engineering. Furthermore, the Phoenix KE immersion program could be segmented into three primary data domains to facilitate targeted learning.

In addition, masterclasses should be instituted to provide foundational data knowledge to individuals from industries outside of the data sector. These masterclasses could cover essential skills such as Microsoft Excel, the Pandas library, data visualization techniques, and introductory Python programming. It is important to note that the current and future masterclasses are designed for individuals who already possess a basic understanding of the data industry, thus emphasizing the need for entry-level offerings.

