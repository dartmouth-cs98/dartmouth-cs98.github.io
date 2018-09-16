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
name: CS98

## Senior Design and Implementation Project

#### _the startup experience_<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;^<font style="color:grey;font-style:italic;">founder</font>

???
* 2 terms long
* a lot of you have had internships - working at a company
* academic course project experience
* but probably not a do your own startup experience
* try to make this as real as possible with best practices, given that its still a course
* will be about you so if you have ideas on how to improve just talk to me

---
name: Online @

<iframe src="//giphy.com/embed/3oD3YveOJWdwIAfZ5e" width="600" height="389" frameBorder="0" class="giphy-embed"></iframe>


* web: [http://cs98.me](http://cs98.me)
* github: [http://github.com/dartmouth-cs98](http://github.com/dartmouth-98)

???

* administrative stuffs
* using github extensively, get comfortable
* previous projects on github and on the website
* open an issue or PR!


---
name: etc

.medium_small[![](http://i.giphy.com/tn8zWeNYA73G0.gif)]

* 3B — 4:30-6:20pm - Carson 61
* Tuesdays various class things
* Thursdays are mostly team meeting and work time (Carson 61)
* x-hours
  * Mon 5:35 - 6:25pm
  * meeting time as necessary - room available

???
* coding together
* activities such as bughunts and testing
* brainstorm and pitch ideas
* inter and intra group collaboration
* will keep time logs - for billing purposes
* both rooms on thursdays to make your team scheduling easier



---
name: Code

.small[![](img/giphy_cheating.gif)]

* the internet is full of the codes
* if (cite) { ~no penalty }
* else { mandatory vacation }

```javascript
// adapted from: http://stackoverflow.com/someurl
// this method does x and y
```

???
* think of it more like industry intellectual property
* don't use another companies code without it being above board
* internet full of codes is a good thing - we're all archeologists - puzzle solvers
* if copy - just cite it
* sharing is caring (when cited)
* goals is to share your work - have lots of green squares on github
* remember, I am hyper available, just talk to me
* helps me helps your teammates
* sometimes important because maybe there's more reasoning to why something was done some way




---
name: Slack

.small[![](img/giphy_slack.gif)]

* [https://cs98-dartmouth.slack.com](https://cs98-dartmouth.slack.com)!
* **all** course communication
* each team will have a channel
* download mobile, desktop, web apps
  * get used to it

???
* i don't do email well...
* will send out invites later today
* teams that use slack do better - its true - the bestest (and canvas)
* don't use groupme or texting, if issues come up i can't help
* don't worry about me being in channels - i'm friendly and don't bite - here to help
* honestly don't read unless you @mention me
* and if problems come up later there's history and i'm aware of it

---
name: Grading

<iframe src="https://giphy.com/embed/KVeeqrI575N8A" width="480" height="271" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

* Project Milestones — 75%
  * milestone weights will vary
* Weekly Progress: Instructor Checkins + Written Logs — 25%
* Github pull requests and commits
* Project difficulty
* Individual contribution scaling vs Team grade
* 1 Individual 30 minute meetings at beginning of each term
* What you set out to do and how far you get is considered

???
* may be adjusted slightly
* your grade my vary based on individual contribution (combined metric of time+feedback+participation+github)
* logs are like hour logs for  billing at a company - will attach to git flow somehow instead this time
* weekly checkins will start once you have teams
* will send out info about doing 1 goal setting meeting individually in the next couple of weeks for each of you
* grumpier in my old age
* have in the past been too nice at the beginning - leading to disappointment all around at the end
* people have complained that project goals weren't clear and they were penalized about user experience issues
* "didn't realize that there would be a focus on UX and whether the project was usable"
* problem unless researchy or difficult then we can talk about pivoting / progress on solving the problem
* again talk to me if things are unclear


---
name: Project Complexity


.tiny.fancy[![](img/puppy-shake-head.gif)]


* code full system - no platforms as a services
* reasonable complexity - server/client/computation
* will discuss per project later


???
* some data persistance or computation
* some display of said data or computation that is reasonably complex
* it is two terms so you have time to implement something cool!
* don't worry we'll figure this out together
* reward for challenge - min complexity - but better grade if challenged
* will give feedback: easy - medium - hard levels
* can negotiate but time converts to complexity at some point
* past -> rigor
* 2 terms == lotta f' time
* will try to have some rubrics for each milestone in advance



---
name: Commitment

<iframe src="https://giphy.com/embed/3oKIPnAiaMCws8nOsE" width="407" height="430" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

* 10hrs a week min (outside of class)
* bonus points for working together
* class time (some of which can be coding time)
* the more you put in the more you'll get out in terms of project satisfaction / grade / fame

???



---
name: thesislyfe -> startuplyfe

.left[![](img/thesis.jpg)]
.right[<br><br>![](img/thesis2.gif)]


???
* how many of you have had friends disappear due to doing thesis?
* we are't doing thesis
* buuuut hopefully you'll care abouut enough
* also there is honors available but requires a thesis in addition...
* honestly - the course is designed to be 10-15 hours a week
* if you spend that you'll be happy with the result
* less and your team will eventually be mad at you
* don't need to disappear completely, cause milestones will prevent procrastination


---
name: Monies

<iframe src="https://giphy.com/embed/l0HFkA6omUyjVYqw8" width="480" height="357" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

* some funding available
* 100 per team per term to start

???
* hosting
* hardware if necessary
* assets etc
* discounts or credits available
* hindsite story: aws x-large instances racked up 300$ in a day
  * elastic search clsuter tutorial

---
name: Tech Stacks


.large[![](img/stackCover.png)]
*(remixed from [brianfalls.com](http://brianfalls.com/))*

???
* common question and every developers first dilemma - what tools to use
* (one person on team django but really maybe not best tool) all groups hate it eventually
* how data is stored (persistance)
* how it is served
* how it is displayed
* client - mobile, web, game, IoT etc
* first couple of weeks trying out some different things - warm up



---
name: Potential Stacks

* no BAAS/PAAS allowed
* client-side:
  * web: HTML5, _react_, etc
  * desktop: native, _electron_, etc
  * mobile: native, _react-native_, etc
  * game/vr: _unity3d_, unreal, etc
  * IoT: _arduino_, raspberry pi, wearables, etc
* server-side:
  * _node_, _express_, rails, elixir, _flask_, django*
* hosting:
  * _Heroku_, _GitHub pages_, AWS, etc
* databases:
  * _MongoDB_, sqlite, RDS, MySQL, Postgres
* hardware:
  * buttons, eye tracking, vr, cameras, sensors!
  * hololens, kinect, oculus, cardboard

And much much more

???
* can't use firebase and call it done
* hack-a-thing is exactly so you can play with some
* \*hate
* we're actually gonna learn some shit
* let me know if you want to try some cool hardware - we can try working that out



---
name: From Scratch?!?

<iframe src="https://giphy.com/embed/OdwX6AhjmbN9C" width="480" height="364" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

* from blank terminal to full project
* worktime during most classtime
* can use libraries and frameworks

???
* we have 2 terms to build an awesome thing
* and learn how to do it right
* learning from past experiences so i can help avoid pitfalls from the past
* this will be the best cs98 to date
* starter projects can be helpful but also dangerous, too complex sometimes (eval starter projects)
* having that experience and confidence that you too can be a startup founder
* a builder of worlds


---
name: How do we get there?

<iframe src="https://giphy.com/embed/ZgNQXIMhy2JCE" width="480" height="364" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

* hack-a-thing to get us warmed up
* then milestones to guide us
* github to keep us on track

???
* we'll just follow a simple recipe for success - weekly progress
* never had a team not have a successful working project
* caveat last spring a couple teams had last minute breaking changes during demos... broke my heart to see it


---
name: What is at the end?

## Project Demos!

The goal: a project you are super proud of!

### also Fame and Fortune*

.left[![](img/cs-unleashed.png)]

.right[![](img/mafia.jpg)]




???
* how many have been to the technigala demos?
* together with DALI, previous 98, some other classes
* 500+ people
* not presentations (science fair style)
* what to work towards
* show off your work!
* invite your friends!
* the goal is for you to be proud of your work
* but you should also want me to be proud of your work



---
name: this is git

.fancy.medium_small[![xkcd git](http://imgs.xkcd.com/comics/git.png)]

???
* mandatory


---
name: git help

.small[![](img/git_data_transport.png)]

* [https://onlywei.github.io/explain-git-with-d3/](https://onlywei.github.io/explain-git-with-d3/)
* [http://www.ndpsoftware.com/git-cheatsheet.html](http://www.ndpsoftware.com/git-cheatsheet.html)

???


---
name: Problems to Solve

<iframe src="https://giphy.com/embed/c5eqVJN7oNLTq" width="380" height="272" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

* Considerations
  * Novelty: explore something new(ish)
  * Impact: bigger than here
  * Format: game, web, mobile, iot, wearable, etc

* There are [lots of fascinating apis](https://www.programmableweb.com/) out there: from beer reviews to machine learning, and vision apis, to fictional datasets. Could you integrate some of these to enhance your idea?

???
* some of you have ideas, don't worry but take a step back and do some more ideating
* Think outside of what is useful to Dartmouth students
* startup advice is wrong - don't always have to solve a problem you yourself face
  * we have all the same problems - finding out events/parties, waiting in line at kaf, buying stuff
* new event apps, social network clones, and marketplaces have been attempted before and you might find it more rewarding to build something that challenges you.
* sometimes can't be solved - event planning for instance - just needs everybody to use the same platform


---
name: Outside the Box?

<iframe src="https://giphy.com/embed/ZhypAXYqYPS7e" width="283" height="380" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

* if you had half a year to build anything you want?
* why build something boring?

???
* with a team of cool people
* consider improvements on existing things - or games
* Games, could you take some known game and make it a site or mobile app?
* Is there an existing product that you want to clone but with a special take.  Uber for puppies, airbnb for breakfast sandwiches, cryptocurrencies for goldfish?
* Your ideas can be serious, world changing, or completely silly.  The point is to enjoy building something cool.


---
name: Previous Project: Hindsite 16f-17w


.medium[![](../../projects/previous/16f-17w/img/timeline-reef.gif)]

???
* better history chrome extension
* full text search of every page you've visited - previews
* was in the chrome store for a little while
* cost a lot in hosting - they all had jobs
* but they applied to ycombinator
* and worked on it for an extra term too
* sam altman kept it installed and logged in for a few months
* cool problems to solve like scalability and security


---
name: Previous Project: Climb.AR 16f-17w


.medium[![](../../projects/previous/16f-17w/img/music_game_demo.gif)]

???
* climbing game platform
* uses kinect and camera to identify holds, and provide a unity library for event based game building



---
name: Previous Project: Lensflare 16f-17w


.small[![](../../projects/previous/16f-17w/img/lensflare_poster.jpeg)]

???
* HoloLens app to allow spatial annotations with text, video and 3D animated assets
* has a backend and management interface to allow easily adding/customizing assets
* production quality could have been a product

---
name: Previous Project: Queue 17w-17s


.medium[![](../../projects/previous/17w-17s/img/queue.jpg)]

???
* ios app that allows sharing music playlist based on bluetooth distance
* in the same room, share your playlist / add tracks to others


---
name: Previous Project: MiAM 17f-18w
.tiny[![](../../projects/previous/17f-18w/img/miam-feed.gif)]
.tiny[![](../../projects/previous/17f-18w/img/miam-remix.gif)]


???
* react-native app that allows people to create / stack different gifs and stickers together and remix others
* also meme battle
* published but didn't get the PR push at the end



---
name: Previous Project: WebAdventure 17f-18w
.tiny[![](../../projects/previous/17f-18w/img/webadventure-end.gif)]


???
* a better wikigame
* published for a while in chrome store
* didn't really think through game dynamic so in the end wasn't quite fun?


http://localhost:4000/projects/previous/17f-18w/img/planit2.gif


---
name: Previous Project: Planit 17f-18w
.medium[![](../../projects/previous/17f-18w/img/planit2.gif)]


???
* travel planning webapp
* built a nice complex system (phoenix elixir/ react)
* didn't really do much user testing so in the end the product wasn't ready for prime time


---
name: Previous Project: Scannible 17f-18w
.tiny[![](../../projects/previous/17f-18w/img/scannibble1.gif)]

???
* travel planning webapp
* built a nice complex system (phoenix elixir/ react)
* didn't really do much user testing so in the end the product wasn't ready for prime time




---
name: The Tale Of Pretty Music Maker


.medium[![](../../projects/previous/16f-17w/img/prettymusicmaker.gif)]

???
* web loop music creator
* a 2 week cs52 project
* regretted their project in 98
* and wished they had worked on something more engaging like prettymusicmaker
* was almost like they were completely different people when they enjoyed the project




---
name: The Tale Of OrderOrchard


.medium[![](img/order-orchard.png)]

???
* student project
* kept at it
* initially online food ordering
* but pivoted when they identified a bigger pain point for restaurants
* big enough pain point that they've signed some big customers



---
name: just breathe

.medium[![](img/breathe.gif)]
.medium[![](img/rocks.gif)]

???

* You can do it!  Some of the groups in the past had no experience with what they were building
* no kinect or hololens exp, or react-native etc
* you can learn and build a lot in 6 months


---
name: start with: Interviews

* [Interviews Milestone](../projects/milestones/interviews)

.left-small[![](img/have-an-idea.gif)]
.right-large[![](img/big-idea.gif)]
.right-large[![](img/crazy-idea.gif)]


???
* talk to at least 1 person who is not a student
* they can be professor you find inspiring, a mentor, a parent, a co-worker from an internship etc
* ask about a problem or idea for something they would like improved/fixed/made
* record: target audience, what the problem is,  what the proposed solution might look like
* idea is to get our thoughts percolating about ideas that might be outside dartmouth
* who knows prof: Misha Gronas?
* he always has crazy ideas - his last was outsourcing streaming videos of talks/events  


---
name: next week: Hack-A-Thing

.medium_small[![](img/hack-a-thing.gif)]

* [Hack-a-thing-1](../projects/milestones/hack-a-thing-1)
  * individually or in pairs
  * choose some technology based on interesting
  * hack something together
  * plan to spend 10 hours (min) learning/exploring

???
* idea is to broaden your horizons
* choose something you'd like to learn
* potentially could be related to an idea you have
  * but don't get tooo attached
* follow a tutorial
* plan to spend at least 10 hours on this


---
name: as you go: Inspiration Board

* Start an inspiration board.
* cool tool: [milanote](https://www.milanote.com/refer/rcAxjfzasgu2C6IoR8)

.left[![](https://media.giphy.com/media/26BkNrGhy4DKnbD9u/giphy.gif)]
.right[![](https://media.giphy.com/media/QveMWHFk4ojsI/giphy.gif)]



???
* keep track of things you see online that are interesting
* clip pictures / urls / etc
* we'll compile then for an upcoming milestone




---
name:

.medium[![](img/hacktivity_rules.jpg)]

* 10 Min - brainstorm
* 20 Min - BUILD a prototype
* 10 Min - Prep Pitches
* 2 Min - Pitch It!

???
* each person write down a random word
* form teams of 4ish people
* swap words with another team
* brainstorm and create a product that ties together all words
* can be a digital or physical product
* create a little presentation
