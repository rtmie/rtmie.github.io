# Devops Intro

#### Agile Lean Ireland 
_Rob Mason 14th March 2017_ 

  <a href="http://www.twitter.com/rtmie"><img border="0" alt="twitter" src="https://upload.wikimedia.org/wikipedia/en/thumb/9/9f/Twitter_bird_logo_2012.svg/1259px-Twitter_bird_logo_2012.svg.png" width="70" height="70"></a>
  <a href="http://www.github.com/rtmie"><img border="0" alt="github" src="https://image.flaticon.com/icons/svg/25/25231.svg" width="70" height="70"></a>

  <img src="https://licensebuttons.net/l/by/3.0/88x31.png"><sup><sub>(for my parts)</sub></sup>

  * press 's' for notes view!
Note:
* Introduce myself - electronics tech, systems engineer
* working in HVol mfg 90's
* software dev, varied
* latterly building devops platform
* preparing an induction course for grads reflecting across the 2
* devops in the context of lean


## The course is all in one slide

Note:
Around the same time I had been re-reading an inspirational book


<!-- .slide: data-background-image="http://techbeacon.com/sites/default/files/UX-user-experience-lessons-learn-IT-phoenix-project-book-information-technology.jpg" -->
# Read This Book!
Note:
Novel - not text

About IT, Devops and winning in business

The three ways - flow, feedback, continuous expirement 

It will provide a context - and it's a good read

Companies who put IT at the centre and see it as the differentiator will win


### Any Questions
<img src="static/Low-Poly-Shattered-Question-Mark.svg" style="height: 600px"/>


## Traditional IT Practice

<img src="static/dev.svg" style="width: 1024px; height: 450px;"/>
Note:
### Disadvantages
* 2 departments with different goals, skills, heartbeat, constraints
* Different environments between development and production - "it works for me!"
* Dev - " the code passed all tests, let's go!"
* Ops - "We had to work through the night to get it live"
* Ops on call for dev bugs/issues
* Local ops workarounds hinder onward development
* No awareness of impact of decisions on the other side
* *Devops - bit of a misnomer just representative the silos*
* Silos may exist within Dev and Ops & other parts of the organisation


### Waste
<img src="static/waste.svg" style="width: 1024px; height: 450px;"/>


# Enter DevOps
Note:
* for orientation we look at definitions
* Then generalise towrds lean


### Definitions of Devops

