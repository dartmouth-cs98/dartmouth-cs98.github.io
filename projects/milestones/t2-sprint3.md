---
layout: page
title: Sprint 3
published: true
---



## Overview 

This is the time to transition to the next sprint!  This will involve a short review and team retrospective and planning next steps. 

You should have an in-person team meeting and resolve all your currently working on tasks as best you can in preparation for this meeting.  All your previous sprint assigned issues and feature pull requests should be reviewed and merged into master so you can demo your work.

### Review

During the meeting you should each demo your week's work to your team. It is nice to use this moment to celebrate accomplishments, clap loudly for your teammates and support each other.

This is a good time to get immediate feedback as well — so try the features out and if there are bugs, put them in ZenHub!

### Tag Sprint Version in Master

Don't forget to tag a working end-of-sprint version of your repos. Merge working features that you are closing into your `master` branch (if you have a different naming scheme let us know),  make sure that each repo is in a **buildable** state (compiler checks pass, the project can be run).  Then apply a tag with the name of the sprint you are closing. Use the following naming convention: `t2.sprint#` 

#### Using git tags

```bash
#make sure you are in your master branch
git diff #make sure you are all committed and pushed
git tag t2.sprint1 #this will tag the current place you are at as t2.sprint1
git push origin --tags
```

## Retrospective 

🚀 Discuss what is working and what isn't and then summarize your meetings notes in the below format.

🚀 Create a new Issue titled:  `Sprint Retrospective Term 1 - Sprint #`

Here's a template:

```markdown
* Sprint #_ Retrospective: 
    * members in attendance:
        ![selfie proof of meeting]()
        - [x] Jasmine
        - [ ] Alladin
    * what worked well
        * we made progress
        * ![post some progress screenshots]()
        * etc
    * what didn't
        * we didn't make much progress
        * etc
    * self assessment on progress
        * where are you in relation to progress towards product and milestones? 
          * give an estimate of how far towards your goals you are, do you think you're on track? 
        * lay out *each* of the following weeks till end of term with brief goals for each
          * current week: goals
          * week #: goals
          * week #: goals, etc
    * briefly summarize any other topics/discussions
```

Each week you will create a new issue that will summarize your sprint. 

🚀 Assign `@{{ site.github_username }}`, `@{{ site.ta_github_username }},``@{{ site.ta2_github_username }},` to the issue so we can review and give feedback. Thanks!  


## Planning / Rake Your ZenHub Garden

Now plan out your next steps.  Add in *Unsorted* new issues, sort them into *Later* and *Next*.  Assign at least 4 issues per person.

During this step you should follow the [Rake Your ZenHub Garden](wiring-start-sprint#rake-your-zenhub-garden) steps. You'll do this every week.

1. 🚀**Create New Sprint Milestone**
1. 🚀**New Bugs**
1. 🚀**Update Epics**
1. 🚀**New Subtasks**
1. 🚀**Process All Issues**
1. 🚀**Assign Subtasks**


## To Turn In:
* submit zenhub link to your workspace
    * showing new assignments
    * and all of your previous sprint finished!
* submit wiki page link to your retrospective