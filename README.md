# Methods of historical research

## General introduction

The purpose of this course is to familiarize students of the Research MA programme History with computational techniques to analyse structured and unstructured data. More and more historians are using large sets of digital data--both numerical as textual--as well as a growing variety of digital techniques to extract information from this data. Scholars are discussing the disruptive nature of these increasingly common practices for historical scholarship under the header of Digital Humanities and Digital History. It is not only timely to become acquainted with a number of widely used techniques and skills, but also to learn how to use them for the study of history in a critical and conscientious way. A last goal of this course is to provide students with sufficient information to form their own opinion of the extent to which digital resources and tools change the heuristics of historical enquiry.

In this course students will work with tools for the analysis of unstructured (textual) and structured (numerical) historical data within the R environment . Students are trained in the analytical tools in a ‘hands on’ setting, in which they work on their own research projects. Students will work in groups on a paper that answers a research question using both types of data. Students will have to reflect in their research projects on the opportunities, but also the risks and pitfalls of digital tools for this type of historical study. More generally, they will evaluate and discuss the strengths and weaknesses of a selection of books, articles, and working papers that employ digital humanities methods with these tools.

## Teachers
Pim Huijnen
Milan van Lange
Auke Rijpma

## Grading
The grade will consist of two parts:

1. Participation and assignments (20%).
2. Research paper (80%).

To pass the course you must get at least a 5 for the paper. Points will be subtracted from the grade if you are late handing in the paper. If the final grade of the course is between a 4 and a 5.5, you may repair the paper. 

## Schedule

### Week 1: 
No classes due to opening academic year.


### Week 2: structured data

