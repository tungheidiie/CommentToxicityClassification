# CommentToxicity

### Build an RNN model to classify comment toxicity, including toxic, severe_toxic, obscene, threat, insult, and identity_hate. The data is obtained from https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/data.

### 1. The initial training data is as follows:
![image](https://github.com/tungheidiie/CommentToxicityClassification/assets/170008056/18e2ba18-b6be-471d-9e1e-6d19ec98bcef)

### 2. Split the data into 70% train and 30% validation.

### 3. After the data is encoded through TextVectorization. The RNN model is constructed as follows:
![image](https://github.com/tungheidiie/CommentToxicityClassification/assets/170008056/c85f8fc6-dc75-4166-95e1-537a2bbf9bcc)

### 4. After training with one epoch:
![image](https://github.com/tungheidiie/CommentToxicityClassification/assets/170008056/bf48d464-c97d-4cbd-b984-3836112553be)

### 5. Testing with the test data:
![image](https://github.com/tungheidiie/CommentToxicityClassification/assets/170008056/bae48035-4e65-4f31-ab7f-ac0b6baee590)

### 6. Testing with a text sample gives the result:
![image](https://github.com/tungheidiie/CommentToxicityClassification/assets/170008056/ff8960ff-591a-46e6-9618-e95781220ffd)

### 7. Save the model to a file: cmt_toxicity.keras
