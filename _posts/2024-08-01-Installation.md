---
title: Installation
author: Haosheng Wu
date: 2024-08-01
category: Jekyll
layout: post
---

In this workshop, we will use [Jupyter Notebook](https://jupyter.org/) as the interface to do the exercises. All the necessary materials (exercises, simulation data, numerical tools etc.) are already contained in a [Docker image](https://www.docker.com). The docker image contains everything, including the code, runtime, libraries, environment variables, configuration files, and dependencies. We use the Browser to acess the docker container which is a running instance of a docker image.

You may have a question that Why do we use this format for the workshop? The answer is:

Because it provides a consistent, isolated, and portable way for all participants. This reduces setup time, minimizes compatibility issues, and allows everyone to focus on the detailed physics and do not waste time on configure the setup of environment.

In this page, we provide the instructions about how to install the Docker and Vscode step by step both for **Windows** and **Mac**.

## For Windows:

### Step1: Install Docker

In the [Docker official website](https://www.docker.com/) download the Window version which is marked by red line as the following picture and then install the docker according to the instruction.<br>

![win_step1](/pex2024/assets/win_step1.png){: style="width: 60%;" }

***

### Step2: Download the pex2024 image in docker desktop

Run the docker program and then click the "Images" icon. In the search bar, type "pex2024" then you will see the corresponding image. Click the 'pull' botton to automatically install the corresponding image.<br>
This image contains all the necessary materials which are used for the hand-on sessions.<br> 

![win_step2](/pex2024/assets/win_step2.png){: style="width: 60%;" }

***
### Step3: Run the pex2024 image to create the container

As presented by the following picture, in the this step:<br>
1) In the 'Images', click the run botton which is an triangular '>' <br>
2) Use 8888 for 'Host port'.<br>

![win_step3](/pex2024/assets/win_step3.png){: style="width: 60%;" }

***
### Step4: Open the Launch the container.

As presented by the following picture, in the this step:<br>
Click the link will automatically opern the Jupyter Notebook in your Browser.<br>

![win_step4](/pex2024/assets/win_step4.png){: style="width: 60%;" }

***
### Step5: Stop the container

In **Containers**, if you haven't finished the exercise, you can pause the container by clicking **Stop**. You can **Start** the container again when you want to continue the exercise.

If you have finished the hands-on sessions, I suggest downloading the `*.ipynb` file to your local computer. Or converting it to the PDF format file.

You can also delete the current container and re-create a new one. The new container will return to the initial state, which means that if you didn’t save your `*.ipynb` file, it will be lost.

![win_step5](/pex2024/assets/win_step5.png){: style="width: 60%;" }
***


## For Mac:
The installations for Mac is similar to Windows, followings are the steps:<br>

### Step1: Install Docker

In the [Docker official website](https://www.docker.com/) download the correct Mac version according to your CPU, which is marked by red line as the following picture and then install the docker according to the instruction.<br>

![mac_step1](/pex2024/assets/mac_step1.png){: style="width: 60%;" }

***

***
**You can do the following steps by yourself or We can do the them together in the first time of hand-on session.**
***

### Step2: Download the pex2024 image in docker desktop
Run the docker program and then click the "Images" icon. In the search bar, type "pex2024" then you will see the corresponding image. Click the 'pull' botton to automatically install the corresponding image.<br>
This image contains all the necessary materials which are used for the hand-on sessions.<br>

![mac_step2](/pex2024/assets/mac_step2.png){: style="width: 60%;" }

***
### Step3-Step5 are the same as the Steps in Windows.