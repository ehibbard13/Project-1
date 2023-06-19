# Parking Lot Data From 10 Largest US Cities
---

## Background

For our project, we decided to focus on parking lots in 10 of the biggest cities in the US. The data that  
we grabbed came from `Geoapify's` parking data. This included the cpacity, fee, type of parking, access type,   
and location for each parking lot. We pulled eached cities coordinates and plugged them into our API code and   
created a dataframe with all the cities parking lot data. From there, we created visuals to the questions that   
we came up with. At the end, we came up with a hypothesis and tested to see if it was true or not.

---

## Hypothesis : Does a city’s population affect the capacity of a parking lot?

*Alternative* : If a city’s population is related to the capacity of a parking lot, then a city with a higher   
density of people will have a parking lot with more capacity offered.

*Null* :  If a city’s population is not related to the capacity of a parking lot, then a city with a higher   
density of people will not offer more parking spaces per parking lot.

**Findings** : We pulled data from Atlanta (the smallest population) and Los Angeles (the biggest population)  
and preformed an Independent T-test. The `pvalue` came out to **0.15133837895751248**. This accepts the null and   
finds that there is no correlation between the population of a city and the capacity of their parking lots.

---

 ## Questions
 
 1. **Which parking type is most common (per city and overall)?**
    
    * Overall, the most common type of parking for all 10 cities is **public**(*'yes'*) parking.  

    * For each city, the most commmon parking type is...  
      **New York** : public  
      **Los Angeles** :  public  
      **Chicago** : public  
      **Houston** : customer's  
      **Fort Worth** : private  
      **Miami** : public  
      **Atlanta** : customer's  
      **Milwaukee** : public  
      **Philadelphia** : customer's  
      **Phoenix** : public  

![alt text][logo]

[logo] : https://github.com/ehibbard13/Project-1/blob/main/Project%201/Output/Parking_Type.png

  2. **What is the mean, median, and mode of parking capacity for each city?**
     **What are the potential outliers?**

     

