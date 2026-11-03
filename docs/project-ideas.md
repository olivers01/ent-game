# Project Ideas (Combined Shortlist)

*Single living document for project proposals. Update this file in place as the team narrows down and refines the final choice.*

The original 8 ideas have been combined where they overlap or fix each other's weaknesses. **Nothing was dropped:** every original idea lives on inside one of the 5 concepts below, and each combined concept notes which part can still run on its own.

All concepts are checked against [course-outline.md](./course-outline.md) and [project-context.md](./project-context.md):
- **Scalable in real companies** (no "manager memorizes 12 employee profiles" surveys, no XP slapped onto checklists).
- **Playable by classmates** in a self-contained 15–20 minute slice for the Week 12 playtest.
- **Defensible on the rubric:** clear theory link, coherent mechanics, a good answer to "isn't this just X?" in Q&A.
- **Balanced for our team** (1 developer + 3 creative/research/report teammates).

| Original idea | Now part of |
|---|---|
| Charter Clash | 1. *The Unwritten Rules* |
| The Unwritten Rules | 1. *The Unwritten Rules* |
| First Week in the Wild | 2. *First Week in the Wild* |
| Day One Cold Case | 2. *First Week in the Wild* |
| Incident Zero | 3. *Incident Zero* |
| Silo Breakers | 3. *Incident Zero* |
| Pitch Pit | 4. *Pitch Pit* (refined) |
| Shadow AI Dilemma | 5. *Shadow AI Dilemma* (refined) |

---

## 1. *The Unwritten Rules* — Hidden-Norms Game That Ends in a Team Charter
- **Combines:** *The Unwritten Rules* + *Charter Clash*.
- **Why combine:** On its own, *Unwritten Rules* is close to the existing simulation *Barnga*, which stops at the debrief. On its own, *Charter Clash* is a team poll with no stakes or win condition. Played in sequence, the game creates real friction and the charter turns the insight into something the team keeps using.
- **Domain:** Onboarding & multicultural / cross-functional teamwork.
- **Medium:** Room-code web app (players on phones/laptops via QR code, shared screen on the projector).
- **Business Problem:** Culturally diverse and hybrid teams lose months to unspoken friction (blunt vs. indirect feedback, public vs. private disagreement, late deadline flags). People understand cultural differences from slide decks but revert to habit and blame teammates ("they're rude" / "they're evasive") under pressure. Personality surveys don't fix this because managers can't memorize individual manuals.
- **How It Plays (~20 min):**
  1. **Play (~10 min):** Groups of 3–4 work on a product-launch prioritization task. Each player's screen secretly enforces different communication rules and point penalties (Player A loses points whenever anyone is contradicted publicly; Player B loses points for ambiguous commitments; Player C must defer to seniority). The rules are fictional and never tied to real nationalities.
  2. **Reveal (~3 min):** The projector shows every rulebook side by side, plus the moments where the rules collided.
  3. **Commit (~5 min):** The *Charter Clash* phase. For each friction point (e.g., "How do we disagree?"), everyone taps their instinctive answer **and predicts how the room will split**. The anonymous split graph is revealed, correct predictions score points, the group debates for 90 seconds, then votes on one shared team rule. Ends with an exported **1-page Team Charter**.
- **Standalone option:** The charter phase alone (6 dilemma rounds, ~15 min) works as a lightweight kickoff tool for real teams that can't spare time for the full game.
- **KPIs:** Time-to-team-alignment, cross-site rework/escalation rate, Day-30 psychological safety pulse score. **Measurable in the Week 12 playtest:** ask players "Why did your teammate do X?" before and after, and check whether answers shift from personality ("rude", "evasive") to rules and context.
- **Theory & Ethics:** Kolb's Experiential Learning Cycle (experience → reflect → apply), SDT (*Relatedness* in play, *Autonomy* in rule-setting), MDA (*Discovery* aesthetic at the reveal), Fundamental Attribution Error, Hall (High/Low Context), Meyer's *Culture Map* for the norm dimensions; Hofstede only alongside its published critiques (e.g., McSweeney, 2002). Ethics: no nationality stereotyping, no stored personal profiles (GDPR / *Betriebsrat*), anonymous charter answers.

---

