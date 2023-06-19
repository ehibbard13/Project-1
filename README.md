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

![alt text](https://github.com/ehibbard13/Project-1/blob/main/Project%201/Output/Parking_Type.png)



  2. **What is the mean, median, and mode of parking capacity for each city?**  

     | **City**    | **Mean**  | **Median** | **Mode** |
     |:-----------:|:---------:|:----------:|:--------:|
     | New York    | 231.090909 | 166.0	    | 140.0    |
     | Chicago     | 472.500000	| 217.5     | 299.0    |
     | Los Angeles	| 174.866667 | 127.0     | 35.0     |
     | Phoenix     | 758.000000 | 758.0     | 1400.0   |
     | Milwaukee   | 404.718750 | 257.5     | 444.0    |
     | Houston     | 481.500000 | 375.0     | 1155.0   |
     | Philadelphia| 293.777778 | 280.0     | 403.0    |
     | Atlanta     | 453.666667 | 550.0     | 611.0    |

     **What are the potential outliers?**
     
       * **New York's** *potential outliers are* -60.0 : 444.0  
       * **Chicago's** *potential outliers are* -480.75 : 993.25  
       * **Los Angeles's** *potential outliers are* -332.5 : 647.5  
       * **Phoenix's** *potential outliers are* -526.0 : 2042.0  
       * **Milwaukee's** *potential outliers are* -447.75 : 1116.25  
       * **Houston's** *potential outliers are* -886.25 : 1843.75  
       * **Philadelphia's** *potential outliers are* -100.5 : 631.5  
       * **Atlanta's** *potential outliers are* 66.75 : 888.75  
         
![alt text](https://github.com/ehibbard13/Project-1/blob/main/Project%201/Output/Capacity_BoxPlot.png)

<img width="966" alt="Screenshot 2023-06-19 at 4 34 53 PM" src="https://github.com/ehibbard13/Project-1/assets/130424499/36245dc8-2825-452c-bd8d-bce807ac4d4d">
