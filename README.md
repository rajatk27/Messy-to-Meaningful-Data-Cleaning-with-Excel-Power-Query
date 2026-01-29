🔍 Project Overview

This project demonstrates real-world data cleaning and transformation using Excel Power Query.
The raw dataset contained highly inconsistent, messy loan records stored in a single column with mixed delimiters, formats, currencies, dates, and text patterns.

Preview:
<img width="1316" height="708" alt="CleanLoanData" src="https://github.com/user-attachments/assets/817ab50b-53a6-47dd-86dc-2f6c18df52ec" />



Using Power Query, the data was cleaned, standardized, and transformed into a structured, analysis-ready table.


🧾 Raw Data Challenges

--The original data had multiple issues commonly seen in real business datasets:

--All fields combined into one column

--Mixed separators (|, ,, ;)

--Inconsistent column names (Loan Amt, Amount, Amt, LoanAmount)

--Different date formats (dd-mm-yyyy, mm-dd-yyyy, text dates)

--Currency symbols and text values (₹, “5 lakh”, “FiveHundredThousand”)

--Inconsistent status values (Active, ACTIVE, Closed, Overdue)

--Missing and malformed values

--Irregular spacing and casing issues


🛠 Tools & Technologies Used

--Microsoft Excel

--Power Query (M Language)


🔄 Data Cleaning & Transformation Steps

--Key transformations performed in Power Query:

--Split raw text into columns using conditional delimiters


Extracted and standardized:

Loan ID
Customer Name
Loan Amount
Interest Rate (ROI)
Start Date
Tenure (Months)
Loan Status
City

--Converted text-based amounts into numeric values

--Unified date formats into a single standard (dd-mm-yyyy)

--Normalized categorical values (Status, City)

--Handled missing and invalid entries

--Applied proper data types for analysis and reporting


✅ Final Output

--The cleaned dataset is:

--Fully structured and tabular

--Ready for reporting, dashboards, or SQL/Python analysis

--Suitable for real-world banking or finance use cases


Final Columns:

Loan ID

Name

Loan Amount

ROI (%)

Date

Tenure (Months)

Loan Status

City


🎯 Key Takeaways

Power Query can handle extremely messy real-world data

--No VBA or external tools required

--Ideal for analysts working with Excel-based pipelines

--Strong foundation for BI tools like Power BI


🚀 Who This Project Is For

--Data Analysts

--Business Analysts

--Excel / Power BI learners

--Anyone working with messy operational data
