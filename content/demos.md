---
title: "Demos"
date: 2018-09-30T14:54:20-07:00
draft: false
---

### Sentiment Analysis
[live](https://sentiment.erickramer.live), [code](https://github.com/erickramer/sentiment)

Rather than labeling text as simply "positive" or "negative", this project tags your text with emojis. This method allows for for dozens of different sentiments, while preserving some of the inherent ambiguity in language.

The app uses a recurrent neural network written in Python using Keras and Theano. The data visualization is built with d3.js. Flask and jQuery provide the communication between the python backend and the javascript front-end. Training data were collected from Twitter via their API.


### Object Recognition
[live](https://image.erickramer.live), [code](https://github.com/erickramer/image_recog)

Rapid advances have made deep learning accessible to everyone. Here, I use two well-known object recognition networks (VGG and MobileNet) to demonstrate object recognition in the browser. The app takes snapshots using your webcam and then returns the top-5 objects predicted by the model.

This app also uses deep learning implemented in Python using Keras and Theano. The javascript front-end uses jQuery.js and underscore.js. The backend uses Flask for serving the predictions from the model.

### Financial Modeling
[live](https://eransom.shinyapps.io/financial_planning/), [code](https://github.com/erickramer/financial_dashboard})

Planning for your financial future can be a daunting task. This app takes some of the guess work of this planning. It recommends an optimal allocation across retirement accounts and forecasts returns from your portfolio of stocks and bonds. The user specifies their expected income and their desired savings rate.

This app is written in R and C++. Stock forecasts use both R's statistical functions and custom C++ code written for the app. Data visualization is done with ggplot2 and vegalite. Interacting tables use HandsOnTable.js.
