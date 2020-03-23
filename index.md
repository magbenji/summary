---
layout: page       # Can leave this alone
root: .            # Can leave this alone
---
[//]: # (This is a comment that won't be rendered at github.io)
[//]: # (MD Cheat sheet: https://www.markdownguide.org/cheat-sheet/)
    
# Introduction

Covid-19 (Coronovirus) was declared a pandemic by the World Health Organization (WHO) on January 30, 2020. According to [John Hopkins University](https://coronavirus.jhu.edu/map.html) as of March 22, 169 countries/regions have reported at least one Covid-19 case; there have approximately 330,000 confirmed cases of Covid-19 and nearly 15,000 deaths. The United States (US) reported its first case in Washington on January 21. On March 13, when Idaho reported its first case, a total of 2,179 cases in the US, and 145,193 cases globally had been reported. 

On March 18, universities throughout Idaho (Boise State University, Idaho State University, and University of Idaho) were asked to identify a team of researchers to provide a report that would help predict the expected number of people in Idaho anticipated to contract Covid-19, how many of these would require hospitalization, and likely effects of different interventions. 

On March 20, a small team of researchers met with TJ Bliss (Board of Education), Martijn van Beek (Idaho Department of Health and Welfare) *[others important to mention, who outside of Idaho was on the call]*. The information provided in the document is a short summary of the number of infected, hospitalized, and dead, we could expect to see in Idaho from Covid-19. 

The information presented below has been compiled from limited data sources, and during a brief period of time. Predicting Covid-19 is very difficult and there is no guarantee that the information presented below is correct. However, based on the information we had at the time, the below summarizes what we might anticipate in the coming weeks and months.

# Predictions
As mentioned above, predicting the number of infected, hospitalizations, and deaths in Idaho due to Covid-19 is difficult. We use a model to make the predictions, and there are currently many unknowns in the equations we are using. For instance, if the number of people who are exposed is higher (or lower) than the parameter in the model, the model will under (or over) estimate the number of people who become infected. While the exact value for the parameters is unknown, we can use the prior information to guess a range of plausible values. For each parameter we have examined a range of values, and we present the expected potential values based on these ranges. 

A simplistic approach of modeling Covid-19 starts with a number of people susceptible to an illness (in this case the Idaho population). 
People who are susceptible can become exposed, those who are exposed become infectious, and those who are infectious either recover or die. 
The rate at which people go from being susceptible to exposed to infected to recovery or death are major paramaters of the model, with changes in these paramters resulting in significant differences in predictions. 
This model is called a Susceptible, Exposed, Infected, and Removed (SEIR) model and it has been successfully used for other, similar, epidemics [cite]. 

*Once recovered, people can become susceptible again - is this true for the models you are running?*.

A total of xx models are presented below. Each of the models is slightly different, resulting in different predictions. 
These differences in predictions are expected given the differences in the model paramters - at this point it is unclear which model is the most realistic. More testing will result in more accurate predictions in how many people will be impacted by Covid-19. 

*Assumptions of models constent*
*Italy infection rate*
* (1) When do infections peak?*
* (2) What are the total counts of infections at the peak?*
* (3) What proportion of population is infected?*

*Infections peak August 16th, at 239,000 (47 initial infections)*
*Infections peak July 22, at about the same total cases (47 * 5 initial infections)*
*Infections peak July 10, at about the same total cases (47 * 10 initial infections)*

Model A: *brief summary*

Model B: *brief summary*

Model C: *brief summary*

Model D: *brief summary*


<img style="float: right" width="30%" src="./fig/SEIR.PNG">
<b>Figure 1</b> simplistic SEIR modell</div>
<br>

We anticipate that there are roughly 2,500 Hospital Available Beds for Emergencies and Disasters (HAvBED) and 400 ventilators in Idaho. The number of these available for Covid-19 patients would be lower, it is unclear at this time how many HAvBED and ventilators are typically in use.

One concern is that the number of cases reported is an under-estimate. This is a significant problem as if the number of people who are infected is unknown, it becomes very difficult to predict how many people are actually infected - and contagious.
We anticipate that the number of cases on https://coronavirus.idaho.gov/ is an underestimate as not everyone is likely to present for testing (especially those who are asymptomatic), and it is also our understanding that not everyone who presents with likely Covid-19 will be tested. Given this potential under-estimate in the number of cases three different models were run.

Model 1: The model uses the number of offically recorded Covid-19 cases as reported on Mar 22, 2020. As six of the seven Public Health Districts were reporting a case of Covid-19, for simplicity the seventh Public Health District (North Central) was set to have one case as well. This resulted in a total of 48 cases in Idaho.

Model 2: The model used five times the number of Covid-19 cases than were used in Model 1, resulting in a total of 240 cases in Idaho.

Model 3: The model used ten times the number of Covid-19 cases than were used in Model 1, resulting in a total of 480 cases in Idaho.

# Results
The number of reported Covid-19 cases by each US state have been increasing at an exponential rate.
We anticpate that the number of Covid-19 cases in Idaho will follow this exponential rate seen in the other states in the short term.
Figure 3 shows the number of cases reported by each US state, since the first day with cases reported. 
The number of Covid-19 cases data for Idaho is shown in red, and the predicted number of cases for Idaho for the next two weeks (if the spread continues at the same rate) is shown in blue.

<div align = "center"> <img width="80%" src="./fig/US_Idaho_predicted.PNG">
<br>
<b>Figure 2 </b> Known cases of Covid-ID by state. Red line = Idaho reported, blue line = Idaho predicted</div>
<br>


Figure 4 shows the anticipated number of infected, hospitalized, and deaths for Idaho if no mitigation is done. 
This suggests that if no mitigation is done the the peak number of infections will be [date range].
If there is no mitagation we anticpate that the ventilators wil be overwhelmed [date range], *resulting in an ever higher number of deaths - please let me know if your death rates take into account ventilators*.


*image*

Earlier start social distancing = less bad
Depending on the measures taken to control Covid-19.
*image*




## Suggestions
The limited number of tests being conducted, and the delay in testing results becoming available, is significantly hampering modeling efforts. It is difficult to accurately model Covid-19 in Idaho given the wide range of uncertainty in the model parameters. So far, the places that have controlled Covid-19 have implemented wide-scale testing and tracing measures. In our opinion, mass testing has the potential to help prevent the spread of Covid-19, which can help mitigate the economic impacts. This is because in many communities in Idaho the spread is sufficiently low that mass testing in combination with contact tracing has the potential to quelch local spread. We believe that without mass testing, community spread is inevitable and has devastating economic and health infrastructure consequences.
 
Our predictions suggest that ventilators will be overwhelmed if no social distancing effort are put in place. Once the ventilators are overwhelmed the death rate will increase. If Idaho slows the spread by 50% (such as by shutting schools and isolate Covid-19 cases) then ventilators will be available for the majority of the time. If Idaho slows the spread by 60% (such as by shutting schools, isolating Covid-19 cases, and *xxxx*) then ventilators would be overwhelmed *how much*.

One suggestion that balances the demands of economics and health is to have a (hopefully short) period of strong social distancing while mass testing is ramped up to large levels. This would allow health workers to determine where Covid-19 is, and ensure infected cases were isolated. This period would allow researchers and healthworkers to determine how widespread and severe Covid-19 is in Idaho. 
After this period of strong social distancing a period of relaxed social distancing measures could be implemented, ramping up to strong social distancing as needed (if the number of cases was at risk of exceeding hospital demand).

If people who are likely immune (based on prior exposure or serology) are not infections, there is no reason for these people to not  get back to normal economic activity. PCR tests and serology (once available) will indicate how many people are likely immune from this current Covid-19 virus. 

Providing more detailed information on who is infected by Covid-19 (e.g., age, gender, comorbidities) will help future predictions be more accurate.


## Additional information
For more information specific to Idaho, see the following websites:
A visual summary of trends over time in Idaho: https://rpubs.com/IrenevanWoerden/587899
A dashboard with multiple parameters that https://benridenhour.shinyapps.io/COVID-19_ID/
A dashboard with multiple parameters that xxx https://public.tableau.com/profile/jeff.lingwall7921#!/vizhome/Statewide_SEIR_Projections_ver1/Dashboard12?publish=yes


[//]: # (Links below)
[image1]: ./fig/SEIRmodel.PNG
[image2]: ./fig/Health-Districts-Exploded_Color.jpg
[image3]: ./fig/US_Idaho_predicted.PNG
[Alt text for image1]: slack snapshot

