---
#This is the barter system page.
layout: default
title: FixFlow
description: Bug tracker full stack application which uses react and flask.
---
# Description
FixFlow is a bug tracking fullstack web appplication which uses react framework to implement user side interface with Node.js server and utilises Python Flask library to develop API which provides endpoints for backend which is connected to a SQL server to seed data.

<img src="{{ site.baseurl }}/assets/images/uml-diagram.png" alt="Structure" style="width:550px;" />

# Working

## Frontend
* Developed using React V18 Framework and hosted with Node.js Server, it provides a dynamic client side web app with javascript.

* The app displays all the project linked to the user on the homepage, and allows clickable card objects to navigate and open each one on different page using dynamic routing using Routes, Route and Links. 

<img src="{{ site.baseurl }}/assets/images/home-page.png" alt="Home" style="width:550px;" />

* To go to a specific porject click on the title and it opens a new page with full details of that project along with the bugs in that project. 
* It also provides you the opputunity to add new bugs/projects and delete those as neccessary, which is handled using React hooks: useeffect and usestate and seeding with Flask API (backend)

<img src="{{ site.baseurl }}/assets/images/bug-page.png" alt="Home" style="width:550px;" />

## Backend
* Developed using python Flask library which allows to create API endpoints which the react frontend is hooked to, and allows Cross-Origin Resource Sharing with 'CORS'.

<img src="{{ site.baseurl }}/assets/images/project-form.png" alt="Backend" style="width:550px;" />

* The python backend app is running on flask server, it connects to SQL server to store data secured, and performs the necessary connection to load/modify data when required by React app.


* Source: [FixFlow](https://github.com/samGill00/FixFlow)