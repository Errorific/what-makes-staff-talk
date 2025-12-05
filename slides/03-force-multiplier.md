---
layout: section
---

# The Force Multiplier in Action

## Behaviors and Archetypes

<!--
I've brought up a bit that being a force multiplier is important for a staff engineer. Lets take a closer look at ways you can do that.
-->

---

# Staff Engineer Archetypes

Based on Will Larson's "Staff Engineer" book

<table>
<thead>
<tr><th>Archetype</th><th>Focus</th></tr>
</thead>
<tbody>
<tr><td><strong>Tech Lead</strong></td><td>Technical direction for a team/product</td></tr>
<tr><td><strong>Architect</strong></td><td>Org-wide architecture and standards</td></tr>
<tr><td><strong>Solver</strong></td><td>Parachutes into critical problems</td></tr>
<tr><td><strong>Right Hand</strong></td><td>Extends reach of executive leadership</td></tr>
<tr v-click><td><strong>Socialite</strong></td><td>Bridges teams, facilitates collaboration</td></tr>
<tr v-click><td><strong>Expert</strong></td><td>Deep specialist in critical domain</td></tr>
</tbody>
</table>

<!--
There's a book by Will Larson about staff engineering that surfaces 4 archetypes categorising how staff engineers show up. I'm not going to go into much depth on these, but the books well worth reading if you want more details.

First you've got the tech lead. They understand how to plan complicated projects, organise resourcing requirements, verify technical pathways, and manage stakeholders and adjacent technical boundaries.
Second is the Architect. They take a wider focus of how to uplift the engineering standards and tooling available to the organisation. When you start seeing proposals to convert old tech stacks to microservices or some similarly outrageous idea, thats the architect.
Third there's the solver. You start having emergent performance issues from your central data stores, or you need to meet emergent security requirements for a big new deal, the Solver is who jumps on that grenade and makes the problem go away.
Forth is the right hand. This archetype extends the radius of a director or executive that they're attached to, borrowing their authority to solve complex organisational issues. This might be assisting with re-organisation and hiring plans, reviewing budgeting concerns, or any number of issues where technical insight can improve outcomes. This archetype typically jumps from problem to problem, making calls and delegating where appropriate, and moving on quickly.

There's 2 other types that I want to mention here that I see too often and are signs of disfunction.
~Click here~
First of these is the socialite. This type of engineer talks to everyone, but contributes little. They're catchline is "that sounds like something X is interest in, you should go have a chat to them". When you've got silo'ing problems or bad communication in the company, this archetype can still be useful to encourage connections that would otherwise get missed and surface work that would have stayed hidden, but in a healthy organisation they underperform.
~Click here~
The last is the expert. We've all got that system which is a crime against god and we wish we could delete, but there's always someone who's been at the company 10 years who knows it inside out and is the only person who can get any work done in it. Inside that system they're essential, but outside of it they barely move the needle. They typically end up getting promoted to staff because they're perceived as a 10x engineer because they can do what other engineers say is impossible in that system, or because they're identified as an existential flight risk from the company, but if your company is healthily managing its tech debt then this archetype shouldn't exist.
-->

---

# A Note on Archetypes

**On the journey to Staff**: You typically embody ONE archetype. This is often your path to promotion.

**Once you're Staff**: You flex between archetypes depending on organizational needs.

The role is fluid, not rigid. Most Staff engineers blend multiple archetypes over time.

<!--
These archetypes make it easier to frame how you can contribute, but don't feel wedded to a particular hat. You'll likely flex between different types of impact as organisational needs evolve around you and new challenges are presented.

That said, if you're trying to become staff, pick one and focus on it. Make that how you prove yourself.
-->

---
layout: section
---

# Finding the Right Leverage Points

<!--
Next topic, it's on you to figure out how to maximise your impact, how do you find those high value problems.
-->

---

# Proactive Investigation & Discovery

- Seeks out challenges instead of waiting for assignments
- Investigates problems deeply before proposing solutions
- Surfaces issues and risks early, even when uncomfortable
- Asks "why" repeatedly to understand root causes

*Archetypes in action: The Solver identifies bottlenecks, The Right Hand surfaces strategic problems*

