---
layout: section
---

# How Staff Engineers Work Differently

<!--
So those differences now being surfaced, how does this end up reflecting in what a staff engineer is doing day after day.
-->

---

# Technical Work

- Time spent coding is **highly variable** (70%, 30%, or less depending on needs)
- Stay hands-on and technically sharp - never become "too senior to code"
- When they code: Setting patterns, proving concepts, unblocking critical paths
- More time on: Architecture, design reviews, technical debt strategy
- Less time on: Bugs, features, day-to-day tickets, individual code reviews, hands-on debugging

<!--
Don't let anyone tell you Staff engineers don't code. We do.
It's highly variable, I do have weeks where I don't touch any code, and others where it can be 70% coding. Most weeks it's sub 50%. 
What has changed is why I code. I keep saying staff shouldn't focus on features and that holds true. I'm typically digging into architectural issues or improvements, bugs that jump across organizational or knowledge boundaries, or just experimenting.
The rest of the time that I used to spend coding, I now keep up with 5 teams worth of projects and roadbumps, try to at least be aware of the headlines in another 4, and keep up with any larger technical decisions being made across the entire build org.
Feedback for technical proposals in particular ends up taking a lot of time, I end up needing to research systems that span multiple product and company areas and quickly develop deep understanding of how they work. Being able to surface gaps in those proposals and pick viable pathways out of what has been proposed is often the difference between the company successfully delivering customer value or generating troubling levels of technical debt that will haunt us for years to come.
-->

---

# Time & Attention

- Meeting load goes up **substantially**
- Interrupt-driven work increases - pulled into emerging situations and planning
- More context switching between teams and problem domains
- Must actively manage your time - deep work requires deliberate protection from constant interruptions
- Exercise judgment on where your time creates most value - not every meeting or request needs your presence

<!--
This difference in time allocation is something that you will feel. Your calendar doesn't quite end up looking like a managers with back to back meetings all day, but you are going to have significantly more face time with people up and down the org tree.
You're going to be doing 1:1s, tee-ups with management, early shaping with product managers. And thats just the stuff that gets scheduled.
Multiple times a week there will be requests that come out of nowhere that need immediate attention. It could be a critical decision that a manager needs input on, engineers that are stuck and need advice on how to move forward, critical bugs that need expert oversight. 
With how much wider your radius of impact is now you will find yourself having to switch between projects multiple times a day and the whiplash gets fatiguing.
All these demands on your attention means you need to be deliberate about what you get involved in and defend your time if you plan to be able to afford any project the amount of time and energy it deserves. Get used to telling people no and figure out how to exit a project because no one is there to do it for you any more.
-->

---

# Focus Areas

What Staff engineers work on:

- Identify and tackle **ambiguous, organizationally important** problems
- Create clarity from complexity
- Raise the technical bar (code quality, testing, architecture patterns)
- Build systems that scale - technical AND organizational
- Mentor and develop engineers - building better engineers is a key objective

<!--
When looking for where to invest your time, the key word is "organizationally important." You're not just solving hard technical problems - you're solving problems that matter to the business.
If your work isn't lifting the quality of engineering, improving the engineers around you, or smoothing the pathway forward for everyone else, then you're probably working on the wrong thing. Even if what you're doing does tick all the right boxes, you're always going to have multiple opportunities in front of you and you need to figure out which is going to have the biggest impact at the right time.

For all these opportunities, always ask can someone else do this instead. If you've identified an opportunity and you think there's a senior you can help guide through it instead of doing it yourself, thats a double win. High impact work and an opportunity to mentor growth in someone.
-->

---

# Examples of Org-Level Problems

- Migration strategy for a deprecated platform affecting multiple teams

- Performance bottlenecks impacting customer experience across products

- Technical architecture decisions that will impact hiring and team structure

<!--
You need to look for the kinds of problems where no single team owns the solution and multiple teams will benefit. Someone needs to step up and drive it - that's often the Staff engineer.

You've seen 3 patterns for auth across different teams and they're all repeating the same mistakes, time to try and get that to a single right way and make it easy for others to adopt moving forward. Just be careful not to create the 4th pattern.

Customer reports are your primary method of bug discovery? You're finding every error after it's been causing 2 months of problems for users? Time to establish some better observability practices and bug triage processes. Work with directors to better budget resourcing for bug fixing and prevention and then work with team managers to establish processes that get the right problems prioritised.

Team thats been loaded up 150% for the past 12 months and haven't been able to dig themselves out, time for you to apply some outside perspective before they all quit. Go digging through their workload, what their planning looks like, where the work requests are coming from. Is it a resourcing problem or a workstream problem? Are they stuck at a critical crossroads of your infrastructure so get drawn into problems by many teams? Has their product manager been saying yes to every request and the engineering manager not intervening to defend the teams time? You're positioned to discover all of that, advise the managers and directors of what needs to change, and help guide that team out of the trenches.

The impact from any of these can exceed your yearly salary, and you'll have a number of these across your desk each year.
-->

---

# Investing in Engineers

- Active mentorship of engineers across the organization
- Growing talent in technical skills AND organizational navigation
- Creating learning opportunities and knowledge sharing
- Building the next generation of technical leaders

<!--
Even with that sort of impact, to make your changes stick you need to develop the other engineers around you. Help them through their problems and teach them how to recognise good solutions and what you think about when you think about a problem.

Something that I've learnt over the last few years is the difference between coaching and mentoring. 
Coaching is structured and performance-focused, where a coach uses techniques and questions to help you develop specific skills or achieve particular goals, they won't necessarily be an expert in your field, and more often than not they aren't.
Mentoring is a longer-term relationship where someone with relevant experience shares their wisdom and guidance to help you navigate your broader career or personal development. 

Coaches help you get better at doing something specific, while mentors help you figure out what to do and who to become based on their own journey.

It's been my experience that good mentors are far rarer than coaches, and with the skills and experience you bring to the table as staff, and the specialised awareness you have of the organisation you're both in, the mentorship you provide can rapidly develop the engineers around you.

With a little focused effort you can take a promising junior to senior in 2 years, and you're going to have the freedom to go hunting for these candidates. You find them, and you make them your special projects. By the time they're flourishing, they'll be thinking like you, they'll be building like you, and they'll be your extensions into the organisation.
-->

---

# Communication & Decision Making

**Communication increases significantly:**
- Written artifacts: RFCs, design docs, ADRs
- Cross-functional collaboration with PMs, product, executives
- Translation layer: Making technical concepts accessible

**Decisions become more nuanced:**
- Not just "what's technically best" but "what's best for the business"
- Explicitly consider: maintainability, team skills, time-to-market, cost
- Know when to accumulate technical debt vs. pay it down

<!--
While direct mentoring is extremely valuable, you won't be able to make time for everyone who deserves your advice, so to cover that you need to let people see the experience whenever you're solving problems.

Do your work in the open, let people see what you're considering and what evidence contributed to the opinions you're reaching. Document your work and surface it wherever you can, and make it as accessible as possible. Your audience will span juniors through seniors, managers both with and without an engineering background, salespeople and support personnel, and execs.  If you can make the technical decisions approachable and keep them from being lost in terminology and rhetoric than they can learn more about the problem spaces and how to approach problems better. 

It also generates trust. You're going to be working in problem spaces where you haven't previously participated and when you turn up, you want to have a seat at the table prepared for you. If you're seen to be solving issues, people think you do it well, and you've made other peoples lives easier, then your opinions and work will always be welcome.
-->
