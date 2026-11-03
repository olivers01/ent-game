# Project Ideas (Consolidated Shortlist)

*Single living document for project proposals. Update this file in place as the team narrows down and refines the final choice.*

All 5 concepts below are designed around [course-outline.md](./course-outline.md) and [project-context.md](./project-context.md):
- **Scalable in real companies** (no unscalable "manager adapts to 12 employee profiles" surveys).
- **Strong on the rubric** (Business Context & KPIs 5%, Theory 10%+5%, Design Quality 5%, Prototype & Week 12 Playtest 5%+5%, Ethics 5%).
- **Balanced for our 4-person team** (1 developer + 3 creative/research/report teammates), choosing whichever medium—web app, multiplayer phone-to-projector app, digital-tabletop hybrid, or board game—makes each idea strongest.

---

## Top 5 Project Proposals

### 1. *Charter Clash* — Jackbox-Style Multiplayer Game for Team Working Norms
- **Medium:** **Live Room-Code Web App** (1 shared projector/laptop screen + players join on phones via QR code, zero login friction).
- **Theme:** Onboarding & Multicultural / Cross-Functional Teamwork.
- **Business Problem:** Newly formed, hybrid, and culturally diverse squads lose months to unspoken friction (deadline warnings, blunt vs. indirect feedback, public vs. private disagreement). Static HR personality surveys fail because managers cannot memorize individual manuals.
- **Core Game Loop:**
  1. Squad scans a QR code at project kickoff (or when a new hire joins) for a 15-minute session.
  2. The main screen deals **6 grey-area workplace dilemmas** (*"It's Wednesday and a hidden dependency threatens Friday's client demo..."*, *"A senior lead's proposal has an obvious flaw on a cross-office call..."*).
  3. Players tap their instinctive move on their phones within 20 seconds.
  4. **Anonymous Split Reveal:** The screen animates where instincts clashed (*3 chose "Flag in public channel", 2 chose "Fix quietly first"*)—protecting juniors from hierarchy pressure—and starts a 90-second debate timer.
  5. **Charter Lock-In:** Phones display 3 concrete **Team Rule options**; the squad votes to lock one in. Round 6 exports a **1-Page Squad Charter** + alignment radar.
- **Measurable KPIs:** Time-to-team-alignment, cross-site escalation rate, Day-30 new-hire psychological safety pulse score.
- **Theory & Ethics:** SDT (*Autonomy*: team co-writes its rules; *Relatedness*), MDA, Meyer's *Culture Map* dimensions applied to *team norms* without nationality stereotyping or GDPR-invasive profiling.
- **4-Person Split:**
  - *Dev (1):* Room-code session engine, phone voting UI, live split visualization, Charter export.
  - *Teammates (3):* Author 20+ workplace dilemma & rule cards, UX/presentation design, SDT/HEXAD/Culture theory & Ethics report sections.

---

### 2. *First Week in the Wild* — Safe-to-Fail Onboarding & Subtext Simulator
- **Medium:** **Interactive Desktop Web App** (simulated Slack + Email + Calendar workspace; *Papers, Please* meets *Reigns*).
- **Theme:** Employee Onboarding + Cross-Cultural Communication.
- **Business Problem:** New hires ignore passive Confluence/Notion handbooks, hesitate to ask questions or push back on seniors, and misread high- vs. low-context communication across global offices—while managers lack time to micro-coach.
- **Core Game Loop:**
  1. Player steps into a compressed **5-Day Global Launch Sprint** as a Day-1 hire (modeled on anonymized scenarios from a real company).
  2. Competing pings arrive across channels: an ambiguous ticket from a blunt HQ lead, an indirect warning (*"that timeline may be ambitious"*) from an overseas partner, conflicting requests from two seniors, and a staging bug.
  3. Player spends limited **Daily Focus Blocks** choosing *who* to answer, *which channel* to use (public thread, 1:1 DM, pre-meeting sync), and *how* to respond (optionally tagging perceived subtext first).
  4. Hidden state tracks **Trust**, **Psychological Safety**, and **Delivery Clarity**. Day 5 ends with an interactive **Causality Post-Mortem Timeline** showing where misread cues snowballed and explaining the company's real norms.
