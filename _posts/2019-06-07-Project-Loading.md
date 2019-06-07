---
layout: post
title: Project Loading...
categories: [Cucumber, Testing]
---
## An Update

Hello again! I've decided I want to take on another project for this site: making a working example of Cucumber for Java! So, I've begun working on a tutorial/how-to with some code and examples with screen shots. 

<p align="center">
	<img src="https://mlegere1323.github.io/TheBlog/images/CucumberLogo.PNG">
</p>

**What is Cucumber Anyway?**

[Cucumber](https://cucumber.io) is a software [acceptance testing](http://softwaretestingfundamentals.com/acceptance-testing/) tool (originally written in Ruby) that helps automate tests, and foster collaborative communication amongst developers, business stakeholders, and anyone involved in the [Software Development Life Cycle](https://www.tutorialspoint.com/sdlc/sdlc_overview.htm). Cucumber inherently enforces good [Behavior-Driven Development](https://en.wikipedia.org/wiki/Behavior-driven_development), and employs simple syntax and structure for writing tests.

**Context and Concepts**:

The following quotes were taken from [the book](https://read.amazon.com/kp/embed?asin=B00V20IEXM&preview=newtab&linkCode=kpe&ref_=cm_sw_r_kb_dp_JNU9CbV63PKHM) I discussed in my [previous post](https://mlegere.site/First-Post/), chapter 1, page 8.
* "Software teams work best when the developers and business stakeholders are communicating clearly with one another. A great way to do that is to collaboratively specify the work that's about to be done using automated acceptance tests."
* "When the acceptance tests are written as examples, they stimulate people's imaginations and help them to see other scenarios they hadn't previously considered."
* "When the team members write their acceptance tests collaboratively [together, concurrently in a room somewhere, ideally], they can develop their own ubiquitous language for talking about their problem domain."
* "Cucumber was designed specifically to help business stakeholders get involved in writing acceptance tests."
* "Each test case in Cucumber is called a *scenario*, and scenarios are grouped into features." Each scenario contains several steps."
* "The business-facing parts of a Cucumber test suite, stored in feature [.feature] files, must be written according to syntax rules--known as Gherkin--so that Cucumber can read them."
	* FYI: Gherkin is written using a Given-When-Then syntax. *Given* an initial system context, *when* an event occurs, *then* we expect ... to occur.
* "Under the hood, step definitions translate from the business-facing language of steps into code."
