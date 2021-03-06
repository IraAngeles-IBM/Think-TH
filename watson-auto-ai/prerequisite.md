# Step 1: Watson Service Creation
Create Watson Service in IBM Cloud and download sample data.

### Create Watson Studio Service

![Create Watson Studio Service](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/create_watson_studio.png)

### Create a project in Watson Studio

1. Start by creating a project

![Create Project in Watson Studio](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/ws_create_project.png)

2. Project creation details

![Create Project Details](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/watson_studio_create.png)

### Sample data

Download the sample training data file to your local computer from here: [gosales.csv](https://raw.githubusercontent.com/IraAngeles-IBM/Think-TH/master/.gitbook/assets/gosales.csv)

The sample data is structured: in rows and columns, and saved in a .csv file.

You can view the sample data file in a text editor or spreadsheet program:

![Preview of training data](https://github.com/IraAngeles-IBM/WatsonAutoAi/raw/master/sample_data.png)

**Feature columns**

Feature columns are columns that contain the attributes on which the machine learning model will base predictions. In this historical data, there are four feature columns:

* GENDER: Customer gender
* AGE: Customer age
* MARITAL\_STATUS: “Married”, “Single”, or “Unspecified”
* PROFESSION: General category of the customer’s profession, such “Hospitality” or “Sales”, or simply “Other”

**What do you want to predict?**

You will be asked to choose the column label representing the values your model will predict.

In this tutorial, the label column is the IS\_TENT column:

* IS\_TENT: Whether or not the customer bought a tent

The model built in this tutorial will predict whether a given customer is likely to purchase a tent.

### Steps overview

This tutorial presents the basic steps for building and training a machine learning model using model builder in Watson Studio:

1. [Build and train the model](step-1-build-and-train-the-model.md)
2. [Deploy the trained model](step-2-deploy-the-trained-model.md)
3. [Test the deployed model](step-3-test-the-deployed-model.md)

