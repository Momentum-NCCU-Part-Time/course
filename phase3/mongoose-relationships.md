---
layout: topic
title: Mongoose Relationships
parent: Phase 3 Vue & Node.js
nav_order: 19
published: true
---

## 🎯 Objectives

- Learn how to deal with relationships in Mongoose
- How to perform CRUD actions with nested resources
- Work on project in class

## 🏗️ Project: Shopping List API Part Two

**Today we start work on part two** of this project, in which we will add in **support for items on our shopping lists**.

Continue working in the same repository you used for part one (the link below will take you to that same repo). There is no new README for part two, but the requirements are listed below.

- [Shopping List API Project Part Two]({{ site.data.phase3.projects.express-shopping-list-api-part-two.url }})

This second part is **due {{ site.data.phase3.projects.express-shopping-list-api-part-two.due_date | date: "%A, %B %-d"}}**.

### Requirements for Part Two

Add model and CRUD support for items on the shopping list.

Users should be able to see all the items on a given shopping list when they see the detail of a shopping list. They should be able to add, update, and delete items on a shopping list.

1. **Update your model**: Update your Shopping List model to include nested items on the shopping list (in Mongoose these are called subdocuments). A list item should have a name, a quantity, a "done" or "crossed off" field (you can name it whatever you want), and timestamps for createdAt and updatedAt.

2. **Update your endpoints or create new ones**: Revisit your existing endpoints and make whatever changes are necessary to support creating, reading, updating, and deleting items on the shopping list. You may need to create new endpoints for this, and/or you may update existing endpoints. **Use RESTful guidelines and remember that you should only build what you need.**

## 📖 Read | 📺 Watch | 🎧 Listen

- [Mongoose 101: Working with Subdocuments](https://zellwk.com/blog/mongoose-subdocuments/)
- [Mongoose Docs: Subdocuments](https://mongoosejs.com/docs/subdocs.html)
- [Mongoose Docs: Timestamps](https://mongoosejs.com/docs/timestamps.html)

## 🔖 References

- [MongoDB & Mongoose]({% link references/mongodb.md %})
- [Express.js][express]

{% include reference_links.md %}
