# Lab 6B: Publishing a Pipeline

After you've created a pipeline, you can publish a REST endpoint through which the pipeline can be initiated. This enables you to run the pipeline on-demand or at scheduled times.

## Before You Start

Before you start this lab, ensure that you have completed [Lab 1A](Lab01A.md) and [Lab 1B](Lab01B.md), which include tasks to create the Azure Machine Learning workspace and other resources used in this lab; and [Lab 6A](Lab06A.md) in which you create the pipeline you will publish in this lab.

## Task 1: Publish a Pipeline

In this task, you'll create a pipeline to train and register a model.

1. In [Azure Machine Learning studio](https://ml.azure.com), view the **Compute** page for your workspace; and on the **Compute Instances** tab, ensure your compute instance is running. If not, start it.
2. When the compute instance is running, click the **Jupyter** link to open the Jupyter home page in a new browser tab.
3. In the Jupyter home page, in the **DP-100** folder, open the **06B - Publishing a Pipeline.ipynb** notebook. Then read the notes in the notebook, running each code cell in turn.

> **Note**: If you intend to continue straight to the [next exercise](Lab07A.md), leave your compute instance running. If you're taking a break, you might want to close all Jupyter tabs and **Stop** your compute instance to avoid incurring unnecessary costs.
