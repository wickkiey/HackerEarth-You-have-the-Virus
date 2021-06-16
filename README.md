# Predict if a user is infected with virus


Chatbots have proven success in handling massive surges in call volume that the contact centers are witnessing globally during this pandemic. The reasons why chatbot technologies are being used is clear: 

* Promises consistency in all customer interactions
* Deploys immediate information irrespective of the time
* Enables instant scalability to meet demand spikes
* Handles huge query spikes in a timely and consistent manner.
* A series of other companies have also started implementing pandemic-specific chatbots for answering questions coming in from their concerned customers.

## Task
Your task is to predict whether a user is infected with the coronavirus based on the conversations between the user and the chatbot.

## Data description
The dataset folder contains the following files:

The trainConversation folder: Contains 4900 .json files that represent the conversations between each user and the chatbot
The testConversation folder: Contains 2100 .json files that represent the conversations between each user and the chatbot
train.csv: 4900 x 2
test.csv: 2100 x 1
sample_submission.csv: 5 x 2
The columns provided in the dataset are as follows:


|  Column name      | Description |
| ----------- | ----------- |
| userID      | Represents a unique user identification number       |
| Prediction   | Represents whether a user is infected with the coronavirus        |


## Evaluation metric
score = 100 x metrics.f1_score(actual, predicted)


Try-Out the problem 

https://www.hackerearth.com/problem/machine-learning/predict-if-a-user-is-infected-with-virus-23-b0b6e3c3/