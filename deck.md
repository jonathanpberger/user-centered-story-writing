layout: true
class: middle

  <div class="my-header">
    <!-- <img src="images/logo_tiny.png" style="height: 30px;"/> -->
  </div>
  <div class="my-footer">
    <span class=left>2U Core Practices</span>
    <span class=right>Points, Estimation, & Velocity</span>
  </div>

---
class: center

# Hi! :-)

---

2U Core Practice Talks

# Points, Estimation, & Velocity

February 2016

---

subj: what are core practice talks?

# What are Core Practice Talks?

- a place to share best practices and context about agile concepts
- we'll repeat talks as necessary to keep room size conversational
- WIP / experimenting w format

---
.f1[What are Core Practice Talks? (cont.)]

- an opportunity to ask questions and deliberate
- let us know what you want to hear about
- success criteria: more debate, more and more ppl feel comfortable giving them

---

name: points

# I.Points

---

## What are points?

- predictive, not descriptive
- relative, arbitrary measure
- ... of difficulty
- ... of complexity
- ... of uncertainty
- ... of business value

---

## What points are *not*?

- measure of time
- for tracking performance
- meaningful in and of themselves

---

## Feature Stories (aka "Stories")

- pointed
- **"smallest amount of work that represents business value"**
- "should" in the title
- As a [USER], I want to [ACTION], because [MOTIVATION]
- pro tip: write AC in Gherkin ("Given", "when", "and", "then")

---

name: point-values

## Point Values

- **1:** “I understand exactly what needs to be done, and exactly how to do it."
- **2:** “I understand exactly what needs to be done, but I’m going to have to do some thinking or research to figure out how to do it.”
- **4:** “I mostly understand what needs to be done, and unless I’m way off base, I kind of understand how I would do it.”, i.e. Uncertainty
- **X:** “I’m not sure what needs to be done here at all, or if it’s even possible or desirable to do this at this time.” **Not Pointable. Break it down.**

???

- traditionally based on uncertainty & complexity
- evolved to this form to keep everyone honest
- encourages stories to be broken down to small common size
- differences in amount of work (e.g. for 1pt) shake out over time

---

## Bugs

- *un*pointed
- (because the points were already assigned and spent)
- should represent work the PM thought was already done / had already accepted
- "it's a bug if it was created here"

???

- what's a bug? A regression? Should we change the word in PT to 'regression', because that's the word everyone else uses.
- unpointed bugs affect velocity; that's good. We want to drive the conversation

---

## Chores

- *un*pointed
- "things the client doesn't know to ask for"
- something that has to be done and cannot be accepted by the PM
- "something we're gonna do whether the PM likes it or not"

???

- not things the client asked for
- we should make them care. "You can stick w/ this new version, but we'll move faster if we spend a few days upgrading rails"
- this all ties into tech debt: how to manage it, how to advise clients?
- refactoring can be a feature, it's not always a chore (eg refactoring on open-source)

---

name: estimation

# II. Estimation

???

what are we estimating?

- bness value?
- risk?
- complexity?
- uncertainty?
- effort?
- *not* time
-'complexity' == 'can we break it down?'

---

## What are we estimating?
- Effort: easy, medium, or hard
- Complexity: is the story small enough to estimate?
- it doesn't matter if they're accurate, they just need to be consistent
- estimates have expiration dates

???

- when vel is known, how do we dissociate the estimate from time? If vel is 10, a 3-point story ought to be a day-and-a-half
- over time, estimates get more experiential: "this looks like that other thing we did last week, and that was a 2-pointer."
- "risk" == "uncertainty"

---

## Who estimates?

- the people who'll do the work
- at *least* two engineers (sanity check)

---

## When do we estimate?

- at inception
- at backlog grooming / IPM
- ad hoc

---

## When is it ok to re-estimate a story?
- always (before you start the story)
- should you re-estimate after a story's done? **No.**
- if you estimate after you start, it's not an 'estimation'

---

name: velocity

# III. Velocity

---

## Velocity

- looking backward: what was the team's progress over time?
- looking forward: predictive. when will we get there? when can we release this?


???

- Intrinsically tied to est'n, a factor of team size and story size
- useful to see how the project changes over time
- have not seen velocity as a predictor of team productivity
- 2-pair teams can have 30 pt vel, 4 pair teams can have 12 pt vel
- "vel is a measure of bness value": true or false?

---

## Team Velocity <br/>is a Speedometer,<br/> not a Tachometer

---

**tachometer**: indicating the rotation speed of the engine of a car, i.e. _how hard your engine is working_.

vs.

**speedometer**: measures actual speed (aka velocity) of a vehicle, i.e. _how_ _fast (or slow) you are actually moving along_.

---

.f3[we care about]

**how quickly teams deliver business value** (speedometer)

.f3[more than we care about]

**how hard teams are working** (tachometer)

---

## SUSTAINABLE PACE

---

- indefinitely rising velocity != goal
- work at a _sustainable pace_
- commit to enough work to operate near maximum efficiency; no more, no less.


???

Let’s first consider effort, _how hard the team is working_. Modern agile teams are supposed to work at a _sustainable pace_. They commit to enough work to operate near maximum efficiency; no more, no less.

---

If you push an engine to its redline it will resist. When it hits maximum RPM, it will not go any further.

The engine says **no**.

---

If someone tries to force a modern agile team to do more work than they are capable of doing responsibly, they resist.

.f1[The team says **no**.]

???
- this is a change
- you are **responsible** for saying "no"

---

Metaphor:

a team’s sustainable pace ~= engine efficiency of a car’s engine.

---

