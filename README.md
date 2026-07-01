# UK-University-Performance-Analysis
Data analysis and visualisation project investigating UK university league tables and higher education enrolment data. The project explores institutional performance rankings, competitive benchmarking, and analyses patterns across key metrics. I use Alteryx automated workflow to import and cleanse the datasets. Finally, I use Tableau to visualise the findings across a series of interactive dashboards.

# Data Collection & Preprocessing
University League Tables source & methodology: https://www.thecompleteuniversityguide.co.uk/league-tables/rankings

Higher Education Statistics Agency (HESA) subject enrolment data: https://www.hesa.ac.uk/data-and-analysis/students/what-study<br>

Column Definitions (for more detailed information, visit the League Tables methodology link above):

- Entry Standards: The average UCAS tariff score of new undergraduate students.
- Student Satisfaction (maximum score 4): A measure of student views of the teaching quality at the university. 
- Research Quality (maximum score 4): A measure of the quality of the research undertaken in the university.
- Research Intensity (maximum score 1): A measure of the proportion of teaching staff involved in research.
- Graduate Prospects - Outcomes (maximum score 100): A measure of the success in employability or further study of graduates completing their first degree.
- Academic Services Spend: The expenditure per student on all academic services.
- Facilities Spend: The expenditure per student on staff and student facilities.
- Degree Completion: A percentage of full-time UK domiciled students starting a first-degree course who are projected to gain a degree.




Below is the Alteryx ETL workflow that I used to dynamically input, clean, and append the HESA enrolment data


<img width="705" height="246" alt="Alteryx ETL workflow" src="https://github.com/user-attachments/assets/df522ef4-35a8-4185-917a-40517a37b5fc" />



# Data Analysis and Visualisation
- League Ranking Overview: Surfaced how a university's average score and research quality compare to the national average across 130 institutions, giving immediate context on competitive standing.
- Score Distribution: Identified where the bulk of universities cluster in the scoring range, highlighting how differentiated (or compressed) the league table is at different performance tiers.
- Research vs Outcomes: Revealed a positive relationship between research quality and graduate prospects, supporting the case that research investment correlates with stronger student employment outcomes.
- Comparative Performance: Pinpointed which institutions consistently outperform peers across multiple metrics simultaneously (versus excelling in just one area), useful for identifying genuinely well-rounded universities.
- University Benchmarking: Enabled stakeholders to instantly see how a chosen university's rank, percentile, and overall score stack up against both the national average and top-tier institutions, flagging specific performance gaps to target.
- Performance Metrics: Diagnosed which specific areas (entry standards, degree completion, graduate outcomes, research quality) are dragging a university's overall position down or lifting it up relative to top performers, informing where strategic improvement would have the most impact.
- Trend Analysis: Tracked whether a university's performance is improving, declining, or stagnant over nearly two decades relative to top 10% and national benchmarks, useful for assessing the effectiveness of past strategic initiatives.
- Subject Enrolment Insights: Highlighted which subjects drive the bulk of a university's enrolment, informing decisions on resource allocation, course investment, or marketing focus.

# Dashboard

Access Tableau dashboard [here](University%20Performance%20Analysis.twbx)

Below are the overview and performance dashboards.<br><br>

<img width="1707" height="909" alt="University Overview Dashboard" src="https://github.com/user-attachments/assets/8a20ad90-d3e1-4fb2-b3ff-5a1809f041dd" /><br>

<img width="1708" height="910" alt="University Benchmark Dashboard" src="https://github.com/user-attachments/assets/b31ab64a-1ac9-4ede-bdd3-209e58015d21" />







