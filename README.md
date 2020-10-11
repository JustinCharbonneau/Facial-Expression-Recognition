[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/JustinCharbonneau/Smile-Detection/master?filepath=%2Fvoila%2Frender%2Fvoila_smile.ipynb)


Smile Detection 🙂 😐
==============================

A Computer Vision Project for the course of EBC6300 Affective and Persuasive Computing (Winter 2019).

What is affective computing?

>Affective computing is the study and development of systems and devices that can recognize, interpret, process, and simulate human affects. https://en.wikipedia.org/wiki/Affective_computing

# Introduction

For this project, the goal is to develop a binary image classifier using only 400 images (200 smiling and 200 neutral images). Here is a quick look at six images:

![Screen Shot 2020-03-09 at 1 59 02 PM](https://user-images.githubusercontent.com/25487881/76243133-3bc43500-620e-11ea-9917-be55e255c94f.png)

Part of the requirements for this project was to use 10-fold cross-valdiation.

# Project set-up

Create a new conda environment `smile`:

`conda env create -f environment.yml`

To update the environment (after modifying `environment.yml`):

`conda env update -f environment.yml`


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
