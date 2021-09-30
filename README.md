# Google-review-rating
In this project i had been provided the data that contain category of google reviews  by different user . I used K-means clustering to cluster the reviews that will help marketing team to target right audience 

# Loading the dataset
loading the data that is in csv format 

# ** Summary of data**
>> checking the datatypes and no.of columns and rows  

# Investigating the outliers 
while checking outliers i found out that there are no such outliers

# Investigating the null values 
treating null values by filling median

# Standardise the data 
it consist changing values of dataset in standard form that mean between 0 and 1

## Applying PCA (Principal Component Analysis)
array([4.71954707, 3.49434357, 1.84977447, 1.59793926, 1.26458958,
       1.1424795 , 1.06855466, 0.99582162, 0.78408477, 0.71399843,
       0.64134171, 0.60520409, 0.57894001, 0.51684111, 0.51026615,
       0.46622654, 0.4439419 , 0.43867521, 0.42937891, 0.400506
       81,
       0.37397659, 0.34723147, 0.33014007, 0.29059614])
       _choosing the number of components upto where eigen value get closer to the 1_
       
       


### Running clusters into for loop between in range of 1,8 to get a fine cluster point


![graph](https://user-images.githubusercontent.com/87512268/135421528-b3aba5aa-10c6-4b03-ab06-82d9741e3361.png)


after running the loop i have choosen the cluster on the basis of cuts in the graphs 


## Run model on different cluster 
i ran the model on different clusters i.e 4,5,6

### Visulization of groups at different clusters

I visualised the group at different cluster and determined the most precise cluster 




![image](https://user-images.githubusercontent.com/87512268/135413331-5e7dd00b-c58c-43bd-81c7-b2ec12731de0.png)


       
