theme: Ostrich, 1

# BDD Basics

@garyfleming

^ Intro

--

TODO Outline and then fill

- TDD and BDD - Why are _we_ talking about it?
  - TDD drives concrete design from specs
  - BDD helps build that spec in the large (i.e. system level)
  - Double-loop Process (TODO maybe show this towards the end)
- BDD - What it's not
  - Not a testing process
    - Seems to be a misconception based on test-after philosophy
    - Often see teams develop "the BDDs" as a tool using 
  - Not a tool
    - The relationship of tools like Cucumber and SpecFlow to BDD are clear, but you can do BDD without any tools.
- A Brief, incomplete, and somewhat wrong history of BDD
  - Based largely on my interactions with the community and their own talks and writing. Not intended as historical record.
  - Dan North introduced to agiledox - tool that generated docs from test names, and made them a little more human. Changed how he wrote test names because when tests failed he could look at the expected behaviour in the name.
  - Started writing JBehave, one of the earliest BDD tools, to replace JUnit. Largely wanted to replace "test" vocabularly with "behaviour".
  - Enter Chris Matts, BA with financial background, who injects the idea of business value into BDD. Brings focus to process: what's the next most important thing your system doesn't do
  - Eric Evans introduces DDD. Won't go into that here, but has the idea of ubiquitous language. Dan and Chris realise this is what they need. Leads to a combination of the Connextra "as a, I want, so that" user story template, with "given ... when... then..." for actual behaviours.
  - Incorporated into JBehave and the magic just works.
- BDD - What it is
  - With what it's not and a little history covered, we can start to see what it is: a way of thinking about the behaviours we want our systems to have. That is, it's a bunch of alignment and analysis tools, in the same way that TDD is a bunch of Design tools.
- asadads
- BDD Books
  - Seb Rose (Cucumber) and Gaspar Nagy (SpecFlow)
  - Discovery
  - Formulation
  - Automation
- Example Mapping
- Given... when... then... -- In detail
- BDD Gives us
  - A way of thinking about and exploring the behaviours we want in our systems (Discovery)
  - A way of writing down the behaviours in a clear way that we can all agree on (Formulation)
  - A way of taking those agreements and using tooling to automate the behaviours are in the system, as intended.


---

# Slide Title

^ Presenter notes

---

# Thank You

![inline](images/cat3.gif)

@garyfleming
