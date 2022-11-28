# Healthcare Proffesionals in New Jersey and North Carolina

## Exploring County Heath Data

This is a repository contains datasets about public health in different counties in the United States of America. This repository is the final project for **Unit 3: writing in the natural sciences.**

This repository contains 1 python notebook, covering how to utilize the orginal county healthdata set, and visualizations created from the resulting subset. 


## Description of Datasets

The original set contains data regarding county health data for all 50 states in America. The data included was collected in 2014 and 2015. 
The new dataset contains data from North Carolina and New Jeresy. The series included are the healthcare proffesionals: **primary care physicians, dentists, mental health providers.** The steps described in **Process_Documentation1.ipynb** will get us from the original dataset to the new subset. 

## Accessing the Datasets

1. Have [Anaconda](https://www.anaconda.com) Installed. Anaconda is a distribution of Python and R, and we will be using Python to explore the data. 
2. Once you have [Anaconda](https://www.anaconda.com) installed, open [JuypterLab](https://jupyter.org). JuypterLab is located on the home screen of Anaconda, and JuypterLab should open in a web browser when you open the application. JuypterLab is a web-based development enviornment, where we will be entering code.
3. Download the original **CountyHealthData_2014-2015.csv** file onto your computer, and open it in your working directory in JuypterLab.

## Organization of Repository

This Data Repository contains the following files: 

* README.md
* Python_Lessons
  * README.md
  * Process_Documentation1.ipynb
* data
  * README.md
  * NC_NJ_subset.csv
  * CountyHealthData_2014-2015.csv
  * Visualization 1.jpg
  * Visualization 2.jpg

## Home State vs. Current State of Residence.

This repository was created to compare the access to health care proffesionals between New Jersey- my home state, and North Carolina- the state that I currently reside in. By using the steps descibed in the **Process_Documentation1.ipynb**, we manipulate the dataset to create a subset that makes this comparison more clear. 

An important note to consider is that North Carolina has a larger population compared to New Jersey. If we consider populations of each state from when the dataset was colleced (2014-2015), the population of North Carolina was 9.937 million, while the population of New Jersey was 8.867 million. Given this significant difference in population, it can be expected that North Carolina has more Health Care Proffesionals, as it has a larger population to serve. Viewers should keep in mind that the comparison explored in this repository is a raw comparison, and not a comparision with healt

## Visual Comparisons of Health Care Proffesionals

### Bar Graph Visualization
This visualization shows the number of primary care providers, mental health providers, and dentists in North Carolina and New Jersey. This visualization was created using the "NC_NJ_subset." This visualization clearly depicts that North Carolina has more primary care providers, mental health providers, and dentists than New Jersey. It is also evident that mental health providers are the most abundant health care providers in each state.

![Visualization 1B](https://user-images.githubusercontent.com/118193891/203074677-e2a99f6e-e561-456d-b362-2d4c561de470.jpg)

### Map Visualization
This visualization shows the total number of health care proffesionals by county in North Carolina and New Jersey. Total Healthcare proffesionals is the sum of **primary care providers, mental health providers, and dentists**. This visualization was created using the "NC_NJ_subset." In this map, the darkers shades of blue represent a high number of healthcare proffesionals, while the lighter shades of blue represent a low population of healthcare proffesionals. Compared to the previous visualization, this visualization provides a geographical understanding of where the most healthcare proffesionals are located in each state. Oftentimes, the darker colored counties are more urban counties with higher populations, while the lighter shaded counties are more rural with lower populations. 

![Visualization 2](https://user-images.githubusercontent.com/118193891/203073603-d8ccfcca-847e-41ba-b1af-78627c151e84.jpg)
