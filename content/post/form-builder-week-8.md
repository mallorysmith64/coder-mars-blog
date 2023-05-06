---
title: "A Journey of Building a Form Builder: Week 8 Progress Report"
date: 2023-04-16T09:00:00-00:00
math: false
tags: [coding, form-builder, react.js, javascript, html, css, flask, python]
categories: [form builder series]
draft: false
---
## A Journey of Building a Form Builder: Week 8 Progress Report

-----------------------------------------------
 ![paperwork-avalanche-behind-and-around-older-woman-at-her-desk](https://lh3.googleusercontent.com/wSqCgv9BdO-ar8Z1Lj3Anh-fiXdctP0wdo-86fD_Pncjqk4olDO4O5c2XJ19io_yXdINPiXv3GDqK3K6G_NnUIZ6m6rEoV0VSzYiTKY)

-----------------------------------------------
Hello fellow readers! I’ll be sharing my latest developments, including implementing a WYSIWYG editor, fixing bugs, adding real-time updates for user inputs, and differentiating the header form element from the other elements. Read on for more details!

### Day 1 – Implementing WYSIWYG Editor with React-Quill Library

I implemented a WYSIWYG editor using the react-quill library, which includes a toolbar with options like bold, italics, and alignment. I also added conditional rendering, so the editor only appears when the user clicks on the edit button for a particular form element. To make the toolbar more user-friendly, I added hover animation transitions to all the toolbar option buttons.

### Day 2 – Fixing a Bug and Creating Separate Components for Form Elements

I discovered a bug where multiple cards that were added to the form were being rendered in the side panel, making it hard for users to edit specific elements. I fixed this bug so that only the card the user is editing is rendered in the side panel. I also created separate components for three form elements (Header, Paragraph, and Email), which render conditionally depending on the element being edited. This makes the code more modular and easier to manage.

### Day 3: Implementing Real-Time Updates for Input Textboxes

I added real-time updates for the input textboxes in the header and the email side panels, so users can see their changes reflected on their form immediately. I made sure that only the card the user is editing updates with their changes, and not all instances of the same card. I also added placeholder text to make the interface more user-friendly.

### Day 4: Adding Default Font Size for Header Form Elements

To differentiate the Header form element from other elements, I added a default font size that is larger and bolder than the other ones. This makes it easier for users to see the distinction between the different types of form elements.

### What I Learned This Week – XP Gained

I learned how to use the React-Quill library to implement a WYSIWYG editor in my project. Additionally, I learned about the useContext React hook, which allowed me to pass text between components without relying on prop drilling. While I could have used prop drilling, it was becoming too complicated for my use case, and the useContext hook proved to be a handy solution. Overall, I feel like I learned a new nifty hook and library, which I may be able to use for future projects!

### Final Thoughts

This week, I implemented a WYSIWYG editor with a toolbar full of formatting options, added real-time updates for input textboxes, fixed a bug that was causing multiple cards to be rendered in the side panel, and created separate components for each form element. I also added a default font size for the Header form element.

Thank you for following along with my progress. Stay tuned for more updates to come!

-----------------------------------------------

#### Supplemental Resources

1. React Quill Library
    * [github repo](https://github.com/zenoamaro/react-quill)
    * [npmjs.com](https://www.npmjs.com/package/react-quill#custom-toolbar)
2. useContext React Hook
    * [how-to guide](https://dmitripavlutin.com/react-context-and-usecontext/)
    * [official docs](https://react.dev/reference/react/useContext)

