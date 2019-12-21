# Lab 10B: Monitoring Data Drift

Changing trends in data over time can reduce the accuracy of the predictions made by a model. Monitoring for this *data drift* and retraining as necessary is an important way to ensure your machine learning solution continues to predict accurately.

## Before You Start

Before you start this lab, ensure that you have completed [Lab 1A](Lab01A.md) and [Lab 1B](Lab01B.md), which include tasks to create the Azure Machine Learning workspace and other resources used in this lab.

## Task 1: Monitor Data Drift for Datasets

In this task, you'll monitor datasets for data drift.

1. In [Azure Machine Learning studio](https://ml.azure.com), view the **Compute** page for your workspace; and on the **Compute Instances** tab, ensure your compute instance is running. If not, start it.
2. When the compute instance is running, click the **Jupyter** link to open the Jupyter home page in a new browser tab.
3. In the Jupyter home page, in the **DP-100** folder, open the **10B - Monitoring Data Drift.ipynb** notebook. Then read the notes in the notebook, running each code cell in turn.

> **Note**: If you have finished with the labs in this course, you might want to close all Jupyter tabs and **Stop** your compute instance to avoid incurring unnecessary costs. If you don't intend to work with your Azure Machine Learning workspace again, delete the resource group in which it is defined in your Azure subscription.
