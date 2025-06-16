# CIS-591-Property-Maintenance
SECTION 1.
Authors:

Nasim Ranjbari

Alvin Lee

Sahil Walia

Balbir Singh

Miao

Project Name: CIS 591 Python for Data Analysis
Duration: Sept. - Oct. 2024
Faculty: Prof. Lu Xiao

Problem Statement
We are conducting an analysis of the Property Maintenance dataset, which captures complaints and concerns reported by residents in the Phoenix area. Our goal is to derive key insights from the data to aid in decision-making.

Specifically, we aim to:

Identify the top neighborhoods with the highest number of reported complaints.

Evaluate neighborhoods based on complaint metrics to suggest the top neighborhoods to live in.

Analyze the status of complaints (open, closed, in progress) and the number of inspections required to resolve them.

Examine whether there is a correlation between the number of inspections and complaint resolution.

Provide insights into the maintenance concerns within different neighborhoods and inform potential improvements in service response and neighborhood conditions.

Dataset Description
The dataset relates to neighborhood services and property maintenance, updated monthly.

Raw Data Attributes:

Total Rows = 106,322

Total Columns = 6

Fields:

CSM_CASENO – Case Number (string)

CSM_ADDRESS – Property Address (string)

PRC_COUN_DIST – Council District Number (integer)

CSM_STATUS – Current Case Status (string)

TOTAL_INSP – Number of Completed Inspections (integer)

NOTES – Inspector Notes (string)

SECTION 2.
Pseudo Code
Load and Clean Data

Load Excel file

Remove rows with missing or trash values

Drop unknown addresses and error notes

Descriptive Analysis

Count unique cases

Total inspections

Distribution of statuses

District-level counts

Inspection Performance Analysis

Top districts with complaints

Properties with high inspection counts

Average inspections per status

Correlation Analysis

Compare closed vs open cases

Explore inspection–resolution link

Anomaly Detection

Detect properties with extreme inspection frequency

Final Insights

Common complaint issues

Council districts with highest cases

Whether more inspections lead to resolution

Conclusion

Interpret findings

Suggest actionable strategies

