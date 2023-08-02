# New_York_City_Airbnb
Dataset from Kaggle 
"New York City Airbnb Open Data"
link: https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data?datasetId=268833&sortBy=voteCount

Hello 

Exploring Pandas Library and finding outliers and removing them from a dataframe using  IQR method.

1)What is a outlier?
 An Outlier is a data-item/object that deviates significantly from the rest of the (so-called normal)objects.
 They can be caused by measurement or execution errors. The analysis for outlier detection is referred to as outlier mining.
 
2)what is IQR method?
  IQR method involves the following steps:
  Step 1:find Quartile 1 (Q1=25 percentile)
  Step 2:find Quartile 3 (Q3=75 percentile)
  step 3:find IQR 
         IQR=Q3-Q1
  
  step 4:find lower filter limit 
		lower_limit=Q1-1.5*IQR
  
  step 5:find upper filter limit 
		upper_limit=Q3-1.5*IQR
		
  Step 6:then filter out values on basis of the lower limit and upper limit.
  
  
