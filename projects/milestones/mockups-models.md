---
layout: page
title: Mockups & Data Models
published: true
---


![](https://media.giphy.com/media/povenlBAIz14s/giphy.gif){: .fancy .small}


## Mockups/Sketches

### Step 1: Paper Sketch
Based on the various features and pages you described in the feature spec, draw up sketches of each view.  Napkin style quick sketches are a good place to start. Focus more on thinking through the common actions that the users will be making rather than how and where the buttons go.  As you draw our these sketches with your team several things will come to light, features you might have missed or interactions that need to be changed.  Make your sketches comprehensive, they should cover all the views and functionality that your apps needs. Additionally you should make a site map style overview showing how the views are connected. It's more important to think through layout and functionality than making sure your color scheme or logo are perfect as you can continue to iterate on those.  Do not use wireframing software, for wireframing you might as well just sketch on paper, waste of time to learn a separate program.

Time to take the abstract to concrete. Sketch rough layouts of screens focused on **features**.

#### Generate options as a group
* Determine which **(2-5) main features** you will sketch that are essential to your product (e.g. the feed, leaderboard, comments, etc)
* Get thick markers, printer paper, and designate a timekeeper
* Allow for **5 minutes of individual sketching per feature**, working on as many unfiltered iterations as possible in that time limit. Treat this much like improv - try not to self-edit or rule out anything just yet.
* After each round, compare sketches and create a few group versions that incorporates the best of all the ideas. Actively agree/disagree with specific elements. Aim for **2-3 versions per feature**.

#### Rules
* Use the “thick marker trick” - the thicker the marker, the more you force yourself to keep the designs at a conceptual level (it’s difficult to add in details when the marker tip is so large!). Whiteboard markers are great here too, just take photos!
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

Once you are ready to make it prettier just go straight into a tool like [Figma](https://www.figma.com/) (free for students) or Sketch (I recommend Figma though). [Invisionapp](https://www.invisionapp.com/) is a nice way to put your designs together.

There are many good design resources out there. Here's [one](http://cdn.ustwo.com/PPP/PP3.pdf) about pixel perfect design.

[Here's an beautiful example](https://projects.invisionapp.com/share/HABOKZQRZ#/) of an invision walkthough for a smaller scope 2 week project from CS52 and [a tutorial for figma](http://cs52.me/workshops/design).  And another cool invision mockup for a [project that did AR](https://projects.invisionapp.com/share/76AJI0NJN).

## Site Map / Flow Diagram

A flow diagram documents the tasks the user will perform, in relation to each other and over time. Create flows for the primary tasks, but keep this in sketch or text form (best to not dwell on how it looks at this stage but rather how these elements connect to each other).

![](img/flowdiagram.png)

Checkout what [polished versions](https://speckyboy.com/collection-inspiring-sitemaps-user-flow-maps/) looks like for some inspiration.  You can have your flow diagram be your Invision or Pop Paper connections.

## Data Models
This is also a good time to plan out some of your data models.  Consider what data you need for your project and figure out some of the fields and objects.  You don't need to create a full relational model, but do consider what your data should look like. Describe the objects you think you will need (an informal schema for your data).  Create a Wiki page with the data models you plan out.

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

## To Turn In:
* Sketches of each view of your product (photos of paper)
* Higher fidelity mockups submitted in [invisionapp](https://www.invisionapp.com/) or [figma](https://www.figma.com) links - link from your github wiki!
* A flow diagram/site map showing how your views interconnect (can be hand drawn) or can just be invision/figma connections.
* Data Models on a Wiki page
* Submit urls to each wiki page on canvas
