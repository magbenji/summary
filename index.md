---
layout: page       # Can leave this alone
root: .            # Can leave this alone
---
[//]: # (This is a comment that won't be rendered at github.io)
[//]: # (MD Cheat sheet: https://www.markdownguide.org/cheat-sheet/)
    
# Introduction

Covid-19 (Coronovirus) was declared a pandemic by the World Health Organization (WHO) on January 30, 2020. According to [linked phrase](https://coronavirus.jhu.edu/map.htm) as of March 22, 169 countries/regions have reported at least one Covid-19 case; there have been 328,275 confirmed cases of Covid-19 and 14,366 deaths. 

The United States (US) reported its first case in [location] on [date]. On March 13, when Idaho reported its first case, a total of 2,179 cases in the US, and 145,193 cases globally had been reported. 

On March 18, universities throughout Idaho (Boise State, Idaho State, and University of Idaho) were asked to identify a team of researchers to provide a report that would help predict the expected number of people in Idaho anticipated to contract Covid-19, how many of these would require hospitalization, and likely effects of different interventions. 

On March 20, a small team of researchers met with TJ Bliss (Board of Education), Martijn van Beek (Idaho Department of Health and Welfare) *[others important to mention, who outside of Idaho was on the call]*.  

# SEIR
Modelling Covid-19 is difficult given the number of unknowns in the equation. The models and results presented below are based on the limited amount of information currently available. There are many unknown parameters, such as the rate of exposure in Idaho, that will significantly change the model predictions. For instance, if the number of people who are exposed is higher or lower than the parameter in the model, the model will under- or over-estimate the number of people who become infected. While the exact value for the parameters is unknown, we can use the prior information to guess a range of plausible values. For each parameter we have examined a range of values, and we present the expected potential values based on these ranges. 

Susceptible, Exposed, Infected, and Removed (SEIR) models have been successfully used for other, similar, epidemics [cite] and have been used to model Covid-19 in Idaho. The simplest SEIR model starts with a number of people susceptible to an illness. People who are susceptible become exposed at rate \(\beta\), those who are exposed become infectious at rate $$\sigma\$$, and those who are infectious recover at rate $\gamma$. Once recovered, people can become susceptible again at rate xx.

*[image SEIR, currently direct copy paste /plagerism from https://www.idmod.org/docs/hiv/model-seir.html]* 

![SEIR model][image1]

The SEIR model was used to predict the number of cases in Idaho examined the following parameters
* age
* spatial structure
* social distancing
* school closures by city

* S = susceptible
* Q = quarantine
* E = latent (infected but not infectious)
* I = infectious with symptoms
* A = infectious without symptoms
* H = infections, hosptialized
* R = recovered



forgot to mention that in the new version of the code, you can specify when social distancing and school closures occur for each city (because this was a feature mentioned on the call on Friday). In other words, you could have schools in Boise closing right now and lasting for some period of time, while some other city might wait to close schools for another month and only close schools for a short period of time. The easiest thing to do is just specify a statewide start and stop time though.
 

## Methods 1
More paragraph

## Results

## Suggestions

I believe that a useful message for decision makers is that mass testing has the potential to help prevent spread and mitigate economic impacts.  In many communities in Idaho, the spread is sufficiently low that mass testing plus contact tracing has the potential to quelch local spread.  Without mass testing, community spread is inevitable and has devastating economic and health infrastructure consequences.
 
Mass testing is also required to accurately parameterize these models. Without it, there is a huge amount of uncertainty.  A useful strategy could be a (hopefully short) period of strong social distancing while mass testing is ramped up to large levels, followed by relaxation of social distancing measures (which hurt the economy) once we find out where we are.


[Link to page 2](page2)


[//]: # (Links below)
[image1]: ./fig/SEIRmodel.PNG
[Alt text for image1]: slack snapshot

