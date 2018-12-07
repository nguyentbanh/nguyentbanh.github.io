---
layout: project
type: project
image: images/project2.png
title: NanaIkehu(Visualize Energy)
permalink: projects/nanaikehu
# All dates must be YYYY-MM-DD format!
date: 2018-12-08
labels:
  - Meteor
  - MongoDB
  - React 
  - Semantic-UI
  - Victory (Graphs)
  - React-Leaflet (Map)
  - Technical Documents 
summary: This app visualizes energy usage throughout the University of Hawaii campus through the use of graphs and maps.
---

[Meteor/React application](http://ics-software-engineering.github.io/meteor-application-template-react/) to analyze power usage data, designed for the [University of Hawaii at Manoa](https://manoa.hawaii.edu/) as part of the [Hawaii Annual Code Challenge 2018](http://hacc.hawaii.gov/)

Nānā Ikehu visualizes energy usage throughout the University of Hawaii campus through the use of graphs and maps. Users are able to see the amount of energy used for each building by either clicking a building on the campus map, or by selecting a building through the drop down menu.
By visualizing complicated data, user are able to see just how much energy UH Manoa uses. Users are able to play with a wide variety of graphs. Users are also able to view the campus data using maps. By simplifying data, users are able to find a clear solution for our energy sustainability problem.
UH Manoa spends $30M a year on electricity. Is there a way to reduce this massive cost? To find a solution, data must be collected and analyzed. Nānā Ikehu has access to this collection of data. The raw data includes things such as the University of Manoa's campus building list, building energy usages, energy usage through out time, and many more.

My role on the project was to corporate with another group member to create new MongoDB collections and incorporate them into different aspects of the website. This involved creating and wiring with a building collection and kwdata collection.

I was also in charge of creating the map, choosing what libary for the graph and map, making sample graphs for other member can use as temples. The map will have two pages. One has markers on each building and one has heat map.
From this application I used software engineering practices such as version control and agile development. By creating issues and making branches that contain work for those issues the team was able to work on most parts of the application in parallel. This improved the quality of the code.

As a team, we are proud of the fact that our application works the way we want to. We see value in providing tighter integration with other data sources and plan to add REST APIs. These APIs will allow other teams to get data from our application transparently as well as allow users to import data in real time using HTTP. We also would like to develop more historical tracking and metrics to further insights.

You can see more at the [Github](http://https://github.com/nanaikehu/Nana-Ikehu/) .
