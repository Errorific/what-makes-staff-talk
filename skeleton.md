# Staff Engineers: Content Scaffold

<!-- This file contains the raw content and notes for the staff engineer presentation -->
<!-- Once sections are finalized, they'll be converted into slides.md -->

## 1. Introduction / Overview

**What is a Staff Engineer?**
- The level beyond Senior Engineer where you're no longer bound to a single team
- Technical leadership without direct reports
- **Impact radius**: Zone level or organizational level (minimum)
  - Staff: Zone level or beyond
  - Principal: Wider radius, thinking multiple horizons into the future
  - Distinguished: Company-wide impact, long-term strategic thinking

**Autonomy at Staff Level**
- Identify and discover high-impact problems worth solving
- Manage their own time budget
- Apply themselves where they'll be most effective
- Operate without needing direction on what to work on

**Staff Engineer vs. Engineering Manager**

Staff engineers may have teams working under their direction for specific projects, but they are NOT Engineering Managers. Key distinctions:

- **No performance reviews**: EMs own career development and performance evaluation for their reports
- **No hiring authority**: EMs manage headcount, make hiring decisions, and build teams
- **No 1:1s or personnel management**: EMs handle team rituals, conflict resolution, and people issues
- **No administrative overhead**: EMs deal with budgets, timecards, HR processes, and team logistics

Staff engineers lead through influence, technical direction, and expertise—not through organizational authority.

**A Note on Terminology** (separate slide)

Different companies define "Staff Engineer" differently:
- **Our definition**: First level beyond Senior where you operate across teams with zone/org-level impact
- **Some companies**: Treat Staff as a "super senior" who still belongs to a single team, only graduating to Principal+ for cross-team work

Throughout this presentation, we use the first definition.

## 2. What Differentiates Staff from Senior Engineers?

**Impact Radius & Scope:**
- Senior: Impact radius within their team. Concerned with what they can individually build and deliver
- Staff: Impact radius at zone/org level. Concerned with multiplying the impact of engineers around them
- Staff execution sets direction: When Staff engineers build, they're establishing patterns and showing "how we do things"

**The Mastery Progression:**
- Senior Engineer: Approaching **technical mastery**
- Staff Engineer: Approaching **social mastery** (building consensus, influencing without authority, navigating organizational dynamics)
- Principal Engineer: Approaching **business mastery**

**Technical Decision Making:**
- Senior: Make decisions within their domain/service, thinking 1-2 quarters ahead
- Staff: Make decisions affecting system architecture and cross-team standards, thinking multi-quarter to multi-year ahead
- Staff: Bring deeper expertise and consider longer time horizons when evaluating trade-offs

**From Individual Contributor to Force Multiplier:**
- Senior: Success = shipping high-quality features and systems
- Staff: Success = making multiple teams more effective
- Staff value examples: Creating reusable patterns, unblocking multiple teams, raising the technical bar
  - TODO: Revisit these examples, they need improvement
