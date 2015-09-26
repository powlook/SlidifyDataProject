---
title       : Data Products Project
subtitle    : Singapore Election Results 2015
author      : PL Yap  
job         : Data Projects
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Results of Singapore General Elections 2015  

1. The Singapore General Election was held on 11 Sept 2015. General elections are held once every 4 - 5 years according to the Westminster System.  
2. The following graphs below shows the performance of the ruling party (PAP) vs the results of the Opposition parties (Opp). There is a plot of PAP performance in 2011 (GE2011) and also a plot of the predicted results by book makers(Predicted) for the 2015 elections.  
<img src="assets/fig/Election Results-1.png" title="plot of chunk Election Results" alt="plot of chunk Election Results" style="display: block; margin: auto;" />

--- .class #id

### Linear Regression of PAP % Votes Against Media Chatter  

1.The Plot showed the scatterplot of the percentage wins by the PAP against the percentage of the media
exposure in terms of blogs and media posts. This percentage is calculated as a percentage for each
Electoral Division.  
2. The green line shows the linear regression line. There is a correlation between the votes received by the PAP vs the percentage of media chatter about them.  
3. The horizontal red line represents the 50% popular votes. The 2 divisions below the red line also received the lowest percentage of blog share by PAP.  
<img src="assets/fig/Linear Regression-1.png" title="plot of chunk Linear Regression" alt="plot of chunk Linear Regression" style="display: block; margin: auto;" />
--- 

--- 

### Logistic Regression of PAP Wins Against Media Chatter  

1. The Plot showed the logarithmic Regression of Win/Lose by the PAP versus the percentage of Blogs obtained.  
2. The Logistic Regression gives a good prediction of electoral wins againsts the percentage of Blog Posts.  
<img src="assets/fig/Logistic Regression-1.png" title="plot of chunk Logistic Regression" alt="plot of chunk Logistic Regression" style="display: block; margin: auto;" />

---

## Observations

1. The report shows that there is a correlation between the percentage of blogs post about PAP to their performance in the election.
2. The Logistic Regression show that it is possible to predict the election wins from the percentage of blogs received. However as the next election is only 4 years later, we will have to wait until then to determine if this prediction holds true.


### Acknowledgement

Data of the media and blog posts of election candidates are compiled from the following site :
http://research.larc.smu.edu.sg/ge2015/ (Living Area Research Centre, Singapore Management University)




