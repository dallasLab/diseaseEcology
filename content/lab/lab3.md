---
title: "Lab 3: Host Range and Parasite Specificity"
author: "Grant Foster"
date: "2024-01-08"
output: html_document
---



## Student Learning Outcomes

At the end of this lab, a successful learner should be able to…

1. Perform the necessary steps to begin analyzing data in the R language (open a development environment, Create a new analysis file, load in analysis packages, load data into the environment). 

2. Create basic linear models in R and interpret their outputs.

3. Create scatter plots and histograms in R and add lines of best fit

4. Describe different ways we can describe levels of parasite host range and explain what types of information these different metrics capture (Number of Hosts, phylogenetic host range, tissue specialization, geographic range, etc). 

5. Describe potential evolutionary tradeoffs between generalist and specialist parasites and evaluate empirical evidence for these tradeoffs. 

6. Define the terms “intensity” and “prevalence” of infections in host populations

7. Summarize takeaways from primary literature supporting and opposing the results of your analysis


## Pre-Lab Materials
Make sure to look over the lab presentation and worksheet before coming to lab!


We'll be using R for data analysis for this, and some future labs. The lab computers already have both R and Rstudio downloaded for you to use, but I'd also recommend downloading them to your personal computer so you can work on things outside of the lab. [Instructions for how to install both of those are located here](https://www.earthdatascience.org/courses/earth-analytics/document-your-science/setup-r-rstudio/). Upon successful installation, you should be able to open Rstudio from wherever apps normally live on your computer (applications for mac, start menu for windows, etc).


That same site also provides a useful [introduction to the RStudio IDE](https://www.earthdatascience.org/courses/earth-analytics/document-your-science/intro-to-r-and-rstudio/) (We'll talk about what makes Rstudio different from R in class)


Finally, during class we'll be using a few common packages to help us in our analyses. You're able to download the required packages using the `install.packages("PackageName")` command in R. I've also created a small file that lists all the packages we'll be using for this lab and install them; feel free to download that here and run it to install those. (Note: This only needs to be done once on each computer; once we've **installed** a package once, we can use the `library("PackageName") command to load the package without reinstalling.)

## Presentation
[Lab 1 Presentation Stand-in](/lab/lab3_hostRange/Lab1Notes.pdf)

## Worksheet
[Lab 1 Worksheet Stand-in](/lab/lab3_hostRange/531L_Lab1Notes.docx)

## Resources
[Global Mammal Parasite Database](https://parasites.nunn-lab.org/)

[GMPD Data Paper](https://doi.org/10.1002/ecy.1799) 

[Folks are using this data for lots of cool things!](https://scholar.google.com/scholar?cites=14643424445719922754&as_sdt=5,41&sciodt=0,41&hl=en) 
