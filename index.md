---
layout: page       # Can leave this alone
root: .            # Can leave this alone
---
[//]: # (This is a comment that won't be rendered at github.io)
[//]: # (MD Cheat sheet: https://www.markdownguide.org/cheat-sheet/)
    
# Introduction
Covid-19 (Coronovirus) was declared a pandemic by the World Health Organization (WHO) on January 30, 2020. According to [John Hopkins University](https://coronavirus.jhu.edu/map.html) as of March 23, 168 countries/regions have reported at least one Covid-19 case; there have approximately 400,000 confirmed cases of Covid-19 and 16,000 deaths. On March 13, when Idaho reported its first case, a total of 2,179 cases in the US, and 145,193 cases globally had been reported. 

On March 18, a call was sent out to identify a team of researchers to provide a report that would help predict the expected number of people in Idaho anticipated to contract Covid-19, how many of these would require hospitalization, and likely effects of different interventions. 

On March 20, a small team of researchers from Boise State University, Idaho State University, University of Idaho, Lewis and Clark, and Washington State University met with TJ Bliss (Board of Education), Martijn van Beek (Idaho Department of Health and Welfare) *[others important to mention]*. The information provided in the document is a short summary of the number of infected, hospitalized, and dead, we could expect to see in Idaho from Covid-19. 

The information presented below has been compiled from limited data sources, and during a brief period of time. Predicting Covid-19 is very difficult and there is no guarantee that the information presented below is correct. However, based on the information we had at the time, the below summarizes what we might anticipate in the coming weeks and months.

## Methods
As mentioned above, predicting the number of infected, hospitalizations, and deaths in Idaho due to Covid-19 is difficult. We use a model to make the predictions, and there are currently many unknowns in the equations we are using. For instance, if the number of people who are exposed is higher (or lower) than the parameter in the model, the model will under (or over) estimate the number of people who become infected. While the exact value for the parameters is unknown, we can use the prior information to guess a range of plausible values. For each parameter we have examined a range of values, and we present the expected potential values based on these ranges. 

<figure style="float:right;width:40%">
<img src="./fig/SEIR.PNG" >
<figcaption><b>Figure 1</b> simplistic summary of the models used in predictions </figcaption>
</figure>

A simplistic approach of modeling Covid-19 starts with a number of people susceptible to an illness (in this case the Idaho population). 
People who are susceptible can become exposed, those who are exposed become infectious, and those who are infectious either recover or die. 
The rate at which people go from being susceptible to exposed to infected to recovery or death are major paramaters of the model, with changes in these paramters resulting in significant differences in predictions. 
This model is called a Susceptible, Exposed, Infected, and Removed (SEIR) model and it has been successfully used for other, similar, epidemics [cites please]. 
**Once recovered, people can become susceptible again - is this true for the models you are running?**.

The R0 is one of the parameters in the model, R0 is the average number of people an infected person will infect. 
An R0 of two means that, on average, each infected person will infect two other people.
An R0 of one means that, on average, each infected person will infect one other person.
An R0 of 0.5 means that, on average, for every two infected persons, only one person will become infected.
The exponential growth observed with Covid-19 is due to the R0 being greater than one.
As social distancing increases, the average number of people who an infected person infects with Covid-19 reduces, resulting in a lower R0. Only when R0 is less than one will the spread of Covid-19 decrease.

All of the models assumed the infection rate, the R0, was similar to that observed in Italy. 
The infection rates of Italy were chosen given the number of infections in the United States is currently similar to Italy.
The models also assumed *what else was constant across models*

*Figure 2 - image of Wuhan vs Italy infectious rates with Idaho data*

We anticipate that there are roughly 2,500 Hospital Available Beds for Emergencies and Disasters (HAvBED) and 400 ventilators in Idaho.
These supplies are to meet the demand for all emergencies and disasters, not just for Covid-19. 
If approximately 30% of these beds and ventilators are available for Covid-19 patients, Idaho would have around 750 HAvBED and 120 ventilators available.

One concern is that the number of cases reported is an under-estimate. 
We anticipate that the number of cases on https://coronavirus.idaho.gov/ underestimates the current number of cases.
This is because not everyone is likely to present for testing (especially those who are asymptomatic), a potential lack of supplies such that not everyone with Covid-19 who presents is tested, and delays in processing tests and confirming and reporting cases. 

The number of cases in Idaho are required to accurately model Covid-19. 
Given the anticipated under-estimate in the number of officially reported cases three different scenarios were run.

**Scenario 1**: The model uses the number of offically recorded Covid-19 cases as reported on Mar 22, 2020 (a total of 48 cases).
For simplicity, some of models set the seventh Public Health District (North Central), which was not reporting any cases on Mar 22, to have one case as well. 

**Scenario 2**: The model used five times the number of Covid-19 cases than were used in Model 1.

**Scenario 3**: The model used ten times the number of Covid-19 cases than were used in Model 1.

# Results
The number of reported Covid-19 cases by each US state have been increasing at an exponential rate.
We anticpate that the number of Covid-19 cases in Idaho will follow this exponential rate seen in the other states in the short term.
Figure 3 shows the number of cases reported by each US state, since the first day with cases reported. 
The number of Covid-19 cases data for Idaho is shown in red, and the predicted number of cases for Idaho for the next two weeks (if the spread continues at the same rate) is shown in blue.

<div align = "center"> <img width="70%" src="./fig/US_Idaho_predicted.PNG">
<br>
<b>Figure 3 </b> Known cases of Covid-ID by state. Red line = Idaho reported, blue line = Idaho predicted</div>
<br> 

**Scenario 1.** Starting with 48 cases in Idaho
- Time to peak:  roughly 150 days, August 16-22
- At peak:  
      - estimate 1: 1,000 hospitalizations, 20,000 symptomatic, 130,000 asymptomatic.
      - estimate 2: 239,000 infected
- Final outbreak size:  80.6%
- Total deaths: 400 (~315 deaths in 65+, ~70 in 55-64, and ~15 in 25-54)

**Scenario 2.** Starting with 240 cases in Idaho
- Time to peak: July 22,
- At peak:  
       - estimate 1: 
       - estimate 2: 239,000 infected
- Final outbreak size: 
- Total deaths: 

**Scenario 3.** Starting with 480 cases in Idaho
- Time to peak: July 10
- At peak:  
      - estimate 1: 
      - etimate 2: 239,000 infected
- Final outbreak size: 
- Total deaths: 

Figure 4 shows the anticipated number of infected, hospitalized, and deaths for Idaho if no mitigation is done. 
This suggests that if no mitigation is done the the peak number of infections will be [date range].
If there is no mitagation we anticpate that the ventilators wil be overwhelmed [date range], *resulting in an ever higher number of deaths - please let me know if your death rates take into account ventilators*.


*Figure predicted Idaho infected hospitilations, deaths showing range in predictions - send me your day 1-365 predictions*


## Conclusions
The limited number of tests being conducted, and the delay in testing results becoming available, is significantly hampering modeling efforts. It is difficult to accurately model Covid-19 in Idaho given the wide range of uncertainty in the model parameters. We ran a large number of models, 

Several different approaches to modelling Covid-19 in Idaho were used.
As each of the models is slightly different the predictions for each of the models are also different. 
At this point it is unclear which model is the most realistic. 

**If no social distancing measures are implemented**, all of the models suggest that the ventilators will become overwhelmed.
The date range that the ventilators will be overwhelmed ranges from [range].
This is assuming that there are *number ventilators in use for non-covid, for covid*.
While there is a range of dates here, the important thing to note is that all models suggest that the ventilators will be overwhelmed.
This is important as once the ventilators are overwhelmed the death rate is expected to increase.

With no social distancing we anticipate that the peak of infection will be between [date] and [date], with up to xx% of Idaho eventually effected. 

**With moderate social distancing** such as school closures and isolation of infected cases *what about working from home vs office, bars, restaurants etc* our models suggest that the ventilators will only be overwhelmed for some short periods.
If Idaho slows the spread by 50% (such as by shutting schools and isolate Covid-19 cases) then ventilators will be available for the majority of the time.

**With strong social distancing** our predictions suggest that ventilators will be overwhelmed if no social distancing effort are put in place.  If Idaho slows the spread by 60% (such as by shutting schools, isolating Covid-19 cases, and *xxxx*) then ventilators would be available in Idaho (not necessarily) for the majority of the time. 

**Overall summary**
The number of cases reported in Idaho likely has a delay, such that it may take several days for a person with Covid-19 who is tested to be officially confirmed and reported. This means that any intervention will also have a delay in reducing the number of cases in Idaho. If there is a week-long delay between testing and results, it will take one week before the results of any intervention can start to be seen. As the current growth of Covid-19 is exponential, a one-week delay (for instance) would result in the actual numbers in Idaho being much, much, higher than what is reported. Given this exponential growth we suggest a period of social distancing while the extent of Covid-19 in Idaho is determined.

Not testing - This is a significant problem as if the number of people who are infected is unknown, it becomes very difficult to predict how many people will be infected in the future.

One suggestion that balances the demands of economics and health is to have a (hopefully short) period of strong social distancing while mass testing is ramped up to large levels. This would allow health workers to determine where Covid-19 is, and ensure infected cases were isolated. This period would allow researchers and healthworkers to determine how widespread and severe Covid-19 is in Idaho. 
After this period of strong social distancing a period of relaxed social distancing measures could be implemented, ramping up to strong social distancing as needed (if the number of cases was at risk of exceeding hospital demand).

If people who are likely immune (based on prior exposure or serology) are not infections, there is no reason for these people to not  get back to normal economic activity. PCR tests and serology (once available) will indicate how many people are likely immune from this current Covid-19 virus. 

The models will be more accurate once more testing is implemented, or when we death data starts to be available.

The first cases of Covid-19 in Idaho were observed after other states were infected. By tracking the number of cases reported by state we may be able to see how well different intervention strategies have worked elsewhere in the US.

Large-scale testing will help create more accurate future predictions researchers. While death data (once available) will help with improving the predictions, relying on testing is preferrable for obvious reasons. 

Providing more detailed information on who is infected by Covid-19 (e.g., age, gender, comorbidities) will help future predictions be more accurate.

## Additional information 
For more information specific to Idaho, see the following websites:

A visual summary of trends over time in Idaho: https://rpubs.com/IrenevanWoerden/588295 

A dashboard with multiple parameters that https://benridenhour.shinyapps.io/COVID-19_ID/

A dashboard with multiple parameters that xxx https://public.tableau.com/profile/jeff.lingwall7921#!/vizhome/Statewide_SEIR_Projections_ver1/Dashboard12?publish=yes

Who was involved (+ email contacts):
Boise State University:
Idaho State University:
University of Idaho:
Washington State University:
Lewis and Clark:

[//]: # (Links below)
[image1]: ./fig/SEIRmodel.PNG
[image2]: ./fig/Health-Districts-Exploded_Color.jpg
[image3]: ./fig/US_Idaho_predicted.PNG
[Alt text for image1]: slack snapshot