## 2. *First Week in the Wild* — Onboarding Sim With a Cold Case to Crack
- **Combines:** *First Week in the Wild* + *Day One Cold Case*.
- **Why combine:** Both need the same build: a simulated Slack / email / wiki / ticket workspace. On its own, *First Week* lacks a clear goal and needs a lot of branching story. On its own, *Cold Case* is a puzzle without day-to-day pressure. Together, the cold case gives the week a goal, and the inbox gives the investigation stakes.
- **Domain:** Employee onboarding + cross-cultural communication.
- **Medium:** Desktop web app (simulated workspace) played in pairs, with optional printed clue/role cards.
- **Business Problem:** New hires skim handbooks, don't know who actually owns what, hesitate to reach out to strangers or push back on seniors, and misread cues across global offices, while managers lack time to coach them one by one.
- **How It Plays (~20 min slice):** Pairs of "Day-1 hires" get one task from their lead: *find out why the Q3 release shipped upside-down pricing in two regions, by Friday.* The 5-day week is compressed into 5 rounds. Each round, the pair spends limited **Focus Blocks** between digging through tickets, wiki pages and Slack history, and answering incoming messages (a blunt lead, an indirect overseas partner, two seniors who contradict each other). Limited **Coffee Chat Tokens** let them interview colleagues for tribal knowledge, so choosing whom to ask is itself the lesson. Hidden **Trust** and **Clarity** scores react to how they handle messages, and misread messages can send them down false leads. Ends with a **Causality Timeline** showing the real incident chain next to the pair's own decisions.
- **Standalone option:** Either half works alone: the investigation only (less writing), or the inbox survival only (no puzzle).
- **KPIs:** Time-to-first-autonomous-task, cross-team contacts made in Month 1, reduction in Month-1 manager coaching hours, documentation retention vs. standard onboarding.
- **Theory & Ethics:** SDT (*Competence* through safe failure, *Relatedness* through coffee chats), Octalysis CD7 (Unpredictability & Curiosity), Flow, Kolb, HEXAD (Free Spirits & Achievers). Ethics: training sim vs. covert performance assessment, so scores are never shared with managers; no streaks or mandatory completion pressure.
- **Scope note:** Heaviest writing load on the list (case files, messages, characters). The writers carry most of it; the developer builds one reusable workspace UI driven by a content file. The case is one-shot, so a real company would rotate cases per onboarding cohort.

---

