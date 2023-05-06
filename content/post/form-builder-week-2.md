---
title: "A Journey of Building a Form Builder: Week 2 Progress Report"
date: 2023-02-18T09:00:00-00:00
math: false
tags: [coding, form-builder, react.js, javascript, html, css, flask, python]
categories: [form builder series]
draft: false
---
## A Journey of Building a Form Builder: Week 2 Progress Report

-----------------------------------------------
![woman-holding-stack-of-binders-with-paperwork](https://lh3.googleusercontent.com/M9iZS_fii5p5Mc7knxGJDhQ4tHNrHYRQNSYr71KQt7yshQ0yAH_2R10-Gn5a2Fspo-IsbF_WmZSpl_IbONkNKt8gaZHC5PxRF3AQK38T)

-----------------------------------------------

Welcome to the second progress report of my journey in building a form builder. Last week, I ran into an issue displaying the drag-and-drop form builder in the browser, but I got it on the first day of week 2 by switching to a different package manager.

Note: A “day” varies in the number of hours worked. Some days I worked for a couple of hours or so, others I worked for several hours depending on that day’s goal and how much time I had to dedicate. This week, I intentionally continued my development with a 4-day work week over the traditional 5-day work week schedule.

### Day 1: Displaying the Form Builder

I sat down and uninstalled npm from my project and installed yarn instead. The form builder library I was trying to implement last Friday instantly showed up on my webpage. It seems that this particular library was just not compatible with npm and that’s why it wouldn’t display in the browser before.

However, once I started using yarn to get my project to start in chrome, I ran into an issue where every change I tried to make to my project would not update unless I built the project each time. I would have to run the command “yarn build” and then “yarn preview” every time I made a minor change to see the page update. This was somewhat annoying because each build would take several minutes to complete. Yet, when I was using npm as my package manager, I could run “npm start” and my project would immediately start running with the changes I made in real-time. Yarn should work similarly, but for some reason “yarn start” was not updating any changes that I would make. So, although I got the form builder to display, I was having to wait several minutes in between build times before I could see my changes. For now, I’m not going to worry about yarn’s slow build times. I’m glad I got the form builder to at least display.

### Day 2 and 3: Finding a Way to Submit the Form Data

My goal was to find a way to save the initial JSON that the form builder would create when a user drags and drops fields onto the form and clicks the “publish” button. However, I was stuck trying to figure out how to submit the form’s data since the library I was using didn’t have an obvious way to do so. I consulted the library’s documentation on GitHub and npmjs.com, but I couldn’t get the object (the form’s data) from the console to display on a different page when the user submitted the form.

### Day 4: Brainstorming How to Store the Data

I decided to move on from the data submission issue I was having on the frontend and focus on how I was going to store the data. I started creating models (i.e., database tables) to format how each form’s data would be stored in MongoDB. However, after talking to a Senior DevOps Engineer/Software Developer, I learned that creating models for MongoDB would defeat the purpose of using a NoSQL database. MongoDB doesn’t require that you create models to use it, some people choose to do it that way, but doing so could cause headaches down the road that could be avoided altogether. With that information, I stopped designing the models in Flask and started exploring alternative solutions for storing the data.

Although I encountered some challenges this week, I’m still committed to making progress on this form builder project. Stay tuned for the next progress report!

#### Supplemental Resources

1. Vite.js Docs
   * [vite.js - npm/yarn scripts](https://vitejs.dev/guide/)
2. React Form Builder 2 library
   * [github repo](https://github.com/Kiho/react-form-builder)
   * [npmjs.com](https://www.npmjs.com/package/react-form-builder2)
