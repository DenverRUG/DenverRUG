Denver R User Group <img src='images/drug-hexsticker.png' width="250px" align = "right"/>
================================================================================

https://www.meetup.com/DenverRUG/

Our meetup is designed to bring together all of the R users along the Front
Range of Colorado. We welcome R newbies as well as the experience hacker. All
backgrounds are encouraged to join the group -- life sciences, social sciences,
etc.

## Upcoming Meetups
Please refer to the [meetup page](https://www.meetup.com/DenverRUG) for upcoming meetups.

## Past Meetups

|      | Date         | Topic                                                                                          |
| :--- | :----------- | :--------------------------------------------------------------------------------------------- |
| 2019 | November  19 | [Reactivity in Shiny Aps](#2019-november-19)                                                   |
|      | October   22 | [Two talks: 1. regexp; 2. larger than memory data packages](#2019-october-22)                  |
|      | September 24 | [Propensity Score Methods](#2019-september-24)                                                 |
|      | August     6 | [Quantified Self: R tools for the analysis of personal data to improve health](#2019-august-6) |
|      | June      25 | [Sparklyr: Connecting R and Apache Spark](#2019-june-25)                                       |
|      | April     23 | [knitr::spin -- A more dynamic approach to dynamic documents](#2019-april-23)                  |
| 2018 | November  13 | [Two Talks: 1. Natural Language Processing (NLP); 2. Spark and Sparklyr](#2018-november-13)    |
|      | October    9 | [Two Talks: 1. R + TensorFlow: GPU-Accelerated Computing; 2. data.table](#2018-october-9)      |
|      | September 11 | [Two Talks: 1. Causal Inference; 2.  ggogleVis](#2018-september-11)                            |
|      | February  13 | [R packages development](#2018-february-13)                                                    |
|      | January   10 | [R Basics](#2018-january-10)                                                                   |
| 2017 | December  13 | [Topic TBA](#2017-december-13)                                                                 |
|      | November   8 | [Two Talks: 1. Webscraping in R; 2. Accessing databases](#2017-november-8)                     |
|      | October   11 | [Lightning Talks](#2017-october-11)                                                            |
|      | August    10 | [kerasR: building neural networks (deep and otherwise) in R using keras)](#2017-august-10)     |

### 2019 November 19

**Reactivity in Shiny Aps**

Kyle Bartsch, @kbartsch, presented on the various ways to configure and debug
reactivity in Shiny apps, from simple user input to dynamic user interaction
with data tables and plots.

* [Slides and Examples](https://github.com/DenverRUG/2019-11-19-DRUG-Shiny-Demos)
* [Meetup Event](https://www.meetup.com/DenverRUG/events/265318284/)

### 2019 October 22

**Two Talks**

1. Matt Pocernich, @mjpdenver, presented on regular expressions, grep, and
   sub in R.

2. Peter DeWitt, @dewittpe, presented on building and using R data packages
   for data sets which are larger than memory. Applications for this type of
   work can include large static data sets and/or collaboration when a central
   data base is not an option.

   * [Slides and Examples](https://github.com/DenverRUG/2019-10-22-R-data-pkgs)

* [Meetup Event](https://www.meetup.com/DenverRUG/events/265318268/)

### 2019 September 24

**Propensity Score Methods**

Office Hours (minutes). Want to pose a question to the group that can be
addressed in a few minutes? Please do.

Propensity Score Methods using R. (Matt Pocernich at Oracle Data Cloud)

With a brief overview of the concepts behind propensity scores methods, this
talk will look at several R packages, such as hdPS, twang and Zelig, focusing on
twang (Toolkit for weighting and analysis of non-equivalent groups ) . This talk
was inspired by the Advanced Topics in Propensity Score Methods workshop by Wei
Pan, Duke University; Haiyan Bai, University of Central Florida taught at this
year’s JSM.

magrittr : A basic introduction to the piping operators provided by the
magrittr. (Also by Matt Pocernich - unless someone else would like to speak on
this topic. )

### 2019 August 6

**Quantified Self: R tools for the analysis of personal data to improve health**

https://www.meetup.com/DenverRUG/events/263490698/

JP Snow will be presenting.

*Abstract*

"Quantified Self" involves tracking personal data to improve fitness,
health and personal performance. The data and analytic packages available
in R make personal quantification even more valuable. Participants in this
session will learn how to create a personal dashboard and see how how
machine learning can be used to determine optimal sleep factors, all via R.
Other concepts to be covered will include:
- Flexdashboard package for dashboard development
- ggplot techniques, including ggplotly for more interactivity
- Accessing personal data directly from R into Fitbit’s web API
- Using scatter charts, box plots and decision tree methods for analysis

JP Snow has been involved in analytics roles in financial services
throughout his twenty-year career. He currently leads Institutional
Analytics & Client Loyalty at Charles Schwab. A few years ago he started
tracking fitness metrics and realized R had substantial advantages over
Excel. He also leads the Denver Quantified Self Meet-Up group.

* [Meetup Event](https://www.meetup.com/DenverRUG/events/263490698/)

### 2019 June 25

**Sparklyr: Connecting R and Apache Spark**

Ben Hoffman will be presenting an introduction to Sparklyr, an R package to
working with Apache Spark. Do you have data that is too big to fit into memory?
Spark will let you work in memory or on disk, cache tables in memory, and use
machine learning libraries on data that is too big to fit into memory!

* [Slides and Examples](https://github.com/DenverRUG/2019-06-25-Sparklyr)
* [Meetup Event](https://www.meetup.com/DenverRUG/events/262309100/)

### 2019 April 23

**knitr::spin -- A more dynamic approach to dynamic documents**

Building dynamic documents via literate programming is a critical part of
responsible and reproducible science. Built on a literature programming
framework, authoring .Rmd, .Rnw, .Rhtml, or other files, uses a markup language
(markdown, LaTeX, html, ...) as the primary language for the file and the
analysis/programming language (R, C++, SAS, ...) is a guest language. This
paradigm has been extremely useful and durable since its formal introduction in
the book "Literate Programming" Donald Knuth in 1984. R users should be at least
aware of Sweave and knitr::knit, two R focused literate programming tools.

However, the common method of literate programming is, from the perspective of
an analysis, backwards. As an analysis my primary language is the analysis
language and the human readable report is nothing more than detailed code
comments about the analysis script(s). knitr::spin is the tool needed to use
literate programming paradigms where the analysis language is the primary
language for the file(s) and the markup language is the guest language.

This talk will cover the following:

1. Introduction to knitr::spin -- concept and syntax
2. Simple reports -- that is analysis.R --> analysis.(docx|html|pdf)
3. Non-trivial reports -- child documents and conditional code evaluation

* [Slides and Examples](https://github.com/DenverRUG/2019-04-23-spin)
* [Meetup Event](https://www.meetup.com/DenverRUG/events/260632409/)

### 2018 November 13

**Natural Language Processing (NLP) / Spark and Sparklyr**

1. You down with NLP? (yeah you know me)<br>Richard Vlasimsky with IMIDEX will
   demonstrate some basic natural language processing concepts and techniques in
   R using data from the Open Lyrics database on Github.

2. Spark and sparklyr<br> Sean Lopp from Rstudio will go through how to get
   started with Spark and sparklyr. We'll also discuss what Spark is and where
   its used, and demo examples of data wrangling, machine learning, and spark
   streaming.

* [Meetup Event](https://www.meetup.com/DenverRUG/events/255628505/)

### 2018 October 9
Two talks:

**R + TensorFlow: GPU-Accelerated Computing in the Age of Deep Learning**
by Matt Hergott

Today’s complex neural networks and large data sets make it difficult or
impossible to solve problems with traditional computational methods. This talk
will focus on how we can use R with TensorFlow and graphics processing units
(GPUs) to achieve our goals in a dramatically accelerated fashion.

Topics covered include: What is GPU computing? Why do we use libraries like
TensorFlow? What is the relationship between TensorFlow and Keras? What does an
R + TensorFlow program look like?

Matt Hergott focuses on traditional econometric analysis, deep learning
architectures, and complex quantitative visualizations through his firm MiaBella
AI. His GPU programming experience includes the emerging field of 3D holograms,
and a statistical visualization package he wrote made Microsoft’s top-16 list of
“noteworthy HoloLens content.”

**data.table package**

by David Heisler

This talk provides an overview of the data.table package including a brief
history of data.table, basic and some advance syntax and a comparison with
dplyr.

* [Meetup Event](https://www.meetup.com/DenverRUG/events/255157224/)

### 2018 September 11
Two talks:

**CausalImpact Package**
Karen Kazor - Oracle Data Cloud

CausalImpact is a package contributed by the folks at Google to estimate the
effect of a treatment or intervention on a individuals observed over time. In
online advertising a common example is estimating additional clicks or other
actions attributed to a campaign. Karen will discuss some of the ins and outs of
this package.

**Hans Rosling - Truthfulness and googleVis**
Matt Pocernich - Oracle Data Cloud

Inspired by Hans Rosling's book - Factfulness, I will re-visit the googleVis
package which was inspired by the very cool animated plots used in his 2006 Ted
Talk. This talk will illustrate some the topics from recent book using goolevis
and ggplot.

Question for discussion: When and why do you use R Notebooks in lieu of
traditional Markdown documents?

* [Meetup Event](https://www.meetup.com/DenverRUG/events/253570063/)

### 2018 February 13

**R package development**

Peter DeWitt will be presenting. The focus will be on reproducible reporting,
documenting, and collaboration. The presentation will first show that relying on
a script is insufficient for sharing code and having reproducible results. The
movement from `important-analysis.R` script to an R package will be shown.

Expanding on the R package structure, Peter will provide examples of when
version control and continuous integration tools not only provide for higher
quality documentation and work, but can be essential for keeping each developer
on a team accountable.

We will cover SVN and Git log and blame. Using the testthat package, and using
CI.

* [Slides and Examples](https://github.com/DenverRUG/2018-02-13-pkgstr-and-ci)
* [Meetup Event](https://www.meetup.com/DenverRUG/events/246924064/)

### 2018 January 10

Three talks on R Basics

These talks provide a brief overview of topics needed to you going using R. Each
talk will be about 20 minutes. While the talks are aimed users new to R -
everyone is welcome and there are always new tricks to learn. Talks will begin
at 7:30.

1. **Loading and writing Data** - Steve Sullivan
   - save, load
   - read.table, write.table
   - read.csv, write.csv
   - readLines
   - readline
   - Only mention: readChar, writeChar, readBin, writeBin
   - scan
   - cat==write, paste, sprintf
   - plots: ggsave, png, pdf
   - Briefly mention packages: jsonlite, yaml, RSQLite, RMySQL, RPostgreSQL
   - Resources ...

2. **dplyr** - Andy Pickering
   - piping
   - The 5 main verbs of dplyr and examples usingdata frames
   - What the equivalent functions would be in SQL and/or base R
   - Introduction to the pipe and chaining operations.
   - Group-by operations and pipe examples.

3. **ggplot2** - Leila Afzali - Data Scientist
   - What is ggplot2 and components of a ggplot2 plot
   - Briefly discussing installing and loading the package
   - Go over example(s) showing the usage of ggplot2 for EDA, model diagnostics
     and result of analysis

* [Meetup Event](https://www.meetup.com/DenverRUG/events/243291958/)

### 2017 December 13
Topic TBA -- Meetup didn't happen.

### 2017 November 8

Two Talks:

**Webscraping**

Ryan Elmore will introduce an newish R package (ballr, pronounced baller) for
scraping data from basketball-reference.com (http://basketball-reference.com/).
He will highlight the use of the rvest package, along with the selectorgadget
tool. He would love it if others are interested in contributing to this project!

* [ballr on cran](https://cran.r-project.org/package=ballr)
* [ballr on github](https://github.com/rtelmore/ballr)

**Databases in R**

Matt Pocernich will discuss accessing databases in R. This introductory talk
will focus on accessing data using a functions found in RODBC, touch a little on
dplyr, but then show how dbplyr extends dplyr to access databases.

* [Meetup Event](https://www.meetup.com/DenverRUG/events/243291900/)

### 2017 October 11

1. Danny Inman - NREL
   - Using R for selecting efficient production frontiers for local sensitivity
     analysis.

1. Sean Lopps - Rstudio
   - Group Choice (pick one) 1. RStudio 1.1 Updates (List Viewer, Databases,
     Terminals) 2. Turning R code into RESTful APIs 3. Intro to testthat

1. Andy Pickering
   - Have you every found yourself saying "It seems hotter/colder than normal
     lately"? I do all the time (maybe I just really like weather). Now you can
     check the data yourself with the WeatherComparer Shiny App. I'll show the
     app and talk a little about some issues I encountered when making it.

1. Laura Kinney Metro State
   - discusses analyzing survey results using the tidytext package and built a
     shiny app evaluating Likert scale questions to measure the effectiveness of
     the Colorado Youth at Risk program.

1. Peter DeWitt - Neptune
   - A quick talk about Non Standard Evaluation with dplyr and how to move away
     from the (depreciated) select_, mutate_, filter_, .... functions.
   - [Slides and Examples](https://github.com/DenverRUG/2017-10-11-non-standard-eval)

1. Ed Wolfrum - NREL
   - Ed has been using RMarkdown to simplify reporting of data in standard
     formats from multiple Excel files which contain different types of
     analytical chemistry data that must be combined and summarized before being
     reported out. In this lightning talk, Ed will talk about what he has
     learned about using RMarkdown, and also ask for advice in improving the
     current workflow.

1. Taylor Larsen is a Data Science Engineer at Health Catalyst and is part of the team responsible for healthcareai
   - healthcareai is an open source machine learning package developed with
     healthcare use cases in mind. We'll do a quick overview of healthcareai's
     current features, implemented use cases, and the community behind the
     package.

* [Meetup Event](https://www.meetup.com/DenverRUG/events/243291874/)

### 2017 August 10

**kerasR: building neural networks (deep and otherwise) in R using keras**

Barton Rhodes will be presenting.

A simple walk-through of creating a convolutional neural network to recognize
handwritten digits. Examples based on the MNIST and/or notMNIST data sets.

Everyone is welcome to come around 7:00pm and socialize. Barton's talk will
start around 7:30pm. After the talk we may walk over to Cap City Tavern for food
and drinks.

* [Slides and Examples](https://github.com/DenverRUG/2017-08-10-keras/tree/master/2017-08-10-keras)
* [Video of the talk](https://vimeo.com/229361206)
* [Meetup Event](https://www.meetup.com/DenverRUG/events/241913353/)

