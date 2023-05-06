---
title: "A Journey of Building a Form Builder: Week 7 Progress Report"
date: 2023-04-09T09:00:00-00:00
math: false
tags: [coding, form-builder, react.js, javascript, html, css, flask, python]
categories: [form builder series]
draft: false
---
## A Journey of Building a Form Builder: Week 7 Progress Report

-----------------------------------------------
 ![female-office-worker-searching-through-paperwork](https://lh3.googleusercontent.com/lHygnFAzBgnGvRDSfQIfWky0tNqP9A2qsN-5COA3FE3iWX18Sf7W5_vFClEh9k51MKWDfxSWUyNh_Vqk1Nld2kGzm-DWpT5l7GUrjckDTw)

-----------------------------------------------
Welcome folks! Last week, I implemented the react-dnd library and made the cards draggable and droppable onto the form. This week I built upon that progress by improving the appearance of the cards being dropped, working on fixing a duplicate card bug, adding the ability to delete cards, and starting to implement a sidel panel with a wysiwyg (What You See Is What You Get) editor.

### Day 1 – Improving the Visual Appearance

I made some visual improvements to the form builder by styling the cards to be larger in the form compared to when they are in the toolbar. I improved the naming conventions being used to be more consistent throughout the project. I also got the icons to conditionally render depending on whether they were in the toolbar or not. This is important because no one wants the default icons on their forms once they publish their newly created form and share it with others.

### Day 2 – Fixing the Duplicate Card Bug

I worked on fixing the duplicate card bug that caused users to see two cards on the form instead of one when they moved a card to a new position. I added indexing on the cards in React.js and made keys unique to ensure that when the user moves a card, it works the way they would expect. This task is a work in progress.

### Day 3 – Adding the Ability to Delete Cards

I added a trash can icon to each card on the form and the functionality to delete cards the user no longer wants. I then researched WYSIWYG editor libraries available on npmjs.com in order to start working on the form’s edit functionality.

### Day 4 – Creating the Side Panel and Implementing a WYSIWYG Editor

I created a side panel for where the user will be able to edit each card. After implementing one of the WYSIWYG libraries, I found that it didn’t come with toolbar options like “bold”, “italics”, “alignment”, and other customization options. My plan is to find another WYSIWYG library that comes with at least a few of these toolbar options out-of-the-box, so that I don’t have to waste time trying to make my own.

### What I Learned This Week – XP Gained

I learned some of the CSS needed to create a side panel. I also explored different WYSIWYG editor libraries and gained an understanding of some of the available options on npmjs.com.

### Final Thoughts

I made strides in improving the form’s appearance, working on fixing a duplicate card bug, adding the ability to delete cards, and beginning to implement a side panel with a WYSIWYG editor. I’m proud of the progress I’ve made thus far and excited to keep refining the project. I look forward to sharing next week’s updates.

Thanks for reading!

-----------------------------------------------

#### Supplemental Resources

1. [npmjs.com](https://www.npmjs.com/)
2. [WYSIWYG Editor Wiki](https://en.wikipedia.org/wiki/WYSIWYG)
