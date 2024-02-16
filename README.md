# The-Pragmatic-Programmer-20th-Anniversary-Edition

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
- [Chapter 3. The Basic Tools](#chapter-3-the-basic-tools)
	- [16.-The Power of Plain Text](#16-the-power-of-plain-text)
	- [17.-Shell Games](#17-shell-games)
	- [18.-Power Editing](#18-power-editing)
	- [19.-Version Control](#19-version-control)
	- [20.-Debugging](#20-debugging)
	- [21.-Text Manipulation](#21-text-manipulation)
	- [22.-Engineering Daybooks](#22-engineering-daybooks)
- [Chapter 4. Pragmatic Paranoia](#chapter-4-pragmatic-paranoia)
	- [23.-Design by Contract](#22-engineering-daybooks)
	- [24.-Dead Programs Tell No Lies](#24-dead-programs-tell-no-lies)
	- [25.-Assertive Programming](#25-assertive-programming)
	- [26.-How to Balance Resources](#26-how-to-balance-resources)
	- [27.-Don't Outrun Your Headlights](#27-dont-outrun-your-headlights)
- [Chapter 5. Bend, or Break](#chapter-5-bend-or-break)
	- [28.-Decoupling](#28-decoupling)
	- [29.-Juggling the Real World](#29-juggling-the-real-world)
	- [30.-Transforming Programming](#30-transforming-programming)
	- [31.-Inheritance Tax](#31-inheritance-tax)
	- [32.-Configuration](#32-configuration)
- [Chapter 6. Concurrency](#chapter-6-concurrency)
	- [33.-Breaking Temporal Coupling](#33-breaking-temporal-coupling)
	- [34.-Shared State Is Incorrect State](#34-shared-state-is-incorrect-state)
	- [35.-Actors and Processes](#35-actors-and-processes)
	- [36.-Blackboards](#36-blackboards)
- [Chapter 7. While You Are Coding](#chapter-7-while-you-are-coding)
	- [37.-Listen to Your Lizard Brain](#37-listen-to-your-lizard-brain)
    - [38.-Programming by Coincidence](#38-programming-by-coincidence)
	- [39.-Algorithm Speed](#39-algorithm-speed)
	- [40.-Refactoring](#40-refactoring)
	- [41.-Test to Code](#41-test-to-code)
	- [42.-Property-Based Testing](#42-property-based-testing)
	- [43.-Stay Safe Out There](#43-stay-safe-out-there)
	- [44.-Naming Things](#44-naming-things)
- [Chapter 8. Before the Project](#chapter-8-before-the-project)
	- [45.-The Requirements Pit](#45-the-requirements-pit)
	- [46.-Solving Impossible Puzzles](#46-solving-impossible-puzzles)


- [Quick Reference](#quick-reference)
	- [Tips](#tips)
	- [Quotes](#quotes)
	- [CheckList](#checklist)
		- [Languages To Learn](#languages-to-learn)
		- [Communicate](#communicate)
		- [Debugging Check](#debugging-check-1)
		- [Common Things To Put It Configuration Data](#common-things-to-put-it-configuration-data)
		- [How To Program Deliberately](#how-to-program-deliberately-1)
		- [Security Basic Principles](#security-basic-principles-1)
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
Prototyping is a learning experience. Its value lies not in the code you produce, but in the lessons you learn.

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

# Chapter 3. The Basic Tools

## 16.-The Power of Plain Text

We like our plain text to be understandable to humans

**Tip 25: Keep Knowledge in Plain Text**

### The Power Of Text

* Insurance Against Obsolescence
* Leverage
* Easier Testing

## 17.-Shell Games

A benefit of GUIs is **WYSIWYG**. The disadvantage is **WYSIAWYG-** What you see is *all* what you get.

**Tip 26: Use the Power of Command Shells**

## 18.-Power Editing

**Tip 27: Achieve Editor Fluency**

## 19.-Version Control

**Tip 28: Always Use Version Control**

## 20.-Debugging

### Psychology Of Debugging

Embrace the fact that debugging is just problem solving, and attack it as such.

**Tip 29: Fix the Problem, Not the Blame**

It doesn't really matter whether the bug is your fault or someone else's. It is still your problem.

### A Debugging Mindset

You need to turn off many of the defenses you use each day to protect your ego, tune out any project pressures you may be under, and get yourself comfortable.

**Tip 30: Don't Panic**

Don't waste a single neuron on the train of thought that begins "but that can't happen" because quite clearly it *can*, and has.

Always try to discover the root cause of a problem, not just this particular appearance of it.

### Where To Start

* Before *start*, make sure that you're working on code that built cleanly-without *warnings*.
* Watch the user who reported the bug in action to get sufficient level of detail.

### Debugging Strategies

**Reproducing Bugs**
* The best way to start fixing a bug is to make it reproducible.
* We want a bug that can be reproduced through short steps (*single command*).

**Tip 31: Failing Test Before Fixing Code**

**Tip 32: Read the Damn Error Message**

* Make sure you know how to move up and down the call stack and examine the local stack environment
* Keep pen and paper nearby so we can jot down notes.
* Looking at a stack trace seems to scroll on forever. There is often a quicker way to find the problem than examining each and every stack frame: use a *binary chop*. Two common bugs scenarios
	* Sensitive to Input Values
	* Regresssions Accross Releases

**Logging and/or Tracing**

Watch the state of a program or a data structure over time.

**Rubber Ducking**

Explain the bug to someone else.

**Process of Elimination**

It is possible that a bug exists in the OS, the compiler, or a third-party product—but this should not be your first thought

**Tip 33: "select" Isn't Broken**

### The Element of Surprise

When faced with a "suprising" failure, you must accept that one or more of your assumption is wrong.

**Tip 34: Don't Assume It - Prove It**

* Beyond fixing the bug, you need to determine why it this failure wasn't caught earlier. Consider amend the unit or other tests so they would have caught it.
* Are there any other places that may susceptible to this same bug?
* If it took long a long time to fix this bug, *Why*? How could you make fixing this bug easier next time?
* Finally, if the bug is result of someone else's wrong assumption, discuss the problem with the whole team

### Debugging Check

* Is the problem being reported a direct result of the underlying bug, or merely asymptom?
* Is the bug really in the framework you're using? Is it in the OS? Or is it in your code?
* If you explained this problem in detail to a coworker, what would you say?
* If the suspect code passes its unit tests, are the tests complete enough? What happens if you run the tests with *this* data?
* Do the conditions that caused this bug exist anywhere else in the system?

## 21.-Text Manipulation

**Tip 35: Learn a Text Manipulation Language**

## 22.-Engineering Daybooks

Use daybooks to take notes in the meetings, to jot down what we're working on, to note variable values when debugging, to leave reminders where we put things, to record wild ideas, and sometimes just to doodle.

Main benefits:
* More reliable than memory.
* Gives you a place to store ideas that aren't immediately relevant to the task at hand.

# Chapter 4. Pragmatic Paranoia

**Tip 36: You Can't Write Perfect Software**

No one in the brief history of computing has ever written a piece of perfect software. Pragmatic Programmers don't trust themselves, either.

## 23.-Design by Contract

Every function and method in a software system does *something*. Before it start that *something*, the function may have some expectation about the state of the world before and after
* Preconditions
* Postconditions
* Class invariants

**Tip 37: Design with Contracts**

Write "lazy" code: be strict in what you will accept before you begin, and promise as little as possible in return.

### Implementing DBC

Simply enumerating at design time:

* what the input domain range is
* what the boundary conditions are
* what the routine promises to deliver (and what it doesn't)

### DBC And Crashing Early

DBC fits in nicely with our concept of crashing early.

## 24.-Dead Programs Tell No Lies

It's easy to fall into the "it can't happen" mentality. We're coding defensively. We're making many assumptions. 

All errors give you information. You could convince yourself that the error can't happen, and choose to ignore it. Instead, Pragmatic Programmers tell themselves that if there is an error, something very, very bad has happened.

**Tip 38: Crash Early**

### Crash, Don't Trash

One of the benefits of detecting problems as soon as you can is that you can crash earlier, and crashing is often the best thing you can do.

When your code discovers that something that was supposed to be impossible just happened, your program is no longer viable.

`A dead program normally does a lot less damage than a crippled one.`

## 25.-Assertive Programming

**Tip 39: Use Assertions to Prevent the Impossible**

* Assertions are also useful checks on an algorithm's operation.
* Don't use assertions in place of real error handling.
* Leave Assertions Turned On, unless you have critical performance issues.

## 26.-How to Balance Resources

We all manage resources whenever we code: memory, transactions, threads, network connections, files, timers-all kinds of things with limited availability. Most of the time, resource usage follows a predictable pattern: you allocate the resource, use it, and then deallocate it.

**Tip 40: Finish What You Start**

When in doubt, it always pays to reduce scope.

**Tip 41: Act Locally**

### Nest Allocations

* Deallocate resources in the opposite order to that in which you allocate them.
* When allocating the same set of resources in different places in your code, always allocate them in the same order (prevent deadlocks)

### Balancing And Exceptions

If an exception is thrown, how do you guarantee that everything allocated prior to the exception is tidied up?:
* Use variable scrope
* Use a `finally` clause in a `try...catch` block

## 27.-Don't Outrun Your Headlights

We can't see too far ahead into the future, and the further off-axis you look, the darker it gets. 

**Tip 42: Take Small Steps-Always**

Always take small, deliberate steps, checking for feedback and adjusting before proceeding. Never take on a step or a task that's "too big".

**Tip 43: Avoid Fortune-Telling**

Much of the time, tomorrow looks a lot like today. But don't count on it

# Chapter 5. Bend, or Break

## 28.-Decoupling

**Tip 44: Decoupled Code Is Easier to Change**

Some of the symptoms of coupling:
* Wacky dependencies between unrelated modules or libraries.
* "Simple" changes to one module that propagate through unrelated modules in the system or break stuff elsewhere in the system.
* Developers afraid to change code because they aren't sure what might be affected.
* Meetings where everyoen has to attend because no one is sure who will be affected by a change.

```js
function applyDiscount(customer, orderId, discount) {
	let totals = customer
				.orders
				.find(orderId)
				.getTotals();
	totals.grandTotal = totals.grandTotal - discount;
	totals.discount = discount;
}
```

This chunk of code is traversing five levels of abstraction, from customer to total amounts.

**Tip 45: Tell, Don't Ask**

This principle says that you shouldn't make decisions based on the internal state of an object and then update that object. Doing so totally destroys the benefits of encapsulation and, in doing so, spreads the knowledge of the implemenation throughout the code.

```js
function applyDiscount(customer, orderId, discount) {
	let totals = customer
				.findOrder(orderId)
				.applyDiscount(discount)
}
```

**Tip 46: Don't Chain Method Calls**

It is subjective, sometime chain method is the best approach

**Tip 47: Avoid Global Data**

**Tip 48: If It's Important Enough to Be Global, Wrap It in an API**

Keeping your code shy: having it only deal with things it directly knows about, will help keep your applications decoupled, and that will make them more amendable to change.

## 29.-Juggling the Real World

An *event* represents the availability of information

### Finite State Machines

A state machine is basically just a specification of how to handle events. It consists of a set of states. For each state, we list the events that are significant to that state. For each of those events, we define the new current state of the system.

### The Observer Pattern

In the *observer pattern* we have a source of events, called the *observable* and a list of clients, the *observers*, who are interested in those events.

An observer registers its interest with the observable, typically by passing a reference to a function to be called. Subsequently, when the event occurs, the observable **iterates** down its list of observers and calls the function that each passed it. The event is given as a parameter to that call.

The problem of observer pattern:
* Each of the observers has to register with the observable, it introduces coupling
* Performance bottenecks as callbacks are handled inline by observable, synchronously

### Publish/Subscribe

We have *publishers* and *subscribers*. These are connected via channels.
Subscribers register interest in one or more of these named channels, and publishers write events to them. Unlike the observer pattern, the communication between the publisher and subscriber is handled outside your code, and is potentially asynchronous.

### Reactive Programming, Streams, And Events

If you've ever used a spreadsheet, then you'll familiar with *reactive programming*. If a cell contains a formular which refers to a second cell, then updating that second cell causes the first to update as well. The value *react* as the values they use change.

*Streams* let us treat events as if they were a collection of data. 

## 30.-Transforming Programming

**Tip 49: Programming Is About Code, But Programs Are About Data**

### Finding Transformations

*Top-down* approach: find steps that lead from input to output

**Tip 50: Don't Hoard State, Pass It Around**

Think of code as a series of (nested) transformations can be a liberating approach to programming. You will find your code cleaner, your functions shorter, and your designs flatter.

## 31.-Inheritance Tax

Inheritance is coupling. Not only is the child class coupled to the parent, the parent's parent, and so on, but the code that *uses* the child is also coupled to all the ancestors. 

**Tip 51: Don't Pay Inheritance Tax**
Consider alternatives that better fit your needs, such as interfaces, delegation, or mixins

### The Alternatives Are Better

#### Interfaces and Protocols

The code for class must include the functionality of interfaces it *implements*

**Tip 52: Prefer Interfaces to Express Polymorphism**
Interfaces make polymorphism explicit without the coupling introduced by inheritance.

#### Delegation

**Tip 53: Delegate to Services: Has-A Trumps Is-A**
Don’t inherit from services: contain them.

### Mixins, Traits, Categories, Protocol Extensions, ...

**Tip 54: Use Mixins to Share Functionality**

Mixins add functionality to classes without the inheritance tax. Combine with interfaces for painless polymorphism.

## 32.-Configuration

**Tip 55: Parameterize Your App Using External Configuration**

When code relies on values that may change after the application has gone live, keep those values external to the app. When you application will run in different environments, and potentially for different customers, keep the environment and customer specific values outside the app.

# Chapter 6. Concurrency

*Concurrency* is when the execution of two or more pieces of code acts as if they run at the same time.
*Parallelism* is when they *do* run at the same time.

## 33.-Breaking Temporal Coupling

Two aspects of time:
* Concurrency: things happening at the same time
* Ordering: the relative positions of things in time

We need to allow for concurrency and to think about decoupling any time or order dependencies. In doing so, we can gain flexibility and reduce any time-based dependencies

**Tip 56: Analyze Workflow to Improve Concurrency**

Exploit concurrency in your user’s workflow.

Use *activity diagram* to maximize parallelism by identifying activities that could be performed in parallel, but aren't.

### Opportunities For Concurrency

Find activities that take time, but not time in our code. These are all opportunities to do something more productive.

### Opportunities For Parallelism

Take a large piece of work, split it into independent chunks, process each in parallel, then combine the results.

## 34.-Shared State Is Incorrect State

**Tip 57: Shared State Is Incorrect State**

We should make atomic operation so the underlying value can't change in the middle.

**Semaphores and Other Forms of Mutual Exclusion**
Classically, the operation lock the access to the resource and release when it is done.

**Make the Resource Transactional**
The current design is poor because it delegates responsibility for protecting access to the resource to the people who use it. Let's change it to centralize that control.

**Multiple Resource Transactions**
If we add a new resource to the transaction, we should have a new module to handle the transaction. It either succeeds or fails.

In the real world, there are likely to be many composite resources; you'd probably want some item containing references to its components and a generic method that handles the resources. 

**Tip 58: Random Failures Are Often Concurrency Issues**
Variations in timing and context can expose concurrency bugs, but in inconsistent and irreproducible ways.

## 35.-Actors and Processes

* An *actor* is an independent virtual processor with its own local state. Each actor has a mailbox. When a message appears in the mailbox, the actor will process the message.
* A *process* is a more general-purpose virtual processor, often implemented by the operating system to faciliate concurrency.

Actor execute concurrently, asynchronously, and share nothing.

**Tip 59: Use Actors For Concurrency Without Shared State**
Use Actors to manage concurrent state without explicit synchronization.

In the actor model, there's no need to write any code to handle concurrency, as there is no shared state. There's also no need to code in explicit end-to-end "do this, do that" logic, as the actors work it out for themselves based on the messages they receive.

## 36.-Blackboards

**Tip 60: Use Blackboards to Coordinate Workflow**
Use blackboards to coordinate disparate facts and agents, while maintaining independence and isolation among participants.

# Chapter 7. While You Are Coding

## 37.-Listen to Your Lizard Brain

Instincts make you feel, not think.

### Fear Of Blank Page

As a developer, you've been trying things and seeing which worked and which didn't. You've been accumulating experience and wisdom. When you feel a nagging doubt, or experience some reluctance when faced with a task, it might be that experience trying to speak to you. Give it time and your doubts will probably crystallize into something more solid, something that you can address. 

You afraid of making a mistake. 

That's a reasonable fear. We developers put a lot of ourselves into our code, we can take errors in that code as reflections on our competence. Perhaps there's an element of *imposter syndrome*

### Fighting Yourself

Sometimes coding feels like walking uphill in mud. 

Your code is trying to tell you that this is harder than it should be. Whatever the reason, your lizard brain is sensing feedback from the code, and it's desperately trying to get you to listen.

### How To Talk Lizard

**Tip 61: Listen to Your Inner Lizard**
When it feels like your code is pushing back, it’s really your subconscious trying to tell you something’s wrong.

First, stop what you're doing. Stop thinking about the code, and do something that is fairly mindless for a while. Give yourself a little time and space to let your brain organize itself. Eventually ideas may bubble up to the conscious level, and you have one of those *a ha!* moments.

If that's not working, try externalizing the issue. Make doodles about the code you're writing, or explain it to a coworker, or to your rubber duck. Expose different parts of your brain to the issue, and see if any of them have a better handle on the thing that's troubling you. 

But maybe you've tried these things, and you're still stuck. It's time for action.

### It's Playtime!

Typing in some cde, then do another thing, then type some more code, then do select-all/delete and start again. And again. And again.

There is a brain hack that seems to work. Tell yourself you need to prototype something.

1. Write "I'm protyping" on a sticky node, and stick it on the side of your screen.
2. Remind yourself that protypes are meant to fail. And remind yourself that prototypes get thrown away, even if they don't fail. 
3. In your empty editor buffer, create a comment descibing in one sentence what you want to learn or do.
4. Start coding.

### Not Just *Your* Code

A large part of our job is dealing with existing code, often written by other people. Those people will have different instincts to you, and so the decisions they made will be different. Not neccessarily worse, just different.

Read code mechanically, making notes on stuff that seems important.

Or you can try an experiment. Once you spot strange things, jot it down. Continue doing this, and look for patterns. If you can see what drove them to write code that way.

And you might just learn something new along the way.

### Not Just Code

Learning to listen to your gut. Sometimes things feel wrong. Stop and analyze these feelings.

## 38.-Programming by Coincidence

Avoid programming by coincidence-relying on luck and accidental successes-in favor of *programming deliberately*.

### How To Program By Coincidence

**Accidents of Implementation**
Accidents of implementation are things that happen simply because that's the way the code is currently written. You end up relying on undocumented error or boundary conditions.

For code you write that others will call, the basic principles of good modularization and of hiding implementation behind small, well-documented interfaces can all help. 

For routines you call, rely only on documented behavior. If you can't, for whatever reason, then document your assumption well.

**Phantom Patterns**
Tests that seem to pass on your machine but not on the server might indicate a difference between the two environments, or maybe it's just a coincidence.

Don't assume it, prove it.

**Accidents of Context**
When you copied code from the first answer you found on the net, are you sure your context is the same? Or are you building "cargo cult" code, merely imitating form without content?

Finding an answer that happens to fit is not the same as the right answer

**Tip 62: Don't Program by Coincidence**
Rely only on reliable things. Beware of accidental complexity, and don’t confuse a happy coincidence with a purposeful plan.

### How To Program Deliberately

* Always be aware of what you are doing.
* Can you explain the code, in detail, to a more junior programmer? If not, perhaps you are relying on coincidences.
* Don't code in the dark. Build an application you don't fully grasp, or use a technology you don't understand, and you'll be likely be bitten by coincidences. If you're not sure why it works, you won't know why it fails.
* Proceed from a plan.
* Rely only on reliable things. Don't depend on assumptions. If you can't tell something is reliable, assume the worst.
* Document your assumptions. It can help clarify your assumptions in your own mind, as well as help communicate them to others.
* Don't just test your code, but test your assumptions as well. Don't guess, actually try it.
* Prioritize your effort. Spend time on the important aspects, more than likely, these are the hard parts.
* Don't be a slave to history. Don't let existing code dictate future code.

## 39.-Algorithm Speed

Whenever we write anything contain loops or recursive calls, we subconsciously check the runtime and memory requirements. 

### Big O Notation

The Big O Notation is a mathematical way of dealing with approximations. When we write that a particular algorithm take `O(n²)`, we are simply saying that the worst-case time taken will vary as the square of `n`

The Big O notation doesn't apply just to time; you can use it to represent any other resources used by an algorithm. For example, it is often useful to be able to model memory consumption.

### Common Sense Estimation

Simple loops: `O(n)`
Nested loops: `O(n²)`
Binary chop: `O(lg(n))`
Divide and conquer: `O(n lg(n))`. Algorithms that partition their input, work on the two halves independently, and then combine the result.
Combinatoric: `O(Cⁿ)`

### Algorithm Speed In Practice

**Tip 63: Estimate the Order of Your Algorithms**
Get a feel for how long things are likely to take before you write code.

**Tip 64: Test Your Estimates**
Mathematical analysis of algorithms doesn’t tell you everything. Try timing your code in its target environment.

#### Best Isn't Always Best
Be pragmatic about choosing appropriate algorithms—the fastest one is not always the best for the job.

Be wary of premature optimization. Make sure an algorithm really is a bottleneck before investing time improving it.

## 40.-Refactoring

As a program evolves, it will become necessary to think earlier decisions and rework portions of the code.

Code needs to evolve; it's not a static thinng.

### When Should You Refactor

* Duplication. You've discovered a violation of the DRY principle ([The Evils of Duplication](#7-the-evils-of-duplication)).
* Nonorthogonal design. You've discovered some code or design that could be made more orthogonal ([Orthogonality](#10-orthogonality)).
* Outdated knowledge. Things change, requirements drift, and your knowledge of the problem increases. Code needs to keep up.
* Performance. You need to move functionality from one area of the system * to another to improve performance.
* The Tests Pass. When you've added a small amount of code, and that one extra test passes, you now have a great opportunity to dive in and tidy up what you just wrote.

#### Real-World Complications

Time pressure is often used as an excuse for not refactoring. Fail to refactor now, and there'll be a far greater time investment to fix the problem down the road.

Think of the code that needs refactoring as "a growth". 

**Tip 65: Refactor Early, Refactor Often**
Just as you might weed and rearrange a garden, rewrite, rework, and re-architect code when it needs it. Fix the root of the problem.

### How Do You Refactor
1. Don't try to refactor and add functionality at the same time.
2. Make sure you have good tests before you begin refactoring.
3. Take short, deliberate steps.

## 41.-Test to Code

Testing is the process of validating and verifying that software works under certain circumstances. However, the key advantages of testing are not just in terms of execution time, but also in terms of how we think about the tests.

**Tip 66: Testing Is Not About Finding Bugs**
A test is a perspective into your code, and gives you feedback about its design, api, and coupling.

### Thinking About Tests
If we are continuously thinking about testing, we will consider how we may design a software structure that is testable code, what we should test, how we test, and so on.

### Tests Drive Coding 
Started by thinking about our tests, and without writing a line of code, we can reduce coupling in our code and increase flexibility. 

Thinking about writing a test for our method make us look at it from the outside, as if we were a client of the code, and not its author.

**Tip 67: A Test is the First User of Your code**
Use its feedback to guide what you do.

Think about testing boundary conditions and how that will work *before* you start coding, you may find the patterns that simplify the function. If you think about the error coditions you'll need to test, you'll structure your function accordingly.

#### Test-Driven Development

The basic cycle of TDD is:

1. Decide small piece of functionality you want to add.
2. Write a test will pass once that functionality is implemented.
3. Run all tests. Verify that the only failure is the one you just wrote.
4. Write a smallest amount of code needed to get the test to pass, and verify that the tests now run cleanly.
5. Refactor your code. Make sure the tests still pass when you're done.

**Tip 68: Build End-To-End, Not Top-Down or Bottom Up**
Build small pieces of end-to-end functionality, learning about the problem as you go.

### TDD: You Need To Know Where You're Going

Tests can definitely help drive development. But, as with every drive, unless you have a destination in mind, you can end up going in circles.

### Unit Testing

Testing done on each module, in isolation, to verify its behavior. A software unit test is code that exercises a module.

### Testing Against Contract

This will tell us two things:

1. Whether the code meet the contract
2. Whether the contract means what we think it means.

How to test the combination
* Test subcomponents of a module first. Once the subcomponents have been verified, then the module itself can be tested. 

This technique reduces debugging effort by focusing on the likely problem source, avoiding unnecessary reexamination of subcomponents.

**Tip 69: Design to Test**
Start thinking about testing before you write a line of code.

### Ad Hoc Testing
Ad-hoc testing is when we run poke at our code manually.

After debugging, formalize the ad hoc test. If the code broke once, it may break again. Don't discard the test; add it to the existing unit test arsenal.

### Build A Test Window
* Log files
* Hot-key sequence or magic URL
* Feature switch

### A Culture Of Testing

**Tip 70: Test Your Software, or Your Users Will**
Test ruthlessly. Don’t make your users find bugs for you.

Testing, design, coding-it's all programming.

## 42.-Property-Based Testing

Code has *contracts*. When input is provided, it ensures specific output guarantees.

Code *invariants* are truths about a piece of state that hold when it's passed through a function.

*Property-based testing* automates testing by utilizing *properties*, which are combinations of contracts and invariants.

**Tip 71: Use Property-Based Tests to Validate Your Assumptions**
Property-based tests will try things you never thought to try, and exercise your code in ways is wasn’t meant to be used.

Property-based tests prompt you to consider your code regarding invariants and contracts, focusing on elements that should remain unchanged and conditions that must hold.

## 43.-Stay Safe Out There

### Security Basic Principles

#### Minimize Attack Surface Area
* Code complexity leads to attack vectors
* Input data is an attack vector
* Unauthenticated services are an attack vector
* Authenticated services are an attack vector
* Output data is an attack vector
* Debugging info is an attack vector

**Tip 72: Keep It Simple and Minimize Attack Surfaces**
Complex code creates a breeding ground for bugs and opportunities for attackers to exploit.

#### Principle of Least Privilege

Allow only minimum authorization, if someone asked. Don’t grant them all to be an administrator.

#### Secure Defaults

Prioritize maintaining the default security of your application, even if it may feel inconvenient. For instance, hide password when typing with an asterisk. Some people may wish to see whether it is right or not. If you are in a public are

#### Encrypt Sensitive Data

Never leave sensitive information in plain text.

#### Maintain Security Updates

Always keep all of your working PCs’ security patches up to date. It may be in danger if it is out of date.

**Tip 73: Apply Security Patches Quickly**
Attackers deploy exploits as quick as they can, you have to be quicker.

## 44.-Naming Things

> There’s some science behind the idea that names are deeply meaningful. It turns out that the brain can read and understand words really fast — The Pragmatic Programmer

The most crucial aspect is consistency. All teammates should understand the meaning of each word and use them in the same context. Many teams utilize dictionaries to list out the special terms to the team.

Lastly, carefully specify the name of everything making sense because renaming consumes a lot of effort to figure out what it really means. It’s even difficult.

**Tip 74: Name Well; Rename When Needed**
Name to express your intent to readers, and rename as soon as that intent shifts.

# Chapter 8. Before the Project

## 45.-The Requirements Pit

Requirements rarely lie on the surface. Normally, they're buried deep beneath layers of assumptions, misconceptions, and politics. Even worse, often they don't really exist at all.

**Tip 75: No One Knows Exactly What They Want**
They might know a general direction, but they won’t know the twists and turns.

**Tip 76: Programmers Help People Understand What They Want**
Software development is an act of co-creation between users and programmers.

Client comes to us with a need.
The mistake new developers often make is to take this statement of need and implement a solution for it.

**Tip 77: Requirements Are Learned in a Feedback Loop**
Understanding requirements requires exploration and feedback, so the consequences of decisions can be used to refine the initial ideas.

Sometimes the feedback wasn't easy to express in words.
We produce mockups and prototypes, and let client play with them.

**Tip 78: Work with a User to Think Like a User**
It’s the best way to gain insight into how the system will really be used.

**Tip 79: Policy Is Metadata**
Don’t hardcode policy into a system; instead express it as metadata used by the system.

The requirements can be in form that can fit on a real index card (often call *user stories*). A single index card can't hold the information needed to implement a component of the application. By keeping requirement short, you're encouraging developers to ask clarifying questions. You're enhancing the feedback process between clients and coders before and during the creation of each peace of code.

**Tip 80: Use a Project Glossary**
Create and maintain a single source of all the specific terms and vocabulary for a project.

## 46.-Solving Impossible Puzzles

The key to solving puzzles is both to recognize the constraints placed on you and to recognize the degrees of freedom you do have, for in those you'll find your solution.

**Tip 81: Don’t Think Outside the Box—Find the Box**
When faced with an impossible problem, identify the real constraints. Ask yourself: “Does it have to be done this way? Does it have to be done at all?”

When faced with an intractable problem, enumerate *all* the possible avenues you have before you. Don't dismiss anything, no matter how unusable or stupid it sounds. Now go through the list and explain why a certain path cannot be taken? Are you sure? Can you *prove* it?

Identify the most restrictive contraints first, and fit the remaining contraints within them.

If you find yourself stuck with the problems for too long or go on the wrong path. Take a break to pause your unconscious brain for a while or work on something different.

## 47.-Working Together

### Pair Programming

There are many benefits to pair programming. Different people bring different backgrounds and experience, different problem-solving techniques and approaches, and differing levels of focus and attention to any given problem. The developer acting as typist must focus on the low-level details of syntax and coding style, while the other developer is free to consider higher-level issues and scope.

When we encounter more difficult issues, we may use *mob-programming*, which allows more than two people to work with the same issue. A business analyst, tester, etc., can be one of them. Only one operates a keyboard while the others talk about a problem that is emerging.

**Tip 81: Don't Go into the Code Alone**
Programming can be difficult and demanding. Take a friend with you.

## 48.-The Essence of Agility

**Tip 82: Agile Is Not a Noun; Agile Is How You Do Things**
Agile is an adjective: it’s how you do something.

Agility is all about responding to change, responding to the unknowns you encounter after you set out.

There is no single plan you can follow when you develop software. 

Recipe for working in an agile way:
1. Work out where you are.
2. Make the smallest meaningful step towards where you want to be.
3. Evaluate where you end up, and fix anything you broke.

However, we need start with a good design to make it simple to change via decoupling in order to enable the best agile appear.

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

**Tip 25: Keep Knowledge in Plain Text**

**Tip 26: Use the Power of Command Shells**

**Tip 27: Achieve Editor Fluency**

**Tip 28: Always Use Version Control**

**Tip 29: Fix the Problem, Not the Blame**

**Tip 30: Don't Panic**

**Tip 31: Failing Test Before Fixing Code**

**Tip 32: Read the Damn Error Message**

**Tip 33: "select" Isn't Broken**

**Tip 34: Don't Assume It - Prove It**

**Tip 35: Learn a Text Manipulation Language**

**Tip 36: You Can't Write Perfect Software**

**Tip 37: Design with Contracts**

**Tip 38: Crash Early**

**Tip 39: Use Assertions to Prevent the Impossible**

**Tip 40: Finish What You Start**

**Tip 41: Act Locally**

**Tip 42: Take Small Steps-Always**

**Tip 43: Avoid Fortune-Telling**

**Tip 44: Decoupled Code Is Easier to Change**

**Tip 45: Tell, Don't Ask**

**Tip 46: Don't Chain Method Calls**

**Tip 47: Avoid Global Data**

**Tip 48: If It's Important Enough to Be Global, Wrap It in an API**

**Tip 49: Programming Is About Code, But Programs Are About Data**

**Tip 50: Don't Hoard State, Pass It Around**

**Tip 51: Don't Pay Inheritance Tax**

**Tip 52: Prefer Interfaces to Express Polymorphism**

**Tip 53: Delegate to Services: Has-A Trumps Is-A**

**Tip 54: Use Mixins to Share Functionality**

**Tip 55: Parameterize Your App Using External Configuration**

**Tip 56: Analyze Workflow to Improve Concurrency**

**Tip 57: Shared State Is Incorrect State**

**Tip 58: Random Failures Are Often Concurrency Issues**

**Tip 59: Use Actors For Concurrency Without Shared State**

**Tip 60: Use Blackboards to Coordinate Workflow**

**Tip 61: Listen to Your Inner Lizard**

**Tip 62: Don't Program by Coincidence**

**Tip 63: Estimate the Order of Your Algorithms**

**Tip 64: Test Your Estimates**

**Tip 65: Refactor Early, Refactor Often**

**Tip 66: Testing Is Not About Finding Bugs**

**Tip 67: A Test is the First User of Your code**

**Tip 68: Build End-To-End, Not Top-Down or Bottom Up**

**Tip 69: Design to Test**

**Tip 70: Test Your Software, or Your Users Will**

## Quotes
I'm not in the world to live up to your expectations and you're not in this world to live up to mine. - Bruce Lee

The greatest of all weaknesses is the fear of appearing weak.

Striving to better, oft we mar what’s well - Shakespeare, King Lear 1.4

An investment in knowledge always pays the best interest. - Benjamin Franklin

Nothing is more dangerous than an idea if it's the only one you have. 

Progress, far from consisting in change, depends on retentiveness. Those who can not remember the past are condemned to repeat it. - George Santayana, Life of Reason

It is a painful thing to look at your own trouble and know that you yourself and no one else has made it. - Sophocles, Ajax

There is a luxury in self-reproach. When we blame ourselves we feel no one else has a right to blame us. - Oscar Wilde, The Picture of Dorian Gray

It's tough to make predictions, especially about the future

When we try to pick out anything by itself, we find it hitched to everything else in the Universe.

Things don't just happen, they are made to happen.

If you can't describe what you are doing as a process, you don't know what you're doing

Without writers, stories would not be written, Without actors, stories could not be brought to life - Angie-Marie Delsante

Only human beings can look directly at something, have all the information they need to make an accurate prediction, perhaps even momentarily make the accurate prediction, and then say that it isn't so. - Gavin de Becker, The Gift of Fear

Perfection is achieved, not when there is nothing left to add, but when there is nothing left to take away…

## CheckList

### Languages To Learn
Tired of C, C++, and Java? Try the following languages. Each of these languages has different capabilities and a different "flavor." Try a small project at home using one or more of them.
* Closure
* Elixir
* Elm
* F#
* Go
* Haskell
* Python

### Communicate

* Know Your Audience
* Know What You Want To Say
* Choose Your Moment
* Choose A Style
* Make It Look Good
* Involve Your Audience
* Be A Listener
* Get Back to People

### Debugging Check

* Is the problem being reported a direct result of the underlying bug, or merely asymptom?
* Is the bug really in the framework you're using? Is it in the OS? Or is it in your code?
* If you explained this problem in detail to a coworker, what would you say?
* If the suspect code passes its unit tests, are the tests complete enough? What happens if you run the tests with *this* data?
* Do the conditions that caused this bug exist anywhere else in the system?

### Common Things To Put It Configuration Data
* Credentials for external services (database, third party APIs, and so on)
* Logging levels and destinations
* Port, IP address, machine, and cluster names the app uses
* Evironment-specific validation parameters
* Externally set parameters, such as tax rates
* Site-specific formatting details

### How To Program Deliberately

* Always be aware of what you are doing.
* Can you explain the code, in detail, to a more junior programmer? If not, perhaps you are relying on coincidences.
* Don't code in the dark. Build an application you don't fully grasp, or use a technology you don't understand, and you'll be likely be bitten by coincidences. If you're not sure why it works, you won't know why it fails.
* Proceed from a plan.
* Rely only on reliable things. Don't depend on assumptions. If you can't tell something is reliable, assume the worst.
* Document your assumptions. It can help clarify your assumptions in your own mind, as well as help communicate them to others.
* Don't just test your code, but test your assumptions as well. Don't guess, actually try it.
* Prioritize your effort. Spend time on the important aspects, more than likely, these are the hard parts.
* Don't be a slave to history. Don't let existing code dictate future code.

### Security Basic Principles

* Minimize Attack Surface Area
* Principle of Least Privilege
* Secure Defaults
* Encrypt Sensitive Data
* Maintain Security Updates

### Solving Hard Prolems
* Consider all possible solutions. Think about all constraints you have. Don’t throw anything away. Because all parts can be included in the solutions.
* Identify the most restrictive contraints first, and fit the remaining contraints within them.
* Stuck with the problems, take a break or do something else.
* Find someone to explain it to.



Content from The Pragmatic Programmer: Your journey to mastery, 20th Anniversary Edition, by Andrew Hunt and David Thomas. Visit [https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/](https://pragprog.com/titles/tpp20/the-pragmatic-programmer-20th-anniversary-edition/).
Copyright 2000 by Addison Wesley Longman, Inc.
