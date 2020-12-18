# PROGRAMMING GUIDELINES

### 7 STUDY TIPS

1. Prepare yourself to study. Make a plan.
2. Set study goals. Manage your time.
3. Take regular study breaks. Get enough rest.
4. Review the information periodically. Use memory techniques.
5. Switch between different topics. Learning only one thing is a great lost.
6. Practice more. Learn more.
7. Be positive. Hope for the best.

### 15 FACTS ABOUT PROGRAMMING

#### 1. Programming Isn’t Like Studying For a Test

```
Memorizing stuff doesn’t matter all that much.
```
#### 2. Cheating Is Completely Acceptable

```
I use Google to solve most of my problems, and so do most programmers.
```
#### 3. Don’t Let Problems in Your Code Pile up Endlessly without Checking If

#### It’s Actually Working

```
I used to make endless changes to my code and expect it to work right away. The problem
with this approach is that it stacks one problem on top of another, and it becomes difficult
to figure what went wrong.
```
# PROGRAMMING

# GUIDELINES


#### 4. Don’t Get Too Emotional Early On In the Programming Journey

You’re going to see error messages on your journey to becoming a programmer. When
screwing up is such an integral part of the process, you need to be ok with making mistakes
in order to grow.

#### 5. Think You Need 5 Different Monitors to Learn To Code

Contrary to what Hollywood might tell you, you don’t need an insane external monitor
setup to be a programmer. The computer that you own right now is probably good enough
to use to start programming. Don’t waste your money.

#### 6. Trying to Understand Something before Moving On To the Next Thing

#### Is a Lost Cause

In the beginning, I tried to chase down the “why” to every problem I encountered. This isn’t
necessary. Computers are so complex and there is so much to learn, and you’re never going
to understand everything.

#### 7. Changing Bad Code Is Part of the Process

I used to think that every piece of code I wrote needed to be perfect. But making
improvements to your code is normal. You’re not writing a book that can’t be changed once
it’s published.

#### 8. Always Celebrate the Small Wins

Building stuff with code is really cool. I never would have arrived where I’m at if I hadn’t
stepped back and admired the awesome things I was building along the way.

#### 9. It’s Ok to Admit What You Don’t Know

When you land your first programming job, you might be inclined to “fake it till you make
it.” Don’t. Nobody expects you to know everything right away.

#### 10. Programming Is About Using The Right Tool For The Job.

There are so many different open source libraries, tools, and frameworks at your disposal.
So you need to grow your developer toolkit and understand which tool makes sense for
each problem that they encounter.

#### 11. Make the Computer Think Like a Human


Too many people have the impression that you need to think like a computer. It’s actually
the opposite.

#### 12. Programmers Never Stop Learning

New technologies come out all the time, so the programmers that succeed are the ones
who continue to learn and develop their craft on an ongoing basis.

#### 13. You’re Never Going to Feel like You’re Ready to Program Full Time

Imposter syndrome is real. Try to remember that it’s normal to not know everything. The
most important thing is understanding that you can figure out the stuff that you don’t
know.

#### 14. Overlooking the Difference between a Capital Letter and a

#### Lowercase Letter

In programming, the details matter. Even small details- like the difference between a capital
and lowercase letter. It’s important to get used to noticing subtle differences between
similar symbols.

#### 15. Endlessly Research Technologies without Spending Time Actually

#### Writing Code

The fact is: you can’t learn to code by reading about it. The only way to learn is by actually
coding. Don’t worry about learning the wrong thing. Any language that you pick will at least
help you learn the concepts central to programming. Skills like naming variables, defining
functions and breaking down complex problems apply to all programming languages. So it’s
not a big deal where you start.

Once you master one language, picking up a second language is much easier. So don’t let an
analysis paralysis prevent you from ever starting.


## 10 BASIC PROGRAMMING PRINCIPLES

#### What Makes A Good Programmer?

Anyone can write code. But good code? That’s where it gets tough. Don’t settle for writing
code that works. Aim to write code that can be maintained - not only by yourself, but by
anyone else who may end up working on the software at some point in the future. To that
end, here are several principles to help you clean up your act.

#### 1. KISS “Keep It Simple, Stupid”

The **“keep it simple, stupid”** principle applies to pretty much all of life, but it’s especially
necessary in medium-to-large programming projects.

It starts way in the beginning when you’re defining the scope of what you want to create.
Just because you’re passionate about game development doesn’t mean you can create the
next World of Warcraft or Grand Theft Auto. When you think you’ve simplified enough,
simplify it one level further - feature creep is inevitable, so start small.

But even after coding has begun, keep it simple. Complex code takes longer to design and
write, is more prone to bugs and errors, and is harder to modify later down the road. In the
wise words of Antoine de Saint-Exupery, **“Perfection is achieved, not when there is
nothing more to add, but when there is nothing left to take away.”**

#### 2. DRY “Don’t Repeat Yourself”

The **“don’t repeat yourself”** principle is crucial for clean and easy-to-modify code. When
writing code, you want to avoid duplication of data and duplication of logic. If you notice
the same chunk of code being written over and over again, you’re breaking this principle.

The opposite of DRY code is WET code: **“write everything twice” (or “waste everyone’s
time”).** One of the best ways to diagnose WET code is to ask yourself: in order to alter the
program’s behavior in some way, how many areas of code would you need to modify?

Suppose you’re writing a podcast directory app. On the search page, you have code for
fetching a podcast’s details. On the podcast page, you have code to fetch that podcast’s
details. On the favorite page, the same fetching code. Consider abstracting all of that into a
function so that if you need to edit it later, you can do it all in one spot.

#### 3. Open/Closed “Open To Extension But Closed To Modification.”


