# 432 Class 03: 2021-02-09

[Main Website](https://thomaselove.github.io/432/) | [Calendar](https://thomaselove.github.io/432/calendar.html) | [Syllabus](https://thomaselove.github.io/432-2021-syllabus/) | [Course Notes](https://thomaselove.github.io/432-notes/) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/432-data) | [Sources](https://github.com/THOMASELOVE/432-2021/edit/master/references) | [Contact Us](https://thomaselove.github.io/432/contact.html)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------: | :-------------:
for everything | deadlines | expectations | from Dr. Love | zoom info | downloads | read/watch | need help?

![](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class03/figures/branch_tw.png)

## Materials for Today's Class

- Today's Slides are [available in PDF](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class03/432_2021_slides03.pdf), as well as in [R Markdown](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class03/432_2021_slides03.Rmd).
- All 432 classes are video-recorded, and the recordings will be archived in the Zoom section of [Canvas](https://canvas.case.edu).

## Reminders

- The [Minute Paper after Class 03](http://bit.ly/432-2021-minute-03) is due Wednesday 2021-02-10 at noon. 
    - It should take about 5 minutes. Remember to log into Google via CWRU to [access the form](http://bit.ly/432-2021-minute-03).
    - Please complete these Minute Papers in a timely fashion even if you haven't yet caught up with us in class.
    - The [complete schedule of Minute Papers](https://github.com/THOMASELOVE/432-2021/blob/master/minutepapers/README.md) is available.
- *Reading*: We expect you to have read the introduction and Chapter 1 of Nate Silver's *The Signal and the Noise* as well as the Data-Sharing and Reading scientific papers sections of Jeff Leek's *How to be a modern scientist* by now. (See Lab 1.)
    - We won't be discussing these pieces each week, but we will catch up with them irregularly through the semester, and in Labs and Quizzes.
- The Answer Sketch for Lab 1 is [now available](https://github.com/THOMASELOVE/432-2021/tree/master/labs/lab01#post-deadline-materials).
- [Lab 2](https://github.com/THOMASELOVE/432-2021/tree/master/labs/lab02) is the next substantial assignment, due at 9 PM on 2021-02-22.
- Were I you, I would take advantage of the relative lull coming up this weekend in 432 work to look closely at the requirements of [Project 1](https://github.com/THOMASELOVE/432-2021/tree/master/project1) and in particular, the [Project 1 Proposal](https://github.com/THOMASELOVE/432-2021/blob/master/project1/01_project1_proposal.md) which is due on 2021-03-01. 
    - It's never too early to get started, and finding an appropriate data set and ingesting it into R is something you probably need to do in the next two weeks in order to get everything finished at the end of the month comfortably.

## Need some suggestions for attractive data for 432 projects?

*Note*: I've added this information to the [Project 1 main page](https://github.com/THOMASELOVE/432-2021/blob/master/project1/README.md), too.

- If you have any doubt at all about whether a data set would work or whether we'll find it to be acceptable, drop in to [TA office hours](https://thomaselove.github.io/432/contact.html) and show it to us, or send us a note about it on [Piazza](https://piazza.com/case/spring2021/pqhs432).
    - Otherwise, you run the risk of us rejecting your proposal because we don't want you to use the data you've chosen.
    - If a TA is unsure about what you're suggesting, they'll put you in touch with Dr. Love for an "OK".

Four especially appealing sources that I'd really like to see people use for Project 1 are:

1. The [Health and Retirement Study](https://hrsdata.isr.umich.edu/data-products/public-survey-data?_ga=2.79574685.849210420.1612760982-241136149.1612760982)
2. The [General Social Survey](https://gssdataexplorer.norc.org/)
3. The many many public use data sets available at [ICSPR](https://www.icpsr.umich.edu/icpsrweb/ICPSR/)
4. The [500 Cities and PLACES data portal](https://chronicdata.cdc.gov/browse?category=500+Cities+%26+Places&sortBy=newest&utf8), most probably I would focus on the [County-level data](https://chronicdata.cdc.gov/500-Cities-Places/PLACES-Local-Data-for-Better-Health-County-Data-20/swc5-untb).

Three other sources students have used successfully in the past and that I’m generally happy to see include:

5. [County Health Rankings](https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation)
6. [National Center on Health Statistics](https://www.cdc.gov/nchs/data_access/ftp_data.htm) including NHANES
    - I encourage those of you who used NHANES data last Fall in 431 to use something else (just so that you can get familiar with some new data), but those of you who really want to may benefit from some [advice from the 431 class about using NHANES data](https://thomaselove.github.io/431-2020-projectB/your2.html) in a different project. Note that your rules are different, but most of the advice still holds well.
7. [Behavioral Risk Factor Surveillance System](https://www.cdc.gov/brfss/data_documentation/index.htm)

#### Data Sets I'd probably avoid:

- Don't type "regression data sets" into Google. That will lead you to data sets we've seen before or to data that have been nicely cleaned up, that's not what we're looking for, at all. 
- We're not going to let you use "textbook"-style examples because we want you to confront real issues with defining and understanding sources of data, types of measurements and with missing and surprising data.
- [Kaggle Public Datasets](https://www.kaggle.com/datasets) are allowed but **only** those with really useful variables, no hierarchical structure and strong descriptions of how the data were gathered (which is probably less than 1% of what's available on Kaggle). 
- The same goes for data from the [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php), and in addition, for several of those data sets, we've either seen them before or they're just too "clean" or there isn't enough information about the variables involved and how they were collected. 
- Data on COVID-19 is permitted for 432 projects, but most of the available data is longitudinal and thus unsuitable for Project 1. 
- The data sets posted by the Cleveland Clinic for educational purposes are really nice, but also a poor choice because we've seen them before, many times, and because they're generally pretty well cleaned up. Other sources of data for "educational purposes" usually have similar problems.
    
## from [rstudio::global(2021)](https://rstudio.com/resources/rstudioglobal-2021) 

Today, I'll share Ahmadou Dicko's inspiring 19-minute talk [Humanitarian Data Science with R](https://rstudio.com/resources/rstudioglobal-2021/humanitarian-data-science-with-r/). 

- Ahmadou Dicko is a statistics and data analysis officer at the United Nations High Commissioner for Refugees (UNHCR) where he uses statistics and data science to help safeguard the rights and well-being of refugees in West and Central Africa. 

## Tips for Graduate Students

![](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class03/figures/mchorse_2020-12-26.png)

- See [Dr. McHorse's suggestions here](https://twitter.com/fossilosophy/status/1342871356254334977).

## One Last Thing

Ted Laderas runs a nice [newsletter of Ready for R materials](https://tinyletter.com/ready4r), with lots of practical tips that might interest you. You can see the archive and sign up (free with an email) at https://tinyletter.com/ready4r.

