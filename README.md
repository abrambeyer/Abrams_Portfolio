# Welcome to Abram's Portfolio.  

## Personal Programming/Data Science Projects
<br/>

## [Project 1:  Consumers Energy Job Text Analysis](https://github.com/abrambeyer/consumers_energy_job_text_analysis)
- Open the [Consumers Energy Careers Website](https://www.consumersenergy.com/company/careers)
- Use Selenium and BeautifulSoup to open each job listing page, open job listings and scrape the job description text from the page.
- Results pulled as of 10/18/2020.  However, each time you run the script, it will pull what job listings are currently available.
- Final vocabulary of 1792 words from 18 distinct analytics-related jobs 

![](https://github.com/abrambeyer/Abrams_Portfolio/blob/main/images/cms_job_description_word_cloud.png)

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

![](https://github.com/abrambeyer/Abrams_Portfolio/blob/main/images/beyer_orchard_tree_variety_layout1.PNG)

## Research/Publications/Conference Talks
<br/>
## [Conference Presentation:  Vizient Connections Summit 2020](https://github.com/abrambeyer/Research_Publications_Conference_Presentations_Posters/tree/main/vizient_summit_2020)
- Built an automated python pipeline with selenium to configure and run hundreds of Vizient CDB reports, wrangle and organize excel files, extract data from the excel files and store into SQL Server database
- Built custom database schema to store the data and query from it
- Built a series of SQL queries to automatically perform roll-up calculations
- Built a Tableau dashboard and SSRS scorecards to report out numbers to hospital leadership in an aligned fashion 
- Created a timely, system-wide inpatient quality composite in order to promote fair system-wide benchmarking against similar hospital cohorts  

![](https://github.com/abrambeyer/Abrams_Portfolio/blob/main/images/inpatient_quality_composite_pipeline2.PNG)

## Tableau Public Dashboards


