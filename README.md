## College of the Liberal Arts Post-Graduate Dashboard

***Please note that data files and dashboard contents will not be shared to preserve student/gradute privacy, as required under law by FERPA. This is simply a record to indicate that this project was completed.***

This project was completed during my internship with the Office of Analytics and Planning with the College of the Liberal Arts at Pennsylvania State University. Data was pulled from SQL, processed in R, and imported into Microsoft Power BI to create an interactive dashboard for administration to use. It provides a view of trends in student involvement by degree path, as well as student outcomes by degree path. In the attached Markdown file is the synopsis of this project and an example panel with data redacted. 

The dashboard was created for the Career Enrichment Network in the College and was passed to me during my internship from others in the office, Sandy Sollenberger and Heather Rutten. Below is a synopsis of the project. 

### Data Sourcing
Data was compiled from information provided by students in the college-wide End of Semester and Post-Grad Surveys sent out by the Career Enirchment Network (CEN), as well as information stored within the University's SQL server and data noted in student LinkedIn profiles. Information pertaining to study abroad experiences was obtained through a combination of these sources and post-excursion surveys also sent by the CEN. 

### Data Processing
Data was provided to me, unprocessed, in .csv format. A total of 11 files were obtained, cleaned, and merged in RStudio, culminating in over 560 lines of code and multiple hours of manual cleaning to address inconsistencies in the data. This was the most time-consuming aspect of the project, as it was imperitive that merges were conducted accurately, data was properly filtered, and naming conventions were consistent across all files. Once this was completed, data was imported into Microsoft Power BI, where additional measures were created to address visualization needs.

### Backend Management
Upon importing the data, it was necessary to properly define relationships between the finalized data files (of which there were five - student identifying information, post-graduation outcomes, internships, study abroad, and degree guides). This required going into the backend of the dashboard, and assigning the proper relationships between each table. This ensures that filters function appropriately in the dashboard. 

### Data Visualization
Data was aggregated and transformed into interactive visualizations across eight panels in the dashboard. Visualizations include tables, line charts, bar charts (stacked, grouped, and single), interactive maps, and pie charts. Brief summaries were included in the visualizations as well. All visuals change as data is filtered by academic year and degree program.  
