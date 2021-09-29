# Google-review-rating
In this project i had been provided the data that contain category of google reviews  by different user . I used K-means clustering to cluster the reviews that will help marketing team to target right audience 
# investigating the outliers , there are no such outliers
checking outliers 

count	mean	std	min	50%	90%	95%	97%	99%	max
Category 1	5456.0	1.455720	0.827604	0.00	1.340	2.380	2.6400	3.6600	5.0000	5.00
Category 2	5456.0	2.319707	1.421438	0.00	1.905	5.000	5.0000	5.0000	5.0000	5.00
Category 3	5456.0	2.489331	1.247815	0.00	2.060	5.000	5.0000	5.0000	5.0000	5.00
Category 4	5456.0	2.796886	1.309159	0.83	2.460	5.000	5.0000	5.0000	5.0000	5.00
Category 5	5456.0	2.958941	1.339056	1.12	2.670	5.000	5.0000	5.0000	5.0000	5.00
Category 6	5456.0	2.893490	1.282400	1.11	2.680	5.000	5.0000	5.0000	5.0000	5.00
Category 7	5456.0	3.351395	1.413492	1.12	3.230	5.000	5.0000	5.0000	5.0000	5.00
Category 8	5456.0	2.540795	1.111391	0.86	2.170	4.140	5.0000	5.0000	5.0000	5.00
Category 9	5456.0	3.126019	1.356802	0.84	2.800	5.000	5.0000	5.0000	5.0000	5.00
Category 10	5456.0	2.832729	1.307665	0.81	2.680	5.000	5.0000	5.0000	5.0000	5.00
Category 12	5455.0	2.078339	1.249208	0.78	1.690	5.000	5.0000	5.0000	5.0000	5.00
Category 13	5456.0	2.125511	1.406542	0.77	1.610	5.000	5.0000	5.0000	5.0000	5.00
Category 14	5456.0	2.190861	1.576686	0.76	1.490	5.000	5.0000	5.0000	5.0000	5.00
Category 15	5456.0	2.206573	1.715961	0.00	1.330	5.000	5.0000	5.0000	5.0000	5.00
Category 16	5456.0	1.192801	1.107005	0.00	0.800	1.760	5.0000	5.0000	5.0000	5.00
Category 17	5456.0	0.949203	0.973536	0.00	0.740	1.410	3.0125	5.0000	5.0000	5.00
Category 18	5456.0	0.822414	0.947911	0.00	0.690	1.350	2.4300	5.0000	5.0000	5.00
Category 19	5456.0	0.969811	1.203972	0.00	0.690	2.280	5.0000	5.0000	5.0000	5.00
Category 20	5456.0	1.000071	1.193891	0.00	0.690	2.315	5.0000	5.0000	5.0000	5.00
Category 21	5456.0	0.965838	0.929853	0.00	0.760	1.550	2.6300	4.4000	5.0000	5.00
Category 22	5456.0	1.750537	1.598734	0.00	1.030	5.000	5.0000	5.0000	5.0000	5.00
Category 23	5456.0	1.531453	1.316889	0.00	1.070	4.310	5.0000	5.0000	5.0000	5.00
Category 24	5455.0	1.560755	1.171756	0.00	1.290	3.072	5.0000	5.0000	5.0000	5.00



### investigating the null values 
treating null values by filling median

# STANDARDIASE THE DATA
it consist changing values of dataset in standard form that mean between 0 and 1

## applying PCA
array([4.71954707, 3.49434357, 1.84977447, 1.59793926, 1.26458958,
       1.1424795 , 1.06855466, 0.99582162, 0.78408477, 0.71399843,
       0.64134171, 0.60520409, 0.57894001, 0.51684111, 0.51026615,
       0.46622654, 0.4439419 , 0.43867521, 0.42937891, 0.400506
       81,
       0.37397659, 0.34723147, 0.33014007, 0.29059614])
       _choosing components until  where eigen value get close to the 1_
       
       


### running clusters into for loop between in range of 1,8 to get a fine cluster point

after running the loop i have choosen the cluster on the basis of cuts in the graphs 


## run model on different cluster 
i ran the model on different clusters i.e 4,5,6

### visulization of groups at different clusters

i visualise the group in different categories and determined the most precise cluster 




       