- **Measurable KPIs:** Time-to-first-independent-task, reduction in Month-1 manager hand-holding hours, pre/post situational judgement score.
- **Theory & Ethics:** Flow (calibrated inbox pressure), SDT *Competence* (safe failure), Kolb's Experiential Learning. Ethics critiques *training vs. covert HR performance surveillance* and avoiding cultural caricatures via individual persona traits.
- **4-Person Split:**
  - *Dev (1):* Multi-channel workspace UI, JSON scenario state machine, meter animations, post-mortem timeline.
  - *Teammates (3):* Write the 5-day branching script & personas, design artifacts/avatars, map MDA/SDT/Meyer theory & Ethics.

---

### 3. *Incident Zero* — Asymmetric Crisis & Blameless Culture Simulation
- **Medium:** **Digital-Tabletop Hybrid** (coded **Real-Time Crisis Dashboard** with ticking alerts & branching state + physical confidential **Department Role Packets** at each table).
- **Theme:** Operations, Tech/Product, Risk & Psychological Safety.
- **Business Problem:** 40-page crisis playbooks go unread, and during real operational incidents, employees hide early mistakes out of fear of blame until they snowball.
- **Core Game Loop:**
  1. A 15-minute live web dashboard triggers an escalating incident (*"Checkout service is double-charging European customers; social media notices in 3 turns"*).
  2. Four players hold asymmetric physical packets (**Engineering**, **Customer Support**, **Legal/Comms**, **Product Lead**) containing partial clues.
  3. Every 2.5 minutes, the table inputs an action code into the dashboard, dynamically branching the crisis.
  4. **The Blame Trap:** One player's packet reveals *their* department accidentally caused the issue. Disclosing early costs 1 small Reputation hit now *but* unlocks the root-cause fix; hiding it risks a $3\times$ explosion.
- **Measurable KPIs:** Mean Time to Escalate (MTTE) internal errors, near-miss self-reporting rate, crisis SOP recall.
- **Theory & Ethics:** Amy Edmondson's *Psychological Safety*, Flow, Octalysis (CD1 Epic Meaning, CD5 Co-op, CD8 Constructive Loss Avoidance). Ethics examines inducing time stress responsibly and ensuring strictly blameless debriefs.
- **4-Person Split:**
  - *Dev (1):* Live crisis dashboard (timers, alert feed, branching code input, debrief summary).
  - *Teammates (3):* Physical role dossiers & clue cards, crisis narrative balancing, Psychological Safety/MDA/Ethics report sections.

---

### 4. *Pitch Pit* — Live Mobile Prediction Market for Employee Ideas
- **Medium:** **Mobile Web App + Live Projector Stock Ticker**.
- **Theme:** Innovation Management (directly targets *"innovation inertia"* from Page 1 of [course-outline.md](./course-outline.md)).
- **Business Problem:** Corporate suggestion boxes see <5% participation because ideas disappear into slow committees and politics decide winners.
- **Core Game Loop:**
  1. Small teams pitch 3-bullet fixes to real company pain points under a constraint card (*"Zero new headcount"*, *"Launch in 14 days"*).
  2. All players open the mobile web app with **1,000 Innovation Credits** (code-enforced rule: *cannot invest in your own team*).
  3. Projector displays live shifting valuations. Mid-session, a **Market Shock Event** triggers (*"Budget cut 30%"*, *"New EU AI audit"*), opening a 3-minute window for 140-character team pivots and portfolio rebalancing.
  4. Winning teams earn **Protected 2-Week Sandbox Time** (autonomy reward rather than cash).
