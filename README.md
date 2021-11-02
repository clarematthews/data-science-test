### Introduction

Wearable activity trackers that collect data 24 hours a day, 7 days a
week, have become more and more popular to monitor physical activity,
Heart Rate (HR) and sleep quality. The combination of this kind of data
enables the development of tools that can predict the users’ well being.
These data can be greatly beneficial to the scientific community because
they can contribute to research in several fields, enabling the
assessment of the relations between physical, psychological and
physiological characteristics.

This assignment makes use of data from a publicly available dataset.
Multilevel Monitoring of Activity and Sleep in Healthy people (MMASH)
dataset provides 24 hours of continuous beat-to-beat heart data,
triaxial accelerometer data, sleep quality, physical activity and
psychological characteristics (i.e., anxiety status, stress events and
emotions) for 22 healthy participants. Moreover, saliva bio-markers
(i.e.cortisol and melatonin) and activity log were also provided in this
dataset. The MMASH dataset will enable researchers to test the
correlations between physical activity, sleep quality, and psychological
characteristics.

Detailed description of the dataset is accessible here:
<https://doi.org/10.13026/cerq-fc86>  
Rossi, A., Da Pozzo, E., Menicagli, D., Tremolanti, C., Priami, C.,
Sirbu, A., Clifton, D., Martini, C., & Morelli, D. (2020). Multilevel
Monitoring of Activity and Sleep in Healthy People (version 1.0.0).
PhysioNet

For more information please refer to the related publication: Rossi, A.,
Da Pozzo, E., Menicagli, D., Tremolanti, C., Priami, C., Sirbu, A.,
Clifton, D., Martini, C., & Morelli, D. (2020). A Public Dataset of 24-h
Multi-Levels Psycho-Physiological Responses in Young Healthy Adults.
Data, 5(4), 91. <https://doi.org/10.3390/data5040091>

### Review criteria

1.  Code for reading in the dataset and processing the data
2.  Required plots and results
3.  All of the code needed to reproduce the results (numbers, plots,
    etc) in the report

### Assignment

#### Instructions

This assignment will be described in multiple parts. You will need to
write a short report that answers the questions detailed below.
For example, you could complete the entire assignment in a
**R markdown** document that can be processed by knitr and be
transformed into an HTML or PDF file, or in a **Jupyter Notebook**.

Throughout your report make sure you always include the code that you
used to generate the output you present. When writing code chunks in an
R markdown document, always use **echo = TRUE** so that someone else
will be able to read the code.

For the plotting aspects of this assignment, feel free to use any
plotting system e.g. base, lattice, ggplot2 in R, or matplotlib, seaborn, pandas in Python.

Fork/clone this GitHub repository. 

NOTE: The GitHub repository also contains the dataset for the assignment
so you do not have to download the data separately.

#### Questions

##### **Loading and processing the data**

Show any code that is needed to:

1.  Load the data (i.e. read.csv()).
2.  Explore the data.
3.  Clean/process/transform the data (if necessary) into a format
    suitable for your analysis. In particular, any non-physiological
    Heart Rate (HR) (i.e. HR \< 30 bpm) should be removed.

##### **Q1. Mean total number of steps taken per day**

1.  Calculate the total number of steps taken per day per subject.
2.  Make a barplot of the mean total number of daily steps per subject. Which
    subject has the highest mean total number of steps?
3.  Calculate and report the population mean and median of the total
    number of steps taken per day.

##### **Q2. Daily average heart rate pattern of subject 15**

1.  Calculate the average of heart rate in hourly intervals for subject
    15 across all days (in R, the function `hms::round_hms()` can be useful).

2.  Make a time series plot of the hourly intervals (x-axis) and the average heart rate, averaged across all days (y-axis).

3.  At what time does the peak in the daily average heart rate occur?

##### **Q3. Descriptive statistics of the questionnaires scores**

Provide a summary (mean, min, max and median) of the questionnaires
scores.

##### **Q4. Correlation between questionnaires scores and participant characteristics**

Is there any correlation between the participants’ characteristics and
their questionnaires’ scores?

### Submit your assignment

To submit the assignment, email the final report containing the codes, results and output figures. 

