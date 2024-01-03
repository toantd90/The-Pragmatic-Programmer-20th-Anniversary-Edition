This is my summary of The Pragmatic Programmer: Your journey to mastery, 20th Anniversary Edition, by Andrew Hunt and David Thomas. I use it while learning and as quick reference. It is not intended to be an standalone substitution of the book so if you really want to learn the concepts here presented, buy and read the book and use this repository as a reference and guide.

If you are the publisher and think this repository should not be public, just write me an email at toantdfu [at] gmail [dot] com and I will make it private.

Contributions: Issues, comments and pull requests are super welcome 😃
There is a [Quick Reference](#quick-reference) at the end.

<!-- TOC depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->
# Table of Contents
- [Table of Contents](#table-of-contents)
- [Chapter 1. A Pragmatic Philosophy](#chapter-1-a-pragmatic-philosophy)
	- [1.-It's Your Life](#1-its-your-life)
	- [2.-The Cat Ate My Source Code](#2-the-cat-ate-my-source-code)
	- [3.-Software Entropy](#3-software-entropy)
	- [4.-Stone Soup and Boiled Frogs](#4-stone-soup-and-boiled-frogs)
	- [5.-Good enough soup](#5-good-enough-soup)
	- [6.-Your Knowledge Portfolio](#6-your-knowledge-portfolio)
	- [7.-Communicate](#7-communicate)
- [Chapter 2. A Pragmatic Approach](#chapter-2-a-pragmatic-approach)
	- [8.-The Essence of Good Design](#8-the-essence-of-good-design)
	- [9.-DRY-The Evils of Duplication](#9-dry-the-evils-of-duplication)
	- [10.-Orthogonality](#10-orthogonality)
	- [11.-Reversibility](#11-reversibility)
	- [12.-Tracer Bullets](#12-tracer-bullets)
	- [13.-Prototype and Post-it Note](#13-prototype-and-post-it-notes)
	- [14.-Domain Languages](#14-domain-languages)
	- [15.-Estimating](#15-estimating)


- [Quick Reference](#quick-reference)
	- [Tips](#tips)
	- [Quotes](#quotes)
	- [CheckList](#checklist)
		- [Languages To Learn](#languages-to-learn)
		- [The WISDOM Acrostic](#the-wisdom-acrostic)
		- [How to Maintain Orthogonality](#how-to-maintain-orthogonality)
		- [Things to prototype](#things-to-prototype)
		- [Architectural Questions](#architectural-questions)
		- [Debugging Checklist](#debugging-checklist)
		- [Law of Demeter for Functions](#law-of-demeter-for-functions)
		- [How to Program Deliberately](#how-to-program-deliberately)
		- [When to Refactor](#when-to-refactor)
		- [Cutting the Gordian Knot](#cutting-the-gordian-knot)
		- [Aspects of Testing](#aspects-of-testing)
<!-- /TOC -->

# Chapter 1. A Pragmatic Philosophy
**Tip 1: Care About Your Craft**

We feel that there is no point in developing software unless you care about doing it well

**Tip 2: Think! About Your Work**

Think about what you're doing while you're doing it. Never run on auto-pilot. Constantly think about and critique your work in real-time.

## 1.-It's Your Life
Software development must appear close to the top of any list of any careers where you have control. But, for some reason, developers seem to resist change.

**Tip 3: You Have Agency**

## 2.-The Cat Ate My Source Code

### Team trust

### Take responsibility

**Tip 4: Provide Options, Don't Make Lame Excuses**

Don't say it can't be done, explain what can be done to salvage the situation.

## 3.-Software Entropy

The industry gives you a remarkable set of opportunities. Be proactive, and take them.

**Tip 5: Don't Live with Broken Windows**

Fix "broken windows" as soon as it is discovered. Neglect accelerates the software rot faster than any other factor. If you find yourself on a project where the code is pristinely beautiful, you will likely take extra special care to not mess it up.

## 4.-Stone Soup and Boiled Frogs

**Tip 6: Be a Catalyst for Change**

Most software disasters start out too small to notice, and most project overruns happen a day at a time. Determine whether you're making good or doing harm when you try to catalyze change.

**Tip 7: Remember the Big Picture**

Keep an eye on the big picture. Constantly review what's happening around you, not just what you personally are doing.

## 5.-Good enough soup

The scope and quality of the system you produce should be discussed as part of that system's requirements.

**Tip 8: Make Quality a Requirements Issue**

Great software today is often preferable to the fantasy of perfect software tomorrow. If you give users something to play with early, their feedback will often lead you to a better eventual solution.

## 6.-Your Knowledge Portfolio

* Serious investors invest regularly—as a habit.
* Diversification is the key to long-term success.
* Smart investors balance their portfolios between conservative and high-risk,high-reward investments.
* Investors try to buy low and sell high for maximum return.
* Portfolios should be reviewed and rebalanced periodically


### Building Your Portfolio
* Invest regularly
* Diversify
* Manage risk
* Buy low, sell High
* Review and rebalance

**Tip 9: Invest Regularly in Your Knowledge Portfolio**

### Goals
* Learn at least one new language every year.
* Read a technical book each month.
* Read nontechnical books, too.
* Take classes.
* Participate in local user groups and meetups.
* Experiment with different environments.
* Stay current.

It's important to **continue investing**. It doesn't matter whether you ever use any of these technologies on a project, or even whether you put them on resume. The process of learning will expand your thinking, opening you to new possibilities and new way of doing things. 

### Critical Thinking

You need to ensure that the knowledge in your portfolio is accurate and unswayed by either vendor or media hype.

**Tip 10: Critically Analyze What You Read and Hear**

* Ask the "Five Whys"
* Who does this benefit?
* What's the context?
* When or Where would this work?
* Why is this a problem?

## 7.-Communicate

Write natural language as you would write code.

**Tip 11: English is Just Another Programming Language**

### Know Your Audience

You're communicating only if you're conveying what do you mean to convey. You need to understand the needs, interests, and capabilities of your audience.

Don't wait for questions (for the feedback): ask for them.

### Know What You Want To Say

Plan what you want to say. Write an outline. Then ask yourself, "Does this communicate what I want to express to my audience in a way that works for them?" Refine it until it does.

### Choose Your Moment

You need to work out what your audience's priorities are to understand what your audience needs to hear

### Choose A Style

Adjust the style of your delivery to suit your audience.

### Make It Look Good

Find the best way to convey your ideas to the audience

### Involve Your Audience

If possible, involve your readers with early drafts of your document. Get their feedback, and pick their brains. You'll build a good working relationship and you'll probably produce a better document in the process.

### Be A Listener

Encourage people to talk by asking questions, or ask them to restate the discussion in their own words.

### Get Back to People

Keeping people informed makes them far more forgiving of the occasional slip, make them feel that you haven't forgotten them.

**Tip 12: It's Both What You Say and the Way You Say It**

The more effective that communication, the more influential you become.

### Documentation

Document is an integral part of the overall development process. Keep code and documentation together.

**Tip 13: Build Document In, Don't Bolt It On**

# Chapter 2. A Pragmatic Approach

## 8.-The Essence of Good Design

**Tip 14: Good Design Is Easier to Change Than Bad Design**

Every design principle out there is a special case of ETC

### ETC Is A Value, Not A Rule

You need to deliberately asking yourself "did the thing I just did make the overall system easier or harder to change?"

* Try to make what you write replaceable, keeping the code decoupled and cohesive

* Note the situation in your engineering day book: the choices you have and some guesses about change

## 9.-DRY-The Evils of Duplication

Every piece of knowledge must have a single, unambiguous, authoritative representation within a system.

**Tip 15: DRY - Don't Repeat Yourself**

### DRY Is More Than Code

DRY is about the duplication of knowledge, of intent. It's about expressing the same thing in two different places, possibly in two totally different ways.

### Duplication In Code

```js
function printBalance(account) {
  console.log(`Debits: ${account.debits.toFixed(2)}`);
  console.log(`Credits: ${account.credits.toFixed(2)}`);

  if (account.fees < 0) {
    console.log(`Fees: ${-account.fees.toFixed(2)}`);
  } else {
    console.log(`Fees: ${account.fees.toFixed(2)}`);
  }
  console.log("---------");
  if (account.balance < 0) {
    console.log(`Fees: -${account.balance.toFixed(2)}`);
  } else {
    console.log(`Balance: -${account.balance.toFixed(2)}`);
  }
}
```

We can improve the code by 

- Adding `formatAmount` function to handle format and negative numbers for us.

- Adding `reportLine` function to handle label format

```js
function formatAmount(value) {
  let result = value.toFixed(2);
  if (value < 0) {
    return `-${result}`;
  }
  return result;
}

function reportLine(label, value) {
  console.log(`${label}: ${formatAmount(value)}`);
}

function printBalance({ debits, credits, fees, balance }) {
  reportLine("Debits", debits);
  reportLine("Credits", credits);
  reportLine("Fees", fees);
  console.log("---------");
  reportLine("Balance", balance);
}
```

### Not All Code Duplication is Knowledge Duplication

If the code is the same, but the knowledge they represent is different. That's a coincidence, not a duplication.

### Duplication In Documentation

Ask yourself what the comment adds to the code. If it compensates for bad naming and layout then renaming the variable

### DRY Violations In Data

**Tip 16: Make It Easy to Reuse**

If it isn't easy, people won't do it. And if you fail to reuse, you risk duplicating knowledge.

## 10.-Orthogonality

#### A Nonorthogonal System

Nonorthogonal systems are inherently more complex to change and control. When components of any system are highly interdependent, there is no such thing as a local fix.

### Benefit Of Orthogonality

**Gain Productivity**

* Changes are localized, so development and testing time are reduced.
* An orthogonal approach promotes reuse.
* There is a fairly subtle gain in productivity when you combine orthogonal components.

**Reduce Risk**

* Diseased sections of code are isolated.
* The resulting system is less fragile.
* An orthogonal system will probably better tested.
* You will not be as tightly tied to a particular vendor, product or platform

**Tip 17: Eliminate Effects Between Unrelated Things**

### Design

*If I dramatically change the requirements behind a particular function, how many modules are affected?*

Ask yourself how decoupled your design is from changes in the real world. *Don't rely on the properties of things you can't control*

### Toolkits And Libraries

Be careful to preserve the orthogonality of your system as you introduce third-party toolkits and libraries.

### Coding

* Keep your code decoupled
* Avoid global data
* Avoid similar functions

### Testing

### Documentation

### Living With Orthogonality

## 11.-Reversibility

We don't always make the best decisions the first time around

**Tip 18: There Are No Final Decisions**

### Flexible architecture

While many people try to keep their code flexible, you also need to think about maintaining flexibility in the areas of architecture, deployment and vendor integration.

**Tip 19: Forgo Following Fads**

No one knows what the future may hold, especially not us! Be prepared for changes

## 12.-Tracer Bullets

User requirements may be vague, because your users have never seen a system like this before. 

### Code that glows in the dark

Look for the important requirements, the ones that define the system. Look for the areas where you have doubts, and where you see the biggest risks. Then prioritize your development so that these are the first areas you code.

**Tip 20: Use Tracer Bullets to Find the Target**

Tracer development is an incremental approach. 

Advantages of tracer development are:

* Users can see something working early — users can see visible progress toward their system, regardless if there is a lack of functionality.
* Developers build a structure for their work — tracer development produces an outline of the requirements embodied in code.
* You have an integration platform — you have an environment in which you can add new pieces of code after unit-testing. A system connected end-to-end makes integration faster and more accurate.
* You have something to demonstrate — when working with clients who expect demos during every meeting, simply demonstrate the tracer code.
* You get a better feel for progress — tracer development allows developers to take multiple small cases, one at a time. This allows for performance to be measured much easier and demonstrates progress to your users.

### Tracer Bullets Don't Always Hit Their Target

The use of tracer development doesn’t always provide guaranteed results, however it is a technique that can be used when you’re not 100% certain of where you’re going. Typically, you should use tracer development in a new project with little direction regarding requirement implementation. Like with tracer bullets, you can still miss the target and that is fine. Work on how to change what needs to be changed in order to get closer to target.

### Tracer Code Versus Protyping

The key differences between tracer development and prototyping are:

* Prototyping is disposable. Tracer development is not.
* Tracer code isn’t fully functional, but forms part of an applications skeleton.
* Prototyping doesn’t necessarily have done with code. They can be written on whiteboards, index cards, etc.
* Prototyping involves more planning and brainstorming, while tracer development takes on a more make-something-out-of-nothing approach. Adjustments can be made to be closer on target.

## 13.-Prototype and Post-it Notes

We build software prototypes to analyze and expose risk, and to offer chances for correction at a greatly reduced cost.

### Things To Prototype

* Architecture
* New functionality in an existing system
* Structure or conentents of external data
* Third-party tools or components
* Performance issues
* User interface design

Prototyping is a learning experience. Its value lies not in the code produced, but it the lessons learned. That's really the point of prototyping.

**Tip 21: Prototype to Learn**

### How To Use Prototypes

Avoid details:
* Correctness
* Completeness
* Robustness
* Style

### Protyping Architecture

* Are the responsibilities of the major components well defined and appropriate?
* Are the collaborations between major components well defined?
* Is coupling minimized?
* Can you identify potential sources of duplication?
* Are interface definitions and constraints acceptable?
* Does every module have an access path to the data it needs during execution? Does it have that access when it needs it?

## 14.-Domain Languages

Domain Languages refers to specialized languages or notations that are tailored to a specific problem domain or industry. These languages are designed to express concepts and operations in a way that is intuitive and natural for domain experts, making it easier to communicate and work with complex ideas within that particular field.

Domain languages are often created to bridge the gap between technical implementation and the problem domain itself. By using a domain language, developers can write code that closely resembles the language and terminology used by domain experts, making it easier for them to understand and validate the software.

**Tip 22: Program Close to the Problem Domain**

## 15.-Estimating

By mastering estimation and developing an intuitive sense of magnitudes, you can demonstrate the apparent capability to assess feasibility.

**Tip 23: Estimate to Avoid Surprises**

### How Accurate Is Accurate Enough?
**First:** Do they need high accuracy, or are they looking for a ballpark figure?

**Second:** Scale time estimates properly

| Duration   	| Quote estimate in                    	|
|------------	|--------------------------------------	|
| 1-15 days  	| days                                 	|
| 3-6 weeks  	| weeks                                	|
| 8-20 weeks 	| months                               	|
| 20+ weeks  	| think hard before giving an estimate 	|

### Where Do Estimates Come From?

Ask someone who's been in a similar situation in the past.

* Understand What's Being Asked
* Build a Model of the System
* Break the Model into Components
* Give Each Parameter a Value
* Calculate the Answers
* Keep Track of Your Estimating Prowess

### Estimating Project Schedules

Two techniques for reducing uncertainty

**Painting the Missile**
Using a range of values like *optimistic*, *most likely* and *pessimistic* *estimate* is a great way to avoid the estimation error.

**Eating the Elephant**
The only way to determine the timetable for a project is by gaining experience on that same project. Practice incremental development, repeating the following steps:
* Check requirements
* Analyze risks (and prioritize riskiest items earlier)
* Design, implement and integrate
* Validate with users

Unless you are doing an application similar to a previous one, with the same team and the same technology, you'd just be guessing.

The refinement and confidence in the schedule gets better and better each iteration.

**Tip 24: Iterate the Schedule with the Code**

### What To Say When Asked For An Estimate

*"I'll get back to you."*

# Quick Reference
## Tips
**Tip 1: Care About Your Craft**

**Tip 2: Think! About Your Work**

**Tip 3: You Have Agency**

**Tip 4: Provide Options, Don't Make Lame Excuses**

**Tip 5: Don't Live with Broken Windows**

**Tip 6: Be a Catalyst for Change**

**Tip 7: Remember the Big Picture**

**Tip 8: Make Quality a Requirements Issue**

**Tip 9: Invest Regularly in Your Knowledge Portfolio**

**Tip 10: Critically Analyze What You Read and Hear**

**Tip 11: English is Just Another Programming Language**

**Tip 12: It's Both What You Say and the Way You Say It**

**Tip 13: Build Document In, Don't Bolt It On**

**Tip 14: Good Design Is Easier to Change Than Bad Design**

**Tip 15: DRY - Don't Repeat Yourself**

**Tip 16: Make It Easy to Reuse**

**Tip 17: Eliminate Effects Between Unrelated Things**

**Tip 18: There Are No Final Decisions**

**Tip 19: Forgo Following Fads**

**Tip 20: Use Tracer Bullets to Find the Target**

**Tip 21: Prototype to Learn**

**Tip 22: Program Close to the Problem Domain**

**Tip 23: Estimate to Avoid Surprises**

**Tip 24: Iterate the Schedule with the Code**

## Quotes
I'm not in the world to live up to your expectations and you're not in this world to live up to mine. - Bruce Lee

The greatest of all weaknesses is the fear of appearing weak.

Striving to better, oft we mar what’s well - Shakespeare, King Lear 1.4

An investment in knowledge always pays the best interest. - Benjamin Franklin

Nothing is more dangerous than an idea if it's the only one you have. 


## CheckList

### Languages To Learn
Tired of C, C++, and Java? Try the following languages. Each of these languages has different capabilities and a different "flavor." Try a small project at home using one or more of them.
- Closure
- Elixir
- Elm
- F#
- Go
- Haskell
- Python



Content from The Pragmatic Programmer: Your journey to mastery, 20th Anniversary Edition, by Andrew Hunt and David Thomas. Visit [https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/).
Copyright 2000 by Addison Wesley Longman, Inc.
