# JobChangesofDataScientists

In this project, I processed the data about Data Scientist profiles to reach reasonable conclusions about their probability of job changes. The data includes several features such as city, gender, education level, experience etc. Here is the [reference](https://www.kaggle.com/arashnic/hr-analytics-job-change-of-data-scientists) to the data.


I modeled the system as an artifical neural network. To fit the data into the model, I applied:  
* Normalization to numeric data
* One hot encoding to strings  

Then I built the neural network and explored the best parameters for training to reach most accurate results. I analyzed the changes in:  
* Number of layers
* Number of nodes
* Batch size
* Epochs
* Activation functions