<!--
Go and get networking is a good starting point. Talk to people all across the org. Let people tell you about their week and vent about the hard parts. You'll be very surprised how often these little gripes end up pointing towards serious problems that deserve your attention. Patterns emerge where 3 or 4 engineers all point at their project plans being changed and they don't understand what the stakeholder wants, or there's repeated complaints about certain codebases. People complain that they can't get their code merged. These are all signs that point at broken processes and technical misalignment and are worth you digging into. 
Keep asking why these things are going wrong to find where they're coming from, and when you do, start raising them with leadership. Sometimes this gets uncomfortable because often enough the problems are from something leadership established and you're now telling them they were wrong, but if you leave these issues be, they fester, velocity drops, tech debt gets worse, engineers get fed up, and then they leave.

A word of caution. When doing this kind of hunting, make sure you've investigated thoroughly, proven the problems exist, and have an understanding of the space before communicating it upwards. If you bring everything to the desk of leadership they're going to become numb to your reports, especially if it keeps on turning out that the problem wasn't what you thought or wasn't very serious. You need to filter and find the gems.
-->

---

# Strategic Pragmatism

- Focuses energy on highest-impact problems, says no to low-value work
- Ships "good enough" when appropriate, perfects when it matters
- Makes trade-offs explicit and connects to business impact
- Knows when to accumulate technical debt vs. pay it down

*Archetypes in action: The Architect prioritizes platform work, The Tech Lead balances velocity with quality*

<!--
Once you find the valuable problems, you need to make the appropriate investment. Some things only need a light touch to correct. Bad MR reviews might be resolved by a brown bag lunch talk about the importance of code style. Equally so it might be a sign that your engineers are committing AI slop or not testing their code at all and you need to start reviewing everything that team produces for awhile.

There's also times when the investment isn't going to align with business priorities. There might be a codebase that is constantly an issue for engineers working on it, but from your vantage point you're aware that profitability of that product line has been waning, it's likely to be dropped from the offering within 24 months, and the company isn't going to see a return on any investment to address its faults. You need to find quicker wins that can make the system more approachable, or reduce the expectations placed on engineers working in that space.
Making these sorts of judgements can be a case study all by itself.
-->

---

# Navigating Complexity

- Understands how decisions really get made in the organization
- Knows who needs to be involved and when
- Reads the room and adapts communication style
- Escalates appropriately - knows when to raise issues and to whom
- Seeks feedback actively and acts on it
- Learns from failures and shares those lessons

*Archetypes in action: The Right Hand navigates executive priorities, The Architect builds relationships across teams to drive adoption*

<!--
And then you need to navigate the organisation itself.

As much as we might think business is cold and ruthless, there's humans and egos behind every decision. Get familiar with who has the ear of your stake holders. Learn what a declaration means from your execs, what does it sound like when they draw a line in the sand. Be aware of what concerns all the movers and shakers in your business has.

Your VP of product has been fielding evening calls from enterprise customers about errors in the system, start selling your proposals framed to improve reliability. Teams and managers feeling a lack of SRE support, your technical changes improve team autonomy and simplify system management. The problems you're discovering will already align with their pain points, otherwise they wouldn't be organisation level problems, but it's still on you to frame them and get buy-in.

Learn the history of the people you will be involved with. Was there a 3 year investment into a greenfields rewrite that didn't pay off? That's some PTSD that people will hold onto and you need to try not to trigger. You've got a director who has previously seen great success from adopting off the shelf solutions, don't fight them on it, make sure you include those options alongside the tailored home grown solutions so they can make the comparison. Just being right isn't usually enough.

And then there's how decisions get made. Be aware of the escalation processes and tools available to you. Know whether for your environment if you leave something open for feedback it would invite bikeshedding and whether it's better to apply time pressure to force a decision. Are there key powerbrokers in your org that once you get them onboard everyone else falls into place? The environment will be dynamic but you will be able to influence it and take advantage of it if you understand it.

This is also where you start to find out whether there will be buyin for you to solve the issue. An unfortunate truth is your hit rate is much lower as a staff than at lower roles. I'm lucky if 50% of the problems I start investigating actually end up getting resolved. Sometimes it's discovering the problem wasn't as serious, or at least no one who can support you can be convinced it's serious. Sometimes it's that the opinions of leadership are opposed to the change. If you just can't get alignment for an emergent problem, and you know it's not a huge threat to the business, have the grace to drop it and move on. Half the time you see these problems re-raised under a different banner 12 months later and you can join the party then.
-->

