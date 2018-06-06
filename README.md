# Welcome to the Adventures In R Workshop!

*This repository will serve as the base for designing and sharing materials for the 2018 Workshop in R.*

This workshop has been funded by the Faculty of Humanities Arts and Social Sciences, and is open to all postgraduate students at Newcastle University and universities which constitute the NINE-DTP consortium. The aim is to provide a strong foundation in what is fast becoming the standard package for data analysis, manipulation and visualisation. By the end of this course, attendees will have a sufficiently strong foundation to enable them to work on more complex challenges in their own time.

## Information:

**When:** 7-8 June; 09.00 -- 17.00  
**Where:** ARMB.G.17  
**Instructors:** Lauren Ackerman, Jalal Al-Tamimi, Danielle Turton, and Nick Riches  

Before the workshop, please make sure you have downloaded R and RStudio. [**This** brief tutorial](docs/Setting_Up.nb.html) may help.

## Schedule:

We anticipate that basic refreshments, including lunch, will be provided.

### Day 1:

**Morning:** [Introduction to R and RStudio](/docs/Session 1 - Introduction.nb.html) (Download the [Rmarkdown file](/docs/Session 1 - Introduction.Rmd) for this session)

**Afternoon:** Visualisation and data manipulation  

### Day 2:

**Morning:** [Processing text and corpus data](docs/Session_3.nb.html) (Download [the .Rmd file](docs/Session_3.Rmd) and [the data file](data/Shakespeare_data.csv) for this session)  
**Afternoon:** [Techniques for analysing data](docs/Session_4-AnalysingData.nb.html) (Download [the .Rmd file](docs/Session_4-AnalysingData.rmd) and the data files [grammatical](docs/grammatical.csv) and [rating](docs/rating.csv) for this session


*We regret that due to the limited capacity of the room we may not be able to offer a place to all those who apply.*

## What to bring:

The room does not contain any PCs and we would ask attendees to *bring laptops with copies of R and RStudio already installed*
(please visit  https://www.r-project.org/ to download R, and https://www.rstudio.com/ to download RStudio). We believe that it’s preferable to work on laptops rather than university machines as it is much easier to update R to the latest version.

If you already have R and RStudio installed, we recommend you update to the latest versions. The recent updates in R version 3.5.0 are substantial and will require the re-installation of any packages you have previously installed. Instructions and help for doing so can be found here: https://www.r-statistics.com/2018/04/r-3-5-0-is-released-major-release-with-many-new-features/

### Notes:

05 June 2018: The newest version of RStudio is 1.1.453. This fixes the bug described below for data frames and tibbles but not for certain other output.

25 May 2018: One aspect of the bug mentioned below for R version 3.5.0 interacting with RStudio version 1.1.447 can easily be fixed by piping data table displays to `group_by()`.

16 May 2018: R version 3.5.0 has a known bug in its interface with RStudio version 1.1.447. This bug only seems to effect a small number of aspects of compiling R Notebooks (a tool that will be used throughout the workshop). We do not anticipate this becoming an issue during the workshop and will keep this page updated with any announcements regarding this bug. (It is currently being addressed by the RStudio development team as a high priority.)

## Feedback

Please leave anonymous feedback for us at the end of the course using our [feedback form](https://forms.ncl.ac.uk/view.php?id=2216008)
