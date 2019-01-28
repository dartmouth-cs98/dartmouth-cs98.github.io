---
layout: page
title: Scaffolding
published: true
---



![](http://i.giphy.com/GWbMbUysgsIda.gif){: .fancy .medium}

This milestone is all about setting up some initial code scaffolding.

## Scaffolding

Now that you have your functionality mapped out let’s start on planning the coding. 

You should have the features all planned out through the user personas and feature spec in ZenHub. How do you want to build it? Plan out what technology you think you want to use and let’s get some code scaffolding ready. The project does have some minimal technical complexity that must be satisfied, but you are free to choose whatever tech stacks you wish.  *Remember no BAAS or PAAS are allowed except for the case of specialized tasks such as computer vision or ML you can initially start with a platform such as Watson/Google Cloud Vision etc.*

You should get some basics of your project up and running.  If your project has a UI try to do a little layout so that you have a main component and a hello world for the frontend and a hello world from the backend. If you have an idea of any modules and libraries you are planning on using, document them and or get them installed in your repos. At this point you should have your project code started and ready to work on.  The frameworks should be set up and running and a local development environment set up for everybody on the team. If you need multiple github repositories - you all should have permissions to create new repositories and add your github team to it. 

The goal is that everybody has the basic code frameworks up and running in a dev environment on their own machines. This includes: databases, servers, scripts, frontend, etc.  Having a local dev environment is pretty critical for rapid development.  If you need a quick code change to happen such as say a new field represented, you can just change it and test it without messing either with a shared server or waiting for someone else to make the change. 

## Readme

In your project’s main README.md file (you may have multiple repos, but for now just use the repo you’ll be using for whatever is ending up being the frontend) start to outline the tech stack you will using. As you work on the project your README.md file will be a record of the tools you are using and how to get your dev environment running.

Start this doc now:
```markdown

# Project Name

TODO: super short project description, some sample screenshots or mockups that you keep up-to-date.

## Architecture

TODO:  overall descriptions of code organization and tools and libraries used

## Setup

TODO: how to get the project dev environment up and running, npm install etc, all necessary commands needed, environment variables etc

## Deployment

TODO: how to deploy the project

## Authors

TODO: list of authors

## Acknowledgments
```

You don’t have to fill in the whole document for this milestone, but do start on it and fill in what you can. This README is for now the defacto "landing page" for your project. It should be kept up-to-date so that I / anybody can clone your repos and run your project dev environment.  This needs to be updated — this is how I will know how to set up your project to test and how your teammates will know how to get it running as well.


## Git Flow and author name/email

Note: using github will be an essential part of the final project.  We'd like you to use branches and pull requests as you work on the final project together.  You don't necessarily need to do in depth code reviews, but doing git flow with feature branches will help you organize your team and your code. Doing pull requests (PRs) is required and you will be graded on your github code contributions via commits/PRs/issues assigned+closed.

Here is a good tutorial [pull requests](https://yangsu.github.io/pull-request-tutorial/).   

Make sure that your github username and email are set correctly so that we can track your contributions. Your email needs to be [recognized in your commits by github](https://help.github.com/articles/why-are-my-commits-linked-to-the-wrong-user/#commits-are-not-linked-to-any-user).

```bash
git log
```

will show you recent commits and you should check to make sure your email is one that works and is listed as one of your emails in your github settings: https://help.github.com/articles/setting-your-email-in-git/
so that your commits are recognized as belonging to you.  Make sure you have at least 2 commits connected to your github email on this.

🚀 Make sure each team member has made a github pull request to contribute to this as we want to make sure that at this point everybody is comfortable running the starter code and contributing via git.  Yes this a team graded assignment and it is on you to keep each other accountable and submit pull requests.



## To Turn In:
* GitHub URL(s) to your repo on canvas (for grading ease)
* Code scaffolding:
  * some initial starter code
  * working hello worlds for any server/frontend/etc platforms
  * github repos set up with README.md files started
  * demonstrated use by every team member of git branches -> pull requests
