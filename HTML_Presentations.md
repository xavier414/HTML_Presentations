HTML Presentations
========================================================
author: Xavier Bryant
date: March 1 2021
font-import: https://fonts.googleapis.com/css2?family=Akaya+Kanadaka&display=swap
font-family: 'Akaya Kanadaka'
css: custom.css
<!-- font-family: 'Risque' -->





Introduction
========================================================

In this assignment, I will be loading a data set and making basic visualizations from the *Stat2Data* package. I will be working with the *Backpack* data set. I load it here: 


```r
data(Backpack)
```
  

The data set describes: *Weights of College Student Backpack*

It is a data frame with 100 observations on the following 9 variables.

Source: [CRAN: Stat2Data pacakage](cran.r-project.org/web/packages/Stat2Data/Stat2Data.pdf)


Variables
========================================================
type: exclaim


- *BackpackWeight*: Backpack weight (in pounds)
- *BodyWeight*: Body weight (in pounds)
- *Ratio*: BackpackWeight/BodyWeight
- *BackProblems*: 0=no or 1=yes

***

- *Major*: Code for academic major
- *Year*: Year in school
- *Sex*: a factor with levels Female Male
- *Status*: Graduate or undergraduate? G or U
- *Units*: Number of credits taken that quarter



Plot: Body Weight on Backpack Weight
========================================================






<style>
  .p_iframe iframe {
    width:90%;
    height:576px;
}
</style>

<div class="p_iframe">
<iframe frameborder="0" seamless='seamless' scrolling=no src="plotly.html"></iframe>
</div>
