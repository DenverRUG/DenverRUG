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

| Date              | Topic                                                                                          |
| :---------------  | :-----------------------------------                                                           |
| 2019 November  19 | [Reactivity in Shiny Aps](#2019-november-19)                                                   |
| 2019 October   22 | [Two talks: 1. regexp; 2. larger than memory data packages](#2019-october-22)                  |
| 2019 September 24 | [Propensity Score Methods](#2019-september-24)                                                 |
| 2019 August     6 | [Quantified Self: R tools for the analysis of personal data to improve health](#2019-august-6) |
| 2019 June      25 | [Sparklyr: Connecting R and Apache Spark](#2019-june-25)                                       |
| 2019 April     23 | [knitr::spin -- A more dynamic approach to dynamic documents](#2019-april-23)                  |

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