background-image: url(https://en.wikipedia.org/wiki/File:Powerband.gif#/media/File:Powerband.gif)

## All engines have a _power band_


???
## [All engines have a _power band_](https://en.wikipedia.org/wiki/Power_band)

the range of operating speeds under which they are able to operate efficiently.

---

## Engineering teams have a power band too


???

- the range of work commitment that maximizes delivery of business value
- while allowing optimal time for automated testing, addressing technical debt (refactoring), learning, innovation, and maintenance of social cohesion.

---

Under-utilize == not enough work == waste $$$

--

Over-utilize == too much work == waste $$$ + break team

???

Underutilize a team by not giving them enough work and you’ll waste money. Over-utilize a team (redlining?) and you’ll also waste money, plus they’ll eventually break down and fail.

---

## TORQUE & HORSEPOWER

---

### team torque

.f2[the power to deliver effective & elegant solutions to difficult problems]

--

### team horsepower

.f2[an idealized measure of how quickly they deliver solutions]

???

The output of an engine can be measured in [torque](https://en.wikipedia.org/wiki/Torque) (power) and [horsepower](https://en.wikipedia.org/wiki/Horsepower) (rate of work). Engineering teams can be measured that way too. I like to think of _team torque_ as the power to deliver effective & elegant solutions to difficult problems and _team horsepower_ as an idealized measure of how quickly they deliver solutions.

---

### high torque and modest horsepower

.f2[can tackle difficult problems, just not very quickly]

--

### modest torque and high horsepower

.f2[can crank out software at a high rate, as long as the work is not difficult]

???

high torque and modest horsepower == tackle difficult problems (not very quickly).

modest torque and high horsepower == crank out software at a high rate (as long as the work is not difficult).


---
<!-- class: bottom center -->
<!-- background-image: url(http://cdn.emgn.com/wp-content/uploads/2014/03/The-Worst-Supercars-Of-All-Time-Lamborghini-Egoista.jpg) -->

### high torque && high horsepower

--

.f2[rare, expensive, high maintenance costs]

???

Teams with superbly high torque and horsepower, like the engines in supercars,
* rare,
* expensive,
* high maintenance costs.

That said, the natural output metrics of a team affect but do not guarantee, velocity. Why? For the same reason you wouldn’t take million-dollar supercar on an off-roading excursion or enter it in a tractor-pull.

---

## VELOCITY IS SUBJECT TO EXTERNAL FACTORS

--

* External factors matter (sometimes much more than team effort.)
* tachometer is a useful indicator of effort, BUT
* you cannot determine the speed of a vehicle based on the tachometer alone.

???
* You need a speedometer because velocity is always subject to _external factors_.

---

### External Factors in a car

- incline of the roadway
- [rolling resistance](https://en.wikipedia.org/wiki/Rolling_resistance)
- the effects of tail or head winds ([drag](https://en.wikipedia.org/wiki/Aerodynamic_drag))
- the weight of cargo being transported
- etc.

---

### External factors for an engineering team
- Technical debt
- the quality of the specifications
- tooling
- team morale
- etc.


???


---

### "SPRINT" VELOCITY

- behaves like a tachometer
- Scrum has you assign points to *everything* the team does
- that number affects how much work the team will **commit** to
- fancy ceremonial procedures like planning poker

???

- At best, that indicates how hard a Scrum team **plans to work**
- It does not reflect external factors affecting the team’s actual velocity,
- has nil long-term predictive power.

---

### The problem:

You cannot use Scrum’s sprint “velocity” to gain any predictive insight into when milestones will be reached beyond the end of the sprint.

???

Point estimation in Scrum is a _tachometer_. It’s a big part of why I think Scrum is full of _ceremonial bullshit._

---

### MODERN AGILE VELOCITY

- behaves like a speedometer
- estimation and velocity calculation reflect the rate at which business value is delivered
- team velocity truly does indicate speed
- can be used to predict arrival times for future milestones.

---

### WHEN VELOCITY DROPS

- is not prima facie bad
- is not a blamefest
- is an opportunity to talk about why velocity is dropping
- and to fix it

---

name: bloody-obvious

when there’s a problem with the team you want to it to be

.f1[bloody obvious to everyone involved]

that the problem is happening.

???

Since velocity is the primary metric for the team and the one metric that directly affects product manager’s ability to predict releases accurately, it serves nicely as the team’s primary diagnostic tool.

---

# recap: points

- Mercilessly **break down stories** into roughly equal units
- All user stories added to the backlog must be **estimated by a representative of the engineering team**
- **Only use 1, 2 and 4 point estimates** ([guidelines](https://medium.com/modern-agile/how-we-estimate-user-stories-f345fd384474#.wmy0te9m2))
- **Reject any user story that feels larger** than 4 Points
- Identify change **requests masquerading as bugs** — treat as user stories.
- **Do not ever assign points** to work spent on correcting “real bugs” (defects due to programmer error) or addressing technical debt.

---

# recap: estimation
- on complexity and uncertainty
- never based on time
- relates to business value

---

# recap: velocity

---


# Thanks!

---

# Questions?


???

# Scratch from article

## POINTS

In a car, we measure velocity with MPH (miles per hour)or KPH (same, but with kilometers). On a modern agile engineering team we measure _team velocity_ with _points per iteration (PPI?)_ or simply _points_. You might say that points are like miles or kilometers on the speedometer.

In [How we estimate user stories](https://medium.com/modern-agile/how-we-estimate-user-stories-f345fd384474#.ocu944r8d), I explained that only user stories that deliver business value get point estimates, in measures of 1, 2 or 4 points. Stories that are too large and/or undefined to estimate are rejected and refined. Everything else (refactoring, fixing defects and developer chores) is either accomplished in the context of a user story, or tracked individually with zero points.
