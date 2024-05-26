---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, La Trobe University, 2023
  * Thesis title: Person Detection and Tracking in Dense Team Sports Scenes
  * Description: I designed tracking algorithms for team sports such as Hockey, Netball,    Volleyball etc. In addition, I developed models for team action recognition using players pose data. During my PhD, I obtained vast experience of training and experimenting with different neural network model which includes Convolutional neural networks, Recurrent Neural Networks, Transformer and many more. This PhD was funded by Australian Institute of Sport.
* M.Sc. in Information and Communication Engineering Islamic University, Kushtia, Bangladesh, 2012
  * Thesis Title: Improvement of Hijacking Problem for Multi-Target Tracking with Particle Filter
  * Result: 3.57 out of 4.00 (1st Place-out of 40 students)
* M.Sc. in Information and Communication Engineering Islamic University, Kushtia, Bangladesh, 2011
  * Project: Improved Eye Detection and Iris Center Tracking with Eyelashes Occlusion Correction
  * Result: 3.52 out of 4.00 (1st Place-out of 40 students)

Work experience
======
* Machine Learning Engineer, Dynamic Crowd Measurement, AU, 2022-2023
  * Developed a 2-dimensional lidar based crowd counting solution that can count people and their direction in live setup. These solutions were deployed in major events like Dutch grand prix, Melbourne Cup, Moto grand prix etc.
  * Developed a real-time CCTV camera based people counting solution in jetson nano edge device.
  * Developed a multi-modal sentiment prediction system that takes CCTV camera feed, social feed (i.e twitter stream) and weather data as input to a transformer backbone architecture and predicts crowd sentiments of an event. The Sydney Olympic Park Authority has implemented this system to monitor crowd sentiment during and post-events, with a project valued at $1.056 million. (project details)
  * Improved and deployed AI model for different crowd measurement task (e.g. crowd density, flow and sentiment) in different events.
  * Trained, tested, validated computer vision-based CNN models and deployed those model using docker in AWS cloud/on-premise setup with maintaining MLOps best practices (e.g. model and data version management through S3, model serving, model monitoring and retraining etc).
  * Designed python SDK based kafka consumer-producer along with AWS MKS for asynchronous data streaming.
  * Performed causal inference analysis on crowd data for better understanding of crowd behaviour. 
  * Supervise junior engineers and review their PR requests.

* Data Scientist, Additive Assurance, AU, 2021-2022
  * Evaluate the latest neural network model and engage in research aimed at enhancing the performance of defect segmentation in 3D printer layer images, with a specific focus on 3D printed bones.
  * Conduct defect annotation of 3D printed images and train the model using annotated data
  * Working with other team members to develop and deploy code.

* Lecturer, Dept. of Computer Science, Bangladesh University of Business & Technology, BD, 2016-2018
  * Prepare lectures for courses and conduct classes (e.g. Neural Network, C++, Computer Graphics, Discrete Mathematics etc).
  * Evaluate exam papers and supervise undergraduate student in their projects.
  * Participate in academic and its relevant meetings.

  
Technical Skills
======

* Progragramming Language, Libraries and tech stacks
  * Python, C++, PostgresSQL, NoSQL, OpenCV, Numpy, Pandas, CausalML, scikit-learn, APIs
* Model training, experiment and deployment tools
  * PyTorch, Pytorch lightning, Tensorflow, CUDA for training, ONNX runtime model optimisation
  * Llama 2, Langchan, CNN and RNN models, Transormers
* Cloud and Distributed computing
  * AWS and GCP distributed computing
  * Boto3 SDK for python, EKS, ECS, Sagemakers, Fargate, Lambda, EC2, VPC, S3, IAM, Secret Manager, MSK, Cloudwatch etc.  
  * Kubernetes (Deployment, Auto scaling, Load Balancing), Apache Kafka, Cassandra, Snowflakes
* Workflow and package management
  * Docker, Kubeflow, MLflow, github action and bitbucket CI/CD pipeline, argflow, jenkins
* Extensive research and industry background of training Convolutional Neural Network (CNN) and Transformers across various tasks such as image classification. people tracking, eye tracking, segmentation, action recognition, multitask modeling, multimodal learning, text classification etc.
* Experienced in designing MLOps pipeline for model training, serving, monitoring, managing data drift, automated retraining.
* Proficient in diverse data science and machine learning tasks, including data analysis, causal inference, regression, k-mean clustering, Boosting algorithms etc.

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
