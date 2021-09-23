# ML_Covid_Detection
Based on patients answers and the results of real covid-19 test we would like to establish which combination of symptoms will tell us that someone has corona or not. Our hypothesis is that there is link between symptoms data and the result of real covid-19 test and there is a way to calculate that value.

## Description
In this year a big pandemic has hit us, the covid-19 virus. It has changed our lives, also it took many lives
sadly. Covid-19 also known as SARS-CoV-2 is a contagious respiratory virus that first reported in Wuhan,
China. The virus was spreading fast. Most people infected with covid-19 experience mild to moderate
illness and recover without requiring special treatment. People with high risk are older people and
those with underlying medical problems like cardiovascular disease, diabetes, chronic respiratory
disease, cancer and they are more likely to develop serious illness.

Our database contains 5400+ records, which are made of records in which they asked a potential covid19 infected person what symptoms they have. The dataset has 21 features and some of them are
breathing problems, fever, dry cough, sore throat, running nose, headache and others.

Our problem is based on supervised learning and we will teach our algorithm that based on yes/no
answers to tell us if some has potentially corona virus. From a set of 5400 examples we will take 30% of
the data and set it aside for our test data on which we will evaluate it as the final test set. The rest of the
data will be split in train set and validation set. The division will be done randomly.
The goal of our algorithm is to decide if someone has or has not corona virus, so this will be a
classification task. This is a medical trail and our goal is to include all patients that are sick which means
we want high recall. The worst thing that can happen to us is that we classify a positive person as
negative which is False Negative, and we want to avoid that.

## Getting Started

### Dependencies

* python 3.8, pandas, numpy, matplotlib, sklearn, seaborn, xgboost

### Installing

* You can download the project folder

### Executing program

* Code can be run in any python IDE


