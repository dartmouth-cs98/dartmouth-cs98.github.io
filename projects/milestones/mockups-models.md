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

🚀 The following is a sketch generating process to use with your whole team to create some initial ideas and sketches of your product.

#### Generate options as a group
* Determine which **(2-5) main features** you will sketch that are essential to your product (e.g. the feed, leaderboard, comments, etc)
* Get thick markers, printer paper, and designate a timekeeper
* Allow for **5 minutes of individual sketching per feature**, working on as many unfiltered iterations as possible in that time limit. Treat this much like improv - try not to self-edit or rule out anything just yet.
* After each round, compare sketches and create a few group versions that incorporates the best of all the ideas. Actively agree/disagree with specific elements. Aim for **2-3 versions per feature**.
* Finally narrow in on your core set of sketches and digitize them (see below for uploading to Figma).

#### Rules
* Use the “thick marker trick” - the thicker the marker, the more you force yourself to keep the designs at a conceptual level the better. Whiteboard markers are great here too, just take photos!
* Include little or no specific content
* Drop any worries about scale, straight lines, grids, etc.
* Think in flows whenever possible (what views or steps come after?) — you can sketch these out and include them.
* Match your sketches with your flow diagram - what part of the flow is not yet in the sketch?
* Never settle for your first idea!

![](img/papersketch.png){: .fancy .medium}

You can [download all sorts of device paper](http://sneakpeekit.com/) to help.  You can also use color foam for this if you like! 

### Figma! 

We'll be using [Figma](https://www.figma.com/) (free for students) to record sketches as well as do all of our mockups. Don't forget to [verify your student status](https://www.figma.com/student/apply).  *Note: Make sure to create your project in the CS98 Figma Team - and don't create multiple projects.*

[Here's and a basic tutorial for figma](http://cs52.me/workshops/design).

*Additional reading: There are many good design resources out there. Here's [one](https://www.ustwo.com/blog/the-pixel-perfect-precision-handbook) about pixel perfect design.*

#### Record and Upload Sketches

Take pictures / scans ([Scannable](https://apps.apple.com/us/app/evernote-scannable/id883338188)) of your sketches and upload them to Figma.

🚀 Create a [Figma Page](https://www.figma.com/blog/introducing-figma-pages/) called `Sketches` and within that upload your sketches so they are all in one place.  You can play around with linking them via the prototype tool if you want.

### Step 2: Make Prettier

Now that you have some sketches - you can jump into making them digital and prettier in Figma. 

🚀 Create a new *Page* in Figma called `Mockups` under your project which is under the CS98 Figma team. 

🚀 In this page create [*Frames*](https://help.figma.com/article/36-frame-tool)for each of your views. This will allow you to choose your screen size and also to use the prototyping tool later on.

<iframe style="border: none; " width="300" height="500" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FOSX6FgNYF0vY11cfl1P9qO%2FSommelier%3Fnode-id%3D0%253A1%26scaling%3Dscale-down" allowfullscreen></iframe>
<iframe style="border: none;" width="300" height="500" src="https://www.figma.com/embed?embed_host=share&url=https%3A%2F%2Fwww.figma.com%2Fproto%2FFYyrExk1nzz4Jo9yLYO54iEd%2FRecycleIt-Mockups%3Fnode-id%3D0%253A1%26scaling%3Dscale-down" allowfullscreen></iframe>

Here's [an example of an AR mockup](https://projects.invisionapp.com/share/K6AR2EJ5U)) that didn't have as clear of a 2D user interface. 

## No User Interface? No Problem

Some products may not have what you would think of as a traditional user interface: maybe it is a code library,or a physical device that has certain behaviors.  However, these still have a user facing aspect.  If it is a code library — this is a time to map out your public API - function calls or http endpoints are your user interface.  If it is a physical device with certain behaviors - map out what those are and what is the control interface.  The way to approach this is with [storyboards](https://www.figma.com/file/m0FcTyyuadp4S8FS8H8lyb/Storyboard-Design-Exercise).  You can sketch and annotate any interaction flows. Storyboard any interactions / behaviors so that there is a plan of attack. 

Additionally, you can use this opportunity to design any materials that communicate what your device does to the outside world.

## Team Name & Logo

This is also a great time to start on a team/product name and create a logo. Logo's can be both difficult and easy to come up with.  There are [7 different types of logos](https://99designs.ca/blog/tips/types-of-logos/), but some of them are easier than others to create.  Try taking your name and write in a nice font in Figma, then edit the contours of the letters/move them around/zoom in.  Use some of the [icons in the Design Templates](https://www.figma.com/file/9jbm8rHDqoEpXZTLnXp7To/Evericons?node-id=0%3A1) project.  Play around with colors and voila you will have a logo.

![](img/figma-outline.gif){: .fancy .medium}<br>
*(play around with changing fonts or symbols for easy logos: right click -> Outline Stroke)*

## Interactive Prototype

🚀 As you are working on your designs you should [create a clickable prototype in Figma](https://help.figma.com/article/199-getting-started-with-prototyping).  

Since you already have things set up in Figma with views or storyboard elements, you can create simple interactive connections between them.  Usually you would want to map out your user interactions as a separate graph, as this allows you to both see how each view connects to the rest of your product. However, creating a clickable prototype will allow you to show how you think the product should work and run it by people for feedback.

If your product has a digital view as a webapp, mobile, or screen interface then use the prototyping feature to connect buttons and actions to different views.

If your created a storyboard for a physical product, you can create clickable links to advance through the steps / add in buttons if you need any logic that isn't linear. 

*Some of you may have created flow maps for products before - we're going to use the interactive prototype links in Figma instead.  This means you don't have to create a separate sitemap/flowmap and is also interactive and easier to edit as you go.*

## Data Models
This is also a good time to plan out some of your data models.  Consider what data you need for your project and figure out some of the fields and objects.  You don't need to create a full relational model, but do consider what your data should look like. Describe the objects you think you will need (an informal schema for your data).  

🚀 Create a Wiki page called  `Data Models` you plan out.

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

## Design Work Never Stops

While there is a deadline to do the first pass of design work — in reality you'll be updating and interacting with your Figma mockups for the rest of the project.  People (instructors/tas/classmates) will comment and leave feedback, and you should always respond to this.  You don't have to implement all feedback, but do respond to the figma comments and resolve them once you have acted on them — either making design changes or responding to the comment with some reasoning about why you aren't going to implement the suggested changes.

## To Turn In:
* 2 Wiki Pages:
    * `Mockups and Sketches`:
        * Simply link in your [figma](https://www.figma.com) project on this Wiki Page so you can find it easier later.
    * `Data Models`
* Submit urls to each wiki page on canvas and make a comment with your new team/product name if you'd like to update it.
