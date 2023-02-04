# CSC8106-System-Evaluation
## Overview
For this project we were provided with a set of research papers that had each used the modelling language PEPA to model something.
The main goal of this project was to replicate the results of the chosen research paper and then to modify the model in order to make further findings.
From the available papers I chose a paper that had used PEPA to model patient flow through a hospital.
The modification I decided to make was to model patient flow through a Covid ward in a hospital.
For this I researched real statistics and used these to inform the development of the modified model.

I decided to create two separate models for this project because the two elements I wanted to model were on very different time scales.
The first element was the patient admittance to the Covid ward which would be modelled over a matter of hours.
The second element was the patient recovery in the Covid ward which would be modelled over weeks so separate models were required.
## Main Model
This PEPA model would model the patient admittance to the Covid ward.
This model was based on the model from the paper.
The addition that I made was to model the effect of using electronic registration and in-person registration instead of just in-person registration.
For this electronic registration was given a rate of over double the rate of in-person registration.
This was because electronic registration would require less use of hospital resources so would speed up the overall process.
This model was run and compared against the original unchanged model and it was found that it still took 24 hours to admit all 200 patients.
The reason for this was that the rate of new doctors was the bottleneck so even though electronic registration led to a significant time saving in the end it made no overall time difference.
But it would reduce the hospital resources required for registration.
## Patient Recovery Model
This second model was made to model the recovery of patients in the Covid ward.
For this data on the proportion of patients with long Covid and the proportion of patients that required a ventilator was used.
This model was then used to make findings about the number of ventilators required for the Covid patients.
It was found that even though the normal Covid patients made up 70% of the patients they required almost half as many ventilator days as the long Covid patients.
