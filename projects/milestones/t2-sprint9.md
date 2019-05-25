---
layout: page
title: Sprint 9
published: true
---


## Overview 

This is the time to close out our sprints!

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

Last retrospective!  

Have a time to discuss what is working and what isn't.  Include a summary of this when you submit this!

🚀 Create a wiki page:  `Sprint Retrospectives Term 2` 

Here's a template for what to add every week:

```markdown
* Retrospective on Sprint #_: 
    * members in attendance:
        ![selfie proof of meeting]()
        - [x] Jasmine
        - [ ] Alladin
    * what worked well
        * we made progress
        * etc
    * what didn't
        * we didn't make much progress
        * etc
    * self assessment on progress
        * put down any last things you need to do before demos
        * are you ready?
```


## Planning! 

Plan any last steps you need to get you to demos and beyond, put them in ZenHub! Set a `DEMOs` milestone and make it due Wednesday at 6pm!

## To Turn In:
* submit zenhub link to your workspace
* submit wiki page link to your retrospective