## 3. *Incident Zero* — Crisis Game Where Every Department Has a KPI to Protect
- **Combines:** *Incident Zero* + *Silo Breakers*.
- **Why combine:** Both use four asymmetric department roles and a shared company meter. *Silo Breakers*' private KPIs give every player a reason to act selfishly during the crisis, so the Blame Trap becomes pressure on the whole table instead of one player's secret. *Incident Zero* gives *Silo Breakers* a vivid, time-pressured scenario and gives the developer a real job (the live dashboard).
- **Domain:** Operations, cross-department alignment & psychological safety.
- **Medium:** Digital-tabletop hybrid (live crisis dashboard on the projector + physical confidential role packets).
- **Business Problem:** Departments hit their own KPIs while hurting the company (Sales overpromises custom features, Engineering hoards capacity, Ops blocks changes). During real incidents, people hide early mistakes out of fear of blame until they explode, and 40-page crisis playbooks go unread.
- **How It Plays (~15–20 min):** Four roles (**Engineering**, **Support / Customer Success**, **Legal / Comms**, **Product / Sales**) handle an escalating outage over 4 phases. Each role has a **private KPI** (e.g., Support: ticket close time; Sales: keep the big client's launch date) and a secret in its packet; one role's team caused the bug. The dashboard tracks **Shared Company Health** (Cash, Stability, Customer Trust). Admitting a mistake early costs a little of your own KPI but unlocks the root-cause fix; hiding it risks a 3× cascade. If any shared track hits zero, *everyone loses*, including the personal KPI leader.
- **Low-tech variant:** *Silo Breakers* as a pure board game across 4 calm business quarters (no outage), with a simple web calculator for quarter-end scoring.
- **KPIs:** Mean Time to Escalate (MTTE) internal errors, near-miss self-reporting rate, cross-department handoff friction, SOP recall.
- **Theory & Ethics:** Edmondson's *Psychological Safety*, Goodhart's Law, Social Interdependence Theory, Flow, Octalysis (CD1, CD5, CD8), MDA. Real-world precedent: incident tabletop exercises and blameless post-mortems in software operations. Ethics: stress-testing vs. inducing anxiety, a strictly blameless debrief, and a direct critique of toxic competitive leaderboards.

---

## 4. *Pitch Pit* — Live Prediction Market for Employee Ideas
- **Domain:** Strategy & Innovation Management *(directly targets "innovation inertia" from [course-outline.md](./course-outline.md))*.
- **Medium:** Mobile trading web app + live projector stock ticker.
- **Business Problem:** Corporate idea portals get little engagement because ideas vanish into slow committees and office politics pick the winners.
- **How It Plays (~20 min):** Trios draw a **Pain Point card** and a **Constraint card** (*"Zero new hires"*, *"Ship in 14 days"*) and have 3 minutes to shape a 3-bullet pitch. Pre-written cards keep the slice on time instead of relying on classmates to invent ideas from scratch. Everyone gets **1,000 Innovation Credits** in the mobile app (code-enforced: *cannot invest in your own team*). Mid-round, the projector drops a **Market Shock Event** (*"30% budget cut"*, *"EU AI audit"*), opening a 3-minute window for 140-character pivots and live portfolio trading. Top ideas win **2-Week Protected Sandbox Time** rather than cash.
- **KPIs:** Idea submission rate, cross-department backing diversity, pilot conversion rate, decision cycle time.
- **Theory & Ethics:** Octalysis (CD3, CD4 Ownership, CD6 Scarcity), SDT *Autonomy*, Overjustification Effect (why autonomy beats cash bonuses). Ethics: anonymous early trading to prevent popularity bias.

---

## 5. *Shadow AI Dilemma* — Practical AI Adoption & Data-Risk Game
- **Domain:** Change Management, AI Enablement & Data Privacy.
- **Medium:** Fast multiplayer web app (or card + web hybrid).
- **Business Problem:** Employees paste confidential client or HR data into public AI tools ("Shadow AI") to save time, or avoid AI completely, because 30-page compliance PDFs are unreadable.
- **How It Plays (~15–20 min):** Teams race through realistic **Workday Shortcut Scenarios** (*"Summarize 40 customer calls by 2 PM"*, *"Debug proprietary pricing code"*), playing **Tool + Workflow Cards** (Approved Sandbox, Anonymize-First, Public LLM, Manual) to maximize **Hours Saved**. Rival teams can hit **"Audit!"** on their phones if they spot a hidden GDPR, IP, or hallucination landmine. A wrong audit costs the auditor points, and a caught team wins back half its loss by naming the safe workflow, so being caught becomes a learning moment instead of a pure gotcha.
- **KPIs:** Reduction in data-loss prevention (DLP) policy violations, adoption rate of approved AI tools, scenario judgement accuracy.
- **Theory & Ethics:** Fogg Behavior Model (teaching *safe* high-ability shortcuts instead of blanket bans), SDT *Competence*. The core choice is a real speed-vs-risk trade-off, which keeps it from becoming a compliance quiz with points. Ethics: AI surveillance, deskilling, and peer-policing dynamics.

---

## Comparison

| # | Concept | Combines | Topic | Medium | Classmates play it for real? | Dev effort | Writing effort | Main risk |
|---|---|---|---|---|---|---|---|---|
| **1** | **The Unwritten Rules** | Unwritten Rules + Charter Clash | Multicultural teamwork | Room-code web app + projector | Yes, the friction is real | Medium | Medium (rulebooks, dilemmas) | Showing it's more than *Barnga* (the charter phase is the answer) |
| **2** | **First Week in the Wild** | First Week + Cold Case | Onboarding | Simulated workspace, played in pairs | Yes, as role-played new hires | Medium–High | High (case, messages, characters) | Content scope |
| **3** | **Incident Zero** | Incident Zero + Silo Breakers | Crisis, silos, psych safety | Dashboard + role packets | Yes | Medium | Medium (role packets, events) | Balancing private KPIs vs. shared meter needs several playtests |
| **4** | **Pitch Pit** | — | Innovation | Mobile wallet + live ticker | Partly (card-based pitches) | Medium | Low–Medium (cards, shocks) | Tight 20-minute timing |
| **5** | **Shadow AI Dilemma** | — | AI adoption & data risk | Multiplayer web / cards | Yes, most students use AI tools | Low–Medium | Medium (scenarios) | Sliding into a compliance quiz |
