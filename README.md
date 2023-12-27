## Analysis of Treatment Quality and Efficiency of Hospitals


In this project I tried to analyse the treatment quality and efficiency of hospitals using different machine learning algorithms.


First of all I must tell you about the dataset

<img width="720" alt="image" src="https://github.com/Hitesh2112/Analysis-of-Treatment-Quality-and-Efficiency-of-Hospitals/assets/97521900/a270ed43-e3af-4507-bab8-961256638766">


Number of columns/attributes = 13
1. Health Service Area
2. Hospital County
3. Operating Certificate Number
4. Facility ID
5. Age Group
6. Length of Stay
7. Type of Admission
8. Patient Disposition
9. CCS Procedure Description
10. APR Severity of Illness Code
11. APR Risk of Mortality
12. Source of Payment 1
13. Total Costs



Dataset looks like :

<img width="556" alt="image" src="https://github.com/Hitesh2112/Analysis-of-Treatment-Quality-and-Efficiency-of-Hospitals/assets/97521900/3917f1b5-f4a9-49d2-af49-16d453c41516">


Droping some non important attributes (columns)

Drop "Total Costs" :


<img width="305" alt="image" src="https://github.com/Hitesh2112/Analysis-of-Treatment-Quality-and-Efficiency-of-Hospitals/assets/97521900/37e6b31f-4bea-4c42-a649-632a4f8d4c17">


Drop "Hospital County" : 

<img width="289" alt="image" src="https://github.com/Hitesh2112/Analysis-of-Treatment-Quality-and-Efficiency-of-Hospitals/assets/97521900/6b459f9a-cc56-4b9d-8fb0-b7701832b09b">


Drop "Operating Certificate Number" : 

<img width="356" alt="image" src="https://github.com/Hitesh2112/Analysis-of-Treatment-Quality-and-Efficiency-of-Hospitals/assets/97521900/5f226b35-9e8f-49be-becc-f8448979623d">



Checking for NULL values and its cleaning

<img width="473" alt="image" src="https://github.com/Hitesh2112/Analysis-of-Treatment-Quality-and-Efficiency-of-Hospitals/assets/97521900/d0172c4b-7af6-4ed9-b339-2125ce47a4b0">



Dataset (data frame) shape after cleaning of data : 


<img width="101" alt="image" src="https://github.com/Hitesh2112/Analysis-of-Treatment-Quality-and-Efficiency-of-Hospitals/assets/97521900/45aa31ba-e540-4e00-93ea-7f44b8b9e1ca">



Encoding of all attributes having string data ,using LabelEncoder


<img width="301" alt="image" src="https://github.com/Hitesh2112/Analysis-of-Treatment-Quality-and-Efficiency-of-Hospitals/assets/97521900/fbe92d54-72a9-4e3b-9b37-31a1afec9330">



### Modelling

splitting dataset into training and testing dataset :

<img width="389" alt="image" src="https://github.com/Hitesh2112/Analysis-of-Treatment-Quality-and-Efficiency-of-Hospitals/assets/97521900/8408e21b-60aa-4ed6-911f-8e1035c777da">



Training using Logistic Regression : 

<img width="391" alt="image" src="https://github.com/Hitesh2112/Analysis-of-Treatment-Quality-and-Efficiency-of-Hospitals/assets/97521900/b8f6e5bc-5c73-412b-80a4-712cdca5a681">


Similarly we trained the dataset on different machine learning models / algorithms such as Linear regression, Logistic Regression, Decision Trees, Random Forest, Naive bayes, Support vector machines, K nearest neighbours, and we also trained it on Neural networks

## At the Conclusion : we can see that we can achive the maximum accuracy of 97.4 % on training set and 88.5 % on test set using Random Forest Classifier ,AND We also got a very good accuracy of 97.4 on training set and 87.9 % on test set using Decision Trees
