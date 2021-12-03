# Neural_Network_Charity_Analysis

## Overview of Analysis
Using Machine Learning and Neural Networks build a binary classifier to predict if an applicant will be successful if funded by Alphabet Soup. Then adjust the model to get 75% accuracy score of the model.

## Resources 
Data Source
  - charity_data.csv
Tools
  - Libraries used in Jupyter Notebooks
    - sklearn
    - pandas
    - tenserflow

## Results
### Data Preprocessing
- The purpose of the model is to provide prediction if application is successfuly so the "IS_SUCCESSFUL" is the target outcome. 
- Took out Name and EIN as these are not related to the success of the applicant. The rest of the columns will be considered X features to keep all the data included. 
### Compiling, Training, and Evaluating the Model
- I was not able to raise the accuracy score to about 75% but did raise the accuracy score from 72.5% to 73.5%.
- I tried to increase nuerons and layers and then finally change the function of the second layer to sigmoid to get the highest Accuracy Score of 73.5
![png](https://github.com/LauraHaq/Neural_Network_Charity_Analysis/blob/main/v3hidden_layers.png)
![png](https://github.com/LauraHaq/Neural_Network_Charity_Analysis/blob/main/v3accuracy_score.png)
As I increased the number of nuerons the accuracy score increased slightly, however when I added the third layer it raised even slighty more. The reason I countinued to increase the number of nuerons was due to trial and error of while increasing the number the accuracy score also increased. I chose to add a layer the third version because increasing nuerons had not raised it as much as I wanted. 
## Summary
I was not able to achieve the 75%. I would reccomend to start over going through the preprocessing the of data to find X features of high importance to the model. Then use those for a nueral network as one example of rethinking x features for the model. Also, I would use more trial and error of number of nuerons and hidden layers because I was able to increase the score and think in five to six more attmepts I would have gotten there. 
