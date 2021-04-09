## From Big Data to Good Data
Instead of getting more training data to enhance accuracy, it is better for us to enhance the quality of data, especially for small data problems.

Note that big data problems where there's a long tail of rare events in the input(web search, self-driving case, recommender systems) are also small data problems.
## From Model-centric to Data-centric
### Making it systematic - iteratively improving the data:
* Train a model
* Error analysis to identify the types of data the algorithm does poorly on(e.g., speech with car noise)
* Either get more of that data via data augmentation, data generation or data collection(change input x) or give more consistent definition for labels if they were found to be ambiguous(change label y)
* During deployment, monitor the performance and flow new data back for continuous retrain/update of model.
