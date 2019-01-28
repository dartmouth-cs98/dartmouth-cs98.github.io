---
layout: page
title: Mockups & Data Models
published: true
---


![](https://media.giphy.com/media/povenlBAIz14s/giphy.gif){: .fancy .small}

## Mockups/Sketches

### Step 1: Paper Sketch
Based on the various features and pages you described in the feature spec, draw up sketches of each view.  Napkin style quick sketches are a good place to start. Focus more on thinking through the common actions that the users will be making rather than how and where the buttons go.  As you draw our these sketches with your team several things will come to light, features you might have missed or interactions that need to be changed.  Make your sketches comprehensive, they should cover all the views and functionality that your apps needs. Additionally you should make a site map style overview showing how the views are connected. It's more important to think through layout and functionality than making sure your color scheme or logo are perfect as you can continue to iterate on those.  Do not use wire-framing software, for wire-framing you might as well just sketch on paper, it is a waste of time to learn a separate program.

Time to take the abstract to concrete. Sketch rough layouts of screens focused on **features**.

#### Generate options as a group
* Determine which **(2-5) main features** you will sketch that are essential to your product (e.g. the feed, leaderboard, comments, etc)
* Get thick markers, printer paper, and designate a timekeeper
* Allow for **5 minutes of individual sketching per feature**, working on as many unfiltered iterations as possible in that time limit. Treat this much like improv - try not to self-edit or rule out anything just yet.
* After each round, compare sketches and create a few group versions that incorporates the best of all the ideas. Actively agree/disagree with specific elements. Aim for **2-3 versions per feature**.

#### Rules
* Use the “thick marker trick” - the thicker the marker, the more you force yourself to keep the designs at a conceptual level the better. Whiteboard markers are great here too, just take photos!
* Include little or no specific content
* Drop any worries about scale, straight lines, grids, etc.
* Think in flows whenever possible (what pages come after?)
* Match your sketches with your flow diagram - what part of the flow is not yet in the sketch?
* Never settle for your first idea!

![](img/papersketch.png){: .fancy .medium}

You can [download all sorts of device paper](http://sneakpeekit.com/) to help.

You can put all your sketches together using [Pop](https://marvelapp.com/pop/) — Prototyping on Paper, is a good way to get started without doing high quality designs and get something that you can click through.

![](img/popapp-prototype-animation.gif){: .fancy .tiny}

### Step 2: Make Prettier

Once you are ready to make it prettier just go straight into [Figma](https://www.figma.com/) (free for students).  Don't forget to [verify your student status](https://www.figma.com/student/apply).

There are many good design resources out there. Here's [one](http://cdn.ustwo.com/PPP/PP3.pdf) about pixel perfect design.

[Here's an beautiful example](https://projects.invisionapp.com/share/HABOKZQRZ#/) of a walkthough for a smaller scope 2 week project from CS52 and [a tutorial for figma](http://cs52.me/workshops/design).  And another cool mockup for a [project that did AR](https://projects.invisionapp.com/share/K6AR2EJ5U).  There are in Invision - but you can do the same in Figma like so:

<iframe style="border: none; " width="300" height="500" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FOSX6FgNYF0vY11cfl1P9qO%2FSommelier%3Fnode-id%3D0%253A1%26scaling%3Dscale-down" allowfullscreen></iframe>
<iframe style="border: none;" width="300" height="500" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FFYyrExk1nzz4Jo9yLYO54iEd%2FRecycleIt-Mockups%3Fnode-id%3D0%253A1%26scaling%3Dscale-down" allowfullscreen></iframe>


## No User Interface? No Problem

Some products may not have what you would think of as a traditional user interface: maybe it is a code library,or a physical device that has certain behaviors.  However, these still have a user facing aspect.  If it is a code library — this is a time to map out your public API - function calls or http endpoints are your user interface.  If it is a physical device with certain behaviors - map out what those are and what is the control interface.  You can storyboard any interactions / behaviors so that there is a plan of attack. Additionally, you can use this opportunity to design any materials that communicate what your device does to the outside world.

## Team Name & Logo

This is also a great time to start on a team/product name and create a logo. Logo's can be both difficult and easy to come up with.  There are [7 different types of logos](https://99designs.ca/blog/tips/types-of-logos/), but some of them are easier than others to create.  Try taking your name and write in a nice font in Figma, then edit the contours of the letters/move them around/zoom in.  Use some of the [icons in the Design Templates](https://www.figma.com/file/9jbm8rHDqoEpXZTLnXp7To/Evericons?node-id=0%3A1) project.  Play around with colors and voila you will have a logo.  Doing a wordmark 

For the end of this term - we're going to try printing out t-shirts for every team. These will be in a particular format that we'll send out a tutorial on.  For now you can draw some sketches, and start working on something in Figma. 


## Site Map / Flow Diagram / Interactive Prototype

A flow diagram documents the tasks the user will perform, in relation to each other and over time. Create flows for the primary tasks, but keep this in sketch or text form (best to not dwell on how it looks at this stage but rather how these elements connect to each other).

![](img/flowdiagram.png)

Checkout what [polished versions](https://speckyboy.com/collection-inspiring-sitemaps-user-flow-maps/) looks like for some inspiration.


### Interactive Prototype Instead

You have the choice of either drawing it out like the above. OR you can [create a clickable prototype in Figma](https://help.figma.com/article/199-getting-started-with-prototyping).  Since you already have things set up in Figma with views or storyboard elements, you can create simple interactive connections between them.  This allows you both to see how everything connects, but also you can show your product to people and get feedback. See the above Figma examples. 


## Data Models
This is also a good time to plan out some of your data models.  Consider what data you need for your project and figure out some of the fields and objects.  You don't need to create a full relational model, but do consider what your data should look like. Describe the objects you think you will need (an informal schema for your data).  Create a Wiki page called  `Data Models` you plan out.

```javascript
user: {
  id,
  name,
  bday,
  favorite_animal
},
post: {
  author: user.id,
  title,
  date,
  content,
  image_url
}
```

Your project may or may not have data that needs to be serialized or saved to a server, but most likely it will have some data structures that you need to think about. Think about these and write them down — you'll be able to alter them later, this is just a start.


## To Turn In:
* 3 Wiki Pages:
    * Sketches:  Initial sketches of each view of your product (photos of paper) posted on github wiki
    * Mockups:
        * Higher fidelity mockups submitted as [figma](https://www.figma.com) links - link from your github wiki!
        * A flow diagram/site map showing how your views interconnect (can be hand drawn) or can just be Figma connection prototype.
    * Data Models
* Submit urls to each wiki page on canvas