---
layout: section
---

# Executing with Impact

<!--
Anyway, Now you've got your problem, you've managed to find alignment on a solution, you just need to stick the landing. You're still just one person, and a time starved one at that. If you're going to work on this you need to make the changes stick.
-->

---

# Ownership & Accountability

- Takes responsibility for seeing problems through, even across team boundaries
- Owns outcomes, not just individual contributions
- Steps up when something is broken, rather than waiting for assignment
- Takes the blame when things go wrong, gives credit when things go right

*Archetypes in action: The Solver owns the fix end-to-end, The Tech Lead owns team outcomes*

<!--
You have to build a reputation as someone who can be trusted to see things through. Good or bad, your name stays on it. When you get blocked you make the effort to work through the issues. Your reputation needs to be that things that are your problems are as good as solved. If leadership or engineers start worrying about your followthrough then you become a liability and they won't want to get behind your efforts as readily. But if you manage to show that everything you touch turns to gold, people like getting on the winning team.
-->

---

# Leading by Example

- Models the behaviors and standards they want to see in others
- Admits mistakes publicly and shares what they learned
- Does the unglamorous work without being asked
- Stays hands-on, never becoming "too senior to code"

*Archetypes in action: The Tech Lead sets code quality standards, The Architect demonstrates technical craftsmanship through reference implementations*

<!--
Working on such visible problems, you need to exemplify what you want to see in the rest of the business. You set the coding standards, you do the campground improvements on the way through, you engage stakeholders transparently and in the open.
You're spending time mentoring engineers and they're going to want to be like you, so make that a good example.
You can't just get stuck when you realise your plan requires an infrastructure migration. Show off how to engage with your SRE team and how much a single engineer can achieve without assistance.
-->

---

# When Direction Changes

- Business priorities shift, new information emerges, assumptions get invalidated
- Know when to pivot, scale back, or abandon work you've invested in
- Sunk cost fallacy is real - cutting losses is sometimes the right call
- Your job is to deliver the best outcome for the business, not to finish what you started

*Archetypes in action: The Right Hand adapts to shifting executive priorities, The Solver pivots between problems as urgency shifts*

<!--
And you need to be ready for the ground to shift beneath you mid-implementation.
You're halfway through a technical initiative and then a competitor launches something that changes the business priority. Or you discover that your assumptions about a system were wrong and the approach won't work. Or the team you were depending on gets pulled onto an incident.
The sunk cost fallacy hits hard here - you've invested weeks or months, you've built consensus, you've got momentum. But if the circumstances have changed, pushing through to "finish" something that no longer serves the business is ego, not leadership.
Your job is to deliver the best outcome given current reality, not to complete what you planned when reality was different. Sometimes that means pivoting the approach, sometimes scaling back scope, sometimes walking away entirely and calling it a learning experience.
-->

---
layout: section
---

# Lifting Those Around You

<!--
And then there's the impact on the people around you. There's only so far you can drag the work forward with your own efforts, at some point you need to delegate and bring engineers and managers on the journey with you, and if you can make them more effective, the project will be completed faster, and the outcomes will be of higher quality.
-->

---

# Building Consensus & Influence

- Understands stakeholder needs before proposing solutions
- Builds relationships before needing them
- Documents reasoning and trade-offs transparently
- Disagrees constructively, commits fully once decided
- Brings people along rather than pushing solutions through

*Archetypes in action: The Right Hand builds bridges across leadership, The Architect gains buy-in for standards*