#### Preparations
Make sure to have R installed beforehand. You can use [the standard R installation](https://www.r-project.org), but many find the [R-studio version](https://www.rstudio.com) pleasant to work with. Either way, try to get it up and running before the first tutorial (Mon. 11), so we can address any issues before the first lab session (Tue. 12). Once you're up and running, you could take a look at the first videos of [Google's R-intro for beginners](http://www.youtube.com/playlist?list=PLOU2XLYxmsIK9qQfztXeybpHvru-TrqAP)

#### Tutorial: the quantitative approach to history.
* For the first tutorial, every student is to find an interesting paper using quantitative/computational methods (interesting because of its topic and findings, not necessarily because of the methodology). Please read this article and prepare some discussion points for class. Distribute the article itself to the group no later than 17.00 on the Sunday before the tutorial.
* Using the articles you brought with you, we will use this session to discuss about the pros and cons of quantitative research. 
* There are no further readings besides the article on which you prepare talking points. You only need to skim the other articles to get a feeling what they are about beforehand. Next week however, there are substantial readings, so it is good to use the time to begin reading Cleveland.

#### Lab session:
* Basics of working with data in R.

### Week 3: visualising data

#### Readings
* Cleveland, _The elements of graphing data_ (Monterey 1985), pp. 3-227. Book available on course reserve shelf soon: please do not reserve it.

#### Tutorial: visualising data
* In this tutorial we will discuss the principles of making a good visualisation.
* As preparation for the session, find a striking visualisation in a journal article or on the internet and distribute it to the group no later than 17.00 on the Sunday before the tutorial. At the tutorial you will be asked to give a short introduction to the visualisation and explain why you think it is good.

#### Lab session:
* Basic data management and visualisations

In preparations of the following weeks, the students are asked to choose a corpus based on the [Dutch National Library's historical newspaper corpus](http://www.delpher.nl/kranten). This corpus can be based on a query and selection of metadata (in terms of time period, geographical scope, document type, newspaper title, etc.) of the students' own choosing. To query this particular corpus in an effective and critical way, see [Ewoud Sanders]. Prerequisites for this corpus are
* that it has a logical relation with the numerical data the students have been working with
* that it consists of no less than four and no more than ten years
* that it contains no more than 10,000 documents
The students are asked to email the query and metadata selection that represents their corpus to p.huijnen@uu.nl. 

### Week 4: unstructured data 1 - preprocessing & frequency analysis

#### Readings
* [Joris van Eijnatten, Toine Pieters and Jaap Verheul, ‘Big data for global history: The transformative promise of digital humanities’, _BMGN-LHCR_ 128 (2013) 55-77.](https://www.bmgn-lchr.nl/articles/abstract/10.18352/bmgn-lchr.9350/)
* [Dan Jurafsky, Victor Chahuneau, Bryan R. Routledge, and Noah A. Smith, 'Linguistic Markers of Status in Food Culture: Bourdieu's Distinction in a Menu Corpus', _Journal of Cultural Analytics_ Oktober 18 (2016)](http://culturalanalytics.org/2016/10/linguistic-markers-of-status-in-food-culture-bourdieus-distinction-in-a-menu-corpus/)
* David M. Blei and Padhraic Smyth, 'Science and data science', _PNAS_ 114 (2017) 8689-8692.

#### Tutorial
* In this tutorial the students will be familiarized with the relation between 'conventional' and digital historical scholarship (or between 'close reading' and 'distant reading'), and with the opportunities of frequency analyses ('counting words') for the study of history.

#### Lab session
* preprocessing of the newspaper corpus
* frequency analysis in R

### Week 5: unstructured data 2 - KWIC & ngrams

#### Readings
* Jean-Baptiste Michel et al. 'Quantitative Analysis of Culture Using Millions of Digitized Books', _Science_ 331 (2011), pp. 176 -182
* Franco Moretti, Dominique Pestre, ‘Bankspeak. The language of World Bank Reports’, _New Left Review_ 92 (2015) 75-99.

#### Tutorial
* In this tutorial, we will discuss literature that may further illustrate the pros and cons of distant reading for the study of history. The students will be introduced in n-grams and n-gram viewers.

#### Lab session
* n-gram analysis in R
* KWIC analysis in R

### Week 6: unstructured data 3 - relational analysis

#### Readings
* P. Baker, C. Gabrielatos, and T. McEnery, 'Sketching Muslims: A Corpus Driven Analysis of Representations Around the Word "Muslim" in the British Press, 1998-2009', _Applied Linguistics_ 34 (2013) 255-278.
* Michael Pearce, ‘Investigating the collocational behaviour of man and woman in the BNC using Sketch Engine’, _Corpora_ 3 (2008) 1-29.
* Alon Halevy, Peter Norvig, and Fernando Pereira, 'The unreasonable effectiveness of data', _IEEE Intelligent Systems_ 24.2 (2009) 8-12.

#### Tutorial
* In this tutorial, we will discuss literature that is based on relational computational techniques. The students will be introduced in co-ocurrence and tf-idf, as well as in computational techniques that are based on linguistic modeling.

#### Lab session
* co-ocurrence analysis in R
* tf-idf analysis in R

### Week 7

#### Tutorial: evaluating research
In this tutorial we will discuss how to assess the credibility of research using quantitative methods. Some of the literature is somewhat technical, but we will try to distill the core insights in the tutorial.

#### Readings:
* [Angrist and Pischke](https://www.aeaweb.org/articles?id=10.1257/jep.24.2.3)
* [Ioannidis](http://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.0020124)

#### Lab session
* Further data management and visualisations

#### Assignment
* So far there has been ample attention for working in a reproducible way. For this assignment you will have to hand in all the files necessary to reproduce one of the visualisations in the previous lab session on structured data (week 3). Instructions will be provided in that week.
* Due: Fri. October 13, 17.00.

### Week 8 - students' presentations

#### Tutorial
* Guest lecture by Milan van Lange 

#### Lab session
* During the lab session slot of week 8, each group will presesent their work in progress. Each group has 20 minutes in total, for both the presentation and the discussion. The presentation should therefore be no longer than 10 minutes.

### Week 9

#### Deadline paper
The paper is a short paper (3000 words) based on both the unstructured dataset (newspaper corpus) and a large historical structured dataset (LINKS, to be discussed during the tutorials). You will write the paper in groups of two. The paper has to contain an introduction to the historical issue, an introduction of the data, at least three figures or tables (at least one for each type of data), a methodological reflection, and all the files and scripts you used to obtain your results. 

The paper will be graded on the following (roughly in descending order of importance):

* How you use data to answer historical questions.
* The presentation of the results.
* Reproducability.
* Reflection on suitability of data and methodology for the question at hand as well as the comparative strength of both kinds of data for your question.
* Use of literature and formulation of the research question.

Note that the classic elements of a historical paper are last in the list. The research question and the literature it is based on can be somewhat contrived, but they should be present and should not be nonsensical. 

The paper should be handed in no later than Friday, November 3rd, 17.00.
