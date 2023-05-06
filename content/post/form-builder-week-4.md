---
title: "A Journey of Building a Form Builder: Week 4 Progress Report"
date: 2023-03-05T09:00:00-00:00
math: false
tags: [coding, form-builder, react.js, javascript, html, css, flask, python]
categories: [form builder series]
draft: true
---
## A Journey of Building a Form Builder: Week 4 Progress Report

-----------------------------------------------
 ![stack-of-papers-and-folders](https://lh3.googleusercontent.com/IGsjt7OXJeZeHEi0JaqmNLsXJEFlfgH8i720BK3GNCj2VBn5m1z2MqhEeDvOfzO5SY-hCYBWBCcHGBcDV_1DtfENmZLBabVkTCkOApFr)

-----------------------------------------------
Welcome back to the fourth week of building a form builder! This week was all about getting the form data to save in MongoDB, building the ViewForm page, and figuring out how to render the form builder component without edit capabilities.

### Day 1 – Storing Data in Mongo Issue

On the first day, I continued working on getting only one document to be inserted into MongoDB.

### Day 2 – Retrieving Form ID and Building ViewForm Page

The second day was focused on working on storing data in mongo, as well as retrieving the form ID on the frontend. I modified the post and get request on the backend in order to get a unique form ID. However, I got a little stuck trying to figure out how to get the form data in mongo as one document and how to grab the URL ID on the frontend to display for users to copy/paste. Despite this challenge, I was encouraged by the fact that I was able to get the URL with the ID at least in the console from the backend.

### Day 3 – Copy/Paste Form URL/Build ViewForm Screen

On the third day, I successfully retrieved the form ID from the backend so the user can copy the dynamic URL with the form ID in it. I then built the ViewForm page, where the user would be redirected after clicking the copy button. To get a form to display, I used the FormBuilder component from the library and found a way to get the toolbarItems side panel to not be rendered since the user would not need to drag and drop fields once they submit their form. However, I encountered a problem where the side panel with all of the fields had text above it that said “Toolbox”. For now, I decided to hide this text with some custom CSS while still displaying the toolbarItems panel on the FormBuilder screen. Although I removed the submit button for now, I now need to figure out how to render the form builder component without the edit functionality or if that’s even possible.

### Day 4 – Rendering the Form Builder Without Edit Capabilities

The fourth and final day of this week was focused on figuring out how to get the form the user submitted to render without any editing functionality. This means no drag-and-drop abilities and no toolbar on the right-hand side full of fields.

Although there is a ton of work to be done still, I’m excited to continue building this project and sharing my progress in the next week’s report.

Thank you for reading!

-----------------------------------------------

#### Supplemental Resources

No supplemental resources for this week, but there will be plenty in the upcoming week. 🙂
