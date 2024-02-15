---
layout: topic
title: Connecting the Front-End to the Back-End
parent: Phase 3 Vue & Node.js
nav_order: 20
published: true
---

## 🎯 Objectives

- Learn about CORS and how to handle it in an Express application
- Use your Express API with your Vue.js application
- Work on project in class

## 🏗️ Project: Shopping List API Part Three

**Today we start work on part three** of this project, the last part, in which we will **allow the front end to connect to our API**, **run the front end Vue.js application and use our Express API as the backend**, and optionally add in **support for users and logging in**.

Continue working in the same repository you have been working in (the link below will take you to that same repo). There is no new README for part three, but the requirements are listed below.

- [Shopping List API Project Part Three]({{ site.data.phase3.projects.express-shopping-list-api-part-three.url }})

This third part is **due {{ site.data.phase3.projects.express-shopping-list-api-part-three.due_date | date: "%A, %B %-d"}}**.

### Requirements for Part Three

Revisit your Vue.js application and update it to work with your Express API. You will need to make changes in several places. **Don't expect it to automatically work**; you will likely need to read and work through errors.

1. **Allow CORS in your Express API**. You will need to install the `cors` package and use it in your Express application. You can find documentation [here](https://expressjs.com/en/resources/middleware/cors.html). Require the cors package and add `app.use(cors())` to your index.js file to allow CORS for all endpoints.
  
2. **Run the front-end application.** In package.json, you currently have a "start" command that looks like this: `"start": "npm-run-all --parallel dev api"`. Change this to `"start": "vite"` so that you will run ONLY the front-end application and NOT json-server.

3. **Update the URLS you are using in your client-side requests to match the endpoints you have in your API.** The base url can be the same if you are running your Express API on port 3000, but you may need to make changes to the path of the URL or the rest of the request in order for it to work with your Express API. The best way to do this is ONE REQUEST AT A TIME to avoid getting overwhelmed with errors.

4. **Make any other changes to the front end or back end to get the application working**. This could include changes to the way you are handling data (for example, your list objects don't have an `id` property but they do have `_id`), changes to the way you are handling errors, or changes to the user interface.

## 📖 Read | 📺 Watch | 🎧 Listen

- [A Visual Guide to CORS by Lydia Hallie](https://dev.to/lydiahallie/cs-visualized-cors-5b8h)
- [Web Authentication Methods](https://testdriven.io/blog/web-authentication-methods/)
- [Documentation for accessing the GitHub API with Authentication](https://docs.github.com/en/rest/authentication/authenticating-to-the-rest-api?apiVersion=2022-11-28)
- [Understanding API Key Authentication in a Node.js Application](https://blog.logrocket.com/understanding-api-key-authentication-node-js/)

## 🔖 References

- [MongoDB & Mongoose]({% link references/mongodb.md %})
- [Express.js][express]
- [CORS][cors]

{% include reference_links.md %}
