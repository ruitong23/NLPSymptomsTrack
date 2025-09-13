# NLPSymptomsTrack
using nlp to read through doctor word from Vares dataset relate covid-19

There are 12 dataset from VAERS have been used for this project
from 2020 to 2023 2020VAERSDATA, 2020VAERSVAX, 2021VAERSDATA, 2021VAERSVAX, 2022VAERSDATA, 2022VAERSVAX, 2023VAERSDATA, 2023VAERSVAX from https://vaers.hhs.gov/data/datasets.html.

You will need to put all those files in a data folder with the same direction as the code, base code run with 50000 row of data for testting purpose, you can increase the number by setting it in the code frigth after impfort the files. 

basic function
 • Using unsupervised techniques, go through the dataset. Add stop words with the
 word cloud to identify the most common word in the data. like vaccine-related
 name, and obvious symptoms
 • extract the vaccine name and most common symptom. building the pattern in the
 symptom development.
 • using obvious to extract hidden symptoms.
 • extract time from the symptom text, if there is no time in the symptom text, extract
 from VAXDATE and ONSETDate
 • Data virtualization of the relationship between symptoms and time.
