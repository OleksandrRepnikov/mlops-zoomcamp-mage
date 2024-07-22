Question 1. Run Mage
First, let's run Mage with Docker Compose. Follow the quick start guideline.

v0.9.72

Question 2. Creating a project
How many lines are in the created metadata.yaml file?

55 lines

Question 3. Creating a pipeline
Let's create an ingestion code block.

In this block, we will read the March 2023 Yellow taxi trips data.

How many records did we load?

3403766 rows x 19 columns

Question 4. Data preparation

Let's adjust it and apply to the data we loaded in question 3.

What's the size of the result?

3316216 rows x 20 columns

Question 5. Train a model
We will now train a linear regression model using the same code as in homework 1.

What's the intercept of the model?

24.77203445209766


Question 6. Register the model
The model is trained, so let's save it with MLFlow.



Find the logged model, and find MLModel file. What's the size of the model? (model_size_bytes field):

model_size_bytes: 4534
