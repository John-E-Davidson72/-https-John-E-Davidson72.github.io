---
layout: page
title: Projects
permalink: /projects/
---
----

## New Machine Learning Project

Can't say much about this one right now! - Building this around some existing web resources, will leverage learnings from
chapter 1 of [this book](https://www.amazon.co.uk/Hands-Machine-Learning-Scikit-Learn-TensorFlow/dp/1492032646/ref=asc_df_1492032646/?tag=googshopuk-21&linkCode=df0&hvadid=375498709181&hvpos=&hvnetw=g&hvrand=8546052863628994399&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1007293&hvtargid=pla-523968811896&psc=1&th=1&psc=1&tag=&ref=&adgrpid=76471991426&hvpone=&hvptwo=&hvadid=375498709181&hvpos=&hvnetw=g&hvrand=8546052863628994399&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1007293&hvtargid=pla-523968811896) (classic regression model should be a great fit) although I need to overcome a labelling challenge first. 

Have already built some Flask scaffolding to support the MVP app, getting a bit ahead of myself here but effort expended on this now will help later on in the
production phase.  There is even some JS creeping into the project - [this is a great JS reference for any Pythonista](https://realpython.com/python-vs-javascript/).

Currently working with Jupyter, Pandas & Scikit-learn, checking for any statistical significance before progressing to ML model selection phase.

I've also got some other work to do for this one:

* Implement CI / CD pipeline
* Prep for Docker deployment

----

## Forecastr

![Forecastr]({{ site.baseurl }}/images/Forecastr-web.png "Forecastr")

Was interested to see if I could hook up a Flask app with a couple of the main Python sci libraries.  I do a lot of work around market sizing and
product validation so decided a forecast P&L would be a good target.  Went back to basics to start - used numpy to do the back end calcs and matplotlib
to deliver a simple visual.  You can check out the repo [here](https://github.com/John-E-Davidson72/Forecastr-MVP) and the MVP app [here](https://johndavidson.eu.pythonanywhere.com/).  

Need to give [pythonanywhere](https://eu.pythonanywhere.com/) a shout here - their free tier is great for quick deployments of Python apps - also great for on-the-fly tweaks post deployment.

Have some plans for this app;

* Build out - add WTForms, CSRF, persistence layer + login / sessions / user management
* Add extra functionality - currency selection + add other app modules such as ROI calculation
* Improve UX - enhance chart interactivity with Plotly or similar framework

----

## Py-Decom

![Py-Decom]({{ site.baseurl }}/images/Py-Decom-web.png "Py-Decom")

This was the first project I tackled back in 2019 after returning to coding (I started my career in the tech industry - too long ago to talk about!).  
Working in the energy industry (specifically decommissioning) - I have to process & analyse a lot of regulatory data and reports.  This gets really
tedious so decided to use my early Python learnings to automate things - this is what I did to speed things up;

* Web scrape all relevant reports (used Beautiful Soup)
* Convert / flatten to fully searchable format i.e. text (PDFMiner)
* Build a search function & persist search data for later analysis
* Open all relevant reports with a single click
* Extract all well labels (main area of interest)

Built this into a GUI and packaged things up with PyInstaller (clunky!) - then distributed packaged app to users - not the best solution but didn't have
web dev skills back then.  Got some plans for this one too (I still use it!);

* Port to Flask framework
* Integrate proper DB schema
* Leverage natural language classifier to allow context-based searches - either through API or library
* Experiment with text tagging, chunking, phrase extraction & named entity recognition
* Build in search analytics
* Make UI a lot nicer

Repo [here](https://github.com/John-E-Davidson72/python-decom-2).  If you would like the packaged app drop me a line.


