
Minutes of the Group Meeting on Data Mining using Python
]
Members Present:
•	168237 – Austine Namayi
•	150739 – Emma Karanja
•	150367 – Christine Nessy Mungla
•	165828 – Dudi Daniela
•	152318 – Caleb Mugambi
•	167284 – Gacheru Nyaga
________________________________________
Agenda
1.	Discussion of the “Data Understanding” section using the Netflix Titles Dataset.
2.	Responding to the four knowledge check questions provided in the assignment.
3.	Allocating individual tasks and ensuring understanding of the dataset exploration process in Python.

Minutes of Discussion
1. Dataset Overview
The group examined the Netflix Titles Dataset in Google Colab using Python (Pandas library). The dataset was loaded and previewed to understand its structure and contents.
2. Findings
•	Rows and Columns:
The dataset was found to contain [insert actual number after running df.shape] rows and [insert number] columns.
Command used:
•	df.shape
•	Datatypes in the Dataset:
The group identified datatypes such as object, int64, and datetime64.
Command used:
•	df.dtypes
•	Missing Values:
It was confirmed that the dataset contains missing values in some columns such as director, cast, and country.
Command used:
•	df.isnull().sum()
•	Movies vs. TV Shows (Last 20 Rows):
Among the last 20 entries, the group counted the number of Movies and TV Shows using:
•	df.tail(20)['type'].value_counts()
3. Task Allocation
•	Austine Namayi: Code writing and dataset inspection.
•	Emma Karanja: Documentation of findings.
•	Christine Nessy: Analysis of datatypes and missing values.
•	Dudi Daniela: Verification of results.
•	Caleb Mugambi: Preparation of summary text cell for Colab.
•	Gacheru Nyaga: Proofreading and final formatting.
4. Conclusion
The group successfully understood how to perform data exploration and summarization in Python. The next step will involve Data Preparation and Cleaning in the upcoming meeting.

Meeting Adjourned at: [Monday,7:30pm]
Minutes Prepared by: Austine Namayi

