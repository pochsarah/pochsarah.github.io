---
title: Internship
layout: page
---

<div style="text-align: justify">This internship took place in the EO Analytics research team, a team belonging to Paris-Lodron Universität Salzburg (PLUS)  and the Sen2Cube.at project. My supervisors were Professors Dirk Tiede and Martin Sudmanns. The duration of the internship and the number of working hours was as follow : 20
hours per week (part-time) during May and June 2022, 40h (full time) during July 2022 and
1 month as contractor in September 2022. </div>

## Technical report 

<div style="text-align: justify">The goal of my internship was to implement a mobile application in order to access and query the Sen2Cube.at data cube. This austrian datacube already have a user interface (UI) through a website Sen2Cube.at. For this new UI, the mobile app, the user should be able to query the Austrian factbase about its current location and download information, such as curve, in a CSV file. The initial assumption is that the user of the product already knows the Sen2Cube.at web application and is familiar with its use.</div>
<div style="text-align: justify">My taks to achieve were : - get use to the datacube, - make a list of the functionnalities
needed, - choosing a framework to build the application and learning the language attached to it, - implementing the different functionnalities.</div>

<div style="text-align: justify">The required functionnalities to deploy the first version of this app were : </div>

* Basic and easy-to-use interface.
* Safe log in
* Selection of the parameter (Area of Interest, time interval, a knowledgebase model)
* Starting an inference
* Visualization of the inference details and results
* Access to account parameters
* Access to online manual
* Choosing different basemap
* Downloading the current inference results
* Log out

<div style="text-align: justify">And the further functionnalities :</div>

* Access to previous inferences
* Research bar for choosing a location
* Access to contact page
* Access to factbase metadata
* Factbase status (linked to previous point)
* Choosing another factbase
* Resizing the buffer zone


<div style="text-align: justify">The user will use the mobile application on its phone, independently from its operating system. The mobile application needs to run on different operating systems, such as Android and iOS. For fulfilling this condition, the mobile application has been developed as a hybrid single-page application and an internet connection will be needed. The mobile application, as the web application, will be mostly implemented in JavaScript (JS). The JS framework used will be Angular (JS, CSS, HTML) and the UI toolkit Ionic will also be used. The mobile application needs to be easy to use with a simple interface. As the user already has an experience with the web application, the design needs to have similarity with the web application design.</div>

### Results

<div style="text-align: justify">After achieving the 3 first task described earlier, I tried the implement the functionnalities listed before. The tasks done are : - having a basic and easy-to-use interface, which keep the same style as the website, - having the capability to log in and log out, with the KeyCloack package, thesame solution than the website use, - selecting the tree main paramater to run the inference, with geolocation in the case of the area of interest, - having access to online manual (the one online explaining how to use the data cube and a "quick start" button to use the mobile application, - choosing different basemap with Leaflet, having acces to user informations. My "on-going" tasks at this end of the internship, were : - retrieving metadata and previous inferences informations, - Starting a inference.</div>
	
<div style="text-align: justify">My major difficulties were for the authentication and retrieving data via HTTP requests.</div>

### Recommendations

<div style="text-align: justify">My general recommendations about internship are to not stay stuck in only one field of study (or location) in your intership research. Also, asking questions for not staying stuck on the same obstacle to long.</div>