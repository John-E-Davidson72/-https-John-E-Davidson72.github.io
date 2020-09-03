---
layout: page
title: Projects
permalink: /projects/
---
----

## New Machine Learning Project

Can't say much about this one right now! - Building this around some existing web resources, will leverage learnings from
chapter 1 of [this book](https://www.amazon.co.uk/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646/ref=asc_df_1492032646/?tag=googshopuk-21&linkCode=df0&hvadid=375498709181&hvpos=&hvnetw=g&hvrand=8546052863628994399&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1007293&hvtargid=pla-523968811896&psc=1&th=1&psc=1&tag=&ref=&adgrpid=76471991426&hvpone=&hvptwo=&hvadid=375498709181&hvpos=&hvnetw=g&hvrand=8546052863628994399&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1007293&hvtargid=pla-523968811896) (classic regression model should be a great fit) although I need to overcome the labelling challenge first. 

Have already built some Flask scaffolding to support the MVP app, getting a bit ahead of myself here but effort expended on this now will help later on in the
production phase.  There is even some JS creeping into the project - [this is a great JS reference for any Pythonista](https://realpython.com/python-vs-javascript/).

Currently doing all the usual Jupyter, Pandas & Scikit-learn data wrangling & checking for statistical significance before ML implementation phase.  

----

## Forecastr

![Forecastr]({{ site.baseurl }}/images/forecastr.png "Forecastr")

Was interested to see if I could hook up a Flask app with a couple of the main Python sci libraries.  I do a lot of work around market sizing and
product validation so decided a forecast P&L would be a good target.  Went back to basics to start - used numpy to do the back end calcs and matplotlib
to deliver a simple visual.  You can check out the repo [here](https://github.com/John-E-Davidson72/Forecastr-MVP) and the MVP app [here](https://johndavidson.eu.pythonanywhere.com/).  

Need to give [pythonanywhere](https://eu.pythonanywhere.com/) a shout here - their free tier is great for quick deployments of Python apps - also great for on-the-fly tweaks post deployment.

Have some plans for this one;

* Build out - add WTForms, CSRF, persistence layer + login / sessions / user management
* Add extra functionality - currency selection + more app modules such as ROI calculation
* Make single page app
* Improve UX - enhance chart interactivity with Plotly or similar framework

----

## Py-Decom

This was the first project I tackled back in 2019 after returning to coding (I started my career in the tech industry - too long ago to talk about!).  
Currently I work in the energy industry (specifically decommissioning) - 
