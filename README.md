---
title: "Methods of historical research"
author: "Auke Rijpma"
mainfont: Charter
mathfont: Charter
colorlinks: true
date: \today
fontsize: 12pt
geometry: "top=6pc, left=9.3pc, right=9.3pc, bottom=7.5pc"
classoption: a4paper
output:
    pdf_document:
        latex_engine: xelatex
        highlight: default
        keep_tex: true # keeps tex file
        template: NULL
---


# Module
This is the course manual for the structured data module of the MHR course.

# General introduction

The purpose of this course is to familiarize students of the Research MA programme History with computational techniques to analyse structured data. More and more historians are using large sets of digital data as well as a growing variety of digital techniques to extract information from this data. It is not only timely to become acquainted with a number of widely used techniques and skills, but also to learn how to use them for the study of history in a critical and conscientious way. A last goal of this course is to provide students with sufficient information to form their own opinion of the extent to which digital resources and tools change the heuristics of historical enquiry.

In this course students will work with tools for the analysis of structured historical data within the R programming language. Students are trained in the analytical tools in a hands on setting, in which they work on their own research projects. Students will work in groups of two on a paper that answers a research question. Students will have to reflect in their research projects on the opportunities, but also the risks and pitfalls of digital tools for this type of historical study. More generally, they will evaluate and discuss the strengths and weaknesses of a selection of books, articles, and working papers that employ digital humanities methods with these tools.

# Module teachers
* Auke Rijpma

# Grading
For grading please refer to the overall MHR course manual. The grade for this module is entirely determined by the paper. There are assignments, but these are not part of the graded assignments in the MHR course.

# Schedule
* Tutorials: Tuesdays, 11.00–12.45, KNG 80 114.
* Labs: Thursdays, 15.15-17.00, KNG 80 013.

| week | tutorial            | lab               | hand in                  |
| ---: | :---                | :---              | :---                     |
| 1    | intro               | intro to R        | distribute paper (Mo 15) |
| 2    | visualisations      | visualisations    | distribute paper (Mo 22) |
|      |                     |                   | topic and RQ (Fr 26)     |
| 3    | research design     | working with data | assignment 1 (Fr 3)      |
| 4    | individual feedback | advanced material | assignment 2 (Fr 10)     |
| 5    | presentations       | presentations     | Final paper (Fr 24)      |