>"DevOps is the practice of operations and development engineers
>participating together in the entire service lifecycle, from design
>through the development process to production support"
[The Agile Admin](https://theagileadmin.com/what-is-devops/)

> "You build it, you run it!"
_Werner Vogels - Amazon_
Note:
* Many similar definitions, I like the first
* terse but to the point - Werner Vogels - Amazon CTO
* flow / no silos


<figure>
<img src="static/devops.png" style="width: 1024px; height: 450px;"/>
<figcaption>
<sup><sub>
The devops loop - various
</sub></sup>
</figcaption>
</figure>
Note:
* Continuous Flow through the System
* work planning flows from ops to dev based on observation
* dev delivers improvement to ops
* feedback continually


### "Lean" - where does Devops fit?

> "The core idea is to maximize customer value while minimizing waste. Simply, lean means creating more value for customers with fewer resources."
Note:
My view - Devops is lean applied to IT delivery


## Manufacturing Figured this Out

* Lean Manufacturing - Toyota Production System - AKA "Systems Thinking"
* Muda  - _"Eliminate the 7 wastes"_
* Kaizen - _"We improve our business operations continuously, always driving for innovation and evolution"_
* Genchi Genbutsu _"Continuously solving root problems drives organizational learning. Go to the source to find the facts to make correct decisions."_
Note:
* 7 wastes TIMWOOD
* Continuous improvement - 6 Sigma
* Design of expirement


### Lean Software Development

<img src="http://www.poppendieck.com/images/Agiletoolkit.jpg" style="height:600px"/>
Note:
* Mary Poppendieck
* Apply Lean manufacturing principles to software development
* 2003
* Mostly applied in the dev side only



#### Devops -  Lean principles applied to IT delivery

#### But Dev and Ops may not be your only 2 silo problems!


<figure>
<img src="https://cdn.infoq.com/statics_s2_20161004-0306/resource/presentations/microservices-comparison-evolution/en/slides/sl28.jpg" style="height:500px;"/>
<figcaption>
<sup><sub>
Silos - various Adrian Cockroft presentations
</sub></sup>
</figcaption>
</figure>


<!-- .slide: data-background-image="static/phoenix.png" -->
# So did I mention - Read this Book!?


<!-- .slide: data-background-image="static/phoenix.png" -->
# Learn the 3 Ways


### 1. Flow
* Understand how work moves through the system from left to right (dev to deployment)
* Systems Thinking - emphasise the performance of the whole system/organisation, not just specific silos
* Apply to any process large or small


### 2. Feedback -
* Shorten and amplify feedback loops from right to left (from deployment back to dev)
* Fast identification of bugs and validation fixes
* Identify quickly if process change helps/hinders productivity


### 3. Experimentation and learning
* Culture of experimentation, risk taking and learning from failure
* Repetition is the path to mastery
* Don't defer the hard/complex stuff
  * Try it / Learn from failure
  * Iterate
Note:
The upgrading puppet master version anecdote


<iframe  width="854" height="480" src="https://www.youtube.com/embed/nUOXDEvplRc" frameborder="0" allowfullscreen></iframe>


### Theory of Constraints
* Set of management concepts to help identify:
  * What to change
  * What to change it to
  * How to cause the change
* Eli Goldratt - author if "The Goal" - the novel that inspired the Phoenix Project!


<figure>
<img src="static/Bottleneck_vs_constraint.PNG" style="height: 550px;"/>
<figcaption>
<sup><sub>
Constraint vs Bottleneck - Chris Hohmann
</sub></sup>
</figcaption>
</figure>
Note:
* Typically applied to  manufacturing process is automated,repeatable
  * Can be characterised
* Sometimes in IT processes, people or external company factors involved => more variable
* It starts with metrics - no metrics => no identification of constraints
* Automation is key - automated processes more likely to give repeatable constraint


<iframe width="854" height="480" src="https://www.youtube.com/embed/qzhHNM5xWPQ" frameborder="0" allowfullscreen></iframe>


### Systems Thinking

> a way of thinking about the forces and interrelationships that shape the behavior of systems...

> ...helps us to see how to change systems more effectively

_Peter Senge - The Fifth Discipline_

Note:
**as distinct from event based thinking**
* System - set of interrelated and interdependent components that form a unified whole with specific purpose
* Collection != System
* Kitchen - a collection of things (albeit some of those things are systems, e.g. fridge)
* Bowl of fruit - a system - types of fruit in contact cause different decay effect
* Team - a system - people + character types + interactions
* See [Introduction to Systems Thinking - Daniel Kim](https://thesystemsthinker.com/wp-content/uploads/2016/03/Introduction-to-Systems-Thinking-IMS013Epk.pdf)


![alt text](https://www.snideradvisors.com/wp-content/uploads/boat.png)


### A Call to Action
######  Apply these small in your team, project _today_
######  Don't wait for the whole organisation to come round
Note:
* Team can look at time from developer onboarding to productivity
* e.g. using docker to encapsulate dev environment instead of error prone manual process
* reduced new dev setup time from 1~2 days to 1 hour
* Delivery manager can look at end to end flow of a software release


### First - A Sidebar About  Automation
Note:
*Key to effective Lean IT/ Devops realisations
* Test, Infrastructure configuration, Deployment
* Building block for CD


<!-- .slide: data-background-image="static/Ironic-Signage-photography-observations1.png" -->

Note:
* Sometimes in life we don't practise what we preach
* ...Which can lead to embarrassing results


<!-- .slide: data-background-image="static/Ironic-Signage-photography-observations.png" -->
### Computer programming is about:

* Automating repetitive tasks to make them more efficient
* Automating complex tasks so that they can be repeated without error


<!-- .slide: data-background-image="static/Ironic-Signage-photography-observations.png" -->
**"But somehow we didn't always automate our own processes - test, integration, deployment."**

_Me - just now_


## Manual Processes

* Slow
* Error prone
* Costly
* Can't be combined


### How to get there

<img src="static/ppt.svg" style="width: 1024px; height: 450px;"/>
Note:
* Some people may also say People,Processes,Tools
* I prefer practice as it suggests its an engrained thing, a process sounds like


<!-- .slide: data-background-image="static/devops_people.svg" -->
#People

.

.
Note:
refer back to the definition


<!-- .slide: data-background-image="static/devops_people.svg" -->
### (c)  [commitstrip.com](http://www.commitstrip.com/en/2015/02/02/is-your-company-ready-for-devops/)

<img src="static/notdevops_1.png"/>


<!-- .slide: data-background-image="static/devops_people.svg" -->
### (c) [commitstrip.com](http://www.commitstrip.com/en/2015/02/02/is-your-company-ready-for-devops/)

<img src="static/notdevops2.png"/>


### Practices
|                              |                         |
| ---------------------------- |:-----------------------:|
| Small Batches                | Continuous Integration  |
| Integrated SCM               | Continuous Deployment   |
| Automated Testing            | Continuous Monitoring   |
| Infrastructure as Code       | Information Radiators   |
|                              |                         |

Note:
* lets look at 8
* whistle stop
* there are others


### Small Batches
* Break work down into small chunks
* Commit, Test and Deliver often
* Small increments => problem source is easily identified
* Mapping of feature to performance improvement/degradation is obvious


### Integrated Version Control

<img src="http://image.slidesharecdn.com/lucamilanesiogerrit-120320104614-phpapp02/95/gerrit-code-review-20-728.jpg?cb=1332241935"/>


### Automated Test

* TDD/Unit testing
* BDD/Acceptance Testing
* System/Performance  Testing
* Exploratory testing
* All must be automated to enable fast feedback, repeatability
Note:
* System/performance can be related to theory of constraints
* Exploratory testing -good example of integrated teams - part of Kaizen, test hypothesis


### Continuous Integration

* Ensure health state of the codebase in a way that tracks the impact of
every code change
* Provide fast feedback to developers/teams of the impact their code
change has had on overall solution integrity
* Reduce risk in overall delivery
Note:
Anti pattern is to only see impact of change after it gets built into the system with lots of other things
Difficult and expensive to backtrack to root cause


<!-- .slide: data-background-image="static/salt.png" -->
### Infrastructure as code

> "The enabling idea of infrastructure as code is that systems and
> devices which are used to run software can be treated as if they,
> themselves, are software."
_[Keif Morris](https://www.thoughtworks.com/profiles/kief-morris)_
Note:
Same disciplines as any coding
version control, review, test,release


<!-- .slide: data-background-image="static/salt.png" -->
### Infrastructure as code
* Automation requires programability => APIs, even to the infrastructure
* Install the OS, configure the storage server, configure networking etc
* Maintain configuration
* Deliver Updates - different approaches
* Enabler for 'on-demand' provision of infrastructure
Note:
* configuration management e.g. puppet
* orchestration e.g. Saltstack, Ansible
* Immutabe infrastructure - cloud/IAAS


### Continuous Deployment

<img src="https://leantesting-wp.s3.amazonaws.com/resources/wp-content/uploads/2015/12/drawing-cd-header.png" style="width:1024"/>


<!-- .slide: data-background-image="static/go-cd-pipeline-9227c98eca313a7b9f838e12daabf1f2.jpeg" -->   
### Has more complex workflows than CI
* Complex business processes, workflows and tool chains required
* Complex qualification tests - layers of integration
* Tends to be complex and brittle (if your delivery is complex and brittle)
#### *Alternatively*


<!-- .slide: data-background-image="static/go-cd-pipeline-9227c98eca313a7b9f838e12daabf1f2.jpeg" -->   
### Simplify
* Componentise with APIs
* API version negotiation
* Run each component in a container
* Each team continually deploys their service
* No complex inter-service  test flows

_e.g. AKA Microservices_
Note:
* Needs a talk in it's own right
* Good news - there's lots online
* **This one's good!** [The state of Microservices by Adrian Cockroft](https://www.youtube.com/watch?v=pwpxq9-uw_0)
* It is a huge contributor to successful realisation of devops goals
* We will take a peek


<!-- .slide: data-background-image="static/enterprise-hud.png" -->
### Continuous Monitoring

* Not just static alerting of failed states
* Continuous collection/querying of metrics data over time
* Continuous collection/query of logs
* Proactive monitoring -
  * "the system may be about to degrade"


<!-- .slide: data-background-image="static/Info-radiator-.png" -->
### Information Radiator
* Build state, tests passed/failed
* Work/task/project progress
* Everything is in the open/Nothing to hide
* Shared information for the business - everyone a stakeholder


### People + Practices = Culture
<figure>
  <img src="http://martinfowler.com/bliki/images/devOpsCulture/devops_culture.png" style="width: 550px;"/>
  <figcaption>
  <sup><sub>
     Image (c) [martinfowler.com](http://www.martinfowler.com)
  </sub></sup>
  </figcaption>
</figure>     


## Note

* Devops culture characterised by freedom and responsibility - high trust environment
* Traditional IT culture characterised by bureaucracy and blame - low trust environment
* **However that is not a license to "mess around" - apply "Theory of Constraints"**
* **"Responsibility" and "systems thinking" must inform actions and delivery**


> "It is crucial to be open to change and have the correct internal
>environment to allow change to happen.
> This is not just in IT but throughout the business. This is why it is
>so important that devops has the correct senior backing and buy-in,
>otherwise it will fail."

_Gunnar Menzel - Chief Architect, Cap Gemeni_



### Tools
* Devops practices are difficult to realise without the support of *tools*
* Good selection and application of tools is a critical success factor
* Using devops tools is not the same as implementing devops
* No specifically right answers - explosion of tools
* Always watch, review and improve toolchain


### Thought piece
* You have a big-ass complex software system of interdependent components and a fragile manual deployment.
* You want to make it automated and repeatable and have a budget for the work.
* Do you spend the budget to....


* Build a big-ass complex tooling solution to support the automation
* Revise the system architecture/implementation towards simplicity


####  No right answer! 

* Build a big-ass complex tooling solution to support the automation
* Revise the system architecture/implementation towards simplicity

####  But you should be having this conversation ! 



### Section Summary

#### Devops
* Requires systems thinking view
* Requires automation
* Values continuous collaboration
* Abhors silos
* Values speed
* Does more with less resources
* Values (reusable) tooling


## Oh and did I Mention?

#### If you take only one thing away....


<!-- .slide: data-background-image="http://techbeacon.com/sites/default/files/UX-user-experience-lessons-learn-IT-phoenix-project-book-information-technology.jpg" -->


<!-- .slide: data-background-image="http://techbeacon.com/sites/default/files/UX-user-experience-lessons-learn-IT-phoenix-project-book-information-technology.jpg" -->
# Read This Book!


