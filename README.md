![logo](https://github.com/Venom19990/Customer-Segmentation/blob/main/github-header-image%20(3).png)


# CASE STUDY / PROBLEM STATEMENT: 
  A Business owner owns a Mall and wants to increase his Sales in order to generate profitable Revenue for there store's respected Products.
  APPROACH :
    We will use the information / Data of the Customers from the Mall's Database In order to design Marketing Strategies to increase Sales.
    
# Life-Cycle Of The Project :
   
    Data Collection / Gathering.
    Data Pre-processing.
    Model Selection. 
    Selection of Parameters / Variables.
    Training the Model.
    Visualisation of the Model.
  
# Algorithm Used :
    Clustering Algorithm -: K-Means Algorithm.
    The Case Study Statement is an ideal example of clustering problem in which we can form groups/clusters 
    of the customers based on the parameters for which the model is designed.
    
    
# Libraries Includes :
    Numpy,
    Pandas,
    MatplotLib and Sea-Born (sns) for Visualisation,
    Scikit-Learn
    K-means()
    
# Working :
    We decided to visualise this Model on the Parameters such as 'Annual Income' and 'Spending score' of the Customers 
    to form different Clusters.
    
    How to find the Ideal Number of Clusters?
  Solution : By using the Elbow-Point-Graph Method, as we observe the Graph carefully we can see that there is no sudden drop in the line from the number of cluster 
  range 4 to 6, We observe a linear decline. So, we took a business decision of having 5 clusters for our Visualisation.
  
  
   <img align="center" alt="coding" width="650" src="https://github.com/Venom19990/Customer-Segmentation/blob/main/Screenshot%20(532).png">
   
   
 Customers Visualisation into 5 Clusters :
 
  <img align="center" alt="coding" width="650" src="https://github.com/Venom19990/Customer-Segmentation/blob/main/Screenshot%20(530).png">
                      
        Explaination : 
          1) Cluster 1 (BLUE) ==> Contains Customers Having LOW Annual Income with LOW Spending Score.
          2) Cluster 2 (PURPLE) ==> Contains Customers Having LOW Annual Income with HIGH Spending Score.
          3) Cluster 3 (RED) ==> Contains Cusomers Having AVERAGE Annual Income and Spending Score.
          4) Cluster 4 (GREEN) ==> Contains Customers Having HIGH Annual Income with LOW Spending Score.
          5) Cluster 5 (YELLOW) ==> Contains Customers Having HIGH Annual Income and HIGH Spending Score.
  
# Conclusion :
      
        As we can observe Customers into different clusters based on there spending scores and annual income
        So, Marketing Business Decision can be implemented in order to increase sales of products and Customer Retention rate 
        based on customer's Ability to spend along with there income.
  
  
  
  
