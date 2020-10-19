# Welcome to Abram's Portfolio.  

## Personal Programming/Data Science Projects
<br/>

## [Project 1:  Consumers Energy Job Text Analysis](https://github.com/abrambeyer/consumers_energy_job_text_analysis)
- Open the [Consumers Energy Careers Website](https://www.consumersenergy.com/company/careers)
- Use Selenium and BeautifulSoup to open each job listing page, open job listings and scrape the job description text from the page.
- Results pulled as of 10/18/2020.  However, each time you run the script, it will pull what job listings are currently available.
- Final vocabulary of 1792 words from 18 distinct analytics-related jobs 

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/cms_job_description_word_cloud.png" width=300>

## [Project 2:  Beyer Chestnut Orchard Project](https://github.com/abrambeyer/Beyer_Chestnut_Orchard_Project)
##### My father is a hobby chestnut farmer.  His orchard is in the early development stage.  I built him a suite of tools to help manage his orchard and make the best planning decisions possible about what trees he currently has, which trees are performing the best, how to quickly find and track trees of interest, and other adhoc data questions he may have over the years.  The data is stored in an Access database I designed and built from scratch.  Adhoc data questions are answered mainly with adhoc R scripts, RMarkdown reports, and a Tableau dashboard on Tableau public.

- **Access Database** 
  - Built an Access Database from scratch.  This database tracks, tree location, tree events (plantings, death, trimming, fertilization, etc.), tree varieties, etc.  This is a local datbase and not available to view in this repo.  Although, I have included an image of the ER Diagram down below.
- **R Project**
  - *Adhoc Exploratory Data Analysis*:  Several R scripts for answering one-off questions.  The R scripts make the answers easy to reproduce and update as more data is added to the database. 
  - *RMarkdown Files*:  Currently, these RMarkdown reports are pre-designed to quickly allow my father to identify overall turnover in his field, what trees are currently alive/dead in the field, where are each tree variety in his field, any special notes he has attached to a tree (any experiments or trees of concern).
- **Tableau Dashboard**
  - I built a high-level overview dashboard to accompany this suite of tools.  The dashboard gives my father insight into avg. cost per variety, death rates, yearly plantings and deaths so he can better plan for next years and understand how many trees he should be replacing and which variety will do best.
- **Excel**
  - Provides a simple way to record the data and mass insert into Access.  Walking the field with a tablet with Excel installed.  Return to the local machine and mass insert new data points.  

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/beyer_orchard_tree_variety_layout1.PNG" width=300> | <img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/beyer_chestnut_orchards_planning_dashboard_gif.gif" width=300>

<br/>

## Research/Publications/Conference Talks

<br/>

## [Conference Presentation:  Vizient Connections Summit 2020](https://github.com/abrambeyer/Research_Publications_Conference_Presentations_Posters/tree/main/vizient_summit_2020)
- ***Presentation Title: Operationalizing the Vizient Quality and Accountability Study to Unify a Health System’s Performance*** 
- Built an automated python pipeline with selenium to configure and run hundreds of Vizient CDB reports, wrangle and organize excel files, extract data from the excel files and store into SQL Server database
- Built custom database schema to store the data and query from it
- Built a series of SQL queries to automatically perform roll-up calculations
- Built a Tableau dashboard and SSRS scorecards to report out numbers to hospital leadership in an aligned fashion 
- Created a timely, system-wide inpatient quality composite in order to promote fair system-wide benchmarking against similar hospital cohorts  

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/inpatient_quality_composite_pipeline2.PNG" width=300>

## [Publication: Journal of Acute Care Physical Therapy: April 2020](https://github.com/abrambeyer/Research_Publications_Conference_Presentations_Posters/tree/main/improvement_of_physical_and_occupational_therapy_referral_process)
- ***Article Title: Improvement of Physical and Occupational Therapy Referral Process to Reduce Unskilled Consults***
- Baseline data collected for 9 months showed that physical (PT) and occupational therapy (OT) services were consulted 14.5% of the time for unskilled therapy needs. The goal of this performance improvement project was to identify whether acute care physical and occupational therapists can reduce unskilled consults using a multidisciplinary education intervention.

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/Percentage%20of%20Unskilled%20PT_OT%20Consults%20from%20May%2017%20July%2018.jpeg" width=300>

## [Conference Poster: ACRM (American Congress of Rehabilitation Medicine) 2019 Annual Conference](https://github.com/abrambeyer/Research_Publications_Conference_Presentations_Posters/tree/main/using_data_science_to_manage_an_acute_care_rehabilitation_department)
- ***Poster Title: Using Data Science To Manage An Acute Care Rehabilitation Department***
- Established long-term partnership with the Physical & Occupational Therapy Departments to identify strategies to collaborate and improve outcomes.
- Key pain points were demonstrating and advocating the value of the department, better understanding of productivity, and reduced unskilled consults (someone sent to PT/OT when unable or unready for treatment causing wasted time and money)
- Using exploratory analysis, benchmarking, trends and forecasting, identified areas for improvment and advocated for appropriate staffing, appropriate therapy doses and appropriate fiscal stewardship.
- Metrics developed and tracked:  Response to Referall, Adherence to Treatment Frequency, Readmission Rates, Productivity by RVU.
 
 <img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/using%20data%20science%20to%20manage%20an%20acute%20care%20rehabilitation%20department%20acrm%20poster.png" width=300>


## Tableau Public Dashboards


