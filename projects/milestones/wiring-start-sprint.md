---
layout: page
title: Implementation & Data Wiring Sprint Plan
published: true
---


![](http://i.giphy.com/3o6MbnG1lpwIf5stB6.gif){: .fancy .small}


## Overview

For this milestone the main idea is to get a "deep" wiring of your project components.  If you have a frontend and backend, make sure they can talk to each other.  If you have computational elements and display elements, this is the time to move past mockup data and have the display use the computed data.  You should have the full data path demonstrated and working. 

The idea is to have all rudimentary functionality in place. For instance if you were building a web or mobile app there should be frontend components hitting api endpoints that are pulling data from the database. You should have all the components/views planned out and started in code even if they are simple placeholders. You should be at the point where you have some of your presentational components (UI) laid out and have started on wiring things together with any data sources such as your api server (or computational/algorithmic logic depending on your project).

* If you have an *api/client setup*, then client should be able to make requests to server
* If there is a *database*, then it is storing real data and your code uses results of queries
* If some *computational or sensor components* they should be wired in and have working input/output that you handle.


## Your First Official Sprint!

Starting this week and ongoing for the next 16 weeks or so, we will be doing weekly sprints!   A sprint is a development iteration cycle in the agile project framework.  We'll be doing a somewhat simplified version of this in that we'll combine a few different steps together. 

Here's how it will work. 

1. Sprint Planning (start of week)
2. Work on Sprint (during week)
3. Sprint Review+Retrospective (end of week)
4. GOTO 1. 

You are welcome to do 1+3 in one big team meeting, say Sunday night, since you are really recapping the week and then planning the next.


## Scope and Assignment Q/A


❓ When should you use GitHub issues?<br>
✅ ALWAYS!

❓ What is the right scope for an issue?<br>
✅ Each issue should be scoped to be around 1 sitdown work session, just a couple hours. Break up large tasks into individual smaller ones, each one should be under a few hours of work. You can think of issues as individual tasks: "create login button",  "api endpoint for user profile", etc.  Issues can also be bugs that you find along the way. Convert large tasks into **Epics**.  The smaller the tasks the actually faster you will work (not just the appearance of speed). It is easier to take on a manageable scope issue and work through it than if the issue has multiple steps that quickly become overwhelming to think through.

❓ Should I assign my teammates to issues?<br>
✅ Yes! You should assign people to each issue as you work on them so your team knows who is doing what. Feel free to assign each other tasks, a little aggressiveness is ok!  

❓ Can I use comments on issues to coordinate with my team?<br>
✅ Yes! You can interact via comments on the issues, on a good project the board will feel like a community, people upvoting and clapping for each other, discussing the issues, or how best to implement something. EC: mention @timofei7 or @ksalesin in an issue or a PR when you need help or feedback or want to say hi. We're happy to help — and since this was a wall of text we'll know that you happened to read it all. 

❓ Can I just use groupme to tell people what to do?<br>
⛔️ No! You can discuss things to do for sure, but you should always use zenhub to keep track of who is working on what. Also you should be using Slack not groupme, we're all in this together.

<br>

![](img/rocks.gif){: .fancy .small}


🚀 Remember a part of your grade is usage of issues - once your project gets rolling you should shoot aim for closing 5 issues per week per person.  This should give you a sense of the scope of an issue. If each issue is under 2 hrs then 5 issues is around 10 hours.  This isn't a hard and fast rule - but try to do this on average.


## Motivation 

🚂 Consistency in using a task manager style tool is hard. But here's the motivation — this is a very common approach — and in our case we'll also be using issue engagement and closure (together with PRs/commits) as grade metrics.  But at least we won't be doing [stack ranking](https://www.businessinsider.com/stack-ranking-employees-is-a-bad-idea-2013-11)! 😑


## Rake Your ZenHub Garden

Go through ZenHub and organize! 

![](img/pufferfish.gif){: .fancy .small}
![](img/puffer2.gif){: .fancy .small}


1. 🚀Go through **ALL** your current *New Issues* and [deal with them](feature-spec#default-pipeline-breakdown).
    * Either sort them into *Icebox* if you aren't going to work on them soon.
    * *Backlog* if they are something to work on next.
    * *InProgress* for the specific tasks you are currently going to work on.
    * Close issues that are old or deprecated. 
1. 🚀Enter in any bugs that you currently have:
    * create new issues (select the appropriate repo "Create in ..." if associated with a particular repo).
    * label them with a <span style="color: red;">🐛bug</span> label [*(create new labels)*](https://help.github.com/en/articles/creating-a-label)
    * you can break them down further with:
        * <font style="color:red">[ 🔥 blocker]</font>
        * <font style="color:orange">[ ❗️important]</font>
        * <font style="color:lightblue">[ 🍲 back burner]</font>
        * <font style="color:grey">[ 🙅won't fix]</font>
1. 🚀Enter in any **design** feedback you got last week that isn't already in Figma directly:
    * label them with a <span style="color: purple;">[design]</span> label
1. 🚀 Prioritize your Epics/Create new Epics based on the mission this week (to wire it all together):
    * See [Epics](feature-spec#create-epics) to review
    * Use epics for any large task with subtasks that need to be broken out.
1. 🚀Enter in any new feature ideas / create issues for any *Epics* you want to tackle this week.
    * create new issues (select the appropriate repo "Create in ..." if associated with a particular repo) for each new feature idea you had via feedback last term, or as you brainstormed earlier in this milestone.
    * label them with a <span style="color: blue;"> 💎enhancement</span> tag or others as you see fit.
1. 🚀Create a milestone:
    * create a new milestone and label it `sprint 1 - wiring` with a due date of `2/10/2019`.
    * take at least 4 issues per person that fit with the goals of this week and assign them to this milestone.
    * now you'll be able to track progress toward the milestone!  and get graded on it! 🏄
1. 🚀 Finish prioritizing:
    * Add in *New Issues*, sort them into *IceBox* and *Backlog*.  Assign at least 4 issues per person.

**More about good agile workflow [here](https://help.zenhub.com/support/solutions/articles/43000010338-agile-concepts-in-github-and-zenhub).**

**4 issues each?!?!**

Well yes, you gotta make progress right? Gotta make it to DEMOS! If every issue takes 2 hours (a nice casual sitdown work session), then there are you are at 8 hours. That leaves a few hours for things taking a bit longer to do / team meetings and discussions.


## Design Feedback and Updates

Last week we did a round of feedback on designs that we took notes on.  Some of these may be on paper, some you may have put in Figma, and there may be others from grading added to the Figma.  

🚀 Create a new Epic `update designs` if there is a lot of feedback.  Add the issue(s) to your current sprint. 

✋ What do you mean "resolve"?  Well, you should at least respond to each Figma comment with some words, but in most cases this means updating your designs to correspond with your current plans as well as any changes that came up in discussion last week, or in the grading feedback for mockups.


## And a couple of small things

### README.md

Make sure your README.md files are updated with the current installation and deployment instructions as well as any architecture changes. This will be a small part of every milestone, you should always keep it up to date as the README is where your graders start to get it running locally for testing.

### Continuous Integration / Testing (optional)

You could set up Travis CI for your project with automatic linting / build checking. If you are writing for the web - set up your project with [eslint](https://eslint.org/).   Whenever you push to github it will automatically run eslint. There are automatic build runners for most languages. This is optional but can be helpful - especially linting.  You can have Travis CI run other stuff/tests. For web here's a small howto on how to set up [Travis](http://cs52.me/resources/travis).


## To Turn In:
* make sure you have a plan for deep connection test of your components, if api/client that they are making requests to each other, if database that it is storing something and your api uses it somehow, if some computational or sensor components make sure you are getting inputs. 
* do all the steps in the [ZenHub section](#rake-your-zenhub-garden), don't forget to label as we'll be checking for those.
* submit zenhub link to your workspace with a filter set

## Keep up the good work, you're all rockstars

![](img/notarockstar.gif){: .fancy .medium-small}

