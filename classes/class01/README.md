# 432 Class 01: 2021-02-02

[Main Website](https://thomaselove.github.io/432/) | [Calendar](https://thomaselove.github.io/432/calendar.html) | [Syllabus](https://thomaselove.github.io/432-2021-syllabus/) | [Course Notes](https://thomaselove.github.io/432-notes/) | [Canvas](https://canvas.case.edu) | [Data and Code](https://github.com/THOMASELOVE/432-data) | [Sources](https://github.com/THOMASELOVE/432-2021/edit/master/references) | [Contact Us](https://thomaselove.github.io/432/contact.html)
:-----------: | :--------------: | :----------: | :---------: | :-------------: | :-----------: | :------------: | :-------------:
for everything | deadlines | expectations | from Dr. Love | zoom info | downloads | read/watch | need help?

## Materials for Today's Class

- Today's Slides are [available in PDF](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class01/432_2021_slides01.pdf), as well as in [R Markdown](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class01/432_2021_slides01.Rmd).
- All 432 classes are video-recorded, and the recordings will be archived in the Zoom section of [Canvas](https://canvas.case.edu).
- **BONUS video** I pre-recorded a 9-minute video walking through (fairly quickly) the development of the Bradley example in R Studio, anticipating that I might not get to it today in class. 
    - You'll find that recording on our Shared Google Drive (log into Google with your CWRU account).
    - The Shared Drive is called *432 Spring 2021 Dr Love and Students*. Inside that Drive, you should see a folder called *432 Spring 2021 Bonus Videos*. 

![](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class01/figures/lowndes_tidy_tw.png)

- Read [the entire illustrated series about tidy data here](https://twitter.com/juliesquid/status/1315710359404113920). 
- `@juliesquid` and `@allison_horst` are great people to follow on Twitter. 

## Logistics and Reminders

1. You should have received an email from me in the last 3-4 days with the subject heading "**PQHS / CRSP / MPHP 432: Start of the Semester - Welcome!**" 
    - If you have this email, please attend to what it asks you to do. 
    - If you don't have this email, please let me know that via email to Thomas dot Love at case dot edu now.
2. If you haven't taken the Welcome to 432 survey already, please [do so today](http://bit.ly/432-2021-welcome-survey).
    - Thanks to the 50 of you who've now completed the survey!
3. [Lab 01](https://github.com/THOMASELOVE/432-2021/tree/master/labs/lab01) is due this coming Monday 2021-02-08 at 9 PM.
    - To do this Lab, you'll need to have [R and RStudio up and running for you](https://thomaselove.github.io/432/software_install.html), and [download the data from our Data site](https://thomaselove.github.io/432/data_index.html).
4. Please read the [Syllabus](https://thomaselove.github.io/432-2021-syllabus/) and familiarize yourself with the [Course Website](https://thomaselove.github.io/432), the Shared Google Drive (which you can see from your Google CWRU account), [Piazza](https://piazza.com/case/spring2021/pqhs432) and [Canvas](https://canvas.case.edu/) before Thursday's class so that if you have any questions or problems getting started, we can settle them quickly.
    - Questions should be posted to Piazza in the general discussion folder, whenever that's appropriate.
    - I encourage you to change the default Piazza settings so that you receive email notifications either every 12 or 24 hours.
    - If you have an individual concern you want to raise with Dr. Love, email him at Thomas dot Love at case dot edu.
5. [TA office hours](https://thomaselove.github.io/432/calendar.html#TA_Office_Hours) begin on Thursday 2021-02-04. 
    - The schedule is found on [the Course Calendar](https://thomaselove.github.io/432/calendar.html#TA_Office_Hours), and in the [Contact Us](https://thomaselove.github.io/432/contact.html) menu on the website.
    - Zoom information for TA office hours can be found in the [Announcements section of Canvas](https://canvas.case.edu/), and is also in our Shared Google Drive.
6. By next Tuesday (2021-02-09), we'll expect you to have read:
    - the readings in [the required books by Nate Silver and Jeff Leek](https://thomaselove.github.io/432/calendar.html#Readings) listed on [2021-02-05 in the Calendar](https://thomaselove.github.io/432/calendar.html#February_2021)
    - the [instructions for Project 1](https://github.com/THOMASELOVE/432-2021/blob/master/project1/README.md), especially as they relate to the first of its two tasks: the [Project Proposal](https://github.com/THOMASELOVE/432-2021/blob/master/project1/01_project1_proposal.md) (which is due at 9 PM on 2021-03-01.)
7. You might want to take a look at the [Glossary of Statistical Terms](https://hbiostat.org/doc/glossary.pdf) (pdf) compiled by Frank Harrell and colleagues. 
    - This week, we will tacitly assume you know, for example, what the following terms mean: binary variable, case-control study, categorical variable, comparative trial, confidence limits, continuous variable, data science, dummy variable, estimate, goodness of fit, inter-quartile range, mean, median, nonparametric estimator, nonparametric tests, normal distribution, null hypothesis, observational study, one-sided test, p-value, parametric test, percentile, predictor, probability, quartiles, random error, random sample, rate, replication, risk, significance level, standard deviation, standard error, two-sided test, Type I error, variance.
    - If any of these terms seem unfamiliar, read up on them. If that's not too overwhelming, then glance through the remainder of the list and find a few more that interest you, and read those closely.
8. There is no [Minute Paper](https://github.com/THOMASELOVE/432-2021/blob/master/minutepapers/README.md) this week. Our first Minute Paper is due next Wednesday 2021-02-10. If you have comments or questions about the class, ask them on Piazza, or in TA office hours (starting Thursday) or before/after class, or in the chat, etc. We want to hear from you!
9. The final word on all deadlines is the [Course Calendar](https://thomaselove.github.io/432/calendar.html). All deliverables for the entire semester are listed.
10. I want to remind you of the University's resources to help you that are listed in [Section 15 of our syllabus](https://thomaselove.github.io/432-2021-syllabus/university-resources-for-student-support.html), especially the newly available [CWRU Care 24/7 Mental Telehealth for Students](https://timely.md/faq/cwrucare/) program

### Materials for the Bradley et al. Table 1 example

Here are the materials I'll refer to in discussing the development of a Table 1 for the Bradley example. [Chapter 1 in the Course Notes](https://thomaselove.github.io/432-notes/building-table-1.html) covers the topic of building a Table 1 far more extensively, with two detailed examples. Those notes should be helpful for doing the Table 1 work required in [Lab 01](https://github.com/THOMASELOVE/432-2021/blob/master/labs/lab01/README.md).

- **BONUS video** I pre-recorded a 9-minute video walking through (fairly quickly) the development of the Bradley example in R Studio, anticipating that I might not get to it today in class. You'll find the recording on our Shared Google Drive (log into Google with your CWRU account).

You'll also find:

- the [`bradley.csv`](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class01/data/bradley.csv) data file is in the data folder above (click **Raw** to download), and is also available on [our 432-data page](https://github.com/THOMASELOVE/432-data) for general downloads.
- [`bradley_table1.Rmd`](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class01/bradley_table1.md) is the R Markdown script. Click **Raw** to download it.
- [`bradley_table1.md`](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class01/bradley_table1.md) shows the results (on github) of running that R Markdown script
- [`bradley_table1_result.csv`](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class01/bradley_table1_result.csv) is the table generated by that R Markdown script. Again, click **Raw** to download it.
- The original source is Steven M. Bradley, Joleen A. Borgerding, G. Blake Wood, et al. [Incidence, Risk Factors, and Outcomes Associated With In-Hospital Acute Myocardial Infarction](https://jamanetwork.com/journals/jamanetworkopen/fullarticle/2720923) *JAMA Netw Open* 2019; 2(1): e187348. doi:10.1001/jamanetworkopen.2018.7348.
- [JAMA Table Creation Instructions](https://jama.jamanetwork.com/data/ifora-forms/jama/tablecreationinst.pdf) (pdf)
- [How I created/simulated the `bradley.csv` data](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class01/bradley_sim.md)

## Today's References (from the Slides, etc.) 

1. Hadley Wickham and Garrett Grolemund [R for Data Science](https://r4ds.had.co.nz/)
2. Karl W. Broman & Kara H. Woo (2018) [Data Organization in Spreadsheets](https://github.com/THOMASELOVE/432-2021/blob/master/references/pdf/Broman_and_Woo_2018_Data_Organization_in_Spreadsheets.pdf), *The American Statistician*, 72:1, 2-10, DOI: [10.1080/00031305.2017.1375989](https://doi.org/10.1080/00031305.2017.1375989)
3. Jeff Leek and colleagues [How to Share Data with a Statistician](https://github.com/jtleek/datasharing)
    - Shannon Ellis and Jeff Leek's pdf "[How to Share data for Collaboration](https://peerj.com/preprints/3139v5.pdf)" touches on many of the same points.
4. Hadley Wickham [Tidy Data](https://www.jstatsoft.org/article/view/v059i10), *J of Statistical Software*.
5. Jenny Bryan's [Speakerdeck presentation on Naming Things](https://speakerdeck.com/jennybc/how-to-name-files).
    - Jenny and colleagues also provide [Good Enough Practices in Scientific Computing](http://bit.ly/good-enuff).
6. XKCD on 
    - [How to Write Dates](https://xkcd.com/1179/)
    - [Naming Files in Hard](https://xkcd.com/1459/)

### What's that course password again?

Some of the materials on the [References and Resources page](https://github.com/THOMASELOVE/432-2021/blob/master/references/README.md) of books, articles, videos and other things are password-protected. Please dip into them as your time allows.

![](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class01/figures/tukey.png)

## Something Inspiring?

In [Celebrating Black History Month](https://magazine.amstat.org/blog/2021/02/01/celebrating-black-history-month/) the American Statistical Association recognizes 10 of the many individuals from the Black/African-American collective who have made tremendous contributions to the field of statistics.

## Questions (with Answers) from the "[Welcome to 432 Survey](http://bit.ly/432-2021-welcome-survey)"

Again, if you haven't taken the survey already, please [do so today](http://bit.ly/432-2021-welcome-survey).

1. How is Dr. Love feeling?
    - I am fine, in the 2021 sense that I am essentially healthy and my family is, as well, and those of us who were employed last February still are. On the other hand, I am anxious most of the time, and certainly not functioning at full capacity. I ask for your patience.
    - With regard to the upcoming semester, I am hopeful that we can deliver an effective course, and that we can connect with each of you in a helpful, supportive way. 
    - I am very grateful for [our teaching assistants](https://thomaselove.github.io/432-2021-syllabus/teaching-assistants.html), who do a lot to keep us all moving forward (especially me). [Please let us know](https://thomaselove.github.io/432/contact.html) if we can help you along the way.
2. Has Dr. Love been vaccinated against COVID-19?
    - Not yet. Nor has my 86 year old mother in New York, nor anyone else in my family. I look forward to those miraculous occurrences.
    - Some of our teaching assistants work for health systems and have been vaccinated, as have many of my colleagues at Metro. I am very grateful that is true.
3. How did Dr. Love spend his holiday season?
    - With my wife and two children, in the house. We watched a fair amount of stuff together, and did a lot of crossword puzzles and spelling bees, and ate, a lot.
    - My older son has now returned to his off-campus apartment in Pittsburgh for his last semester of undergraduate education and his part-time job at the Carnegie Museum.
    - My younger son continues to do his first year of college (Columbia University) at home, which is not what anyone wants, but he's a good roommate.
4. Are there multiple students who did not take 431 this past Fall?
    - Yes, about a half dozen, I think.
5. (from a student who did not take 431 with us in the Fall) Are there any specific parts of 431 that we should review and pay special attention to and that will be integral to succeeding in 432? 
    - I expect the most obviously useful elements will be the discussion of specific R packages and functions related to working with linear models. It would also be helpful to look at the lab assignments and project requirements and tips from 431 since we build on that knowledge in the 432 materials. [The R-basics document](https://github.com/THOMASELOVE/432-2021/tree/master/r-basics) from the 432 R and Data menu is certainly worth some of your time, too.
6. How can I express interest in being a TA next year?
    - After this semester is over, Dr. Love will send out an email to everyone who completed 432 in the past two years (plus all of this year's TAs) to explain the process and what would be required of you. If you're interested, all you need to do is respond to that email and apply. We have both compensated (very lightly compensated) and volunteer positions available, and I typically find a position for all applicants that are interested. I welcome anyone and everyone to help. There's plenty of work to go around.

## One Last Thing

Want to read the most misguided paper of 2020? Darren Dahly's [Twitter thread has you covered](https://twitter.com/statsepi/status/1338501499039739906).

![](https://github.com/THOMASELOVE/432-2021/blob/master/classes/class01/figures/dahly_2020-12-14.png)

- The paper Darren refers to is [Basic statistics: A research primer for low- and middle-income countries](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7718448/).
- Another 2020 paper in the series called [Research skills and the data spreadsheet: A research primer for low- and middle-income countries](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7718460/) is even more, well, I don't know what to say except for heaven's sake, don't take any of its advice. 
    - I'm happy to believe that the intentions here were nothing but good, but this has really gone wrong.
    - Check out the annotated biography in that second paper, for example.


