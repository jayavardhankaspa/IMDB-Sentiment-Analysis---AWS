# IMDB-Sentiment-Analysis-AWS
IMDB sentiment Analysis model developed as part of Udacity's AWS Machine Learning Engineering Nano Degree.

* Project developed as part of the Nano degree
* **Environment** – AWS
* **Technologies** – AWS Lambda, SageMaker, API Gateway, Pytorch and basic HTML and CSS
*	**Algorithm** - LSTM Classifier
* **Accuracy** - 80%

## The following are the items developed into the source repository of the course work for project completion:

* Completing the build_dict() function in the Feature_Extraction_Training notbook, for creating the dictionary using the vocabulary of the training dataset
  * idnetifying the most frequent words and encoding the text data into numerical values
* Implimenting method to train Pytorch model using the following approach and implimenting the ZOLS in the train method of the file train/train/py
  * Z -> zero_grad()
  * O -> output (preds)
  * L -> loss
  * S -> optimizer.step()
 * Deploying PyTorch model on an AWS Instance
 * Preprocessing the input text data from the web app and formating the model prediction output into the required format in the file serve/predict.py
 * Completing the model deployment with integration of AWS Lambda and API gateway serices