<!--
You can't help others be more effective if they don't trust you or understand your reasoning. Consensus-building is foundational helping people perform better and cut through red tape. 
Rely on the network you've been building. You should already know the painpoints that people are concerned with throughout the company, you should be aware of what the focus of various stakeholders is for the current quarter.
When you start on a project with people, they should already know you, if not from having met you before at least from your reputation. You're not going to have time to understand their world before jumping into a solution.
You also can't turn up and start dictating whats going to happen. First of all people don't like that and don't fully invest if they can't feel involved. Secondly if you dictate the pathway, you stand a risk of being saddled with the maintenance of this project forever. You need to set up the other engineers and managers to carry forward the project in your absence because you're not going to have the availability to be the caretaker of a service forever.
Encourage everyone else to propose solutions. Learn to use leading questions to highlight problems and encourage plans to develop in a productive direction. Be ready to candidly and constructively disagree with your peers to bring forward the best outcomes. And don't let perfect get in the way. That a solution isn't the way you'd build it is not a reason to change it. If what someones proposed will work and there's no material problems with it, no pathway it will impose on future plans, let that solution ride and those engineers own it. If you can let them come up with it, then you don't have to build consensus, they already agree it's the right way forward and they will be more committed to long term ownership of the feature.
-->

---

# Making Others Effective

- Makes themselves available to unblock others
- Creates clarity from ambiguity for team and peers
- Shares knowledge by working in plain sight and through documentation, not just 1:1s
- Gives actionable feedback that helps people grow

*Archetypes in action: The Tech Lead unblocks team members, The Architect shares system-wide context, The Solver connects teams facing similar problems*

<!--
With people onboard, you can then take actions that let them accelerate.
Look for behaviours that are slowing people down. I've seen engineers get stuck for a week trying to figure out what the intent of a feature is and that can be solved in half an hour if you get them in front of the right stakeholder. Solutions getting some bikeshedding, force a decision. Emergent dependencies on adjacent systems, use your access to tap the owners of that system and see if you can plot a way forward with them. Your experience through so many projects means that you've seen and survived all of these issues, you've made these mistakes and hopefully reflected on how you would do it differently next time. Bring that experience to bear and make it happen differently this time.
Make sure you do this in plain sight. The lessons you learned by making mistakes, you're robbing other engineers of that same learning experience. It's important that everyone understands whats going wrong and how the problem is going to be circumvented. Ideally the people you're working with don't let themselves get into the same situation next time and you leave a legacy of better engineers behind you.

Any time you are intervening, the feedback you provide needs to be actionable. Just saying a solution isn't good enough or there's a gap doesn't bring people on the journey. You need to frame it as what technical issue is being ignored, or what failure will emerge as the project proceeds. If you've got suggestions about next steps to take, even better.
-->

---

# Putting It Together

Staff engineers multiply impact through three stages:

1. **Finding the Right Leverage Points** - Where will effort have the most impact?

2. **Executing with Impact** - Setting patterns and creating lasting value

3. **Lifting Those Around You** - Bringing others with you on the journey

<!--
Pulling all that together now, you multiply the effectiveness of your engineering org by finding places where your help will have the most impact, making sure your efforts make a tangible difference in that space, and making your peers part of the solution so they learn from your work. Keep repeating this and you end up with a better skilled engineering org that is better prepared to take on new challenges.
-->

---

# What Breaks the Multiplier Effect

Anti-patterns that block Staff-level impact:

- **Lone wolf / Hero complex**: Taking on everything yourself instead of multiplying others

- **Working in the weeds**: Stuck in implementation details instead of force multiplier activities

- **Waiting for perfect information**: Paralyzed by ambiguity instead of moving forward

- **Avoiding conflict**: Not speaking up when you see problems

<!--
There's plenty of anti-patterns that can sabotage your efforts, watch out for them.
Some that I've seen recently in myself and staff engineers I work with:
- It's real tempting to just build it all yourself or at least fill all the resourcing gaps. You can't. The mythical man month is still a myth and you need to rely on other engineers to complete work.
- The weeds are real and chasing the perfect solution leads to nothing getting done. Getting a solution thats good enough underway and making everyone around you aware of the potential issues and shortcomings it has means there can be future improvements and those can happen without your attention.
- Likewise you'll never have the whole picture. Figure out what you know and what you don't know, what decisions have lasting impact, and what can be rolled back. If there's a pathway forward that aligns with what you know today, take it.
- And then there's ignoring issues because it leads to uncomfortable conversations. Whether they're technical or social, you need to get in front of these and encourage changes to resolve them. You can't just decide these don't involve you, or trust that someone else will take care of them. You're a leader and you need to help fix problems even if talking to people makes you want to run away. There comes a day when you need to give hard feedback to an exec and avoiding it will just make it worse.
-->
