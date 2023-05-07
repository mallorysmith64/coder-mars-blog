---
title: "A Journey of Building a Form Builder: Week 9 Progress Report"
date: 2023-05-07T09:00:00-00:00
math: false
tags: [coding, form-builder, react.js, javascript, html, css, flask, python]
categories: [form builder series]
draft: false
---
## A Journey of Building a Form Builder: Week 9 Progress Report

-----------------------------------------------
![unhappy-female-office-worker-looking-around-stack-of-binders-and-paperwork-on-her-desk](https://lh3.googleusercontent.com/ymwJYytuAObUmadspp1poNLO7ltVCQ7VZYHzZhgso-Cv36yvBqRCDhzJwuKTum42QpO5MjVbSG-FeQy6I3_E3ClUuKNZLMH49rWqf00)

-----------------------------------------------
Hello, readers! I regret that I haven't posted in couple of weeks. I ended up having a bunch of appointments all around the same time. However, I'm back in action and excited to share the progress I made during Week 9. Read on for a summary of what I accomplished.

### Day 1 - Giving Users More Control: Implementing Font Size Options

Following up on my work from my last post, I added the ability to change the text size for the Header form element. Users can now choose from small, default, or large for the Header text. I accomplished this by expanding upon my use of the useContext hook in React.js.

### Day 2 - Say Hello to the Name Form Element: Adding a New Form Field

I removed the paragraph form element for now and added the name form element instead. I made this decision due to the estimated time to fully implement the paragraph form element with a functional WYSIWYG (What You See Is What You Get) editor, including both the frontend and backend work necessary. I would like to come back to working on this element but for timing reasons, just not for the MVP. As for the name element implemented, it comes with two fields, "first name" and "last name".

### Day 3 - Getting Aligned: Adding Realignment Options for Forms

I added realignment options to the Header, Email, and Name form elements, allowing users to realign text on the form to the left, center, or to the right. This may seem simple to implement, and perhaps it is, but it wasn't a one and done implementation. Each form element has custom realignment options in their respected side panels for ease of customization.

### Day 4 - More Options: Adding New Options and Changing Default Ones

To provide more options for users, I added an extra-large text size button to the Header form element. Then, I changed the default alignment for the name form element, making it easier for users to create professional-looking forms without spending too much time on changing the alignment.

I also spent time working on the "Save and Close" button functionality for the side panels. The goal is to save the user's input and button selections for when they inevitably close out of the panel. I have no idea how to implement this, but in all fairness, I never know how to implement anything until I do it. This will be a fun challenge for next week! Haha.

### What I Learned This Week – XP Gained

*Perseverance* - Over the past 2 months, I've felt the urge to work on other projects in search of that new spark of excitement that many of us feel when starting a new challenge. However, by focusing and dedicating time solely on this project, I've found myself becoming more motivated to complete it as an MVP before moving on to anything else. 

Even when I do finally "finish" my initial goals, there will still be many more features and tasks that will need to be completed. It can take a very long time to go through each stage in software development. Sometimes, it's loads of fun, other times it's frustrating and you just want to quit and take an easier path. Despite these challenges, I believe in staying focused, reaching one's goals, and setting new ones to go further than ever before.

### Final Thoughts

Overall, I'm pleased with the progress I made this week. I added new features and options that will make the form builder more powerful and user-friendly.

Thank you so much for reading! Stay tuned for next week's progress report.

-----------------------------------------------

#### Supplemental Resources

1. useContext React Hook
    * [how-to guide](https://dmitripavlutin.com/react-context-and-usecontext/)
    * [official docs](https://react.dev/reference/react/useContext)
2. WYSIWYG Editor
    * [WYSIWYG Editor Wiki](https://en.wikipedia.org/wiki/WYSIWYG)
3. Minimum Viable Product
    * [MVP Definition](https://en.wikipedia.org/wiki/Minimum_viable_product)
