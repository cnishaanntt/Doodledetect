# Doodle detector - Expecto Patronum

Celebrate the magic



## [Live Demo](https://pottercharm.herokuapp.com/)

![Doodle - detector - Expecto Patronum](https://github.com/cnishaanntt/Doodledetector/blob/master/demo.gif)



## To run locally


set your environment variables in the config file.

```

npm install

node index

```



Then open [`http://localhost:3000/`](http://localhost:3000/).

## Description
This is a serverless component consisting of:


- a google object detection api request and response
- a Lambda function, that processes that data and saves

- a Mongodburl, where all your data is stored.



Aside from this main functionality, its important features are:

- Written in Node.js

- Easily composable into your other app components




It's a Nuts & Bolts application component for AWS Serverless Application Repository.

The above shown demo contains integrating it with Visa and Walmart APIs,  however you could remove them if you wish by removing:
- the walmart.pug in www folder 
- security folder under server folder
- getPayment.js in server folder
- visaapiclient.js in server folder

## What it does

Doodle detector - inspired from Quick draw uses google object detection api: 

 A Child's world is full of fantasies and they expect great attention from their care takers. 
 At times they may not coommunicate their needs in an expressive way. 

Expecto Patronum - doodle detector comes to the rescue. 
It prompts for your email address initally, then 
it analyzes the kids drawings and matches with the best ones through google object detection api. 
Click the New button for drawing new doodles. 
Click on the '>' button to get the unique url to your email address. 
You could then track their drawings through the unique url sent to your email id. 
Once you decide to fulfill their wishes click on the magic spark/ flame icon. 
It takes you to the walmart page. 
You could then fulfill their wishes instantly. 

This makes the kids valued and overcome any obstacles quickly.
