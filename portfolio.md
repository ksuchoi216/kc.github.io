---
layout: portfolio
title: Portfolio
slug: /portfolio
items:
  # - category: Computer Vision
  #   title:
  #   image:
  #     src:
  #     alt:
  #   description:
  #   link:
  - category: Data Science
    subcategory: Computer Vision
    title: Unsupervised Face Clustering via Adversarial Variational Graph Auto-Encoder and Similarity Density
    image: 
      src: /assets/img/project/clu_face-image.png
      alt: dissertation
    description: these graph-based methods use label data for training models although face clustering is an unsupervised learning problem. Because of this, there still remains a need for an unsupervised learning method that can solve face clustering problems. In this regard, the aim of this study is unsupervised face clustering via adversarial variational graph auto-encoder(VGAE), which can be trained without label data. The adversarial VGAE makes use of latent information by using graph-structured data and can regularise latent infor- mation by a discriminator. Its decoder can achieve competitive performance on a link prediction task. By utilising the link prediction, the clusters of face images can be found.
    link: https://github.com/ksuchoi216/private-project/tree/master/face-clustering

  - category: Data Science
    subcategory: Computer Vision
    title: Developed CNN based objects classification model
    image:
      src: /assets/img/project/cls_moving-object.png
      alt: water
    description: 
      <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To classify lego blocks extracted from video. The lego part is moving objects because data form is video <br/>

      <i>Difficulties</i> <br/>
        &nbsp &nbsp - To get images from video <br/>
        &nbsp &nbsp - To distinguish objects from background <br/>
        &nbsp &nbsp - To create bounding boxes for objects <br/>
        &nbsp &nbsp - To classify objects <br/>

      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[OpenCV]</b></span> <b>extracted frames from video</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[OpenCV]</b></span> <b>used color tranfromation(hue color) for histogram</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[OpenCV]</b></span> <b>applied gaussian background subtraction with burring</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[OpenCV]</b></span> <b>applied bounding boxes</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[OpenCV]</b></span> <b>applied canny edge detection</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Keras]</b></span> <b>used CNNs</b> <br/>
    
    
  - category: Data Science
    subcategory: Computer Vision
    title: Improved accuracy of microscopy cell image regression
    image:
      src: /assets/img/project/reg_cell-image.png
      alt: sand
    description: 
      <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To develop a regression method for predicting the number of 6 different types of celss in a given microscopy image patch <br/>

      <i>Difficulties</i> <br/>
        &nbsp &nbsp - To extract features from cell images<br/>
        &nbsp &nbsp - To reduce dimensionality for regression <br/>
        &nbsp &nbsp - To find out proper model <br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[PyTouch]</b></span> <b>Customized CNN model by using pytorch</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Cuda]</b></span> <b>Used Cuda method of Pytorch for GPU running</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Sklearn]</b></span> <b>used PCA method</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Sklearn]</b></span> <b>used k-fold cross validation</b> <br/>
        
  - category: Data Science
    subcategory: Computer Vision
    title: Classification with PCA and oversampling
    image:
      src: /assets/img/project/cls_image-pca-oversampling.png
      alt: image-pca-oversampling
    description: <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To classify imbalanced images <br/>

      <i>Difficulties</i> <br/>
        &nbsp &nbsp - To handle imbalanced data <br/>
        &nbsp &nbsp - To reduce dimensionality without losing information<br/>
        &nbsp &nbsp - To tune hyperparameters of classification models<br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[sklearn]</b></span> <b>used PCA and scree graph</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[SMOTE]</b></span> <b>applied oversampling</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[sklearn]</b></span> <b>found proper hyperparameters by using GridSearch</b> <br/>

  - category: Data Science
    subcategory: NLP
    title: Developed emoji preprocessing with Bi-LSTM
    image:
      src: /assets/img/project/cls_tweet.png
      alt: sand
    description: 
      <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To classify sentiment about tweet(Tweet sentiment analysis) <br/>

      <i>Difficulties</i> <br/>
        &nbsp &nbsp - To do preprocessing for extracting information from tweets<br/>
        &nbsp &nbsp - To tranform emoji or other emotion expression(e.g.:()  <br/>
        &nbsp &nbsp - To select a proper model <br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Python]</b></span> <b>Used regular expression for customed preprocessing</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[NLP]</b></span> <b>applied constomed preprocessing for emotion information(including tokenization, removal of stopwords, lemmatisation)</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[sklearn]</b></span> <b>tried executing various models(Bi-LSTM, SVM, and Naive Bayes)</b> <br/>

  - category: Data Science
    subcategory: Machine Learning
    title: Analysed London air pollutants data by Linear regression and classification
    image:
      src: /assets/img/project/da_air-pollutant.png
      alt: air-pollutants
    description: 
      <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To analyse London air pollutants data <br/>

      <i>Difficulties</i> <br/>
        &nbsp &nbsp - To handle raw data provided by london data store<br/>
        &nbsp &nbsp - To do preprocessing for unclean data <br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Weka]</b></span> <b>used classification and regression models provided in Weka</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Report]</b></span> <b>wrote a data analysis report</b> <br/>

  - category: Data Science
    subcategory: Machine Learning
    title: Detection of live music with Spotify API
    image:
      src: /assets/img/project/cls_live-music.png
      alt: air-pollutants
    description: 
      <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To detect live music from non live music<br/>

      <i>Difficulties</i> <br/>
        &nbsp &nbsp - To receive audio data from spotify API<br/>
        &nbsp &nbsp - To transform audio file from time domain to frequency domain <br/>
        &nbsp &nbsp - To extract features from audio data<br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[xgb]</b></span> <b>applied XGBoost classifier</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[librosa]</b></span> <b>used audio handing library</b> <br/>

  - category: Computer Science
    subcategory: High Performance Computing
    title: Improved calculation performance of computational fluid dynamics(CFD)
    image:
      src: /assets/img/project/cs_parallelisation.png
      alt: parallelisation
    description:
      <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To speed up CFD calculation(based on C++)<br/>

      <i>Difficulties</i> <br/>
        &nbsp &nbsp - To find out where majority of running time is <br/>
        &nbsp &nbsp - To apply multiprocessing using multi threads and multi processors <br/>
        &nbsp &nbsp - To understand memory structures in C++<br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[OpenMP]</b></span> <b>used multi threads running </b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[MPI]</b></span> <b>used multi processors running</b> <br/>

  - category: Computer Science
    subcategory: UI/UX
    title: Improving UI/UX and analyzing UI/UX problems for Grocery Shopping Homepage
    image:
      src: /assets/img/project/cs_uiux.png
      alt: sand
    description: 
      <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To fix UI/UX problems <br/>

      <i>Difficulties</i> <br/>
        &nbsp &nbsp - To find out UI/UX problem accoding to Heuristic Evaludation(proposed Jakob Nielsen)<br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Javascript]</b></span> <b>used autocomplete API for reducing human errors</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Report]</b></span> <b>listed up UI/UX problems</b> <br/>

  - category: Computer Science
    subcategory: Full Stack
    title: Creating a Recipe page
    image:
      src: /assets/img/project/fs_landing-page.png
      alt: recipe
    description: <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To create a self introduction page<br/>

      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[html]</b></span> <b>used basic html functions and tags</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[css]</b></span> <b>used basic css functions</b> <br/>
        
  - category: Computer Science
    subcategory: Full Stack
    title: a sketchpad page using javascript
    image:
      src: /assets/img/project/fs_sketchpad.png
      alt: sketchpad
    description: <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To create a sketchpad page using html and javascript<br/>

      <i>Difficulties</i> <br/>
        &nbsp &nbsp - To handle events made by a user <br/>
        &nbsp &nbsp - To connect between html and javascript<br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Javascript]</b></span> <b>used eventhandler in Javascipt</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[css]</b></span> <b>added color change mode by using both css and javascript</b> <br/>
  - category: Computer Science
    subcategory: Full Stack
    title: Web Calculator
    image:
      src: /assets/img/project/fs_calculator.png
      alt: calculator
    description: <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To make a web calculator<br/>

      <i>Difficulties</i> <br/>
        &nbsp &nbsp - To handle javascript with event handlers<br/>
        &nbsp &nbsp - To use grid format<br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[css]</b></span> <b>used grid display for number buttons</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[javascript]</b></span> <b>used javascript eventhandlers</b> <br/>

  - category: Computer Science
    subcategory: Full Stack
    title: CV page
    image:
      src: /assets/img/project/fs_cv.png
      alt: cv
    description: <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To make a restaurant webpage <br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[npm]</b></span> <b>used npm package manager</b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[webpack]</b></span> <b>used webpack for bundling modules </b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Javascript]</b></span> <b>embedded video on the page</b> <br/>

  - category: Computer Science
    subcategory: Full Stack
    title: Memory Card Game
    image:
      src: /assets/img/project/fs_memory-card.png
      alt: 
    description: <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To  <br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Python]</b></span> <b></b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[NLP]</b></span> <b></b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[sklearn]</b></span> <b></b> <br/>
  - category: Computer Science
    subcategory: Full Stack
    title: Basic inventory page (Nodejs and MongoDB)
    image:
      src: /assets/img/project/fs_inventory.png
      alt: 
    description: <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To build a inventory page using Nodejs and MongoDB<br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Python]</b></span> <b></b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[NLP]</b></span> <b></b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[sklearn]</b></span> <b></b> <br/>

  - category: Computer Science
    subcategory: Full Stack
    title: Personal Hompage (React and Expressjs)
    image:
      src: /assets/img/project/fs_homepage.png
      alt: 
    description: <p>
      <i>Objective</i> <br/>
        &nbsp &nbsp To  <br/>
        
      <i>Methods</i>(with what I've learned)<br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Python]</b></span> <b></b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[NLP]</b></span> <b></b> <br/>
        &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[sklearn]</b></span> <b></b> <br/>

  # - category: Computer Science
  #   subcategory: Full Stack
  #   title: Page
  #   image:
  #     src: /assets/img/project/sand.png
  #     alt: sand
  #   description: <p>
  #     <i>Objective</i> <br/>
  #       &nbsp &nbsp To  <br/>

  #     <i>Difficulties</i> <br/>
  #       &nbsp &nbsp - To <br/>
  #       &nbsp &nbsp - To <br/>
  #       &nbsp &nbsp - To <br/>
        
  #     <i>Methods</i>(with what I've learned)<br/>
  #       &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[Python]</b></span> <b></b> <br/>
  #       &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[NLP]</b></span> <b></b> <br/>
  #       &nbsp &nbsp - <span style="color:MediumSeaGreen"><b>[sklearn]</b></span> <b></b> <br/>

---

This is my project page with belif explanation regarding what I did. <br />
If you want to know more about my project, please click "see more" link at each project description
<br />
