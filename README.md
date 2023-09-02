# Data Cleaning and Transformation with Spark

## Description

Rheeza Clinics & Pharmaceuticals conducted a research study on Naproxen,
 a medication claimed to regulate blood pressure in teenagers and young adults.
  The trial took place across three clinic branches and involved over 2000 participants 
  of various genders aged between 14 and 22. The study was conducted from February to May 2021.

The trial consisted of two groups: the inactive (Placebo) group and 
the active (Naproxen) group, aimed at assessing the true effects of Naproxen.

Comprehensive records of all procedures were meticulously maintained 
and subsequently accessed by Machine Learning Engineers for the development 
of algorithms for the upcoming phases of the experiment.

During the analysis, it was identified that the dataset required some 
optimization to enhance accessibility for both Clinicians and Machine Learning Engineers.

In my role as the Data Engineer on this project, I contributed to the data 
optimization efforts, facilitating easier access and utilization by the project's 
stakeholders


## Tools
 - pyspark





## Schema

root
 |-- ageofparticipant: long (nullable = true)
 |-- clinician: struct (nullable = true)
 |    |-- branch: string (nullable = true)
 |    |-- name: string (nullable = true)
 |    |-- role: string (nullable = true)
 |-- drug_used: string (nullable = true)
 |-- experimentenddate: string (nullable = true)
 |-- experimentstartdate: string (nullable = true)
 |-- noofhourspassedatfirstreaction: long (nullable = true)
 |-- result: struct (nullable = true)
 |    |-- conclusion: string (nullable = true)
 |    |-- sideeffectsonparticipant: string (nullable = true)
