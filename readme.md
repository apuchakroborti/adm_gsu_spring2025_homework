# Advanced Data Mining - Homework Repository

This repository contains the homework submissions for the Advanced Data Mining course offered at Georgia State University during Spring 2025.

## Overview

The course involved three major homework assignments, each targeting different aspects of data mining:

- Homework 1: Focused on addressing class imbalance problems using various classification algorithms and evaluation techniques.

- Homework 2: Covered the measurement of interestingness in patterns and the evaluation of association rules.

- Homework 3: Involved classification tasks using time series data, applying appropriate models and preprocessing techniques.

Each assignment folder contains source code, documentation, and datasets (where applicable).

## Contact

For any questions or clarifications, feel free to reach out via email or open an issue in the repository.

## Setup anaconda environment
# Setup Instructions for ADM Homeworks

Follow the steps below to set up your environment for the ADM Homework 1, 2, or 3 project.
## 1. Install Anaconda

Download the Anaconda installer for macOS from the official site:  
➡️ [https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html)

Open a terminal and navigate to the directory where the installer is downloaded:
$ cd /path/to/download
$ bash Anaconda*.sh

Follow the prompts and agree to the license terms when asked:
Do you accept the license terms? [yes|no]
> yes

At the end of the installation, confirm with:
> yes

## 2. Prevent Conda from Auto-Activating on Startup (Optional)
If you don’t want Conda to activate the base environment automatically on terminal startup:
$ conda config --set auto_activate_base false

## 3. Add Conda to Environment Variables
Edit your shell configuration file (`.zshrc` for zsh):
$ vi ~/.zshrc
or for linux
$ vi ~/.bashrc
Add the following line at the end:
export PATH="/Users/apukumarchakroborti/anaconda3/bin:$PATH"

Save and close the file (`:wq!`) and then reload it:
$ source ~/.zshrc
or
$ source ~/.bashrc

## 4. Create and Activate Conda Environment
$ conda create --name adm_homework1
or
$ conda create --name adm_homework2
or
$ conda create --name adm_homework3

$ conda activate adm_homework1
or
$ conda activate adm_homework2
or
$ conda activate adm_homework3

## 5. Launch Jupyter Notebook

Navigate to your desired working directory:

$ cd /path/to/conda_adm_projects
$ mkdir adm_homework1
or
$ mkdir adm_homework2
or
$ mkdir adm_homework3

$ cd adm_homework1
or
$ cd adm_homework2
or
$ cd adm_homework3

$ jupyter notebook

This will open the Jupyter interface in your default browser, where you can begin your homework.
