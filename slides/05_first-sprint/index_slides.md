layout: true
class: center, middle
name: pic
background-size: contain

---

layout: true
class: center, top
name: fragment

.title[{{name}}]

---
layout: true
class: center, middle
name: base

.title[{{name}}]



---
name: Planning our first sprint


.fancy.small[![](../../projects/milestones/img/rocks.gif)]

* Sprint retrospectives are due every Monday night
* Idea for this first one is to connect your components (client <-> server <-> db)

???
*

---
name: Sprint Retrospectives Every Week

* Sprint #_ Retrospective: 
    * members in attendance:
        <div style="width:100px;">![selfie proof of meeting](img/teamselfie.png)</div>
        - [x] Jasmine
        - [ ] Alladin
    * what worked well
        * we made progress
    * what didn't
        * we didn't make much progress
    * self assessment on progress
        * how is your progress? 
        * tentative plan for upcoming weeks
          * current week: goals
          * week #: goals
          * week #: goals, etc
    * briefly summarize any other topics/discussions


---
name: Create a Milestone

.fancy.left[![](img/milestones1.jpg)]
.fancy.right[![](img/milestone2.jpg)]

???
* milestones are by time - weeks
* epics are by subject - features

---
name: Rake Your ZenHub Garden 🌻


1. **Create a new sprint milestone**
1. **New Bugs**
1. **Enter Feedback**
1. **Update Epics/Roadmap**
1. **New Subtasks**
    * create new issues
    * label them
    * assign a time estimate
1.  **Process All Issues**
    * **Later** *(Icebox)*
    * **Next** *(Backlog)*
    * **In Progress**
    * no unsorted **Unsorted** *(New Issues)*.
    * update time estimates
1. **Assign Subtasks**


???
* i know there's a lot of text in the milestone... but its not rocket science - you just have to maintain a current sprint and issues that are sorted
* as the week goes you can add issues into the new issues pile and wait until the retrospective to sort them out
* each subtask is one code session or thereabouts
* using milestones will give you a way to group your weekly tasks even when the are just parts of epics - remember epics are for long feature - milestones group tasks by week - so you can see the progress you are making 


---
name: Your Zenhub Board

![](img/zenhub.jpg)

???


---
name: Your Epics

![](img/epics.jpg)

???



---
name: Scaffolding

.fancy.left[![](img/microservice.png)]
.fancy.right[![](img/gitflow.png)]

.right[
* readme.md
* starter code for every part of project
* hello world from client, server, etc
* github pull request flow -> zenhub issue
]

???
* due thurs


---
name: Deep Wiring

.fancy.left[![](img/mr2.jpg)]
.fancy.right[![](img/mr1.jpeg)]


???
* connect database to server to client
* try out some difficult component
* deep connection