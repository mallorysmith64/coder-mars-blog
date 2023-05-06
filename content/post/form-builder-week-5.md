---
title: "A Journey of Building a Form Builder: Week 5 Progress Report"
date: 2023-03-26T09:00:00-00:00
math: false
tags: [coding, form-builder, react.js, javascript, html, css, flask, python]
categories: [form builder series]
draft: false
---
## A Journey of Building a Form Builder: Week 5 Progress Report

-----------------------------------------------
![stressed-woman-throwing-paperwork-into-the-air](https://lh3.googleusercontent.com/FzTjFxvY4-IN2GmkFTl2xE8zWlvd-7Pli4GoATi1g_9V_wXeuWRMwbDHaJca8Juvc_rr7h6ETYWqb8DCq4Zrikg2R82WKkcUm_ipgQl5UA)

-----------------------------------------------
Welcome back to Week 5 of building a form builder! This week was all about fixing issues with yarn not hot reloading and selecting a new drag-and-drop library for our project. Let’s dive in!

### Day 1 – Fixing Yarn Not Hot Reloading in Dev and Prod

On the first day, I worked on fixing an issue with yarn not hot reloading in both development and production environments. I sat down with a senior developer to brainstorm solutions to the problem and ended up spending a total of 5 hours learning about vite.js’s configurations and exploring the react-form-builder2 library. I was able to fix the issue of my project not reloading with every change by configuring the frontend (including tsc checking) and the backend at the same time, so I can now run everything simultaneously with one command when in my development environment. This will save me loads of time when making code changes and overall make me more productive.

### Day 2 – Project Planning and Updating Trello

I committed changes from the previous day’s coding session and updated the project’s Trello cards. I also did some project planning and brainstorming to ensure that I stayed on track with my project’s goals.

### Day 3 – Fixing the Footer, Navbar, and the Homepage

I focused on fixing the footer and navbar to make them more responsive and visually appealing. I also removed unnecessary links from the navbar and fixed a whitespace issue on the homepage. I continued researching drag-and-drop libraries and decided to switch from react-form-builder2 to a new library due to its limitations.

### Day 4 – Researching and Selecting a New Drag-and-Drop Library

I researched different drag-and-drop libraries, including react-dnd and dnd-kit. I compared and contrasted these libraries by reading their documentation and exploring their GitHub repositories. Ultimately, I decided to go with react-dnd due to its better code health and greater popularity. I started ripping out the react-form-builder2 library and replaced it with react-dnd. I followed along with a tutorial on YouTube to get started with react-dnd, but it didn’t quite work as expected. I decided to re-read the react-dnd documentation and embrace the learning curve that comes with working with a new and complex library.

That’s it for Week 5 of building a form builder. Join me next week as I continue to make progress and share updates. Thanks for reading.

P.S. The reason I haven’t posted in a couple of weeks is that I caught a nasty cold and an ear infection, but I’m starting to get better! 🙂

-----------------------------------------------

#### Supplemental Resources

1. Vite's Docs
    * [Vite’s Config Docs](https://vitejs.dev/config/)
2. React Form Builder 2 Library
    * [github](https://github.com/Kiho/react-form-builder/tree/master/src)
    * [npmjs.com](https://www.npmjs.com/package/react-form-builder2)
3. React Dnd Library
    * [github repo](https://github.com/react-dnd/react-dnd/)
    * [npmjs.com](https://www.npmjs.com/package/react-dnd)
    * [overview docs](https://react-dnd.github.io/react-dnd/docs/overview)
    * [youtube tutorial](https://youtu.be/4bzJrEETW4w)
4. Dnd Kit Library
    * [npmjs.com](https://www.npmjs.com/package/@dnd-kit/core)
    * [overview docs](https://dndkit.com/docs/overview)
