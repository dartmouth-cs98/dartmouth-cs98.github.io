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
name: Design

.fancy.medium[![](https://media.giphy.com/media/povenlBAIz14s/giphy.gif)]


???
* just some tips
* sorry for the repeat for those of you who have heard this before
* not really a designer (tried to go to graphic design school many years ago though)
* here's what I've learned from hanging around designers
* based on working on hundreds of projects


---
name: But I just want to code!!

.fancy.small[![](img/coding.webp)]

*💳credit given for design work*<br>
*and it'll turn out better*


???
* **cowhand** coding - just leads to manure code
* just jumping in will lead to having a big ol mess of features
* stuff you don't even need to build
* i'm happy to help
* also office hours / open lab hours in DALI have many designers happy to help
* doesn't hurt to learn
* credit given for design work



---
name: Step 1: Inspiration Board

* find examples of similar products
* take screenshots / save urls
* copy color schemes

.fancy.medium[![](img/inspiration.jpg)]


???
* other people have made pretty designs,  look at them, use them for inspiration, copy them as best you can
* you've all been keeping these already right?   
* inspiration boards are the **biggest difference between good designers and pretenders**.  if a designer starts with an inspiration board you can see their thought process and it is obvious in the final product that they thought about what they were making


---
name: Step 2: Sketches

* paper is best
* quickly jot down views and functionalities

<iframe src="//giphy.com/embed/d26EH3VCAHS12?hideSocial=true" width="380" height="284" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>


???
* make them on paper first
* much faster
* we'll try to get to that today

---
name: Step 3: Mockups

* with inspiration and sketches
* start on mockups ([Figma](http://figma.com))
* don't code them yet

.fancy.medium[![mockups](img/mockupthings.jpg)]


???
* the case for mockups:
* help you remember what needs to be built
* much quicker to play around with different options quickly and easily to determine what works best for your product
* coordinate with your team - keep everybody on track
* Figma is like google docs for design - super

---
name: No UI? No problem!


.fancy.small[![mockups](img/rover.jpg)]

.medium[![mockups](img/robot.jpg)]


???
* but also use figma for storyboard - upload sketches - use primative shapes / icons
* Some products may not have what you would think of as a traditional user interface
* maybe it is a code library,  or a physical device that has certain behaviors.  
* However, these still have a user facing aspect
* map out your public API - function calls or http endpoints are your user interface
* physical device with certain behaviors - map out what those are and what is the control interface
*  Additionally, you can use this opportunity to design any materials that communicate what your device does to the outside world.


---
name: Step 4: Functional Mockups

* put mockups together
* build with [Figma](https://help.figma.com/article/199-getting-started-with-prototyping)
* for paper sketches use: [MarvelApp PopPaper](https://marvelapp.com/pop/)

.fancy.medium[[![figma prototyping](img/proto-figma-2.gif)](https://help.figma.com/article/199-getting-started-with-prototyping)]

???
* great way to test your interactions
* woop forgot some logic path from one view to another
* can run it by users and see if they can figure it out
* again for the AR or robot projects - can use sketches or shapes and words



---
name: No UI? No Problem, p2

.fancy.medium[![mockups](img/storyboard2.jpg)]

* storyboard

???
* you can storyboard out the interactions and behaviors
* in some cases like AR you probably want to do both!
* think through every step in the storyboard - might the old person trip on the eldercare robot in the dark? 


---
name: Colors

* Not just random
* Use a color scheme chooser: [color.adobe.com](http://color.adobe.com)
* Steal from other sites

.fancy.medium[[![adobe color](img/adobecolor.gif)](http://color.adobe.com)]

???
* picking colors
* beg, borrow, steal color schemes


---
name: Hierarchy

* visual hierarchy
* what users see first, order of gaze
* visual saliency

.fancy.medium[[![fpatttern](img/fpattern2.jpeg)](https://uxplanet.org/f-shaped-pattern-for-reading-content-80af79cd3394)]


???

* laying out your page, remember to think about the visual hierarchy
* ordering of what users see based on size/color/movement
* What will users eyes see first, your call to action, or the large user profile button that they never really need to go to
* Try to imagine what you would notice first as a new user and then order your elements in terms of visual saliency appropriately
* Larger and brighter colored things tend to be noticed first
* Positioning also matters, we tend to look at things in a [letter F pattern](https://uxplanet.org/f-shaped-pattern-for-reading-content-80af79cd3394).


---
name: More Principles


<div id="" style="overflow:scroll; height:400px;">
.fancy.medium[![mockups](img/principles.png)]
</div>

* [more principles](http://blog.visme.co/visual-hierarchy/)


???
* pretty good read with lots of examples
* recommend at least some people on the team get excited about design
* is important - makes or breaks a project



---
name: Mindfulness


.fancy.medium[![mockups](img/quote.jpg)]

UX is like a joke...

???
* famous designer
* every choice you make conveys something
* you chose blue for a restaurant site because you like blue
* but blue is not appetizing, doesn't make people feel hungry - RED does weird.
* think about and defend every choice you make - 'i just like it' doesn't cut it.
* hidden interaction like swiping or hamburger - be careful.
* ux is like a joke - its bad if it needs explaining
* can use this time to test that!


---
name: Appetizing?


.fancy.left[![mockups](img/appetite-blue-toast.jpg)]
.fancy.right[![mockups](img/bluerice.jpg)]

???
* but blue is not appetizing, doesn't make people feel hungry - RED does weird.

---
name: Flux Express


.fancy[![mockups](img/flux-design.jpg)]

???
* you chose blue for a restaurant site because you like blue
* but blue isn't appetizing - they rebranded multiple times
* it looks clean - until you realize you're supposed to order food




---
name: Make or Break


.fancy.medium[![sad chat](img/sadchat.jpeg)]

* [drop in users](https://techcrunch.com/2018/05/01/snapchat-reredesign/)

???
* i always found the hidden slides to be confusing but changing things once people get used to it is even worse
* just announced snapchat originals or some such bullshit to lure back lost users

---
name: resources

.fancy.medium[![good vs bad design](img/goodvsbad.png)]

lots of resources out there

* [cs52.me/workshops/design](http://cs52.me/workshops/design)
* https://dribbble.com/
* https://blog.prototypr.io/design-for-programmers-d38c56982cd0
* http://www.cssdesignawards.com/
* https://www.awwwards.com/web-design-trends-for-2017.html

???
* best form of flattery is imitation



---
name: NEXT Scaffolding

 .fancy.medium[![](img/bamboo-scaffolding.gif)]

* initial code scaffolding
* tools and frameworks chosen
* team has local dev environment set up

???
* Initial code scaffolding started
* component plan
* tools and frameworks chosen
* everybody has local dev environment set up


---
name: NEXT Scaffolding

.fancy.small[![](img/scaffolding-falling-down.gif)]

???
* work together and don't skimp on just winging it
* don't want this to happen - hurricane is coming

---
name:  Sketch Time Step 1: Generate Options


.fancy.medium[![](../../projects/milestones/img/papersketch.png)]

* assignment: [http://cs98.me/projects/milestones/mockups-models](http://cs98.me/projects/milestones/mockups-models)
* which **(2-5) main features** you will sketch that are essential to your product
* thick markers, paper
* **5 minutes of individual sketching per feature**
* compare sketches and create group versions
* Aim for **2-3 versions per feature**.

???
* the thicker the marker, the more you force yourself to keep the designs at a conceptual level 
* Include little or no specific content
* Drop any worries about scale, straight lines, grids, etc.
* Think in flows whenever possible (what pages come after?)
* Never settle for your first idea!


---
name:  Sketch Time Step 2


.fancy.medium_small.left[![](../../projects/milestones/img/popapp-prototype-animation.gif)]

* Put in [Pop Paper](https://marvelapp.com/pop/)
* Test User Flow
