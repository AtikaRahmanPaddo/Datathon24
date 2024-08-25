# Team 8


# Emory_datathon_2024_Team8

There are two approaches that we tried for our problem statement in the datathon.

## 1. Including Microbiologyevents table

Microbiologyevents table had some good features like test_name, organism_name, antibiotic_name and the interpretation from these like whether a patient has a resistance or not, susceptibility or not for a certain antibiotic for a certain organism found a from a certain test. So we used these datas from the table and ran our model on trying predicitng whether a patient will die in the hospital or not.


## 2. Excluding Microbiologyevents table

We excluded the Microbiologyevents table because we want saw that the number of patients who only went through the labtests (top 25 tests and top 25 antibiotics from the value_counts) were very less in number like 4949. That is a really small subset, so we removed the microbiologyevents from the final analysis and included the other tables. Then we ran the model on 55k unique admissions information.
