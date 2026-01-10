# Image Labels Generator

## 🌟 Overview

In this project, I developed an image labeling generator using Amazon Rekognition. The application processes an input image and identifies objects within it by assigning relevant labels, such as detecting whether a person in the image is a woman or a man.


## ☁️ AWS Architecture
### 🛠️ Services used
* Amazon S3: For storing the images in the process of generating labels.
* Amazon Rekognition: To analyse images and generate image labels.
* AWS CLI: Interacting with AWS services through command line interface(CLI).


### Architecture Diagram
![alt text](architect-diagram.png)

### Below is the image I uploaded to Amazon S3
![alt text](downtown-atlanta.jpg)

### In order to use the aws cli, I had to create a secret access key via Amazon IAM, then configure my command line to use the users credentials

## &rarr; Final Result
### Here is the image with labels after Amazon Rekognition processed the image<br/>
![alt text](downtown-atlanta-with-detection-labels.png)

## 🛠️ Learnings and Challenges
### This project was very simple to implement. I did not run into any issue during development.
