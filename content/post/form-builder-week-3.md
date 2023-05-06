---
title: "A Journey of Building a Form Builder: Week 3 Progress Report"
date: 2023-02-26T09:00:00-00:00
math: false
tags: [coding, form-builder, react.js, javascript, html, css, flask, python]
categories: [form builder series]
draft: false
---
## A Journey of Building a Form Builder: Week 3 Progress Report

-----------------------------------------------
 ![woman-sitting-at-desk-pushing-paperwork-stack](https://lh3.googleusercontent.com/HfvmsrmK7L6VGfextzLAl1CXU5qdKXpSt2DiIyaV-Oj09DvG_mL_CP1dUz2aVZLw6sDU1SOaUm3yVNpc1jZOjgamwPcPsez-wnmkhBA)

-----------------------------------------------
Welcome back to the third week of creating a form builder! In this week’s progress report, I’ll share my experiences and accomplishments as I worked on saving form data to Mongo and designing the publish page.

### Day 1 – Saving Form Data to Mongo/Repling to Flask Community on Reddit

On the first day of this week, I worked on getting the form data stored in MongoDB. Although I got the submit/publish button to save data to the database, I found that only blank values were submitted to it.

In addition, I had previously posted on Reddit asking the Flask community if anyone wanted to collaborate on this project with me. I received a few messages from some Redditors regarding a collaboration, which I responded to and engaged with.

### Day 2 – Successfully Stored Form Data in Mongo But With Schema Issues

The second day of this week was a significant milestone as I was able to successfully store form data in MongoDB. The problem I was having was that one of the components I was using from the “react-form-builder2” library wasn’t working for me. I had to wrap the Form Builder component from that library in a simple HTML form in order to get around this and get the POST request to work. I also had to learn more about TypeScript in order to get the form to submit. However, once I got the form data to save to mongo, I quickly realized that mongo was saving multiple documents for each form submission, which was not what I wanted. For each form submission, I was wanting one document to be inserted into mongo in relation to the user who submitted it. Although I encountered some schema issues, I decided to tackle them on a later day, since I had hit a major milestone that allowed me to move forward.

### Day 3 – Learning to Delete Documents from MongoDB Collection

On the third day, I encountered an issue that required me to keep deleting documents in mongo as I was manually testing new form submissions. This led me to learn how to delete all documents, many documents, and one specific document from a MongoDB collection. Although I wasn’t sure if I needed to have written this code, I found it useful to be able to temporarily delete documents at will while manually testing.

### Day 4 – Designing/Building Publish Page for Form Submissions

The fourth day was focused on designing and building the publish page for form submissions. I started by adding a basic input field for where the form’s URL will eventually go. Next to it, I added the submit button with a Font Awesome copy/paste icon. (I had to make sure I had the right version of Font Awesome for the icon to display because the latest version of Font Awesome didn’t work for my project.) Since I’m still working on generating URLs for each form that’s submitted, I hardcoded a URL into the input field and added the copy functionality in React. This allows me to copy a static link for now, but in the near future, it will be a dynamic link to the user’s form.

The third week of building the form builder was focused on several key tasks, including getting the form data stored in MongoDB, designing and building the publish page, and engaging with the Flask community on Reddit. With these accomplishments, I’m excited to continue building this project from the ground up and sharing my progress in the next week’s report.

Thank you for following along!

-----------------------------------------------

#### Supplemental Resources

1. [Reddit’s Flask Community](https://www.reddit.com/r/flask/)

2. [Font Awesome](https://fontawesome.com/)
