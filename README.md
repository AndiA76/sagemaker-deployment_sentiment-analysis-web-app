# sagemaker-deployment_sentiment-analysis-web-app
Simple example of a sentiment analysis deployed as web application using AWS sagemaker

## Overview
This little project from Udacity's nano-degree course "Deep-Learning" is about setting up and deploying a Sentiment Analysis Web Application for movie reviews using [Sagemaker](https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html) on Amazon Web Services (AWS). The Sentiment Analysis Web App is based on an XGBoost Pytorch model that is trained on labeled movie reviews from the [IMDb dataset](http://ai.stanford.edu/~amaas/data/sentiment/). It consists of movie reviews from the website [imdb.com](www.imdb.com), each labeled as either 'positive', if the reviewer enjoyed the film, or 'negative' otherwise.

    Maas, Andrew L., et al. Learning Word Vectors for Sentiment Analysis. In Proceedings of the 49th Annual Meeting of the  Association for Computational Linguistics: Human Language Technologies. Association for Computational Linguistics, 2011.

The project is broken down in subtasks as follows:

    Step 1: Downloading the data
    Step 2: Preparing and Processing the data
    Step 3: Upload the data to S3 (AWS storage)
    Step 4: Build and Train the PyTorch Model
    Step 5: Testing the model
    Step 6: Deploy the model for testing
    Step 7: Use the model for testing
    Step 6 (again): Deploy the model for the web app
    Step 7 (again): Use the model for the web
    Step 8: Deploying our web app

The project is implemented as a Jupyter notebook and can be found there: [Project notebook](SageMaker Project.ipynb)
