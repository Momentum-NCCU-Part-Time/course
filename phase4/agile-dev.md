---
layout: topic
title: Agile Development 101
parent: Agile Development
nav_order: 2
published: true
---

## 🎯 Objectives

- What is agile development?
- Git workflow for a team
- Finalize your team charter
- Decide what you are building for your final project
- Real talk about the job search with Luke

## Final Project

Today your goal is to figure out what you are building for your final project with your team. You'll need to [submit a written proposal for your project by the end of class today](https://forms.gle/2qtXxm1spC7cEZkk9).

**One person** on your team should accept the project invitation and create a new team, using your team name. Then the other devs should follow the project link and choose their team.

Note that this is an empty repo, so cloning it will not give you any code.

[Team Project Repo]({{ site.data.phase4.projects.final-project.url }})

⚠️ NOTE! You have to use the link above to join the team your teammate created in order to have write permissions to the repo.

**Today you will not commit or push any code since your main goal is planning**.

## How to work as one team

You're working together to ship a product, on time. Dividing up the work requires planning out what you need to build ahead of time. You can make product decisions together even though you will implement features separately, and every developer bears a responsibility for the success of the project.

Communicating well with your teammates is a critical part of this project. You will need to communicate with each other frequently so that you aren't duplicating work or building things that won't work together, and meet as often as possible given everyone's schedules. Pairing or working together in groups is encouraged.

**You also are encouraged to work with the other team to share ideas, advice, approaches, and resources.**

Working with other developers in a shared codebase also means that the way you have been using Git and GitHub so far will have to change. This is definitely going to slow you down at first, but it's part of what you are learning in this project.

## Team Trello Boards for Task Management

Trello is a tool that allows us to manage tasks and track the work that is being done on a project. Keeping your task management tool up to date so that it reflects the current state of the project is a critical part of your job as a developer.

Below is an **invite link** to join your team's Trello board. You may be asked to create a free Trello account once you click on the link to join the board.

**You have to join the board through this invite link or you will not be able to view the board.**

- [Team Leonardo](https://trello.com/invite/b/4x9Ze9tS/ATTI54787f44ac2e1bdb7e78070f82dc842d568CF0A4/team-leonardo)
- [Team Michelangelo](https://trello.com/invite/b/2asPEaeJ/ATTIc4a1450281e7230a266330181506b6e6FDB789A2/team-michelangelo)
- [Team Donatello](https://trello.com/invite/b/sk3bBpBi/ATTI46c6bb5019a02b23114bb52708a7a6879653B7B6/team-donatello)
- [Team Raphael](https://trello.com/invite/b/L06qujtz/ATTI130fbc4b984c5be58d3f1f32f40c1781249F513E/team-raphael)

Your Trello board is ready with columns predefined to start you off. You are welcome to adapt it to support the way your team works, but if you make changes please retain at least the columns for backlog, in progress, and done.

You should put your user stories on your Trello board in the User Stories column. You'll find a template card for user stories that you can copy ([how to copy a card in Trello](https://support.atlassian.com/trello/docs/copying-cards-lists-or-boards/#Cards)).

Then, break them down into tasks and put tasks on cards.

### How to make cards

- Task cards go in the Backlog column.
- Use the Task Card template. Please fill out the fields included in the template.
- You can link a task back to its user story card using the User Story field. Remember, one user story may be more than one task.
- One task per trello card
- Each task should be doable in a day or less.
- Don't assign tasks to anyone yet.
- Each card must include how you will know when the task is done (its "definition of done").


### Example Trello Boards

These boards are from real final projects done by full-time teams. You'll see most of the cards in the "Done" column.

- [Open Mic Trello Board](https://trello.com/b/k2dLx20M/copy-of-open-mic)
- [Music Teacher App Trello Board](https://trello.com/b/tqsOYOAl/copy-of-music-teacher)
- [Game Knight Trello Board](https://trello.com/b/ciWUNSIB/copy-of-game-knight)
- [Purple Rain Trello Board](https://trello.com/b/rjMdG4FA/copy-of-purple-rain-%F0%9F%95%8A%EF%B8%8F)

## Planning User Flow

One of your first tasks is to sketch out the **[user flow](https://signalvnoise.com/posts/1926-a-shorthand-for-designing-ui-flows)** and [draw up some **wireframes**](https://xd.adobe.com/ideas/process/wireframing/wireframe-design-101/) for the application. It can help to ask questions like:

- What does our user see when they first land on our site?
- What will they need to do here?
- How will they accomplish that?
- What will happen next?
- If they click on a button or link, what happens?
- What does the UI look like after the user clicks on something / follows a link / submits a form?

If you are building an API, you will need to plan your data models and API endpoints. You should be able to answer questions like:

- What resources will you need to create, read, update, and delete? Think about things that need to be stored so that they can be looked up again.
- What data will you need to send to the server to create or update a resource?
- What data will the server send back to the client?

**Every developer on the team should be able to answer these questions.** In other words, everyone has to be on the same page and how the app works is everyone's responsibility.

## 📖 Read | 📺 Watch | 🎧 Listen

- [Jamie Howard Huddle on Agile, Aug 2022](https://drive.google.com/file/d/1g4J7ncUspw2qh6D2yW0NsG5tISYZCPfM/view?usp=share_link)
- [How we use "ship small" to rapidly build new features at GitHub](https://dev.to/mscccc/how-we-use-ship-small-to-rapidly-build-new-features-at-github-5cl9)
- [CodeNewbie Podcast: What does it mean to be a part of the software development life cycle](https://www.codenewbie.org/podcast/what-does-it-mean-to-be-a-part-of-the-software-development-life-cycle)
- [Reasons to Love Pull Requests](https://elisabethirgens.github.io/notes/2020/05/pull-requests/)
- [Google's Study on what makes a productive team](https://rework.withgoogle.com/print/guides/5721312655835136/)
- [Some of the challenges of managing pull requests and doing code review on a dev team](https://jessitron.com/2021/03/27/those-pesky-pull-request-reviews/)
- 📺 [A Guide to Perfecting Pull Requests](https://dev.to/karaluton/a-guide-to-perfecting-pull-requests-2b66)
- [The 7 Rules of a Great Commit Message](https://cbea.ms/git-commit/#seven-rules)

## 📽️ Slides

- [Agile slides](https://drive.google.com/file/d/11FdKfcBitBjs7R6Tqkug7oTn9NWdCltQ/view?usp=share_link)
- [Using Git & GitHub as a Team](https://slides.com/amy_nc/git-collaboration)

## 🔖 References

- [Agile Development][agile-development]
- [Creating a team charter][team-charter]
- [Managing your time][time-management]
- [Idea generation & inspiration][idea-generation]
- [Git Collaboration][git-collab]
- [Planning User Flows][user-flows]

{% include reference_links.md %}
