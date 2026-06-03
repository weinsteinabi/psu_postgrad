## College of the Liberal Arts Post-Graduate Dashboard

***Please note that data files and dashboard contents will not be shared to preserve student/gradute privacy, as required under law by FERPA. This is simply a record to indicate that this project was completed.***

This project was completed during my internship with the Office of Analytics and Planning with the College of the Liberal Arts at Pennsylvania State University. Data was pulled from SQL, processed in R, and imported into Microsoft Power BI to create an interactive dashboard for administration to use. It provides a view of trends in student involvement by degree path, as well as student outcomes by degree path. Below is the summary page of the dashboard provided, as a well as an edited screengrab of a page in the dashboard. All counts and values will be hidden to preserve student privacy. 

----

The College of the Liberal Arts Post-Graduate Dashboard reports on the outcomes of the College's majors and minors after graduation. 
This is a combined effort between the College's Career Enrichment Network and the Office of Analytics and Planning. 

## Dashboard Contents
The data is a combination of web-scraping LinkedIn annually by EPSS, self-reported data by students during the post-graduation survey, and data from the College SQL server. 

Below are brief descriptions of each page.
- **Summary** - An overview of post-graduation outcomes, further education, international experiences, employment, and internships.
- **Post-Grad Employment** - Details about count of students employed, employers, salary, time range of job offer received, and how students learned about their job posting. Does not include data for 2024.
- **Employment Geography** - Details about job locations in the United States and a list of countries where students found international employment. Does not include data for 2024. 
- **Further Education** - Details about students who continued their education after graduating from Penn State, including a count by degree type and institution list. Does not include data for 2024. 
- **Internships**  - Details about student internships, including top employers, paid vs. unpaid internships, number of internships had by students, and more. 
- **Internships Geography** - Details about internship locations in the United States and a list of countries where students found international internships.
- **International Experiences** - Details about student international experiences and how many students participated annually.
- **International Experiences Geography** - Details about international experience locations and a list of where students studied.

## How to Use: 
Each page has a set of three filters. The first filter (Academic Year) filters for information based on student graduation year. The second (Department + Program) filters for information based on the selected department or degree program selected. Multiple selections can be made in each filter by holding down the CTRL key on your computer as you select. The third filter allows users to filter for information depending on whether a student went to the Career Enrichment Network for coaching (CEN Coaching). 

## Notes and Limitations: 
- On the Summary page, the Further Education count in the Students Who Pursued Education Post-Graduation bar chart may not match with the Further Education count in the Students' Post-Graduation Outcomes table because the latter table only counts primary statuses, which is limited to only one per student. The bar chart allows students to report further education separately from their primary status.
- Note that both further education and internship reporting on the post-graduation survey are encouraged but not required, so underreporting in both areas may be possible.
- Note that median salary is the middle value of all salaries when sorted in order, and average (or mean) salary is calculated by adding all salaries and divided by the total count of salaries. The median is less affected by extreme values on the low or high end.
- Note that graduation year data was inconsistent in raw data, meaning data presented by graduation year may be inaccurate to a small degree. When multiple graduation years were reported, the most recent year was utilized.
- The majority of data is student-reported and may contain inaccuracies and incomplete fields. In some instances, reported information (workplace, internship locale, and post-grad institution) was modified for consistent formatting and analysis.
----
## Snapshot
<img width="1303" height="734" alt="Snapshot of Post-Graduate Dashboard Summary page, redacted for student privacy." src="https://github.com/user-attachments/assets/14e1984c-20da-4a3d-8d5c-3185eecc848a" />


