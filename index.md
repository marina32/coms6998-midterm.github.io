# COMS 6998 Mid-term Seminar Blog
# Option Pricing and Optimal Stopping

This blog shows what I've learnt from the two papers about deep learning in option pricing.

# Motivation
[Week 3](src='Week 3.jpg')
Option is an important financial derivatives which
For optimal stopping problem
High-dimensional optimal stopping problems are notoriously difficult to solve due to the well-known curse of dimensionality. The input data is often high dimension since there might be multiple underlying assets in a hedging portfolio so that almost all of them do not have calculation methods to gain a explicit answer. 
Lots of research try to use different input design and analyse approximation methods to solve it while the deep learning offers not only an approximation of an optimal strategy but also the optimal expected payoff associated to the considered optimal stopping problem. 

# Background
**1. For optimal stopping problem:** 
- The previous work is trying to use delicate input to better calculate the optimal stopping while the deep learning algorithm is insensitive to the input. The uniform sampling is more preferable.
- Avoid the problem of unaffordable computing time for high-dimensional problem
- Detection of wrong inputs with noise
**2. For pricing/calibration of options:**
- Besides geometric Brownian motion(GBM), variance gamma(VG) model is also commonly use in option pricing so the author want to explore the potential of combine those two.
- Other than the simple European options and American options, Barrier options are more complicated with several more condition to execute and the author also consider about pricing those type of option.

# Paper 1: Deep Learning in Optimal Stopping
## 1.1 Introduction

## 1.2 Neural Networks and Deep Learning Algorithms

## 1.3 Numerical Experiments

## 1.4 Observations and Insights
- Deep learning method perform quite well with uniform inputs which seems no need to design a special method to generate input and it can also auto-detect the noisy part although it still perform better for the clean data.
- Provide a solution for high-dimensional problem within affordable computing time 


# Paper 2: Deep Learning in Pricing/Calibration of Vanilla/Exotic Options
## 2.1 Introduction
## 2.2 Neural Networks and Deep Learning Algorithms
## 2.3 Numerical Experiments
## 2.4 Observations and Insights

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text


```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).


Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/marina32/coms6998-midterm.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

# Conclusion


# Reference:
1.[Deep learning for ranking response surfaces with applications to optimal stopping problems](https://www-tandfonline-com.ezproxy.cul.columbia.edu/doi/full/10.1080/14697688.2020.1741669)
2.[Supervised Deep Neural Networks (DNNs) for Pricing/Calibration of Vanilla/Exotic Options Under Various Different Processes](https://arxiv.org/abs/1902.05810)

## Contact Me
If you have any questions on this page, please contact me via rn2498@columbia.edu.
