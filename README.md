# 🌀 Atlantic Hurricanes Dataset Project


### 📝 Project Summary
This repository contains an Excel-based analysis of a dataset of the most significant hurricanes in Atlantic history. The project demonstrates use of the `SWITCH` function in Excel.

### 🎯 Key skills demonstrated:
`SWITCH FUNCTION` 

### 🗂️ Dataset Structure
The initial dataset contained the historical storm data (1870 - 2017) including when the dates, financial impact, maximum wind speed and a separate table listing the Saffir-Simpson hurricane categories. The Saffir-Simpson Hurricane Wind Scale is a classifcation system used to measure the intensity of hurricanes based omn their maximum wind speed. The scale ranges from 1 to 5, with hurricanes assigned as Categpry 5 having the highest maximum wind speed and those assigned Category 1 having the lowest wind speed.  

The below key metrics have been recorded for each hurricane, each represents a column of the dataset:  
| Column Name           | Description                                                |
|-----------------------|------------------------------------------------------------|
| Name                  | The offfical name of hurricane                             |
| Start Date            | The date the storm began                                   |
| Damage (USD Millions) | The estimated financial impact of the storm at the time    |
| Category              | Saffir-Simpson hurricane category (1-5)                    |
| Max Wind Speed        | The maxium sustained wind speed recorded                   |

### 🛠️ Excel Skills Demonstrated
#### ☑️ `SWITCH` Function
Used the `SWITCH` function to ascribe a max wind speed for each hurricane based on it's Saffir-Simpson category. 

---
### 🧩Process
To categorise hurricanes in the dataset according to wind speed using the SWITCH function, ensuring consistent classification across all records. 
 
#### ⤵️ Data Loading
- Imported the dataset into Excel and reviewed the dataset to understand the structure and key variables.
- Checked that dates, numbers and text were in the correct format.
- Ensured there was no missing values.

<img width="378" height="255.4" alt="image" src="https://github.com/user-attachments/assets/f9896abd-0846-4d80-a2d2-4cadddd6c100" />

#### 🔀 `SWITCH` Function
- Inserted a new column: 'Max Wind Speed'
- Applied the `SWITCH` function to assign each hurricane a Saffir-Simpson category.
  
<img width="878.2" height="262.2" alt="image" src="https://github.com/user-attachments/assets/3193e821-de65-4dd2-b8df-dbe40fc16d0e" /> <br> 

- Checked a random selection of rows to ensure the formulas had worked correctly. 
- **Example of formula used:**  
`=SWITCH(D4,1,95,2,110,3,129,4,156,5,"157 and over", "Unknown")`

---
### 🪞 Reflection 
* Each hurricane in the dataset now has a clearly assigned maximum wind speed.
* The categorisation makes it easier to filter, sort and analyse storms by severity.
* The `SWITCH` function applied consistently across all records with no errors (yay!).
* The most damaging hurricances were Irma (300,000M) Katrina (2005, $108,000M) and Jeanne (2004, $7,660M).
* Most hurricanes reached Category 4 and 5, with maximum speeds of 156 mph and 157+ mph respectively.
* Lower-category hurricanes can still cause significant damage e.g. Fifi-Orlene (Category 2, $1,800M) caused more damage than Category 5 hurricane David ($1,540M).

---
### 📁 Files in This Repository
- **[Biggest Atlantic Hurricanes.xlsx]()**

### 📋 Dataset Structure

| Column Name        | Description                                                                 |
|--------------------|-----------------------------------------------------------------------------|
| Transaction ID     | Unique identifier for each transaction                                      |
| Date               | Date of purchase (MM/DD/YYYY format)                                        |
| Customer ID        | Unique identifier for each customer                                         |
| Gender             | Gender of the customer (male/female)                                        |
| Age                | Age of the customer                                                         |
| Product Category   | Category of product purchased (clothing, beauty, electronics)               |
| Quantity           | Number of units purchased                                                   |
| Price per Unit     | Price of a single unit                                                      |                                                        
| Day Name           | Shows the weekday name (Monday–Sunday) of the transaction                   |
| Month Name         | Shows the shortened month name (e.g. Jan) of the transaction                |
| Month              | Shows numeric month (1–12) of the transaction                               |
| Year               | Shows the year of the transaction                                           |
| Day                | Shows the day of the month of the transaction                               |
| Generation         | Shows the generation of customers (young adult, adult and senior) by age    |
| Sale Total         | Shows sale total per transaction (quantity x price per unit)                |
| Commission 2023    | Shows the commission per transaction in 2023                                |
| Commission 2024    | Shows the commission per transaction in 2024                                |
