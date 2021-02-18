---
layout: page
title: Workshop
order: 3
---

## Setup

This workshop has been designed in R in a [R Markdown](http://rmarkdown.rstudio.com) Notebook using [RStudio](https://rstudio.com/). The markdown language allows you to easily format text, include code snippets and display images. When you execute code within the notebook, the results appear beneath the code, which includes any charts or tables created. Finally, notebooks produce a HTML document that can be viewed in any browser. You can download the R Markdown for each section of this workshop using the links below. You may wish to record your work or produce your coursework in an R Markdown Notebook. There is a very handy [R Markdown cheatsheet](https://rstudio.com/wp-content/uploads/2015/02/rmarkdown-cheatsheet.pdf) available from RStudio.

### Using the Virtual Machine

Once you have logged onto your instance, begin the workshop by starting R. On the command line enter

```
R
```

When you press enter you will see the R prompt that should look something like:

![R Prompt](/images/R_prompt.png)

You are now ready to start the workshops using the links below.

### Using your own machine

It is recommended that you use the Virtual Machine for this workshop, but if you have decided to use your own machine please ensure you have downloaded the workshop data, setup the correct directory structure and installed R, Rstudio and  the necessary packages. Steps to complete these tasks are described on the [OpenStack  page](https://uoe-bio3092.github.io/rna-seq/01_prerequisites.html). Once all these steps are complete see the workshop aims and materials below.

## Aims

During the course of this workshop you will:

* Align raw sequencing reads to a reference genome
* Count reads that align to known genes
* Quantify expression and identify differentially expressed genes
* Perform functional pathway analysis using the Gene Ontology

## Workshop materials

1. [Align and quantify expression](docs/align_count.nb.html)
 * [download markdown](docs/align_count.Rmd)
2. [Identify differentially expressed genes - part 1](docs/diff_exp.nb.html)
 * [download markdown](docs/diff_exp.Rmd)
3. [Identify differentially expressed genes - part 2](docs/diff_exp_anova.nb.html)
 * [download markdown](docs/diff_exp_anova.Rmd)
4. [Perform Gene Ontology enrichment analysis](docs/go_analysis.nb.html)
 * [download markdown](docs/go_analysis.Rmd)

## Finishing the workshop

Once you have worked through all the materials and saved your work you are ready to shut down your virtual machine instance. Log into OpenStack, as described on the [prerequisites page](https://uoe-bio3092.github.io/rna-seq/01_prerequisites.html), and find your instance in the instances tab (left hand side). Use the drop down menu for your instance (right hand side) and select 'shut down instance'. Your instance will remain in the instances tab and you will be able to use the drop down menu  to restart the instance at a later date to complete the other sections of the workshop and to complete the coursework.
