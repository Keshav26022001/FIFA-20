# FIFA-20
Machine Learning Project (Clustering)
## Problem Statement:
### 1) Prepare a complete data analysis report on the given data.

### 2) Explore football skills and cluster football players based on their attributes.

### 3) Prepare a rank ordered list of top 10 countries with most players. Whichcountries are producing the most footballers that play at this level?

### 4) Plot the distribution of overall rating vs. age of players. Interpret what is theage after which a player stops improving?

### 5) Which type of offensive players tends to get paid the most: the striker, theright-winger, or the left-winger?

## Steps Involved:
### 1) Importing Neccessary Libraries
i) numpy

ii) pandas

iii) matplotlib.pyplot

iv) seaborn

### 2) Basic Checks and Data Cleaning
i) Checking the number of rows and columns in the dataset

ii) Checking for the top and bottom entries of the dataset for overview.

iii) Checking for the null values in the dataset.

iv) Checking for the data.info() which gives the data types and other information.

v) Coverting some columns into numeric which must be numeric but due to some signs it's data type is object.

vi) Checking for the duplicates.

### 3) EDA
i) Descriptive Statistics 

ii) Checking for the prefered foot  choice by the players

iii) Checking for the unique values from the body type columns and replacing the misentries with the mode.

iv) Ploting the countplot of 'international_reputation', 'weak_foot', 'skill_moves', 'age', 'body_type', 'work_rate'.

v) Count Plot for Players Able to Play in Multiple Positions.

vi) In bivariate analysis checking relationship between some features using lineplot.

### 4) Players Comparison
i) Comparison between Messi and Cristiano Ronaldo

ii) Comparison between L. Suárez and Z. Ibrahimović

### 5) What is the Age after which a player stops improving?

### 6) Which type of offensive players tends to get paid the most: the striker, the right-winger, or the left-winger?

### 7) Which countries are producing the most footballers that play at this level?

### 8) Budget Analysis

### 9) Who are the youngest and oldest players?

### 10) Who are the most valued players?

### 11) Multivariate Analysis
Genearting the heatmap of the features

### 12) Data Preprocessing and Feature Engineering
i) Removing the unneccessary features

ii) Dealing with the missing values

iii) Encoding

iv) Feature Scaling (Standerdization)

v) PCA (Dimenssion Reduction)

### 13) Model Implementation
i) Elbow Tecnique to determine the optimal number of clusters.

ii) kneedle algoritm to confirm optimal number of clusters.

iii) K-Means implementation

iv) Cluster Visualization

### 14) Saving the model

### 15) Challenges Faced

## Key Findings:
### 1) Comparison between Messi and Cristiano Ronaldo
International Reputation:It is observed that both players have equal international reputation.

Value in Euros: Compared to Ronaldo, Messi has a higher value in euros.

Potential: Both players have nearly equal potential.

Overall: Both players have a nearly equal overall rating

Physic: It is observed that Ronaldo beats Messi in the physic rating.

Defending: It is observed that Messi has slightly better defense than Ronaldo.

Dribbling: It is observed that Messi has better dribbling skills than Ronaldo.

Passing: It is observed that Messi has better passing skills than Ronaldo.

Shooting: It is observed that Ronaldo is slightly better than Messi in shooting skills.

Pace: It is observed that Ronaldo has better pace than Messi.

Skill Moves: It is observed that both players are likely equal in skill moves, but Ronaldo has a slight edge.

Weak Foot: Both players have the same ability to use their weak foot.

### 2) Comparison between L. Suárez and Z. Ibrahimović
In each category except skill moves and weak foot, L. Suárez is better than Z. Ibrahimović, but they both still have the same international reputation.

### 3) What is the Age after which a player stops improving?
It is observed that after the age of 40, a player stops improving. It is also observed that there is a sudden peak after 40, but that may be due to chance.

### 4) Which type of offensive players tends to get paid the most: the striker, the right-winger, or the left-winger?
It is observed that, on average, Right-Winger players get paid more than Right-Winger and Striker players.

### 5) Which countries are producing the most footballers that play at this level?
England, Germany, Spain, France, Argentina, Brazil, Italy, Colombia, Japan, and Netherland these are top 10 countries who produces most football players.

### 6) Budget Analysis
#### i) Based on Overall Rating: 
Budget required per player based on overall rating is 48949074.074074075 Euros.

#### ii) Based on Potential:
Budget required per player based on potential is 24252921.348314606 Euros.

#### iii) Comparison:
Investing in a players with high potential is more cost effective.

#### iv) At which point does the budget not allow for significantly better players for the 11-men lineup?
A Budget that does not allow for significantly better players for lineup is 266782134.83146065 Euros.

### 7) Who are the youngest and oldest players?
The top youngest players with age 16 are:

i) A. Hložek	     

ii) Fábio Silva	 

iii) E. Millot	  

iv) S. Esposito	

v) A. Velasco	

The top oldest players with age 42 are:

i) C. Muñoz

ii) H. Sulaimani

### 8) Who are the most valued players?
The most valued players are:
i) Neymar Jr

ii) L. Messi

iii) K. Mbappe

iv) K. De Bruyne

v) E. Hazad

### 9) Optimal Number of Clusters are 3.

### 10) K-Means Clustering 
Silhouette Score: 0.4585379264203034

Davies-Bouldin Index: 0.8255499930544054

A Silhouette score of 0.4585 suggests that the clusters are reasonably well-defined.
A Davies-Bouldin score of 0.8255 suggests that the clusters are compact and well-separated. This is a good indication that the clustering algorithm has performed well in creating distinct clusters.