- (We'll explore how this value is realized in depth later)

**Influence & Communication:**
- Senior: Builds consensus within their team and immediate stakeholders
- Staff: Builds consensus across teams with competing priorities and different contexts
- Staff: Must navigate organizational politics and power structures to drive change

**Handling Complexity:**
- Senior: Navigates technical complexity within known problem spaces
- Staff: Navigates technical AND organizational complexity across ambiguous problem spaces
- Staff: Expected to have deeper awareness of risk, ambiguity, and organizational dynamics

## 3. How They Work Differently

**Technical Work:**
- Highly variable time spent coding (can be 70%, 30%, or even less depending on current needs)
- Always in pursuit of technical outcomes - never stray so far from tools that they lose technical skills
- When they code: Often setting patterns, proving concepts, or unblocking critical paths
- More time on: Architecture, design reviews, technical debt strategy, raising the bar

**Communication & Alignment:**
- Both synchronous and asynchronous communication increase significantly
- Written artifacts: RFCs, design docs, technical strategy docs, ADRs
- Strategic planning: Driving alignment across different teams, engineers, and stakeholders
- Cross-functional collaboration: More meetings with PMs, product, executives
- Translation layer: Making technical concepts accessible to non-technical stakeholders

**Time & Attention:**
- Meeting load goes up substantially
- Interrupt-driven work increases - pulled into emerging situations for triage and correction
- More context switching between teams and problem domains
- Must protect time for deep work while being available for unblocking

**Focus Areas:**
- Identify and tackle ambiguous, organizationally important problems
- Create clarity from complexity
- Raise the technical bar (code quality, testing, architecture patterns)
- Build systems that scale (technical and organizational)

Examples of organizationally important problems:
- Migration strategy for a deprecated platform affecting multiple teams
- Performance bottlenecks impacting customer experience across products
- Technical architecture decisions that will impact hiring and team structure

**Investing in Engineers:**
- Active mentorship of engineers across the organization
- Growing talent - helping engineers level up in technical skills and organizational navigation
- Creating learning opportunities and knowledge sharing
- Building the next generation of technical leaders

**Decision Framework:**
- Not just "what's technically best" but "what's best for the business given constraints"
- Explicitly consider: maintainability, team skills, time-to-market, cost, business impact
- Know when to accumulate technical debt vs. pay it down
- Ties back to the mastery progression: Staff engineers are becoming more aware of business impact and must consider it in their actions and plans, but don't yet have the depth of business understanding expected at Principal+ levels

## 4. Staff Engineer Archetypes

Based on Will Larson's "Staff Engineer" book and common patterns in the industry.

**The Tech Lead:**
- Guides technical direction for a specific team/product
- Balances coding with architecture and mentorship
- Most common archetype
- Example responsibilities: Service architecture, technical roadmap, unblocking team
- Best fit: Teams that need consistent technical direction and growing engineers

**The Architect:**
- Focuses on company/org-wide technical architecture
- Less hands-on coding, more design and strategy
- Creates architectural standards and patterns
- Example: Designing microservices strategy, data platform architecture
- Best fit: Organizations scaling rapidly or undergoing major technical transitions

**The Solver:**
- Parachutes into critical problems and fixes them
- Highly autonomous, moves between challenges
- Deep technical expertise in specific areas
- Example: Performance issues, data migrations, critical incidents
- Best fit: Organizations with many complex technical challenges and need firefighting capacity

**The Right Hand:**
- Extends reach of executive or senior leader
- High degree of organizational context and trust
- Often works on top priorities or fires
- Trusted to represent leadership's perspective
- Best fit: Leadership needs leverage to execute on strategic initiatives

**The Networker:**
- Makes connections and bridges between teams and departments
- Facilitates collaboration and information flow
- Breaks down silos and creates organizational cohesion
- Example: Connecting teams working on related problems, facilitating cross-team initiatives
- Best fit: Larger organizations where coordination and communication are bottlenecks

**The Expert:**
- Deep knowledge of a specific technology or system
- 10x engineer delivery in their domain of expertise
- Go-to person for critical decisions in their specialty
- Example: The Kubernetes expert, the database performance expert, the security specialist
- Best fit: Organizations with critical specialized needs or complex technical domains

**Important Notes:**
- **On the journey to Staff**: You typically embody ONE of these archetypes rather than multiple. This is often your path to promotion.
- **Once you're Staff**: You flex between archetypes depending on organizational needs. The role is fluid, not rigid.
- Most staff engineers blend multiple archetypes over time as they grow and as the organization's needs change.

## 5. Behaviors That Lift Them Above Peers

**Ownership & Accountability:**
- Takes responsibility for seeing problems through to resolution, even when it crosses team boundaries
- Owns outcomes, not just their individual contributions
- Steps up when something is broken or unclear, rather than waiting for someone to assign it
- Takes the blame when things go wrong, gives credit when things go right

**Proactive Investigation & Discovery:**
- Seeks out the next challenge and opportunity instead of waiting for it to be assigned
- Investigates problems deeply before proposing solutions
- Surfaces issues and risks early, even when uncomfortable
- Asks "why" repeatedly to understand root causes, not just symptoms

**Building Consensus & Influence (Social Mastery):**
- Invests time in understanding stakeholder needs and constraints before proposing solutions
- Builds relationships before needing them - networks proactively
- Makes decisions transparent by documenting reasoning and trade-offs
- Disagrees constructively and commits fully once decisions are made
- Brings people along rather than pushing solutions through

**Making Others Effective (Social Mastery):**
- Makes themselves available to unblock others, even when it interrupts their own work
- Creates clarity from ambiguity for their team and peers
- Shares knowledge broadly through documentation, not just 1:1 conversations
- Gives actionable feedback that helps people grow

**Strategic Pragmatism:**
- Focuses energy on highest-impact problems, says no to low-value work
- Ships "good enough for now" solutions when appropriate, perfects when it matters
- Makes trade-offs explicit and connects technical decisions to business impact
- Knows when to accumulate technical debt and when to pay it down

**Leading by Example:**
- Models the behaviors and standards they want to see in others
- Admits mistakes publicly and shares what they learned
- Does the unglamorous work (documentation, tech debt, maintenance) without being asked
- Maintains technical skills and stays hands-on, never becoming "too senior to code"

**Navigating Complexity (Social Mastery):**
- Understands how decisions really get made in the organization
- Knows who needs to be involved and when
- Reads the room and adapts communication style to the audience
- Escalates appropriately - knows when to raise issues and to whom

**Continuous Adaptation:**
- Seeks feedback actively and acts on it
- Comfortable with ambiguity and changing priorities
- Adapts their approach based on what the organization needs, not what they prefer
- Learns from failures and shares those lessons

**Anti-Patterns (Behaviors That Hold Engineers Back):**

- **Waiting for perfect information**: Paralyzed by ambiguity instead of moving forward with imperfect data
- **Lone wolf syndrome**: Solving problems in isolation instead of building consensus
- **Not invented here**: Rejecting solutions because they didn't come up with them
- **Ivory tower architecture**: Making technical decisions without understanding implementation realities
- **Hero complex**: Taking on everything themselves instead of multiplying others' impact
- **Technical purity over pragmatism**: Prioritizing elegant solutions over shipping value
- **Poor upward communication**: Failing to keep leadership informed of risks and progress
- **Avoiding conflict**: Not speaking up when they see problems to avoid discomfort
- **Working in the weeds**: Getting stuck in implementation details instead of focusing on impact
- **Credit seeking**: Taking credit for team accomplishments or avoiding blame when things fail
