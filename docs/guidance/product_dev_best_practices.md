# Product Development Best Practices

The degree of complexity and uncertainty, the number of contributors, and the management and control needs of an open-source project are just some of the factors that can influence the choice of a process to manage contributions for product development. A project team is invited to use any process they are most comfortable with, however considering the bellow list of best practices may help the adoption of enhancements to the processes. 

## 📝 Communication and Documentation 

Effective and open communication within the project team is key for a clear product development process. Documentation allows for knowledge transfer, of everything that is known, and of what has been produced so far, so that others can productively build upon it. There should be an effort to create a transparency with communication and documentation early on.

- Define and document process(es) and guideline(s) of the project that contributors need to be aware of.
- Ensure that documentation is always kept up to date.
- Ensure that expectations are, whenever possible, always communicated in the written format.
- Define a communication channel (MS Teams, Slack as examples) for the project.
- Document your communications, whether done online or offline, and make them visible somewhere in the project repository or in the communication channel.

> :interrobang: Other channels can be used for communications as long as the interactions and decisions are documented and accessible to contributors.

## 👩🏽‍💻 Onboarding New Contributors to an Open Source Project

During the course of an open-source project, many contributors may join, and their engagement can be strengthened if they are able to become productive within the shortest amount of time. To make it possible, contributors need to be onboarded in an efficient manner that helps them understand what is needed and expected.

- Make available helpful information to onboard new contributors, including:
  - A short version describing what is being done (that is, the product), for who, and why;
  - The project vision with the scope and links to the roadmap;
  - A summary of the contribution needs, clear instructions on how to contribute, and how to get started with the project;
  - An outline of the approval process for contributions;
  - Links to other project information that will be useful to contributors; and
  - Links to the communication channel for anyone who needs help and wants to ask questions.

> :bangbang: Ensure that all project information is easily found by new contributors.

## Roles

There are many ways to contribute to an open-source project that are not only related with development.

- Describe how contributors can add value to the project by listing the roles and associated responsibilities or contributions that are being sought after.
> :memo: As an example:
> - Programmers: to write code that addresses software gaps or fixes bugs.
> - Documentation writers: to create or update project or product documentation, or to translate the documentation into other languages for a worldwide audience.
> - Marketing experts: to generate project’s visibility and resources by creating how-to articles, producing videos and screencasts, promoting the project in the media, writing blogs and newsletters, issuing press releases, and so on.
- Identify key contributors that can take up certain leadership responsibilities, such as overseeing the project, reviewing contributions, determining the roadmap, and ensuring the community is a positive and inclusive space.

## ✨ Maintaining a Product Roadmap

The product roadmap is a document that outlines the strategic direction of a product with the intent of aligning stakeholders and project teams on what will be delivered. It should be the source of truth to communicate the vision, direction, priorities, and progress of a product over time. Depending on the complexity of the product to be built, the roadmap can be as simple as a collection of issues in the issue tracker or a detailed timeline with milestones.

- Ensure that the product roadmap is centered around the big picture and problems to solve, not solutions to those problems.
- Review the roadmap frequently, to ensure that is up to date and remains clear and easy to understand.

> :bangbang: Ensure that the parts of the product the contributors can immediately start working on are identified.

## Issue Tracking

The purpose of tracking an issue is to keep track of features, tasks, user stories, bugs, and so on, that are part of the roadmap and project backlog.

- Ensure that the issues being tackled are aligned with the priorities defined in the roadmap.
- Describe the protocol to report/ create issues.
- Whenever possible, define and make available templates for each type of issue within the project.
- Determine the status that can be assigned to an issue for each step of the development cycle, such as new, in analysis, prioritized, in execution, in testing, done.

> :bangbang: Ensure that the tool used to track the issues can be accessed by the contributors.

## 💻 Development Tracking 

There are many methods that can be used by a team to track the development of a product. Two examples of those methods are suggested: 

### Sprints

Sprints are short, time-boxes of iterations to execute work within a project. The team determines the amount of work that can be delivered during each fixed window of time.

- Avoid committing to execute more work than what is possible for the team to do within the sprint
- Avoid prioritizing work with unresolved dependencies

> :interrobang: Ensure that issues to be worked on have the appropriate size to be completed within the sprint.

### Kanban

Kanban is a method in which items are pulled from a backlog and are started when other work items are completed.

-	Ensure that work, workflow, and risks are visible to contributors.
-	Limit the number of items that can be in progress at any point in time (work-in-progress), that means that new items of work can only be pulled in for development when there is enough capacity to deliver it.

> :bangbang: Kanban board is the name of the tool used to manage the issues in development, helping to visualise work, limit work-in-progress, and maximize efficiency of development.

## ✅ Pull and Merge Requests 

A pull request allows a contributor to tell others about the changes that were pushed to a branch in a project repository. Once a pull request is opened, the potential changes can be discussed and reviewed with other contributors and follow-up improvements can be added before all changes are merged into the main project repository (also known as main branch). 

- Describe the protocol to submit pull and merge requests, what response will be given, and expected timelines.

> :heavy_exclamation_mark: For more information, on submitting a pull request, please see the [Contributing Page](https://github.com/WorldHealthOrganization/open-source-communication-channel/blob/main/CONTRIBUTING.md) in this repository.

## ☑ Testing

When a product or a component of a product is developed, it is important to validate if it meets the proposed objectives and functions as intended.

- Describe how to test and where tests are located.

> :interrobang: When possible, use tools to automate testing.

## Resources
For more information on the above topics, please check the following links:
- [Building Welcoming Communities](https://opensource.guide/building-community/)
- [Attract contributors to your open source project with authenticity](https://opensource.com/article/22/6/attract-contributors-open-source-project)
- [Managing the open source product roadmap](https://opensource.com/article/21/9/open-source-product-roadmap)
- [15 Best Practices for Product Roadmaps](https://terem.tech/15-best-practices-for-product-roadmaps/)
- [Tips for managing your project's issue tracker](https://opensource.com/life/16/7/how-take-your-projects-github-issues-good-great)
- [The Value of Open Source Sprints, the scikit-learn Experience](https://blog.scikit-learn.org/events/sprints-value/)
- [The Official Guide to the Kanban Method](https://kanban.university/kanban-guide/#kanban-method)
- [About pull requests](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-pull-requests)
