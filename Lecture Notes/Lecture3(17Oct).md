# Pointing Analysis:
Started working on pointing analysis project. Made copy of the gitlab repo.
___
## Experiment 1 

[Experiment](https://ergo.human.cornell.edu/FittsLaw/FittsLaw.html] completed) completed with parameters:


| Parameter  | Value(s)    |
|------------|-------------|
| Width      | 16,32,64    |
| Amplitudes | 128,256,512 |
| Trials     | 5           |

Data from website saved in .csv files in MYm2r_pointingxp/MYdataExp1


I am getting results different from those presented on the webiste. The differences are in the following table, 
from analysing the meandata .csv file.


| Value     | My result | Cornell website result |
|-----------|-----------|------------------------|
| R2        | 0.8922    | 0.913                  |
| Intercept | 266.40    | 254.848                |
| Slope     | 107.30    | 107.280                |

I had 3 misses during the experiment.

There are some discrepancies here, which is troubling. It is better to perform your own data analysis, such that you 
are sure where the numbers come from and you know how they were obtained.

The following table shows my analysis results from performing identical data analysis on first the meandata .csv file 
from the website, and then on the rawdata .csv file.


| Value     | My meandata result | My rawdata result |
|-----------|--------------------|-------------------|
| R2        | 0.8922             | 0.6551            |
| Intercept | 266.40             | 265.79            |
| Slope     | 107.30             | 107.43            |


While the analysis performed on the rawdata shows 'worse' results (the model fit is not as good) I draw the conclusion 
that it is better to perform the analysis on unmanipulated data, such that you know what has happened every step 
of the way from data collection to the results that you will present. 

Céline raised a very good point that perhaps my conclusion should be a bit more nuanced. For example, in the
human-interaction field it is praxis to use aggregate data for analysis. And the reasoning for this could be that we 
want to consider a hypothetical "average" user. But this might not always be the case, so what data set you use can 
depend on the scope of your research. 

## Experiment 2 (same parameter values as Céline)


| Parameter  | Value(s) |
|------------|----------|
| Width      | 1,2,4    |
| Amplitudes | 16,32,64 |
| Trials     | 6        |

Data from website saved in .csv files in MYdataExp2 directory

The same as analysis as outline in MYpointingAnalysis.Rmd generates the follwing:


| Value     | My meandata result | My rawdata result |
|-----------|--------------------|-------------------|
| R2        | 0.06542            | 0.0466            |
| Intercept | 1095.33            | 1095.16           |
| Slope     | -77.17             | -77.13            |

The linear model is a very bad fit to this data. The slopes have ended up negative, meaning that the model suggests that
the time taken (TM) actually decreases as the difficulty index (ID) increases. This does not make very much sense, 
however the very low R2 value also means that the model is not to be taken seriously.

I believe this model fitting is so poor because the experiment quality was quite low. The width is measured in pixels, 
such that [1, 2, 4] are very thin widths to be able to click on. I am also using a trackpad which doesn't help. This issue 
is manifested in the fact that I had **215** misses. Compared to 3 misses in experiment 1. I wouldn't use these finding 
to reach any conclusions, since the model fit is so poor. 


___
### Discussion

One issue with these problems is that people get tired. The clicking-task that I performed depends
a lot on how invested the test-person is in the experiment. 

Worthwhile thinking before an experiment: Consider what CAN go wrong, then make sure you adapt the experiment so that 
they don't impact the quality of the experiment. 

