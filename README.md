# Winning Space Race With Data Science
IBM-applied-DataScience-CApstone-Project

## Problem statement:

SpaceX is successful because rocket launches are relatively cheap. SpaceX advertises on its website that the Falcon 9 rocket will cost $62 million to launch. Other vendors cost over $165 million each, with much of the savings coming from being able to reuse SpaceX's first stage. So if we can determine if the first stage will land, we can determine the cost of launch. Spaces X's Falcon 9 launches like a normal rocket. He has three phases in rocket launch. The payload is sealed within the fairing. The second stage, or second stage, helps get the payload into orbit, but most of the work is done in the first stage. This stage does most of the work and is much larger than the second stage. This tier is very large and expensive. Unlike other rocket vendors, SpaceX's Falcon 9 can retrieve the first stage. Sometimes the first stage does not land. It crashes sometimes. In other cases, SpaceX will sacrifice the first stage based on mission parameters such as payload, trajectory, and customers.

In this project, you assume the role of Data, his scientist who works for Space Y, a new rocket company that wants to compete with Space X, founded by billionaire businessman Aron Musk. My job is to set a price for each launch. To do this, we collected information about SpaceX and created a dashboard for the team. It also decided whether SpaceX would reuse the first stage. Instead of using rocket science to determine if the first stage will land successfully, train a machine learning model and use public information to predict whether SpaceX will recycle the first stage Did. 



## The objective:
 The objective is very clear. The feasibility of a new Space Y company competing with Space X needs to be evaluated. 

## Preferred answer:
The best way to estimate the total launch cost is to predict the successful landing of the first stage rocket. Where is the best place to start? 


## Methodology:
1.  Data collection from two sources – i) SpaceX API and ii) web scraping from Wikiepdia
2. Data Wrangling - Collected data has been enriched by creating landing result labels based on feature aggregation and post-analysis result data

3. EDA with SQL and visualization

4. Interactive visual analysis by creating dashboards

5. Predictive Analytics with Machine Learning Using Classification Models – The data collected up to this step is normalized and split into training and test datasets    and run on four different classification models (logistic regression, support vector models, decision trees). , and the K-nearest neighbor method). The accuracy of    each model is evaluated using various parameter combinations. 


## Result: 

- All algorithms provide the same level of accuracy, so they all work practically the same.
- A machine learning model can be used to predict whether a competitor's first stage will end up at curacy 83.3.
- Smaller payloads have a higher landing success rate than larger and heavier payloads.
- The launch site with the highest success rate is the KSC LC-39A.
- spaceX's success rate increases over time.  
![image](https://github.com/bastianastudillo98/IBM-Data_Science-SpaceX/assets/131790631/c12501e4-4fbc-4ca3-b845-9bd0bfd65444)