- **Measurable KPIs:** Idea submission rate, cross-department backing diversity, pilot conversion rate, time-to-decision.
- **Theory & Ethics:** Octalysis (CD3 Creativity, CD4 Ownership, CD6 Scarcity), SDT *Autonomy*, Overjustification Effect (why non-cash autonomy beats cash bonuses). Ethics addresses extrovert/popularity bias via anonymous early trading.
- **4-Person Split:**
  - *Dev (1):* Mobile trading wallet, anti-self-dealing ledger, live projector ticker & shock-event trigger.
  - *Teammates (3):* Pain/Constraint/Shock decks, live pitch facilitation script, Octalysis/SDT/Ethics report sections.

---

### 5. *Silo Breakers* — Cross-Department KPI Trade-Off Game
- **Medium:** **Physical Tabletop Board Game + Lightweight Web Quarter-End Calculator**.
- **Theme:** Cross-Functional Alignment & Business-Model Onboarding.
- **Business Problem:** Sales, Engineering, Operations, and Customer Success each optimize their own departmental KPIs while hurting overall company health (local optimization / silo mentality).
- **Core Game Loop:**
  1. Four players manage **Sales**, **Engineering**, **Operations**, and **Customer Success** across 4 simulated quarters using physical capacity cubes and deal/incident cards.
  2. Each role chases a **Private KPI Target**, while the shared board tracks **Company Survival** (Cashflow, Stability, Retention). If any shared meter hits zero, *everyone loses*—even the highest individual scorer.
  3. A companion web screen rolls quarterly market events and calculates cross-impact scores instantly.
- **Measurable KPIs:** Cross-departmental handoff friction, late-stage scope-change rework, new-hire/manager comprehension of company business model.
- **Theory & Ethics:** Goodhart's Law, Social Interdependence Theory, MDA (emergent tension between solo incentives and collective survival), ethical critique of toxic individual leaderboards.
- **4-Person Split:**
  - *Dev (1):* Web event roller & instant quarter-end impact calculator + rules balancing.
  - *Teammates (3):* Board & card art/production, department scenario design, MDA/Goodhart/Ethics report sections.

---

## Comparison Matrix

| Proposal | Medium | Enterprise Scalability | Week 12 Class Experience | Dev Scope (1 coder) | Creative/Research Scope (3 teammates) |
|---|---|---|---|---|---|
| **1. Charter Clash** | Phone + Projector Web App | **Very High** (15-min self-serve kickoff) | Whole class plays live via QR code | Low–Medium | Dilemma bank, UX/slides, SDT/Culture theory |
| **2. First Week in the Wild** | Desktop Workspace Sim (Web) | **Very High** (automated new-hire sim) | Pairs race a 5-day launch crisis | Medium | 5-day branching script, personas, Meyer/SDT |
| **3. Incident Zero** | Live Web Dashboard + Role Packets | **High** (repeatable ops/safety drill) | High-tension 4-role table co-op | Low | Confidential dossiers, crisis writing, Edmondson/Flow |
| **4. Pitch Pit** | Mobile Market App + Live Ticker | **High** (quarterly innovation sprint) | Loud, live classroom trading floor | Medium | Pain/Shock cards, pitch format, Octalysis/Ethics |
| **5. Silo Breakers** | Board Game + Web Calculator | **Medium–High** (cohort workshop) | Face-to-face bluffing & negotiation | Low | Physical board/cards, math balance, Goodhart/MDA |

---

## Secondary / Parked Concepts (Brief Archive)

Kept briefly in case the team wants to borrow a single mechanic later:
- ***Day One Cold Case* (Onboarding Detective):** New hires solve a fictionalized past company bug/incident using simulated wiki docs and limited "Coffee Chat Tokens" to learn who owns what. *(Can also be folded into Idea #2 as an episode.)*
- ***Shadow AI Dilemma*:** Fast card/web audit game teaching employees safe practical AI shortcuts vs. GDPR/hallucination landmines (Fogg Behavior Model).
- ***Phish Hunt* (Positive-Reinforcement Security League):** One-click phishing reporting for team points with blame-free micro-lessons on misses (high KPI clarity, lower originality).
