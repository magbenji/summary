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

*[image SEIR, currently direct copy paste /plagerism from https://www.idmod.org/docs/hiv/model-seir.html] update to show a simple version of what was run for Idaho* 

![SEIR model][image1]

The SEIR model was used to predict the number of cases in Idaho used and examined the following parameters
* demographic information for cities with at least 3,000 individuals [sourced from wikipedia](https://en.wikipedia.org/wiki/List_of_cities_in_Idaho)
* Contact rates by age group (0-14, 15-24, 25-54, 55-64, and over 65)

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

## Additional information
There are roughly 2,500 Hospital Available Beds for Emergencies and Disasters (HAvBED) and 400 ventilators in Idaho. The approximate number of HAvBED and ventilator for each Public Health District are:
* 1 (Panhandle) 500, 58
* 2 (North Central) 300, 12
* 3 (Southwest) 200, 26
* 4 (Central) 500, 201
* 5 (South Central) 300, 20
* 6 (South eastern) 300, 26
* 7 (Eastern) 400, 52

*want image smaller, on right of list*

<img align="right" width=200 src="./fig/Health-Districts-Exploded_Color.jpg" >


# Results
The below figures show the anticipated number of infected, hospitalized, and deaths for Idaho.


For more information 

*may want to remove names from these links, keep it "idaho covid response"*

https://benridenhour.shinyapps.io/COVID-19_ID/

https://rpubs.com/IrenevanWoerden/587899

## Suggestions
The death rate will increase once the ventilators are all in use. Social distance measures of level [6; xxx] is projected to keep the number of people needing ventilators at or below the number of ventilators available.

The limited number of tests being conducted, and the delay in testing results becoming available, significantly hamper modeling efforts as it is difficult to accurately parameterize these models. There is currently a wide range of uncertainty in the model parameters. Mass testing has the potential to help prevent the spread of Covid-19, which can help mitigate the economic impacts. In many communities in Idaho, the spread is sufficiently low that mass testing plus contact tracing has the potential to quelch local spread. Without mass testing, community spread is inevitable and has devastating economic and health infrastructure consequences.
 
A useful strategy could be a (hopefully short) period of strong social distancing while mass testing is ramped up to large levels, followed by relaxation of social distancing measures (which hurt the economy) once we find out where we are.

I should say that the testing message should include PCR tests immediately, but also serology when they become widely available.  If people knew they were likely immune, they could get back to normal economic activity.

[Link to page 2](page2)


[//]: # (Links below)
[image1]: ./fig/SEIRmodel.PNG
[image2]: ./fig/Health-Districts-Exploded_Color.jpg
[Alt text for image1]: slack snapshot

