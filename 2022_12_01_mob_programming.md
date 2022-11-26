

# A familiar picture of a software team

# A typical day
Teams does sprint planning, everyone gets "their" Stories, Bugs, Tasks.
The sprint starts and everyone gets back to their corner, they can finally
work on their committed piece of the spring ALONE.

Here is a bright young man Taavi, who has just made a bugfix. Our team is
very progressive and doesn't trust its own members - every commit to the mainline
goes through a code review.

Taavi tags me and other team members for the review.
I know that reviews are better done sooner than later, so I pull myself out
of my current context and start reviewing the code.
First, I try to understand what exactly caused the bug and how the changes
fix it. The bug is non-trivial and is related to a domain area not know to me.
I spend half an hour just to get deeper into the problem.
Finally I understand how the code caused the bug and how Taavi's code fixes it.
But I don't quite agree with implementation and leave some comments and questions.

Taavi has already started working on another issue. So when my comments arrive,
his mind is already in another context, he has to "switch" it back, recall
everything previously done, answer me and even update the code according to the
comments. Then the cycle repeats.

Some teams won't agree with this narrative. Some teams have a rule that when
a review comes, everyone drops whatever they are doing and review the code
together. That's somewhat a step forward, until it's not. Everyone has to
be pulled of their current contexts. Everyone comments on a ready work and
then gets back to their silos, waiting for the author to fix them.
And what if the changes are BIG? What if there are some hundreds lines of code
and some reviewers don't agree with any of it? Shall everything be re-written?
Does this sound familiar?

I believe you see how flawed this whole thing is. It consists of ridiculous
amounts of delayed communication and feedback, in other words - the feedback loops
are horribly long and the feedback is never there when you need it most.
When do we need that feedback? We need it *before*, *during* and *right after*
we put our thoughts in code.

What if your team mate is always there to provide that feedback?
Together you study the issue *before* - so you get the understanding faster
and catch more subtle details. Together you discuss and prototype the implementation
*before*, so that you both agree on the general approach.
You continue discussing *during* the implementation, and every line of code gets
its immediate feedback. You once again review the changeset before committing
and finally you push it  - to the **mainline**, since you formally had an
"extra pair of eyes" watching every step.

That's а fellow developer on your shoulder. How about getting more people involved?
It's not just "an extra pair of eyes" then - it's a hive mind backing you up.
And they are not just developers, but also QA, PO, even your Scrum master!
At this point, it's not just you, but the whole *mob* of your teammates working
on your JIRA ticket. So, why even assign the tickets to individuals in the first place,
when you can collaborate on every issue and solve them together?

We call this collaborative programming sessions - "Mob programming" or simply
"mobbing".
I've been doing mob programming for almost four years now. For me, mobbing is
light years ahead of work done in silos.


## Collaboration

There are many ways to have a mobbing session, but they also have some common rules.
First, there are roles: the **navigators** and the driver. The job of the
**navigators** to help the driver

The essential parts are that
at any given time, there is only a single person, called a **driver**, who
writes the code


On a typical mobbing day, team members gather closer in dedicated space -
real or virtual and


## Mobbing

"A mob" is usually something wild and uncontrollable. Nevertheless, mobbing
has some necessary key elements which make it effective.




You get a feeling, that you are the **driver** steering the editor wheel,
and **navigators** help you to find the road.

There is a catch though. People would soon get bored to watch you driving and
you'll get tired too!
So it's essential that you switch the **driver** seat often.
How often? If a mob of three changes the **driver** seat once in ten minutes,
it means that every one would get to the keyboard only once in half an hour!

Let's call this group of people a *Mob*.
A *mob* - is not necessarily the whole team, People join and leave when
needed, but in the end the work is done by a *mob* of professionals.



When you start doing At this point you're already doing software development not as individual, but
as a ? What if you stop spreading the backlog to individuals
and start working on ALL issues together.

We call that "Mob programming".
This group of people is not constant in spacetime - they join when possible
and leave when they need.



A mob is not something constant, it is fluid,
with people joining and leaving as they wish. A


# A story of a software engineer

* Meets her team
* Gets onboarded
* Sets up her working environment
* And gets her first task
