---
layout: topic
title: Final Projects & Agile Development
parent: Agile Development
nav_order: 1
published: true
---

## 🎯 Objectives

- Troubleshoot and fix issues with connecting the front-end to the back-end
- Form teams and begin thinking about final projects in advance of next week

## 🏗️ Project: Continue working on Shopping List API Part Three

As a reminder, here are the things to keep in mind as you work to update your front-end application to work with your Express API:

1. **Allow CORS in your Express API**. You will need to install the `cors` package and use it in your Express application. You can find documentation [here](https://expressjs.com/en/resources/middleware/cors.html). Require the cors package and add `app.use(cors())` to your index.js file to allow CORS for all endpoints.
  
2. **Run the front-end application.** In package.json, you currently have a "start" command that looks like this: `"start": "npm-run-all --parallel dev api"`. Change this to `"start": "vite"` so that you will run ONLY the front-end application and NOT json-server.

3. **Update the URLS you are using in your client-side requests to match the endpoints you have in your API.** The base url can be the same if you are running your Express API on port 3000, but you may need to make changes to the path of the URL or the rest of the request in order for it to work with your Express API. The best way to do this is ONE REQUEST AT A TIME to avoid getting overwhelmed with errors.

4. **Make any other changes to the front end or back end to get the application working**. This could include changes to the way you are handling data (for example, your list objects don't have an `id` property but they do have `_id`), changes to the way you are handling errors, or changes to the user interface.

## 📖 Read | 📺 Watch | 🎧 Listen

- [Jamie Howard Huddle on Agile, Aug 2022](https://drive.google.com/file/d/1g4J7ncUspw2qh6D2yW0NsG5tISYZCPfM/view?usp=share_link)
- [How we use "ship small" to rapidly build new features at GitHub](https://dev.to/mscccc/how-we-use-ship-small-to-rapidly-build-new-features-at-github-5cl9)
- [CodeNewbie Podcast: What does it mean to be a part of the software development life cycle](https://www.codenewbie.org/podcast/what-does-it-mean-to-be-a-part-of-the-software-development-life-cycle)

## Final Projects & Agile Development

The final project is partly about the finished product, and partly about the experience of getting to the point where you can ship the product. We will learn and use the practices of Agile Development to work on this project.

Your first goal as a team is to create a team charter that will help you work together effectively. Your second goal is to brainstorm ideas for your final project and be ready to submit your plan in writing next Tuesday.

The goal of the final project is to give you experience working on a team of developers to ship a software product. You will work as a member of a 4-person dev team to build a web application that addresses a particular need. You will need to use the technical skills and tools you have learned, learn some new ones on your own as you work, and lean on your previous professional experience to be successful.

### Teams 🍕 🐢 💥

#### Leonardo

Betty, Rhonda, Lynerd, Jarrod

#### Michelangelo

Austin, Sana, Megan, Joanna

#### Donatello

Ross, Caroline, Girish, Vanessa

#### Raphael

Paola, Poonam, Courtney, Sai

### ✅ TODO before next Tuesday

1. 🌟 Read [How we use "ship small" to rapidly build new features at GitHub](https://dev.to/mscccc/how-we-use-ship-small-to-rapidly-build-new-features-at-github-5cl9) for an engineer's perspective on an approach to building software that parallels almost precisely the approach we take at Momentum.
2. 🗺️ **Create a team charter** together and pin or bookmark the document you create in your team's Slack channel. This is an agreement you create together to determine the expectations you have for each other and ensure you can meet your goals. Use your experience working on teams in the past to figure out what will help you work together with a **minimum of friction** and a **maximum of productivity**. [Use these steps to create a team charter](https://momentumlearn.notion.site/Create-a-Working-Agreement-bb5c3f432a0a4bc792240543b67b8c9a?pvs=4) and post it in your team's Slack channel when it is done.
3. ⏲️ Please be sure to include a discussion of everyone's time, availability, and schedule constraints so that everyone knows what to expect. Look for an overlap in your schedules where you can meet on Zoom at least once a week.
4. 🌩️ Brainstorm ideas for your final project with your team, and **be ready to submit your plan in writing next Tuesday.** Read through the details about the product and the process below to help you.

### The Product

The product you build should be a web application that addresses a particular need, like managing shopping lists or organizing notes.

**The product must reach a "minimum viable product" (MVP) state for it to be valuable to you in a job search.** This means that the first priority is getting the core functionality of the application working. You will have to ruthlessly prioritize your time and focus your efforts.

The following ideas are meant to help you think about what you might build given the time you have to spend. You are not limited to these ideas, but you need to pick something that you actually can build in the time you have. The best approach will be to talk this over as a team and mix-and-match ideas to come up with something that you can all get behind.

You will [submit a written proposal for your project next Tuesday](https://forms.gle/2qtXxm1spC7cEZkk9). You will have time in class to do this. This proposal should include a description of the project, a list of the features you would like to build, how you think you will build it and the technologies you will use (e.g., an Express API; React), and a rough timeline for completing it.

#### If each dev has less than 15 hours a week to spend on the project

- Extend or modify the functionality of notes or shopping list and add on to the front-end and back-end to make it more complex. For example you could, focus on building production-quality UI with validation and error-handling and adding authentication to the back-end, or integrate another third-party API to support the application.
- You can build a front-end application with Vue.js that has a back-end API built with Express that does something _different_ from notes or shopping lists but is still basically a CRUD app.
- Rebuild notes or shopping lists (front and back end) from scratch and change the backend to use a different database (like PostgreSQL), and use the same front-end application with it, and/or build a new front-end for it. Express can serve HTML instead of JSON, so you could build a full-stack application that does not use a front-end framework.

#### If each dev has more than 15 hours a week to spend on the project

- You can build a front-end application with Vue.js that has a back-end API built with Express that does something _different_ from notes or shopping lists and may do something a bit more than a CRUD app (for example, maybe you allow people to track their weekly spending and offer data visualization to show their spending habits over time).
    - Express can serve HTML instead of JSON, so you could build a full-stack application that does not use a front-end framework.
- You can build a front-end application using React or Angular, or [any other front end framework](https://github.com/sorrycc/awesome-javascript#mvc-frameworks-and-libraries). This is a great way to expand your skills and demonstrate that you can learn new things on your own.
    - build a notes or shopping list application and use your Express API with it
    - build something new and use an existing third-party API to support it
    - build something new and make a new Express API to support it
    - build a new backend [using a different framework for Node.js](https://blog.logrocket.com/node-js-alternative-frameworks-express-js/).
- Build a static site using a [static-site generator](https://jamstack.org/generators/) like Vue Press, or Gridsome and use a third-party API to support it. This is a great way to expand your skills and demonstrate that you can learn new things on your own.
- A JavaScript game: for this you should use a framework like [Phaser.js](https://phaser.io/), which uses object-oriented JavaScript (classes and instances). This has a steep learning curve, and it is time-consuming to gather and prepare assets for use in the game (if you have graphic design expertise on the team this may be more within reach).

### The Process

Although the product is important, the most important thing that we are building in this project is your skills: your technical skills AND your collaboration and communication skills.

**You must make a significant contribution to this project for it to be valuable to you in a job search.** You should be able to show it to potential employers and talk about the process of building it, the challenges you faced, and the decisions you made.

We will need to add some new skills to be able to do this project, some which we will cover in class and others that you will need to practice on your own, leaning on your previous professional experience. Here are some of the things you will need to do to be successful:

- Work cooperatively as a team, with each team member making a significant and roughly equal contribution to the project.
- Learn and use an effective Git & GitHub workflow that will allow everyone to work in the same repo. This will include using branches, pull requests, code reviews, and excellent communication.
- Use asynchronous communication tools like Slack and GitHub to manage your work and communicate with your team.
- Communicate regularly, clearly, and proactively with your team and with your instructor, making sure to share information that affects the team's work.
- Prioritize getting the project to a "minimum viable product" (MVP) state. This means that you should focus on getting the core functionality of the application working before you add on extra features or polish the UI.

## References

- [Creating a team charter][team-charter]
- [Managing your time][time-management]
- [Idea generation & inspiration][idea-generation]

{% include reference_links.md %}
