---
description: >-
  AutoAI automatically analyzes your data and generates candidate model
  pipelines customized for your predictive modeling problem.
---

# Step 2: Build and train the model

### 1.1 Specify basic model details

1. From the Assets page of your project in Watson Studio, click **Add to project** and choose **AutoAI EXPERIMENT**.

![add to project auto ai](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/auto_ai.png)

2. In the page that opens, fill in the basic fields:

* Specify a name and optional description for your new model. 

![Define autoai](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/create_auto_ai.png)

* Confirm that the **IBM Watson Machine Learning Service** instance that you associated with your project is selected in the Machine Learning Service section.

![Watson ML](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/WML_create.png)

3. Click **Create**.

![Create Model](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/auto_ai_createWML.png)

### 1.2 Add training data

Upload the training data file, GoSales.csv, from your local computer by dragging the file onto the data panel or by clicking browse and then following the prompts.

### 1.3 Train the model

1. Choose IS\_TENT as the column to predict. AutoAI analyzes your data and determines that the IS\_TENT column contains True/False information, making this data suitable for a binary classification model. The default metric for a binary classification is ROC/AUC.

![Choosing a prediction column ](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/auto_ai_train_data.png)

2. Click **Run experiment**. As the model trains, you will see an infographic that shows the process of building the pipelines.

![Building model pipelines](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/run_autoai.png)

For a list of estimators available with each machine learning technique in AutoAI, see: AutoAI implementation detail

### 1.4 Choose a pipeline

Once the pipeline creation is complete, you can view and compare the ranked pipelines in a leaderboard.

![Pipeline leaderboard](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/pipeline.png)

Choose **Save model** from the action menu for Pipeline 1. This saves the pipeline as a Machine Learning asset in your project.

