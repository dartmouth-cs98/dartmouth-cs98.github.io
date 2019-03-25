---
layout: page
title: Sprint 4
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

Have a time to discuss what is working and what isn't.  Include a summary of this when you submit this!

🚀 Create a wiki page:  `Sprint Retrospectives Term 2` 

Here's a template for what to add every week:

```markdown
* Sprint #_: 
    * members in attendance:
        - [x] Jasmine
        - [ ] Alladin
    * what worked well
        * we made progress
        * etc
    * what didn't
        * we didn't make much progress
        * etc

```

You'll update this weekly during your sprint transitions! 


## Planning

Now plan out your next steps.  Add in *New Issues*, sort them into *IceBox* and *Backlog*.  Assign at least 4 issues per person.

**4 issues?!?!**

Well yes, there is no other milestone other than making progress. If every issue takes 2 hours (a nice casual sitdown work session), then there are you are at 8 hours. That leaves a few hours for things taking a bit longer to do / team meetings and discussions.


## To Turn In:
* submit zenhub link to your workspace
    * showing new assignments
    * and all of your previous sprint finished!
* submit wiki page link to your retrospective