# Lab 1B: Working with Azure Machine Learning Tools

In this lab, you will explore various tools for working with an Azure Machine Learning workspace.

## Before You Start

Before starting this lab, you must have created an Azure Machine Learning workspace by following the instructions in the [previous lab](Lab01A.md).

## Task 1: Use the Azure ML SDK in a Notebook VM

You can perform most asset management tasks to set up your environment in the *Studio* interface, but it's also important to be able to script configuration tasks to make them easier to repeat and automate.

1. In Azure Machine Learning studio, on the **Compute** page, view the **Notebook VMs** tab, and if necessary, wait until the Notebook VM you created in the previous lab has started. Then click its **Jupyter** link to open Jupyter Notebooks on the VM.
2. In the notebook environment, create a new **Terminal**, and in the **Users** folder, run the following command:

    ```bash
    git clone https://github.com/MicrosoftLearning/DP-100
    ```

3. After the command has completed, close the terminal and view the home folder in your notebook file explorer - it should contain an **DP-100** folder, containing the files you will use in the rest of this lab.
4. In the **/DP-100** folder, open the **01Ba - Setting up Your Environment.ipynb** notebook.
5. Read the notes in the notebook, running each code cell in turn.

## Task 2: Use the Azure ML SDK in Visual Studio Code

Notebook VMs in Azure Machine Learning provide an easy to manage Python environment for working with Azure ML. However, sometimes you may want to use your own graphical Python development environment, such as Microsoft Visual Studio Code.

> **Note**: In this course, we'll use Visual Studio Online to simplify installation, but the principles of using the Azure Machine Learning SDK are the same in any Python environment.

1. Steps to setup VSO go here!

> **Note**: If you intend to continue straight to the [next exercise](Lab02A.md), leave your Notebook VM running. If you're taking a break, you might want to close the Jupyter tabs and **Stop** your Notebook VM to avoid incurring unnecessary costs.
