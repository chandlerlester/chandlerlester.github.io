---
layout: splash
title: "Research"
author_profile: true
share: false 
comments: false
classes: wide 
# header:
 # overlay_color: "#5e616c"
 # overlay_image: ../images/Research_splash.jpg
---

# Research 
---
The 2008 financial crisis and ensuing Great Recession permanently altered the global economy and how most people think about their finances. 
Why did financial markets crash? How did the lending behavior of a few banks lead to a global slowdown? 
And, perhaps most importantly, what can we learn to help us prevent future similar catastrophes? 

I seek to answer these questions through developing more sophisticated models of the economy that capture the financial system's influence over individual decision making; just as previous economic tools were developed in response to crises of demand or production, we now require new tools to anticipate crises caused by financial frictions and failing capital markets. 
My research combines work in macroeconomic theory, finance, and behavioral modeling to deliver these tools. 

## Works in Progress

### Bounded Rationality in Macroeconomic and Finance Models: A Continuous-Time Approach (Coming Soon) 





### [Boundedly Rational Decision Making in Continuous-Time](https://chandlerlester.com/images/Lester_Chandler_Ch2.pdf) <i class="fas fa-external-link-alt"></i>
![Convergence of the discrete-time Tmap to the continuous-time solutions](/images/Tmap_Convergence.gif "Convergence of the discrete-time Tmap to the continuous-time solution"){: .align-right}
Continuous-time macroeconomic literature has grown remarkably in recent
years. As work on continuous-time models becomes, more prevalent macroeconomists need to adapt essential discrete-time methods to continuous-time.
This paper modifies adaptive learning techniques to continuous-time. One approach to accomplish this task is shadow-price learning (SP-learning), a framework in which agents forecast their expected shadow prices. To use this framework efficiently, we first need a tractable continuous-time linear-quadratic (LQ)
environment. While discrete-time LQ problems are common in the literature,
there is very little work on continuous-time LQ problems. Thus, our contributions are two-fold. We build a continuous-time LQ framework for solving
Hamilton-Jacobi-Bellman (HJB) equations using iterative methods and implement adaptive learning techniques in this new setting.
{: .text-left}


### Adaptive Learning in a Continuous-Time Setting: Representative Agent Exercises (Third-Year Paper) 
We accomplish two distinct, but closely connected, tasks in this paper.
First, We look to create a connection between discrete and continuous-time models.
This is done by recasting traditional discrete Ramsey models so they are dependent on the increment of time, Δ, 
and then taking the limit of these models as the size of this increment goes to zero. 
The resulting models are equivalent to continuous-time Ramsey models. 
Second, We examine these models in a basic adaptive learning framework. 
We  accomplish this by applying exogenous updating rules to models with a specified stochastic process. 
After seeing that the misspecified models converge, We then implement a real-time updating rule where agents update their parameter estimates---for a stochastic process---after observing output of the process. 

*<font size="3">For more information and code from this project visit my <a href="https://github.com/chandlerlester/Stylized_Learning">repo.</a></font>*

