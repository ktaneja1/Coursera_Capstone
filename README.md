# Coursera Capstone Write-up Week 4
Link to github project: https://github.com/ktaneja1/Coursera_Capstone/blob/main/Capstone_Week3.ipynb

Link to Notebook: https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/501cc0b3-4687-4511-8752-e74a66761af4/view?access_token=7a5b7b73b33d62c59211643cb4fc3bd5be16d4f89fca8331049fb00a32e59c42

# Business Problem
* Introduction where you discuss the business problem and who would be interested in this project.
With interest rates at an all time low, there are many buyers looking for houses, including many young adults who will be first time home owners who may not be familiar with the area. The purpose of this project is to provide new homeowners with information on the points of interest that are in the neighborhoods, so that they know what neighborhoods they would be interested in buying into. This project will be limited Ontario, Canada. 


# Data
I will also be using the following dataset from this page: https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M 
to get information on the postal codes in Ontario. 

I will also be using the Foursquare API to get data on the different attractions in each neighborhood


# Methodology

## Exploratory Data Analysis
I used created a map of the neighborhoods I was given to see where they are geographically. 
I also found out what the most common venues are in each neighborhood

## Machine Learning
I used K means clustering to cluster neighborhoods based on what type of venues are avaiable in that area. This will allow the homeowner to limit their search based on what venues they are interested in. 

## Results/ Recommendations
I discovered a cluster where the most common venue is playground and another cluster (Cluster # 1) where the most common venue is coffee shop (Cluster #2). 
If there are homeowners who are interested in being outdoors, then they could proritize their search within the neighborhoods in cluster 1- North York, East York, and York. If there are homeowners who enjoy coffee shops, then they can proritize their search within cluster 2- North York, Downtown Toronto, Etobicoke.  



