# Codefundo-2018-

# Problem statement: 
Find better ways to save lives and prevent economic losses through mechanisms to predict, prevent, or manage the impact of natural disasters.

# Our idea

## Phase 1: Collection and scraping of data
 
  The first part of the peoject will deal with collecting data from various sources and perform exploratory data analysis on them.
  There are various open source data sources related to natural disasters, some of them being www.data.world, wwww.catalog.data.gov, www.preventionweb.net, etc.
  The next step will be to perform exploratory data analysis on the aquired data.
  
  ### Exploratory Data Analysis
  
  The datasets obtained will have several columns of information and performing EDA on these datasets to gather an intuition as to what data columns give most correlation to the disaster in concern.
  Such EDA will be conducted using techniques like Hypothesis Tests, Confirmatory Statistics, Interval Estimates.
  Python, along with libraries like Pandas, Numpy and Scipy will be used for this part.
  
## Phase 2: Deep Learning/Machine learning

  The next step will be to first identify the best deep learning/machine learning framework for this task. We will experiment between several frameworks like neural networks for deep learning, CNN, RCNN, and SVM for machine learning. A combination of both supervised and unsupervised learning will be performed.
  Our model will then effectively predict whether the natural disaster will occur and also the estimated survival rate.
  
## Phase 3: Post-disaster management

   The problem doesn't end at just prediction of a disaster. 
   We will deploy an algorithm that will assess the data aquired from phase 1 and effectively allow post-disaster management techniques like evacuation, determining potential safe zones, etc.
   
Hence our overall project will basically have the following dataflow:
  1. Gathering, cleaning and performing EDA on data to make sense of open source datasets on natural disasters.
  2. Deploying a deep learning/machine learning framework to essentially predict the occurence (when and where) of a disaster.
  3. Deploying an algorithm for evacuation based on the location and evacuation routes and capacities of such evacuation routes using the data obtained from Phase 1.
  
  
  
Contributors: Parth Dave, Souradeep Chakraborty.
              BITS Pilani, KK Birla Goa Campus.