## Week 1: Introduction
### Tutorial: the quantitative approach to history.
* For the first tutorial, you're asked to find a paper using quantitative/computational methods that you find interesting either because of its findings or its method. Please read this article and prepare some discussion points for class. Distribute the article itself to the group and teacher no later than 12.00 on the Monday before the tutorial. Using the articles you brought with you, we will use this session to discuss the pros and cons of quantitative research. 
* There are no further required readings besides the article on which you prepare talking points. You only need to skim the other articles to get a feeling what they are about beforehand. The recommended readings are useful for the module overall, but will not be explicitly discussed in the tutorial.
* Recommended readings: 
    * Spiegelhalter, David. 2020. _The Art of Statistics: Learning from Data._ London: Pelican. Chapters 1-6. It's a pageturner as far as statistics books go.
    * [Fogel, "The limits of quantitative methods in history" AHR 1975](https://doi.org/10.2307/1850498).

### Preparations
Make sure to have R installed beforehand. You can just use [the standard R installation](https://www.r-project.org), but many find the [R-studio version](https://www.rstudio.com) pleasant to work with. Either way, try to get it up and running before the first tutorial, so we can address any issues before the first lab session. Once you're up and running, you could take a look at [this R-intro](https://eddelbuettel.github.io/gsir-te/Getting-Started-in-R.pdf).

### Lab session:
* Basics of working with R.

## Week 2: Visualisations.
### Readings
* Healy, _Data Visualization: A Practical Introduction_ (Princeton 2019), chapter 1. [Link to the online version](https://socviz.co). Skim the rest of the book, ignoring the R-code for now. 

### Recommended readings
* Cleveland, William S. 1985. The Elements of Graphing Data. Pacific Grove, Calif.: Wadsworth & Brooks/Cole Advanced Books & Software. This is the book we usually read, but limited library access makes it impractical. Should you be able to access it somehow, it is worth a look.

### Tutorial: visualising data
* In this tutorial we will discuss the principles of making a good visualisation.
* As preparation for the session, find a striking visualisation in a journal article or on the internet and distribute it to the group no later than 12.00 on the Monday before the tutorial. At the tutorial you may be asked to give a short introduction to the visualisation and explain why you think it is good.

### Lab session:
* Data management and visualisations

### Assignment
* Hand in a topic and a preliminary research question by Friday Nov 26th, 17.00.

## Week 3
### Tutorial: research design
* In this tutorial we will discuss quantitative research designs. Some of the literature is somewhat technical, but we will try to distill the core insights in the tutorial.

### Readings:
* Required: [Huntington-Klein, _The Effect: An Introduction to Research Design and Causality_](https://theeffectbook.net), chapters 4–6.
* Required: [Ioannidis, "Why Most Published Research Findings Are False"](http://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124)
* Recommended: [Angrist and Pischke](https://www.aeaweb.org/articles?id=10.1257/jep.24.2.3)
* Recommended: Pearl, Judea, and Dana Mackenzie. 2019. _The Book of Why: The New Science of Cause and Effect._ [London], UK: Penguin Books.
* Recommended: The rest of the Spiegelhalter book.

### Lab session: working with data
* Further data management and visualisations

### Assignment
* Writing R-scripts. A small assignment based on the work of the two lab sessions will have to be handed in via email on Friday, Dec 3th. The main point of this exercise is to provide detailed feedback on a simple script and catch any mistakes that could be hard to see during the lab sessions.

## Week 4
### Tutorial: individual feedback session
The tutorial slot will be used to provide feedback on the progress of the research. Send a progress report and questions by Monday 12.00 to make the most of the time.

### Lab: advanced material
### Assignment
* So far there has been ample attention for working in a reproducible way. For this assignment you will have to hand in all the files necessary to reproduce one of the visualisations of the lab session of week 3. Instructions will be provided in that week.
* Due: Fri. Dec 10th, 17.00.

## Week 5
### Tutorial
* During the tutorial of week 5, each group will present their work in progress. Each group has 20 minutes in total, for both the presentation and the discussion. The presentation should therefore be no longer than 10 minutes.

### Lab session
Walk-in hours for dealing with data or R issues.

### Paper
The paper is a short paper (ca. 3000 words), preferably based on the civil registry dataset we will use during the lab sessions. You will write the paper in groups of two. The paper should contain an introduction to the historical issue, an introduction of the data, at least three figures or tables, a methodological reflection, and (separately) all the files and scripts you used to obtain your results. 

The paper will be graded on the following (roughly in descending order of importance):

* How you use data to answer historical questions.
* The presentation of the results.
* Reproducability.
* Reflection on suitability of data and methodology for the question at hand as well as the comparative strength of both kinds of data for your question.
* Use of literature and formulation of the research question. The research question and the literature it is based on can be somewhat contrived, but they should be present and should not be nonsensical. Moreover, while they're not a huge part of the grade, a poor research question will probably affect the rest of your paper.

The paper should be handed in by Friday, December 24th, 17.00.

# Datasets
It is recommended to write your paper based on Dutch civil registry data. This is a dataset about every birth, marriage, and death in the Netherlands that we have been working on with colleagues in Amsterdam. We will use this dataset during the lab sessions which should give you a good understanding of its structure and possibilities. The data should also allow for a wide range of research questions. Selections of the data will be provided.

You are allowed to use another dataset for your paper, though do note that finding and understanding a dataset can take considerable time. Some examples follow:

* [Historical Database of Dutch Municipalities](https://datasets.iisg.amsterdam/dataverse/HDNG)
* [IPUMS/North Atlantic Population Project](https://international.ipums.org/international/)
* [LINKS](http://www.iisg.nl/hsn/news/links-project.php)
* [iPEHD](https://www.cesifo-group.de/ifoHome/facts/iPEHD-Ifo-Prussian-Economic-History-Database.html)
* [Catasto](http://www.disc.wisc.edu/archive/catasto/index.html)
* [Gould sample on Union soldiers](http://www.nber.org/gould/)
* [Union Army Data](http://uadata.org)
* [Drought atlases](http://www.ldeo.columbia.edu/news-events/new-drought-atlas-maps-2000-years-climate-europe): [Old World](http://kage.ldeo.columbia.edu/TRL/OWDA/) [New World](http://iridl.ldeo.columbia.edu/SOURCES/.LDEO/.TRL/.NADA2004/.pdsi-atlas.html)
[Asia](http://iridl.ldeo.columbia.edu/SOURCES/.LDEO/.TRL/.MADA/), 
* [Project Tycho](http://www.tycho.pitt.edu/about.php)
* [Trans-Atlantic Slave Trade Database](http://slavevoyages.org/voyage/download)
* [Australian convict database](https://data.gov.au/dataset/british-convict-transportation-registers)
* [IMDB](https://www.imdb.com/interfaces/)
* Any other dataset you find interesting, provided (i) it is historical, (ii) it is sufficiently big and somewhat tidy; and (iii) you clear it with the instructor. Some general places to look:
    * [Data is plural](https://docs.google.com/spreadsheets/d/1wZhPLMCHKJvwOkP4juclhjFgqIY8fQFMemwKL2c64vk/edit#gid=0) <3
    * [ICPSR](https://www.icpsr.umich.edu)
    * Journal data depositories like the [JEH one](https://www.openicpsr.org/openicpsr/search/jeh/studies).
    * [DANS EASY](https://easy.dans.knaw.nl/ui/home)