Whether you’re writing objects in Java or modules in Python, you should aim to make your
code **“open to extension but closed to modification.”** This applies to all kinds of projects,
but is especially important when releasing a library or framework meant for others to use.

For example, suppose you’re maintaining a GUI framework. You could release it as-is,
expecting end users to directly modify and integrate your released code. But what happens
when you release a major update four months later? How do they implement all of your
additions without throwing away of the work they’ve done?

Instead, **“release code that prevents direct modification and encourages extension.”** This
separates core behavior from modified behavior. The benefits? Greater stability (users can’t
accidentally break core behavior) and greater maintainability (users only worry about
extended code). The open/closed principle is key to making a good API.

#### 4. Composition over Inheritance

The **“composition over inheritance”** principle states that objects with complex behaviors
should do so by containing instances of objects with individual behaviors rather than
inheriting a class and adding new behaviors.

Overreliance on inheritance can lead to two major issues. First, the inheritance hierarchy
can become messy in the blink of an eye. Second, you have less flexibility for defining
special-case behaviors, particularly when you want to implement behavior from one
inheritance branch in another inheritance branch:

Composition is a lot cleaner to write, easier to maintain, and allows for near-infinite
flexibility as far as what kinds of behaviors you can define. Each individual behavior is its
own class, and you create complex behaviors by combining individual behaviors.

#### 5. Single Responsibility

The single responsibility principle says that every class or module in a program should only
concern itself with providing one bit of specific functionality. As Robert C. Martin puts it, **“A
class should have only one reason to change.”**

Classes and modules often start off this way, but as you add features and new behaviors,
it’s easy for them to evolve into God classes and God modules that take up hundreds, or
even thousands, of lines of code. At this point, you should break them up into smaller
classes and modules.

#### 6. Separation of Concerns


The separation of concerns principle is like the single responsibility principle but on a more
abstract level. In essence, a program should be designed so that it has many different non-
overlapping encapsulations, and these encapsulations shouldn’t know about each other.

A well-known example of this is the model-view-controller (MVC) paradigm, which
separates a program into three distinct areas: the data **(“model”)** , the logic **(“controller”)** ,
and what the end user sees **(“view”)**. Variations of MVC are common in today’s most
popular web frameworks.

For example, the code that handles the loading and saving of data to a database doesn’t
need to know how to render that data on the web. The rendering code may take input from
the end user, but then passes that input to the logic code for processing. Each part handles
itself.

This results in modular code, which makes maintenance much easier. And in the future, if
you ever need to rewrite all of the rendering code, you can do so without worrying about
how the data gets saved or the logic gets processed.

#### 7. YAGNI “You Aren’t Gonna Need It”

The **“you aren’t gonna need it”** principle is the idea that you should never code for
functionality that you may need in the future. Chances are, you won’t need it and it will be
a waste of time - and not only that, but it will needlessly increase your code’s complexity.

You could view this as a specific application of the KISS principle and a response to those
who take the DRY principle too seriously. Often inexperienced programmers try to write the
most abstract and generic code possible to avoid WET code, but too much abstraction ends
up in bloated impossible-to-maintain code.

The trick is to apply the DRY principle only when you need to. If you notice chunks of code
being written over and over, then abstract them - but never when you think a piece of code
will be written over and over. More times than not, it won’t be.

#### 8. Avoid Premature Optimization

The no premature optimization principle is similar to the YAGNI principle. The difference is
that YAGNI addresses the tendency to implement behaviors before they’re necessary while
this principle addresses the tendency to speed up algorithms before its necessary.

The problem with premature optimization is that you can never really know where a
program’s bottlenecks will be until after the fact. You can guess, of course, and sometimes
you may even be right. But more often than not, you’ll waste valuable time trying to speed
up a function that isn’t as slow as you think or doesn’t get called as often as you’d expect.


Reach your milestones as simply as you can, then profile your code to identify true
bottlenecks.

#### 9. Refactor, Refactor, Refactor

One of the hardest truths to accept as an inexperienced programmer is that code rarely
comes out right the first time. It may feel right when you implement that shiny new feature,
but as your program grows in complexity, future features may be hindered by how you
wrote that early one.

Codebases are constantly evolving. It’s completely normal to revisit, rewrite, or even
redesign entire chunks of code - and not just normal, but healthy to do so. You know more
about your project’s needs now than when you did at the start, and you should regularly
use this newly gained knowledge to refactor old code.

Note that it doesn’t always have to be a big process. Take a page from the Boy Scouts of
America, who live by these words: **“Leave the campground cleaner than you found it.”** If
you ever need to check or modify old code, always clean it up and leave it in a better state.

#### 10. Clean Code over Clever Code

Speaking of clean code, leave your ego at the door and forget about writing clever code.
You know what I’m talking about: the kind of code that looks more like a riddle than a
solution and exists solely to show off how smart you are. The truth is, nobody really cares.

One example of clever code is packing as much logic into one line as possible. Another
example is exploiting a language’s intricacies to write strange but functional statements.
Anything that might cause someone to say **“Wait, what?”** when poring over your code.

Good programmers and readable code go hand in hand. Leave comments when necessary.
Adhere to style guides, whether dictated by a language (like Python) or a company (like
Google). Observe per-language idioms and stop writing Java code in Python or vice versa.
See our article on tips for writing cleaner code.


## DESIGN PATTERNS

#### What are Design patterns?

Design patterns are solutions to software design problems you find again and again in real-
world application development. Patterns are about reusable designs and interactions of
objects.

The 23 Gang of Four (GoF) patterns are generally considered the foundation for all other
patterns. They are categorized in three groups: Creational, Structural, and Behavioral (for a
complete list see below). Get to know more about design patterns online.


