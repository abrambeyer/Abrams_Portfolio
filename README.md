# Welcome to Abram's Portfolio.  

<br/>

## Personal Programming/Data Science Projects

<br/>

### [Project 1:  Consumers Energy Job Text Analysis](https://github.com/abrambeyer/consumers_energy_job_text_analysis)
- Open the [Consumers Energy Careers Website](https://www.consumersenergy.com/company/careers)
- Use Selenium and BeautifulSoup to open each job listing page, open job listings and scrape the job description text from the page.
- Results pulled as of 10/18/2020.  However, each time you run the script, it will pull what job listings are currently available.
- Final vocabulary of 1792 words from 18 distinct analytics-related jobs 

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/cms_job_description_word_cloud.png" width=300>

### [Project 2:  Beyer Chestnut Orchard Project](https://github.com/abrambeyer/Beyer_Chestnut_Orchard_Project)
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

### [Project 3:  Outlook Invite Sender](https://github.com/abrambeyer/outlook_calendar_inviter)
- Each month, our team organizes a series of tasks by sending out monthly calendar invites via Outlook.  However, the process of updating the dates and sending the invites used to require a manager to manually send more than 50 calendar invites each month.  This took too much of their time.
- Built a vba script that loops over an Excel spreadsheet and sends Outlook meeting invites in seconds.

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/excel_image.PNG" width=300>

<br/>

## Research/Publications/Conference Talks

<br/>

### [Conference Presentation:  Vizient Connections Summit 2020](https://github.com/abrambeyer/Research_Publications_Conference_Presentations_Posters/tree/main/vizient_summit_2020)
- ***Presentation Title: Operationalizing the Vizient Quality and Accountability Study to Unify a Health System’s Performance*** 
- Built an automated python pipeline with selenium to configure and run hundreds of Vizient CDB reports, wrangle and organize excel files, extract data from the excel files and store into SQL Server database
- Built custom database schema to store the data and query from it
- Built a series of SQL queries to automatically perform roll-up calculations
- Built a Tableau dashboard and SSRS scorecards to report out numbers to hospital leadership in an aligned fashion 
- Created a timely, system-wide inpatient quality composite in order to promote fair system-wide benchmarking against similar hospital cohorts  

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/inpatient_quality_composite_pipeline2.PNG" width=300>

### [Publication: Journal of Acute Care Physical Therapy: April 2020](https://github.com/abrambeyer/Research_Publications_Conference_Presentations_Posters/tree/main/improvement_of_physical_and_occupational_therapy_referral_process)
- ***Article Title: Improvement of Physical and Occupational Therapy Referral Process to Reduce Unskilled Consults***
- Baseline data collected for 9 months showed that physical (PT) and occupational therapy (OT) services were consulted 14.5% of the time for unskilled therapy needs. The goal of this performance improvement project was to identify whether acute care physical and occupational therapists can reduce unskilled consults using a multidisciplinary education intervention.

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/Percentage%20of%20Unskilled%20PT_OT%20Consults%20from%20May%2017%20July%2018.jpeg" width=300>

### [Conference Poster: ACRM (American Congress of Rehabilitation Medicine) 2019 Annual Conference](https://github.com/abrambeyer/Research_Publications_Conference_Presentations_Posters/tree/main/using_data_science_to_manage_an_acute_care_rehabilitation_department)
- ***Poster Title: Using Data Science To Manage An Acute Care Rehabilitation Department***
- Established long-term partnership with the Physical & Occupational Therapy Departments to identify strategies to collaborate and improve outcomes.
- Key pain points were demonstrating and advocating the value of the department, better understanding of productivity, and reduced unskilled consults (someone sent to PT/OT when unable or unready for treatment causing wasted time and money)
- Using exploratory analysis, benchmarking, trends and forecasting, identified areas for improvment and advocated for appropriate staffing, appropriate therapy doses and appropriate fiscal stewardship.
- Metrics developed and tracked:  Response to Referall, Adherence to Treatment Frequency, Readmission Rates, Productivity by RVU.
 
 <img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/using%20data%20science%20to%20manage%20an%20acute%20care%20rehabilitation%20department%20acrm%20poster.png" width=300>

### [Research:  CityText Project; Dr. Eli Brown; DePaul University](https://github.com/abrambeyer/CityTextProject)
  - Research project with Dr. Eli Brown (DePaul Unversity)
  - Use Python to collect data from various social media APIs:  Twitter, EveryBlock (Nextdoor.com),Chicago Crime Open Data,Facebook,Reddit
  - For Twitter API, used QGIS to generate centroid and area of each Chicago neighborhood in order to tag tweet with approximate neighborhood source
  - I built a web page using HTML/CSS, javascript and D3.js to visualize Chicago social media data by neighborhood.  Visualizations include a Word Cloud, Suffix Trees, Bar charts.
  - Built a Flask server to serve up the data from MongoDB
  - (images unavailable)

<br/>

## Tableau Public Dashboards

<br/>

### [Tableau Project 1: H1B Visa Project](https://github.com/abrambeyer/Tableau_Projects/tree/main/h1b_visa_project_2015_2019)
- **Tableau Dashboard 1** 
  - Built first Tableau dashboard using pre-wrangled data from [Kaggle](www.kaggle.com).  [Data Source](https://www.kaggle.com/nsharan/h-1b-visa).  Inspired by Sharan Naribole's initial data submission.
- **Tableau Dashboard 2**
  - *Data Collection*:  Updated the Kaggle dataset to new time period.  The original dataset was old (2011-2015).  I wrote my own R code to perform the same data collection for the time period 2015-2019.  This involved heavily updating the original R code from kaggle in order to wrangle the new time period.  [Data Source](https://www.dol.gov/agencies/eta/foreign-labor/performance)
  - *Data cleaning*:  Collected the data, joined multiple data files, filtered and engineered features using dplyr syntax.  Tidying the dataset included probabilistic correction of location data.
  - New dashboard design on Tableau Public for the new dataset.  

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/2015_2019_demo_gif.gif" width=300> | <img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/2011_2015_demo_gif.gif" width=300>  

### [Tableau Project 2: Beyer Chestnut Orchard Project Planning Dashboard](https://github.com/abrambeyer/Tableau_Projects/tree/main/beyer_chestnut%20_orchards_planning_dashboard)
- ***Also displayed above***
- I built a high-level overview dashboard to accompany a suite of tools for my father's hobby chestnut farm.  The dashboard gives my father static view insight into avg. cost per variety, death rates, yearly plantings and deaths so he can better plan for next years and understand how many trees he should be replacing and which variety will do best.  Since this is a static view, there are no filters.  As new data is added to the database, it will update the "current" overview of the orchard.  This dashboard will likely grow as the database grows.  I plan to add information about yearly crop yields and forecasting.

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/beyer_chestnut_orchards_planning_dashboard_gif.gif" width=300> 

### [Tableau Project 3: Hospital Patient Movement Viz](https://github.com/abrambeyer/Tableau_Projects/tree/main/hospital_patient_movement_viz)
- This dashboard project was first motivated by a need to potentially track *where* patients go throughout their stay in the hospital.  To give operations managers a high level view of tracking items such as patient satisfaction and certain patient conditions.  The hope is to give operations leaders an idea of certain pathway trends that lead to patient satisfaction/disatisfaction.  Tracking patient conditions has become increasingly important with the COVID pandemic as patients sometimes test positive after moving to several units in the hospital and the need to quarantine all providers who come in contact with those patients.  

<img src="https://raw.githubusercontent.com/abrambeyer/Abrams_Portfolio/main/images/patient_movement_viz.gif" width=300> 


