
# Indian Paper Curreny Classification :india: 

## Table of Content
  * [Overview](#overview)
  * [Motivation](#motivation)
  * [Technical Aspect](#technical-aspect)


## Overview
This project aims to uncover correlations between variables and pinpoint influential factors contributing to the risk of high cholesterol development in individuals. 
Through rigorous exploration and statistical examination, the study seeks to shed light on key determinants that play a crucial role in understanding and assessing the risk factors associated with elevated cholesterol levels.

## Motivation
What could be a perfect way to utilize unfortunate lockdown period? Like most of you, I spend my time in cooking, Netflix, coding and reading some latest research papers on weekends. The idea of classifying indian currency struck to me when I was browsing through some research papers. 

## Technical Aspect
This project is divided into two part:
1. Training a deep learning model using Keras. (_Not covered in this repo. I'll update the link here once I make it public._)
2. Building and hosting a Flask web app on Heroku.
    - A user can choose image from a device or capture it using a pre-built camera.
    - Used __Amazon S3 Bucket__ to store the uploaded image and classification.
    - Used __CSRF Token__ to protect against CSRF attacks.
    - Used __Sentry__ to catch the exception on the back-end.
    - After uploading the image, the classifications are displayed on a __Bar Chart__.

