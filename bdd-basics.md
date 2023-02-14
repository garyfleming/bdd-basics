theme: Poster, 1

# BDD Basics

### @garyfleming

^ Intro
^ TODO Vending machine kata as our main example?

---

# BDD Is About Alignment

^ Ever had Dev/test argue? Dev says it meets the spec, test says it's broken. Alignment. PO/ says "it's not what I wanted". Conversation earlier to avoid.

---

# TDD and BDD
## Why are _we_ talking about it?

^  - TDD drives concrete design from specs
^  - BDD helps build that spec in the large (i.e. system level)
^  - Double-loop Process (TODO Add an image of the double loop here!)

---

### BDD - What it's not
## Not a testing process

^ Seems to be a misconception based on test-after philosophy
^ Often see teams develop "the BDDs" as a tool using 

---

### BDD - What it's not
## Not a tool

^ The relationship of tools like Cucumber and SpecFlow to BDD are clear, but you can do BDD without any tools to a very large extent.

---

# A Brief, incomplete, and somewhat wrong history of BDD

* Agiledox
* Dan North and JBehave
* Chris Matts and Business value
* Eric Evans and DDD
* Rachel Davies and the Connextra format

^  Based largely on my interactions with the community and their own talks and writing. Not intended as historical record. (Largely cribbed from intro to bdd)

---

# A Brief, incomplete, and somewhat wrong history of BDD

* Agiledox

^ Dan North introduced to agiledox - tool that generated docs from test names, and made them a little more human. Changed how he wrote test names because when tests failed he could look at the expected behaviour in the name.

---

# A Brief, incomplete, and somewhat wrong history of BDD

* Agiledox
* Dan North and JBehave
  
^ Started writing JBehave, one of the earliest BDD tools, to replace JUnit. Largely wanted to replace "test" vocabularly with "behaviour".

---

# A Brief, incomplete, and somewhat wrong history of BDD

* Agiledox
* Dan North and JBehave
* Chris Matts and Business value

^ Enter Chris Matts, BA with financial background, who injects the idea of business value into BDD. Brings focus to process: what's the next most important thing your system doesn't do

---

# A Brief, incomplete, and somewhat wrong history of BDD

* Agiledox
* Dan North and JBehave
* Chris Matts and Business value
* Eric Evans and DDD

^ Eric Evans introduces DDD. Won't go into that here, but has the idea of ubiquitous language. Dan and Chris realise this is what they need.

---

# A Brief, incomplete, and somewhat wrong history of BDD

* Agiledox
* Dan North and JBehave
* Chris Matts and Business value
* Eric Evans and DDD
* Rachel Davies and the Connextra format

^ Leads to a combination of the Connextra "as a, I want, so that" user story template, with "given ... when... then..." for actual behaviours.

---

# A Brief, incomplete, and somewhat wrong history of BDD

* Agiledox
* Dan North and JBehave
* Chris Matts and Business value
* Eric Evans and DDD
* Rachel Davies and the Connextra format

  - Incorporated into JBehave and the magic just works. (Many others did work in this space, like Liz Keogh, Aslak Hellsoy etc before and after this: not minimising their work, just don't have time)

---

## BDD - What it is

^ With what it's not and a little history covered, we can start to see what it is: a way of thinking about the behaviours we want our systems to have. That is, it's a bunch of alignment and analysis tools, in the same way that TDD is a bunch of Design tools.

---

## The BDD Books
### Seb Rose (Cucumber)
### Gáspár Nagy (SpecFlow) 

^ Wrote/writing a series of books that take the history of BDD and the next 20 years of development in the area and distill it down into three main practices - one practice per (short) book

---

## BDD is three practices

  - Discovery - "Shared understanding is established through collaboration and structured conversations"
  - Formulation - "Examples of system behaviour are documented as scenarios"
  - Automation - "Scenarios are automated to be able to verify the system's behaviour"


---

## Discovery
### A way of thinking about and exploring the behaviours we want in our systems

^ TODO expand on this. Show example mapping

---

## Formulation
### A way of writing down the behaviours in a clear way that we can all agree on 

^ TODO expand on this. Show writing gherking scenario. Consider writing a bad scenario (all impl), showing BRIEF, and then making it BRIEF

---

# BRIEF 
  - Business Language - Aids cross-discipline collaboration
  - Real data - Reveal assumptions and edge cases
  - Intention Revealing - Describe desired outcomes, rather than implementation
  - Essential - Skip anything that isn't directly about the behaviour
  - Focused - Each scenario should only be about one rule

^ Acronym used to help make scenarios we right focussed in the right way

---

## Automation
### A way of ensuring those behaviours are verified in the system, using tooling.

^ The easy part if we've done the rest right!
^ Tools like Cucumber or SpecFlow take our scenarios and match them up to methods in our test code.
^ Show an example match.

---

# Credits

"Introduction to BDD" by Dan Terhorst-North
"BDD Books" series by Seb Rose and Gaspar Nagy
