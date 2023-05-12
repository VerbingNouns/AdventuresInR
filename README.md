# Welcome to the Adventures In R Workshop!

*This repository will serve as the base for designing and sharing materials for the 2023 Workshop in R.*

This workshop has been funded by the Faculty of Humanities Arts and Social Sciences, and is open to all postgraduate students at Newcastle University and universities which constitute the NINE-DTP consortium. The aim is to provide a strong foundation in what is fast becoming the standard package for data analysis, manipulation and visualisation. By the end of this course, attendees will have a sufficiently strong foundation to enable them to work on more complex challenges in their own time.

## Information:

**When:** 15 May, 16 May; In-person 10:00-12:00, 14:00-16:00, and asynchronously  
**Session Plan:**

| Session | Time |
| --- | --- |
|Morning lecture and group work|10.00 -- 12.00|
|Break/Individual work|12.00 -- 14.00|
|Afternoon lecture and group work|14.00 -- 16.00|

**Where:** HDB 6.19 (PGR Learning Lab)  
**Instructors:** Nick Riches and Lauren Ackerman 

Before the workshop, please make sure you have downloaded R and RStudio. [**This** brief tutorial](docs/Setting_Up.nb.html) may help. If you cannot get this to work on your own computer, there should be computers available in the room where you can access R either installed on the computer or through [RStudio Cloud (Posit Cloud)](https://posit.cloud/plans/free) for free. **We recommend you make sure you can either access it on your own computer or online before the workshop!**

We also recommend [swirl](https://swirlstats.com/) which is an excellent package for learning R. You load it as a package in R (see the website for detailed instructions), and it creates an interactive tutorial. If you work your way through "swirl" this may give you a headstart in the R training, but it is not a necessary precursor for this workshop. Before the beginning of the workshop, if you have been using swirl, please remember to exit swirl using the bye() function (which it will teach you how to use). This will prevent errors during the taught session and individual work.

## Schedule:

The links and content therein for each day may be changed and updated between now and the day they are taught. Be sure to check back right before the session to ensure you have access to the most up-to-date versions.

### Day 1:

**Morning:** [Introduction to R and RStudio](docs/Session_1-Introduction.nb.html) (Download the [Rmarkdown file](docs/Session_1-Introduction.Rmd) for this session, and the main WHO data files: [.csv format](data/WHR_2017.csv), [SPSS format](data/WHR_2017.sav), [Excel format](data/WHR_2017.xlsx), and the [life expectancy](data/WHO_life_expectancy.csv) data file)  

**Afternoon:** [Intro to tidyverse and data wrangling](docs/Session_2-tidyverse.html) (Download the [.Rmd file](docs/Session_2-tidyverse.Rmd) for this session)  

### Day 2:

**Morning:** [Visualisation and visual interpretation](docs/Session_3-dataviz.html) (Download the [.Rmd file](docs/Session_3-dataviz.Rmd) for this session)  

**Afternoon:** [Intro to Statistical analysis](docs/Session_4-AnalysingData.nb.html) (Download the [.Rmd file](docs/Session_4-AnalysingData.rmd) for this session)  NB 🚧 UNDER CONSTRUCTION 🚧



*We regret that due to the limited capacity of the room we may not be able to offer a place to all those who apply.*

## What to bring: 

The room where we will be meeting has university computers, but we would ask attendees to *have personal computers or laptops with copies of R and RStudio already installed if possible*
(please visit  [https://www.r-project.org/](https://www.r-project.org/) to download R, and [https://www.rstudio.com/](https://www.rstudio.com/) to download RStudio). We believe that it’s preferable to work on laptops rather than university machines as it is much easier to update R to the latest version. However, if you are unable to get R and RStudio to work on a personal computer, you can access it online or use a university computer, as described above.

If you already have R and RStudio installed, we recommend you update to the latest versions. You may need to also update any installed packages to their most recent versions. If you need help with this in advance, please get in contact as soon as possible so we can ensure a smooth and productive workshop on the day!

### Notes:

12 May 2023: Please install the latest version of R (version 4.3.0 Already Tomorrow), a recent version of R Studio (at least from 2023) and the following packages, which we will use during our workshop:  

```
tidyverse
palmerpenguins
knitr
viridis
emmeans
Hmisc
lme4
lmerTest
```

