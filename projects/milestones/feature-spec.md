---
layout: page
title: Feature Spec
published: true
---


![](img/feature_spec.gif){: .fancy .medium}

The feature spec is a document that is a walk-though of your project from the users perspective. It provides a listing of all the features you are envisioning for the product. The feature spec functions as your overall plan for the project. Rather than thinking about it as locking you in, use this as an opportunity to think through your product in detail. Think of it as a living document, don’t be afraid to change it later as your ideas about the project mature. It does not need to be an exhaustive document. Joel Spolsky (of Stackoverflow and more recently Trello) has a nice writeup of the why and how of specs here: [joelonsoftware](http://www.joelonsoftware.com/articles/fog0000000035.html). He references an [overly long example](http://www.joelonsoftware.com/articles/WhatTimeIsIt.html). We’ll simplify things a little bit and keep our document shorter and although he says only one person should write the spec, you should definitely do this as your whole team!  Here's some more [tips on feature specs](https://medium.com/dali-lab/9-ideas-for-more-useful-feature-specs-7ca5c679ca3c).

For our needs — the feature spec is a listing of what you think you need to build this term to be able to prove out your idea. 

Rather than creating a separate document for this — we're going to use [ZenHub](https://www.zenhub.com/)!  Wait what is this ZenHub thing?! Not another tool!  ❌

## ZenHub! 

<iframe class="fancy" src="https://player.vimeo.com/video/207024351" width="640" height="351" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

ZenHub is a tool built on top of GitHub Issues to make them better. GitHub issues are decent on their own, but they are hard to keep track of when you have a lot (just a long list) and it is hard to know who is currently working on what, or to assign due dates to things.  Milestones within GitHub are ok, but also not great.  ZenHub fixes all of this, and is powered by GitHub issues underneath it all, so you can connect/[close them with Pull Requests](https://blog.github.com/2013-05-14-closing-issues-via-pull-requests/). 

![](img/zenhub-board.jpg){: .fancy .medium}
<br>*(a well utilized DALI ZenHub board)*

There are two different ways to use ZenHub - you can either download a [Chrome Extension](https://www.zenhub.com/extension) and then ZenHub appears in the GitHub interface for you automagically. Or you can log in via [zenhub.com](https://app.zenhub.com) - just log in via github, choose **dartmouth-cs98** as your Organization,  change workspace to one of your repos.  It should already be set up that there is a workspace named for your project that is connected to your repos.  This means that all your issues show up (under *New Issues*). 

### Features of ZenHub:

![](img/release-velocity.jpg){: .fancy .medium}
<br>*(release velocity planning in ZenHub)*

* **cohesive**: all your issues from multiple repos appear in 1 workspace
* **pipeline**:  assignments are different from what is currently being worked on - move an issue to *In Progress* when you are working on it. Feel free to claim or assign others to issues. More on pipelines below. 
* **duedates / milestones**: to assign a date to a group of issues you can create a *Milestone*. Milestones should be thought of as sprints,  sets of tasks with a common due date.  Makes sense to have them similar to milestone due dates.
* **epics**: You can also use *Epics* to group sets of smaller tasks.  If a single issue seems too big - *convert to epic*.
* **reports**: One you have milestones you can see an estimate of how quickly you'll finish all your tasks.
* **dependencies**: You can make issues dependent on other issues, so if you have a task that requires someone else to do something you can mark that so they know they are blocking you. Very helpful!


### [Default Pipeline Breakdown](https://help.zenhub.com/support/solutions/articles/43000010339-setting-up-your-first-zenhub-workspace): 

![](img/zenhub-for-class.jpg){: .fancy .medium}
<br>*(starting to use ZenHub for class feedback)*


* **New Issues**:<br>
    New Issues land here automatically. You should drag (triage) them out of here as soon as possible.

* **Icebox**:<br>
    The Icebox represents items that are a low priority in the product backlog. Leaving Issues in the icebox over deleting them helps avoid a cycle of raising duplicate Issues. Icebox Issues should not take up a team member's time or mental bandwidth; putting ideas into the Icebox Pipeline gets them out of the way and helps teams focus on immediate priorities.

* **Backlog**:<br>
    Backlog Issues are not a current focus, but you will act on them at some point. If they don't have a GitHub Milestone, you can consider them part of your “product backlog”. Once you add a Milestone, they become part of your “sprint backlog” (that is, the tasks that you'll complete in an upcoming sprint.) The process of keeping this pipeline organized is known as “backlog refinement”.

* **In Progress**:<br>
     Issues here should have a good amount of detail, like estimates and requirements, since they're your team's current focus. This is the answer to, “What are you doing now?” Ideally, each team member should be working on just one thing at a time. Tasks here should be ordered by priority with Assignees added.

* **Review/QA**:<br>
    Use the Review/QA column for Issues that are open to the team for review and testing. Usually this means the code is ready to be deployed, or already is in a Staging environment.

* **Done Issues**:<br>
    in this pipeline need no further work and are ready to be closed. Having a good ‘Definition of Done’ agreed upon before work starts on an Issue is very helpful here! If there were any objectives or key metrics associated with the Issue, they can be appended prior to closing.


*Outline a proposed development strategy with general feature milestones. Identify minimum viable product (MVP) features and optional stretch goals. Create a list of features that are needed to be able to do some product validation. At the end of the term you'll need to show something that is testable or viewable by a public audience.*

🚀 Create a wiki page `Feature Spec` and use the following template. You may modify it as you see fit. Most of these you will pull from your user personas.  


```markdown
# Feature Spec

## Critical Features
*These are the primary most important features. The product doesn't have a purpose without these features. These are sometimes the harder things, but the most necessary to start tackling early to get validation. Try to list these in order that they happen in the user experience.*

* list your features | priority 1-10 | estimate effort 1-40 (1 person hours-ish)
* main functionality thing | priority 10 | effort 12
* other thing | priority 3 | effort 2

## Secondary Features
*These are features that make the product more usable, but can be hacked around if necessary. Things like login/auth might go here (unless you are building a security product).*

* list your features | priority 2 | effort 1

## Stretch Goals
* Self explanatory. Things not quite critical but would be really cool.

* list your features | priority 2 | effort 1

```


## To Turn In:

* GitHub repository URL to wiki page you created that includes: