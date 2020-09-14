# Supervised Learning and Unsupervised Learning.

This repository contains the results and technical aspects of two notebooks 
## 1. Supervised Learning.
## Identify which individuals visiting our clients site are likely to click on her ad.
First notebook aims to  answer the following research question "A Kenyan entrepreneur has created an online cryptography course and would want to advertise it on her blog. She currently targets audiences originating from various countries. In the past, she ran ads to advertise a related course on the same blog and collected data in the process. She would now like to employ your services as a Data Science Consultant to help her identify which individuals are most likely to click on her ads. 


### Approach 1: Using Support Vector Machines (SVM).
We will use the Radial basis and linear methods to determine which customers are most likely to click on the ad. We will rate our models performance with its accuracy score.

### Approach 2: Using random forest. 
We will use the random forest model to challenge the first approach, we will rate this model against the SVM models and rank it. 

After modelling we will give our conclusions and recommendations.

# 2. Unsupervised learning.
## Customer clustering and finding cluster characteristics.
The second notebook aims to answer the following research question "Kira Plastinina is a Russian brand that is sold through a defunct chain of retail stores in Russia, Ukraine, Kazakhstan, Belarus, China, Philippines, and Armenia. The brand’s Sales and Marketing team would like to understand their customer’s behavior from data that they have collected over the past year. More specifically, they would like to learn the characteristics of customer groups."

### Approach 1: Using Kmeans clustering.
We will first determine the appropriate value of k, then run the kmeans clustering algorithm and finally plot a graph to display the different characteristics of various clusters.

### Approach 2: Challenging the model.
Using the Clvalid package we will find the most approapriate algorithm to use for our dataset, we will then challenge our first approach using this appropriate algorithm and aim to find better clustrers and characteristics.

## Getting Started.

To get a copy of this solution fork the repository. On the upper right there is a Fork button click on it, then after this is successfull click on git clone or download to get a local copy on you machine. 

## Overview.

This repository contains the technical aspects of Data Science Core IP submission week 13 as outlined above. The project applies the EDA techniques learnt as well as other coding techniques learnt in R. The notebook can be accessed above or through the [link](https://colab.research.google.com/drive/1U7tkWw247cgGzNoOkM6-Acnqzy3mGXih?usp=sharing) provided.

## Files in the Repository.

The repository contains the following files/folders:

    *license: MIT
    *google collab notebook 1: Week 13 of R_Analysis_Ad_click_Prediction.ipynb
    *google collab notebook 2: Week 13_Customer_Characteristics.ipynb
    *README: This README.

## Packages

The following packages are necessary to run the cells in notebook 1:

    DataExplorer
    tidyverse
    ggplot2
    data.table
    dplyr
    corrplot
    CatEncoders
    caret
    e1071
    kernlab
    randomForest
    countrycode
  
  The following packages are necessary to run the cells in notebook 2:
  
     DataExplorer
     tidyverse
     ggplot2
     dplyr
     corrplot
     fBasics
     gridExtra
     CatEncoders
     Factoextra
     farver
     ggiraphextra
     clValid
     kableExtra
    

### Prerequisites
1. A browser to access the google collabs.
2. Google collaboratory which can be accessed through the [link](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwius97P4tjpAhVwxoUKHU9jDQQQFjAAegQIBhAC&url=https%3A%2F%2Fcolab.research.google.com%2F&usg=AOvVaw3A5aPK2kLFzKOzb6sOckVw)


### Installing

Install a browser of your choice preferabbly google chrome.


## Built With

* [R version 3.6.3]- The R version used in collabs
* [Google Collabs](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwius97P4tjpAhVwxoUKHU9jDQQQFjAAegQIBhAC&url=https%3A%2F%2Fcolab.research.google.com%2F&usg=AOvVaw3A5aPK2kLFzKOzb6sOckVw) - google collabs notebook




## Authors

* **Antony Mwaura Ngige** - *Initial work* 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to my mentors and peers
* Inspiration
