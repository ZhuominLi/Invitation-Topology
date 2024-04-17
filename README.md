# Project to Track the Chain of Invitationship and Visualize the Chain by Networkx Library

## 1 Problem Background & Data Structure
- Most of time in real world business, we would face the original data of invitationship like blow
  
<img width="240" alt="image" src="https://github.com/ZhuominLi/Invitation-Topology/assets/73721315/d71c6b26-4b30-425e-9b08-1c5643826f6d">

- Logically, the invitationships could be unwinded as chains graphs
  
<img width="378" alt="image" src="https://github.com/ZhuominLi/Invitation-Topology/assets/73721315/87efb68d-6859-46cf-b8fc-89854e1ebf8d">

- But usually these chains could be very long and hard to keep tracking on or visualizing, so this project try to use tree structures to save topological information of invitaionship and visualise each connection by networkx

## 2 Visualization 

### 2.1 Result of data processing
<img width="656" alt="image" src="https://github.com/ZhuominLi/Invitation-Topology/assets/73721315/b40b9f44-81b4-481a-9c83-e9709a3ea48d">

- The data has been parsed into a dictionary format and searched using the Depth-First Search (DFS) algorithm to form 322 structural trees. The largest tree contains 200 nodes distributed across 16 levels.

- select the biggest one to show the graph of connection

###  2.2 Sample of biggest chain

![image](https://github.com/ZhuominLi/Invitation-Topology/assets/73721315/6f388ae7-7723-4b00-b4c8-7796fa58baea)

### 2.3 Delve into the longest chain

![image](https://github.com/ZhuominLi/Invitation-Topology/assets/73721315/3076ace4-b71d-45fc-90ca-03a5ec7ea5d5)

### 2.4 Save topological features as dataframe

<img width="249" alt="image" src="https://github.com/ZhuominLi/Invitation-Topology/assets/73721315/82175a81-187f-42a4-bcef-f25fb2eff40f">


- When dealing with large datasets, utilizing dataframes presents an ideal method for showcasing topological features in real business life


