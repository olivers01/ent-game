# Research: Evidence Base for the Project Ideas

*Literature review backing the concepts in [project-ideas.md](../project-ideas.md), checked against the rubric in [course-outline.md](../course-outline.md). Researched 2026-11-03.*

> **Status:** Complete. **Recommendation: Concept 3, *Incident Zero*** (see [section 6](#6-recommendation)). Runner-up: Concept 1, *The Unwritten Rules*.

## How references were verified

The course gives **0% for fabricated references**, so every source below was checked against a primary record:

- **[CR]** = authors, year, title and venue matched on Crossref and cross-checked in OpenAlex.
- **[A]** = abstract was also read; effect sizes are quoted from it.
- Other methods (publisher page, author-hosted PDF, Open Library for books) are stated next to the source.
- **Books, working papers, technical reports and trade books are flagged.** Only cite them as such.
- "Findings from a secondary summary" means the reference itself is verified, but the finding was not read in the original. Re-check it in the paper before quoting it.

---

## 1. Does gamification work, and when?

### Meta-analyses and reviews

| Source | Key finding | Verified |
|---|---|---|
| Deterding, S., Dixon, D., Khaled, R., & Nacke, L. (2011). From game design elements to gamefulness: Defining "gamification". *Proc. 15th International Academic MindTrek Conference* (pp. 9–15). ACM. https://doi.org/10.1145/2181037.2181040 | Standard definition: "the use of game design elements in non-game contexts." | [CR] |
| Hamari, J., Koivisto, J., & Sarsa, H. (2014). Does gamification work? – A literature review of empirical studies on gamification. *Proc. 47th HICSS* (pp. 3025–3034). IEEE. https://doi.org/10.1109/HICSS.2014.377 | Effects mostly positive but "greatly dependent" on context and users. | [CR][A] |
| Koivisto, J., & Hamari, J. (2019). The rise of motivational information systems: A review of gamification research. *International Journal of Information Management, 45*, 191–210. https://doi.org/10.1016/j.ijinfomgt.2018.10.013 | 819 studies; results lean positive but a "remarkable" share are mixed; points, badges and leaderboards still dominate the field. | [CR][A] |
| Seaborn, K., & Fels, D. I. (2015). Gamification in theory and action: A survey. *International Journal of Human-Computer Studies, 74*, 14–31. https://doi.org/10.1016/j.ijhcs.2014.09.006 | Standard survey of terminology and theory. | [CR] |
| Sailer, M., & Homner, L. (2020). The gamification of learning: A meta-analysis. *Educational Psychology Review, 32*(1), 77–112. https://doi.org/10.1007/s10648-019-09498-w | Cognitive g = .49, motivational g = .36, behavioural g = .25. Game fiction and social interaction were significant moderators; **competition combined with collaboration** worked best. | [CR][A] |
| Sitzmann, T. (2011). A meta-analytic examination of the instructional effectiveness of computer-based simulation games. *Personnel Psychology, 64*(2), 489–528. https://doi.org/10.1111/j.1744-6570.2011.01190.x | 65 studies, N = 6,476. Vs. controls: self-efficacy +20%, declarative knowledge +11%, procedural knowledge +14%, retention +9%. Works better when learning is active and the game supplements other instruction. Reports strong publication bias. | [CR][A] |
| Wouters, P., van Nimwegen, C., van Oostendorp, H., & van der Spek, E. D. (2013). A meta-analysis of the cognitive and motivational effects of serious games. *Journal of Educational Psychology, 105*(2), 249–265. https://doi.org/10.1037/a0031311 | Learning d = 0.29, retention d = 0.36, but **not more motivating** (d = 0.26, n.s.). Better with supplementary instruction, multiple sessions, and **group play**. | [CR][A] |
| Clark, D. B., Tanner-Smith, E. E., & Killingsworth, S. S. (2016). Digital games, design, and learning: A systematic review and meta-analysis. *Review of Educational Research, 86*(1), 79–122. https://doi.org/10.3102/0034654315582065 | Games vs. non-games g = 0.33; better designs g = 0.34. Design matters more than medium. | [CR][A] |
| Huang, R., Ritzhaupt, A. D., Sommer, M., Zhu, J., Stephen, A., Valle, N., Hampton, J., & Li, J. (2020). The impact of gamification in educational settings on student learning outcomes: A meta-analysis. *Educational Technology Research and Development, 68*(4), 1875–1901. https://doi.org/10.1007/s11423-020-09807-z | g = .464 across 30 studies. | [CR][A] |
| Bai, S., Hew, K. F., & Huang, B. (2020). Does gamification improve student learning outcome? Evidence from a meta-analysis and synthesis of qualitative data in educational contexts. *Educational Research Review, 30*, 100322. https://doi.org/10.1016/j.edurev.2020.100322 | g = 0.504 (from a secondary summary; check the abstract before quoting). | [CR] |
| Zeng, J., Sun, D., Looi, C.-K., & Fan, A. C. W. (2024). Exploring the impact of gamification on students' academic performance: A comprehensive meta-analysis of studies from the year 2008 to 2023. *British Journal of Educational Technology, 55*(6), 2478–2502. https://doi.org/10.1111/bjet.13471 | g = 0.782 across 22 studies. Strongest recent estimate, but few studies; read with Sitzmann's publication-bias warning. | [CR][A] |
| Landers, R. N. (2014). Developing a theory of gamified learning. *Simulation & Gaming, 45*(6), 752–768. https://doi.org/10.1177/1046878114563660 | Gamification changes learning-related *behaviours and attitudes*, which then mediate or moderate learning; serious games aim to produce learning directly. **The report should say which one we are building.** | [CR][A] |
| Krath, J., Schürmann, L., & von Korflesch, H. F. O. (2021). Revealing the theoretical basis of gamification. *Computers in Human Behavior, 125*, 106963. https://doi.org/10.1016/j.chb.2021.106963 | Maps 118 theories onto shared principles. Strong backbone for the theory section. | [CR][A] |

### Which game elements help, and which don't

- Sailer, M., Hense, J. U., Mayr, S. K., & Mandl, H. (2017). How gamification motivates. *Computers in Human Behavior, 69*, 371–380. https://doi.org/10.1016/j.chb.2016.12.033 **[CR][A]**. Badges, leaderboards and performance graphs raised competence; stories, avatars and teammates raised relatedness; **autonomy could not be raised.**
- Mekler, E. D., Brühlmann, F., Tuch, A. N., & Opwis, K. (2017). Towards understanding the effects of individual gamification elements on intrinsic motivation and performance. *Computers in Human Behavior, 71*, 525–534. https://doi.org/10.1016/j.chb.2015.08.048 **[CR]** (findings from a secondary summary). Points, levels and leaderboards raised the *quantity* of performance but not intrinsic motivation.
- Hanus, M. D., & Fox, J. (2015). Assessing the effects of gamification in the classroom. *Computers & Education, 80*, 152–161. https://doi.org/10.1016/j.compedu.2014.08.019 **[CR]** (findings from a secondary summary). A course with leaderboard and badges produced lower motivation, satisfaction and exam scores over time.
- Rodrigues, L., et al. (2022). Gamification suffers from the novelty effect but benefits from the familiarization effect. *International Journal of Educational Technology in Higher Education, 19*, Article 13. https://doi.org/10.1186/s41239-021-00314-6 **[CR][A] + publisher page**. N = 756; effects declined after about 4 weeks and partly recovered in weeks 6–10.

### Workplace and enterprise gamification

- **Schönbohm, A., & Jülich, A. (2016). On the effectiveness of gamified risk management workshops: Evidence from German SMEs. *International Journal of Serious Games, 3*(2). https://doi.org/10.17083/ijsg.v3i2.117 [CR][A]. This is the course professor's own study.** A gamified workshop in 3 SMEs motivated participants, increased knowledge, and reduced cognitive and group biases.
- Cardador, M. T., Northcraft, G. B., & Whicker, J. (2017). A theory of work gamification: Something old, something new, something borrowed, something cool? *Human Resource Management Review, 27*(2), 353–365. https://doi.org/10.1016/j.hrmr.2016.09.014 **[CR]**. Treats work gamification as an extension of performance management, with boundary conditions set by the application and the workers.
- Mollick, E. R., & Rothbard, N. (2014). *Mandatory fun: Consent, gamification and the impact of games at work* [Working paper]. SSRN. https://doi.org/10.2139/ssrn.2277103 **[CR], working paper, not peer-reviewed.** Games raised positive affect only for employees who consented and **lowered** it for those who did not; legitimacy and personal agency drive consent.
- Hammedi, W., Leclercq, T., Poncin, I., & Alkire (Née Nasr), L. (2021). Uncovering the dark side of gamification at work. *Journal of Business Research, 122*, 256–269. https://doi.org/10.1016/j.jbusres.2020.08.032 **[CR]** (findings from abstract text found via search). Gamified work reduced frontline engagement and well-being; less harm when employees were willing or could opt out.
- Eger, V. M., Georganta, E., Zuercher, P.-D. J., Mueller, F., Bohné, T., & Diefenbach, S. (2025). The power of play: Gamification in virtual workplace training. *European Journal of Work and Organizational Psychology, 34*(2), 218–236. https://doi.org/10.1080/1359432X.2024.2412360 **[CR][A]**. 355 employees: *more* gamification **lowered perceived autonomy** and worsened affective and performance outcomes at retention.
- Friess, M. (2025). Gamification in virtual sales training: Evidence from a field experiment. *Journal of Personal Selling & Sales Management, 45*(3), 224–237. https://doi.org/10.1080/08853134.2024.2431817 **[CR][A]**. 147 sales reps: a competitive quiz raised enjoyment, then motivation and knowledge; stronger for experienced reps.
- Larson, K. (2020). Serious games and gamification in the corporate training environment: A literature review. *TechTrends, 64*(2), 319–328. https://doi.org/10.1007/s11528-019-00446-7 **[CR][A]**. Benefits and adoption barriers (hierarchy, demographics, ethics, past failures).
- Armstrong, M. B., & Landers, R. N. (2018). Gamification of employee training and development. *International Journal of Training and Development, 22*(2), 162–169. https://doi.org/10.1111/ijtd.12124 **[CR][A]**. Evidence-based process for gamifying training.
- Landers, R. N., Bauer, K. N., & Callan, R. C. (2017). Gamification of task performance with leaderboards: A goal setting experiment. *Computers in Human Behavior, 71*, 508–515. https://doi.org/10.1016/j.chb.2015.08.008 **[CR]**. Leaderboards work as a goal-setting intervention.
- Silic, M., & Lowry, P. B. (2020). Using design-science based gamification to improve organizational security training and compliance. *Journal of Management Information Systems, 37*(1), 129–161. https://doi.org/10.1080/07421222.2019.1705512 **[CR][A]**. 6-month field study, 420 employees: significant behaviour change; "appropriate challenge" was key.
- Baxter, R. J., Holderness, D. K., & Wood, D. A. (2016). Applying basic gamification techniques to IT compliance training: Evidence from the lab and field. *Journal of Information Systems, 30*(3), 119–133. https://doi.org/10.2308/isys-51341 **[CR][A]**. Basic gamification raised satisfaction but learning gains were only about 1–3%.

### Ethics

- Kim, T. W., & Werbach, K. (2016). More than just a game: Ethical issues in gamification. *Ethics and Information Technology, 18*(2), 157–173. https://doi.org/10.1007/s10676-016-9401-5 **[CR][A]**. Four checks: exploitation, manipulation (threats to autonomy), harm, effects on moral character. **Ready-made structure for the ethics section.**
- Butler, N., & Spoelstra, S. (2024). Redemption through play? Exploring the ethics of workplace gamification. *Journal of Business Ethics, 193*(2), 259–270. https://doi.org/10.1007/s10551-023-05584-w **[CR][A]**. Play at work stays ethically ambivalent even when enjoyed for its own sake.
- Mollick & Rothbard (2014) and Hammedi et al. (2021) above: consent and opt-out.

### Debriefing (the strongest effect in this review)

- Tannenbaum, S. I., & Cerasoli, C. P. (2013). Do team and individual debriefs enhance performance? A meta-analysis. *Human Factors, 55*(1), 231–245. https://doi.org/10.1177/0018720812448394 **[CR][A]**. 46 samples: **d = 0.67**, about 20–25% improvement, similar in simulated and real settings.
- Keiser, N. L., & Arthur, W., Jr. (2021). A meta-analysis of the effectiveness of the after-action review (or debrief) and factors that influence its effectiveness. *Journal of Applied Psychology, 106*(7), 1007–1032. https://doi.org/10.1037/apl0000821 **[CR][A]**. 61 studies: **d = 0.79**. Helped by objective performance-review media (a replay), alignment to individual or team, and self-led facilitation.
- Keiser, N. L., & Arthur, W., Jr. (2022). A meta-analysis of task and training characteristics that contribute to or attenuate the effectiveness of the after-action review (or debrief). *Journal of Business and Psychology, 37*(5), 953–976. https://doi.org/10.1007/s10869-021-09784-x **[CR][A]**. 83 studies: **d = 0.92**; especially effective for complex, ambiguous tasks with no intrinsic feedback.
- Cheng, A., Eppich, W., Grant, V., Sherbino, J., Zendejas, B., & Cook, D. A. (2014). Debriefing for technology-enhanced simulation: A systematic review and meta-analysis. *Medical Education, 48*(7), 657–666. https://doi.org/10.1111/medu.12432 **[CR][A]**. Simulation plus debrief vs. nothing: effect sizes 0.28–2.16.
- Crookall, D. (2010). Serious games, debriefing, and simulation/gaming as a discipline. *Simulation & Gaming, 41*(6), 898–920. https://doi.org/10.1177/1046878110390784 **[CR]**. Editorial position: debriefing is central to learning from games.
- Lederman, L. C. (1992). Debriefing: Toward a systematic assessment of theory and practice. *Simulation & Gaming, 23*(2), 145–160. https://doi.org/10.1177/1046878192232003 **[CR]**.
- Garris, R., Ahlers, R., & Driskell, J. E. (2002). Games, motivation, and learning: A research and practice model. *Simulation & Gaming, 33*(4), 441–467. https://doi.org/10.1177/1046878102238607 **[CR]**. Input–process–outcome model with the debrief between the game cycle and learning outcomes.

### What this means for choosing a concept

**The evidence favours:**
- collaboration combined with competition, and game fiction or narrative (Sailer & Homner, 2020);
- group play, and a game embedded in other instruction (Wouters et al., 2013; Sitzmann, 2011);
- above all, **a structured debrief with an objective replay** (d = 0.67–0.92), especially for complex tasks that give no feedback of their own.

**Pitfalls to design around:**
- **Mandatory participation backfires** (Mollick & Rothbard, 2014; Hammedi et al., 2021). Build in consent and opt-out.
- **Points, badges, leaderboards and heavy gamification** raise output, not intrinsic motivation, and can lower autonomy and learning (Mekler et al., 2017; Hanus & Fox, 2015; Eger et al., 2025).
- **Expected, performance-contingent rewards** undermine intrinsic motivation (Deci et al., 1999).
- **Novelty effects** fade after about 4 weeks (Rodrigues et al., 2022). A 20-minute playtest cannot show lasting change, so present real-world KPIs as hypotheses.

---

## 2. Frameworks the rubric asks for (canonical citations)

| Framework | Citation | Verified / type |
|---|---|---|
| MDA | Hunicke, R., LeBlanc, M., & Zubek, R. (2004). MDA: A formal approach to game design and game research. *AAAI Workshop on Challenges in Game AI* (WS-04-04). https://aaai.org/papers/ws04-04-001-mda-a-formal-approach-to-game-design-and-game-research/ | AAAI listing + authors' PDF; no DOI. Eight aesthetics: Sensation, Fantasy, Narrative, Challenge, Fellowship, Discovery, Expression, Submission. |
| SDT | Deci, E. L., & Ryan, R. M. (1985). *Intrinsic motivation and self-determination in human behavior*. Plenum. https://doi.org/10.1007/978-1-4899-2271-7 | [CR], book |
| SDT | Ryan, R. M., & Deci, E. L. (2000). Self-determination theory and the facilitation of intrinsic motivation, social development, and well-being. *American Psychologist, 55*(1), 68–78. https://doi.org/10.1037/0003-066X.55.1.68 | [CR] |
| SDT in games | Ryan, R. M., Rigby, C. S., & Przybylski, A. (2006). The motivational pull of video games: A self-determination theory approach. *Motivation and Emotion, 30*(4), 344–360. https://doi.org/10.1007/s11031-006-9051-8 | [CR]; source of the PENS measure |
| Flow | Csikszentmihalyi, M. (1990). *Flow: The psychology of optimal experience*. Harper & Row. | Book (Open Library); confirm the imprint from your copy |
| Bartle | Bartle, R. (1996). Hearts, clubs, diamonds, spades: Players who suit MUDs. *Journal of MUD Research, 1*(1). https://mud.co.uk/richard/hcds.htm | Author-hosted text; not a validated instrument, derived for MUDs |
| Player types critique | Hamari, J., & Tuunanen, J. (2014). Player types: A meta-synthesis. *Transactions of the Digital Games Research Association, 1*(2). https://doi.org/10.26503/todigra.v1i2.13 | [CR][A]; typologies reduce to 7 dimensions |
| HEXAD | Tondello, G. F., Wehbe, R. R., Diamond, L., Busch, M., Marczewski, A., & Nacke, L. E. (2016). The gamification user types Hexad scale. *Proc. CHI PLAY '16* (pp. 229–243). ACM. https://doi.org/10.1145/2967934.2968082 | [CR][A]; 24 items |
| HEXAD validation | Tondello, G. F., Mora, A., Marczewski, A., & Nacke, L. E. (2019). Empirical validation of the Gamification User Types Hexad scale in English and Spanish. *International Journal of Human-Computer Studies, 127*, 95–111. https://doi.org/10.1016/j.ijhcs.2018.10.002 | [CR] |
| HEXAD (origin) | Marczewski, A. (2015). *Even ninja monkeys like to play*. CreateSpace. | **Book, non-academic** |
| Octalysis | Chou, Y.-k. (2015). *Actionable gamification: Beyond points, badges, and leaderboards*. | **Book, non-academic**; imprint varies by printing, cite from your copy |
| Fogg | Fogg, B. J. (2009). A behavior model for persuasive design. *Proc. 4th International Conference on Persuasive Technology*. ACM. https://doi.org/10.1145/1541948.1541999 | [CR]; uses "trigger" (later renamed "prompt") |
| Overjustification | Deci, E. L., Koestner, R., & Ryan, R. M. (1999). A meta-analytic review of experiments examining the effects of extrinsic rewards on intrinsic motivation. *Psychological Bulletin, 125*(6), 627–668. https://doi.org/10.1037/0033-2909.125.6.627 | [CR]; 128 studies. Engagement-, completion- and performance-contingent rewards undermined intrinsic motivation (d = −0.40, −0.36, −0.28); positive feedback enhanced it (d = 0.33). |
| Incentives + intrinsic | Cerasoli, C. P., Nicklin, J. M., & Ford, M. T. (2014). Intrinsic motivation and extrinsic incentives jointly predict performance: A 40-year meta-analysis. *Psychological Bulletin, 140*(4), 980–1008. https://doi.org/10.1037/a0035661 | [CR][A]; intrinsic motivation predicts quality, incentives predict quantity |
| Kolb | Kolb, D. A. (1984). *Experiential learning: Experience as the source of learning and development*. Prentice-Hall. | Book (Open Library). Four stages: concrete experience, reflective observation, abstract conceptualization, active experimentation. |
| Kolb (peer-reviewed) | Kolb, A. Y., & Kolb, D. A. (2005). Learning styles and learning spaces: Enhancing experiential learning in higher education. *Academy of Management Learning & Education, 4*(2), 193–212. https://doi.org/10.5465/amle.2005.17268566 | [CR] |

---

## 3. "MVE" in the rubric: unresolved

The rubric lists "MDA, MVE, motivation theory". **No gamification framework abbreviated "MVE" could be found.** Plausible candidates:

1. **A typo for MDE** (Mechanics–Dynamics–Emotions), the business adaptation of MDA: Robson, K., Plangger, K., Kietzmann, J. H., McCarthy, I., & Pitt, L. (2015). Is it all a game? Understanding the principles of gamification. *Business Horizons, 58*(4), 411–420. https://doi.org/10.1016/j.bushor.2015.03.006 **[CR]**.
2. **Other MDA successors:**
   - DDE: Walk, W., Görlich, D., & Barrett, M. (2017). Design, dynamics, experience (DDE): An advancement of the MDA framework for game design. In *Game Dynamics* (pp. 27–45). Springer. https://doi.org/10.1007/978-3-319-53088-8_3 **[CR]**.
   - DPE: Winn, B. M. (2009). The design, play, and experience framework. In *Handbook of Research on Effective Electronic Gaming in Education* (pp. 1010–1024). IGI Global. https://doi.org/10.4018/978-1-59904-808-6.ch058 **[CR]**.
3. **Keller's MVP model** (Motivation, Volition, Performance): Keller, J. M. (2008). An integrative theory of motivation, volition, and performance. *Technology, Instruction, Cognition and Learning, 6*, 79–104. Publisher listing; no DOI, issue unconfirmed.
4. "Minimum viable experience" (lean-startup term): no academic source found.

**Action: ask Prof. Schönbohm what MVE refers to.** It is worth 10% of the grade (Theoretical Application).

---

## 4. Measuring change in a 20-minute playtest

The rubric asks "What measurable change do you want to see?" and requires playtest evidence.

| Instrument | Citation | Notes |
|---|---|---|
| Hexad-12 (player types, before play) | Krath, J., Altmeyer, M., Tondello, G. F., & Nacke, L. E. (2023). Hexad-12: Developing and validating a short version of the Gamification User Types Hexad Scale. *Proc. CHI '23*. https://doi.org/10.1145/3544548.3580968 | [CR][A]; 12 items, fits better than the 24-item original |
| Intrinsic Motivation Inventory | Ryan, R. M. (1982). *Journal of Personality and Social Psychology, 43*(3), 450–461. https://doi.org/10.1037/0022-3514.43.3.450; McAuley, E., Duncan, T., & Tammen, V. V. (1989). *Research Quarterly for Exercise and Sport, 60*(1), 48–58. https://doi.org/10.1080/02701367.1989.10607413 | [CR]; use interest/enjoyment and perceived competence subscales |
| Situational Motivation Scale (SIMS) | Guay, F., Vallerand, R. J., & Blanchard, C. (2000). *Motivation and Emotion, 24*(3), 175–213. https://doi.org/10.1023/A:1005614228250 | [CR]; short, suits a post-play questionnaire |
| Basic need satisfaction (BPNSFS) | Chen, B., et al. (2015). Basic psychological need satisfaction, need frustration, and need strength across four cultures. *Motivation and Emotion, 39*(2), 216–236. https://doi.org/10.1007/s11031-014-9450-1 | [CR]; or PENS (Ryan et al., 2006) |
| Gameful experience (GAMEFULQUEST) | Högberg, J., Hamari, J., & Wästlund, E. (2019). Gameful Experience Questionnaire (GAMEFULQUEST). *User Modeling and User-Adapted Interaction, 29*(3), 619–660. https://doi.org/10.1007/s11257-019-09223-w | [CR][A] |
| Gameful experience (GAMEX) | Eppmann, R., Bekk, M., & Klein, K. (2018). Gameful experience in gamification: Construction and validation of a gameful experience scale [GAMEX]. *Journal of Interactive Marketing, 43*, 98–115. https://doi.org/10.1016/j.intmar.2018.03.002 | [CR] |
| Player Experience Inventory (PXI) | Vanden Abeele, V., Spiel, K., Nacke, L., Johnson, D., & Gerling, K. (2020). *International Journal of Human-Computer Studies, 135*, 102370. https://doi.org/10.1016/j.ijhcs.2019.102370 | [CR][A] |
| Game Experience Questionnaire (avoid or caveat) | IJsselsteijn, W. A., de Kort, Y. A. W., & Poels, K. (2013). *The Game Experience Questionnaire*. Technische Universiteit Eindhoven. | **Technical report.** Law, Brühlmann & Mekler (2018, *CHI PLAY '18*, https://doi.org/10.1145/3242671.3242683) found no support for its 7-factor structure. |

**Suggested playtest design:** Hexad-12 before play → the concept's target outcome measured before *and* after play → SIMS or IMI plus BPNSFS after play. With a small class sample, report descriptive statistics and effect sizes, not significance tests.

---

## 5. Concept-specific evidence

Verification tags in this section: **[CR]** DOI resolved on Crossref with matching metadata; **[A]** finding checked against the abstract; **[OA]** OpenAlex record looked up by DOI (OpenAlex had two wrong venues that were corrected from Crossref, so re-open every [OA] DOI at doi.org once before submitting); **[OJ]** checked against the Official Journal of the EU text; **[ISBN]**/**[CAT]** book checked in a library catalogue; **[WEB]** checked on an official or publisher page. In 5.1 and 5.2, findings come from the abstracts unless stated otherwise.

### Applies to Concepts 3–5

- Morschheuser, B., Hamari, J., & Maedche, A. (2019). Cooperation or competition – When do people contribute more? A field experiment on gamification of crowdsourcing. *International Journal of Human-Computer Studies, 127*, 7–24. https://doi.org/10.1016/j.ijhcs.2018.10.001 **[CR][A]**. Competition *between teams* produced more enjoyment and participation than individual competition or pure cooperation. Supports team-vs-team formats.
- Sitzmann (2011), section 1: simulation games work best as a supplement to instruction. Present each game as part of a session with a debrief, not as a standalone tool.

### 5.1 Concept 1: *The Unwritten Rules*

**The original games and how they were evaluated**
- Thiagarajan, S., & Steinwachs, B. (1990). *Barnga: A simulation game on cultural clashes*. Intercultural Press. **[CAT], game kit, not peer-reviewed.** ISBN 1-877864-04-8. The direct precedent.
- Shirts, R. G. (1977). *BaFá BaFá: A cross-cultural simulation*. Simile II. **[CAT], commercial game.**
- Fowler, S. M., & Pusch, M. D. (2010). Intercultural simulation games: A review (of the United States and beyond). *Simulation & Gaming, 41*(1), 94–115. https://doi.org/10.1177/1046878109352204 **[CR]**. Descriptive review of the genre; useful for positioning.
- Bruschke, J. C., Gartner, C., & Seiter, J. S. (1993). Student ethnocentrism, dogmatism, and motivation: A study of BAFA BAFA. *Simulation & Gaming, 24*(1), 9–20. https://doi.org/10.1177/1046878193241003 **[CR]**. **Counter-evidence:** raised motivation but *increased* ethnocentrism vs. classes without it. Simulations can backfire.
- Gannon, M. J., & Poon, J. M. L. (1997). Effects of alternative instructional approaches on cross-cultural training outcomes. *International Journal of Intercultural Relations, 21*(4), 429–446. https://doi.org/10.1016/S0147-1767(96)00035-1 **[CR]** (finding from indexed summaries). N = 105 randomised: the experiential condition (BaFá BaFá) gave **no more** awareness than video conditions, but better reactions.
- Earley, P. C. (1987). Intercultural training for managers: A comparison of documentary and interpersonal methods. *Academy of Management Journal, 30*(4), 685–698. https://doi.org/10.5465/256155 **[CR]**. Documentary and interpersonal training had **additive** benefits: combine experience with explanation.
- **Heidemann, C., & Søndergaard, M. (2023). Systematic cross-cultural management education: A quasi-experimental analysis of guided experiential learning during intercultural simulations. *Cross Cultural & Strategic Management, 30*(2), 413–439. https://doi.org/10.1108/CCSM-01-2022-0007 [CR].** Two quasi-experiments (N = 152, N = 190): **artificial-culture simulations** significantly improved behavioural adaptation, and prior lecture teaching *enhanced* it. Strongest recent support.
- Bücker, J. J. L. E., & Korzilius, H. (2015). Developing cultural intelligence: Assessing the effect of the Ecotonos cultural simulation game for international business students. *The International Journal of Human Resource Management, 26*(15), 1995–2014. https://doi.org/10.1080/09585192.2015.1041759 **[CR]**. Raised metacognitive, motivational and behavioural CQ, but not communication effectiveness.
- Hofhuis, J., Schilderman, M. F., & Verdooren, A. (2020). Multicultural personality and effectiveness in an intercultural training simulation. *International Journal of Psychology, 55*(5), 812–821. https://doi.org/10.1002/ijop.12647 **[CR]**. In Barnga, stress and proactive communication mediated performance. Some players will find it stressful.
- Hofstede, G. J., de Caluwé, L., & Peters, V. (2010). Why simulation games work—In search of the active substance: A synthesis. *Simulation & Gaming, 41*(6), 824–843. https://doi.org/10.1177/1046878110375596 **[OA]**. Games activate players' *own* hidden cultural rules, producing either memorable learning or frustration; facilitation and debriefing need skill.
- Jamieson, P., Grace, L., Mizuno, N., Bell, C., & Davis, D. R. (2016). A simple multi-player video game framework for experimenting and teaching cultural understanding. In *Proceedings of the 20th International Academic Mindtrek Conference* (pp. 422–425). ACM. https://doi.org/10.1145/2994310.2994331 **[CR]**. Digital Barnga-style framework; **no learning-outcome data**.
- Maekawa, Y., Yamaguchi, T., & Takadama, K. (2021). Analyzing early stage of forming a consensus … in Online-Barnga. In *Human Interface and the Management of Information* (LNCS, pp. 269–285). Springer. https://doi.org/10.1007/978-3-030-78361-7_20 **[CR]**. Take the full title and editors from the DOI record. HCI work, not a learning evaluation.
- **Morewedge, C. K., Yoon, H., Scopelliti, I., Symborski, C. W., Korris, J. H., & Kassam, K. S. (2015). Debiasing decisions: Improved decision making with a single training intervention. *Policy Insights from the Behavioral and Brain Sciences, 2*(1), 129–140. https://doi.org/10.1177/2372732215600886 [CR].** A **single game session** reduced biases including the **fundamental attribution error** (≥ 31.9% immediately, ≥ 23.6% two months later); games beat videos.

**Cross-cultural training and cultural intelligence (CQ)**
- Black, J. S., & Mendenhall, M. (1990). Cross-cultural training effectiveness: A review and a theoretical framework for future research. *Academy of Management Review, 15*(1), 113–136. https://doi.org/10.5465/amr.1990.11591834 **[CR]**. Social learning theory basis; evidence base methodologically weak.
- Kealey, D. J., & Protheroe, D. R. (1996). The effectiveness of cross-cultural training for expatriates. *International Journal of Intercultural Relations, 20*(2), 141–165. https://doi.org/10.1016/0147-1767(96)00001-6 **[OA]**. Critical of evidence rigour.
- Morris, M. A., & Robie, C. (2001). A meta-analysis of the effects of cross-cultural training on expatriate performance and adjustment. *International Journal of Training and Development, 5*(2), 112–125. https://doi.org/10.1111/1468-2419.00126 **[OA]**. Performance r = .26, adjustment r = .13: real but modest.
- Littrell, L. N., Salas, E., Hess, K. P., Paley, M., & Riedel, S. (2006). Expatriate preparation: A critical analysis of 25 years of cross-cultural training research. *Human Resource Development Review, 5*(3), 355–388. https://doi.org/10.1177/1534484306290106 **[OA]**. Training effective; moderators and methods under-studied.
- Earley, P. C., & Ang, S. (2003). *Cultural intelligence: Individual interactions across cultures*. Stanford University Press. **[CAT], scholarly book.**
- Ang, S., Van Dyne, L., Koh, C., Ng, K. Y., Templer, K. J., Tay, C., & Chandrasekar, N. A. (2007). Cultural intelligence: Its measurement and effects on cultural judgment and decision making, cultural adaptation and task performance. *Management and Organization Review, 3*(3), 335–371. https://doi.org/10.1111/j.1740-8784.2007.00082.x **[CR]**. The CQ Scale (CQS), a ready-made pre/post instrument.
- Eisenberg, J., Lee, H.-J., Brück, F., Brenner, B., Claes, M.-T., Mironski, J., & Bell, R. (2013). Can business schools make students culturally competent? *Academy of Management Learning & Education, 12*(4), 603–621. https://doi.org/10.5465/amle.2012.0022 **[CR]**. Courses raised mostly metacognitive and cognitive CQ, less motivational and behavioural CQ: the "knowledge without behaviour" gap.
- Rehg, M. T., Gundlach, M. J., & Grigorian, R. A. (2012). Examining the influence of cross-cultural training on cultural intelligence and specific self-efficacy. *Cross Cultural Management, 19*(2), 215–232. https://doi.org/10.1108/13527601211219892 **[OA]**. Lecture training raised cognitive and behavioural CQ, so lectures are not useless.
- Schlaegel, C., Richter, N. F., & Taras, V. (2021). Cultural intelligence and work-related outcomes: A meta-analytic examination of joint effects and incremental predictive validity. *Journal of World Business, 56*(4), Article 101209. https://doi.org/10.1016/j.jwb.2021.101209 **[OA]**. 70 studies: CQ predicts outcomes beyond personality.
- Fischer, R. (2011). Cross-cultural training effects on cultural essentialism beliefs and cultural intelligence. *International Journal of Intercultural Relations, 35*(6), 767–775. https://doi.org/10.1016/j.ijintrel.2011.08.005 **[CR] metadata only; finding unverified.** Summaries contradict each other. Read the full text before citing it for any direction of effect.

**Cultural diversity and team performance**
- Stahl, G. K., Maznevski, M. L., Voigt, A., & Jonsen, K. (2010). Unraveling the effects of cultural diversity in teams: A meta-analysis of research on multicultural work groups. *Journal of International Business Studies, 41*(4), 690–709. https://doi.org/10.1057/jibs.2009.85 **[CR]**. 108 studies, 10,632 teams: process **losses** (task conflict, lower integration) **and gains** (creativity, satisfaction).
- Stahl, G. K., & Maznevski, M. L. (2021). Unraveling the effects of cultural diversity in teams: A retrospective of research on multicultural work groups and an agenda for future research. *Journal of International Business Studies, 52*(1), 4–22. https://doi.org/10.1057/s41267-020-00389-9 **[CR]**.
- Kirkman, B. L., Cordery, J. L., Mathieu, J., Rosen, B., & Kukenberger, M. (2013). Global organizational communities of practice [take the full title from the DOI record]. *Human Relations, 66*(3), 333–362. https://doi.org/10.1177/0018726712464076 **[OA]**. Nationality diversity and performance are U-shaped; **psychological safety** makes the link more positive.
- Edmondson (1999), see 5.3: source scale for a psychological-safety pulse KPI.

**Attribution error and how to measure it**
- Ross, L. (1977). The intuitive psychologist and his shortcomings: Distortions in the attribution process. In L. Berkowitz (Ed.), *Advances in experimental social psychology* (Vol. 10, pp. 173–220). Academic Press. https://doi.org/10.1016/S0065-2601(08)60357-3 **[CR]**. Names the fundamental attribution error.
- Pettigrew, T. F. (1979). The ultimate attribution error: Extending Allport's cognitive analysis of prejudice. *Personality and Social Psychology Bulletin, 5*(4), 461–476. https://doi.org/10.1177/014616727900500407 **[CR]**. Group-level version; fits "they're rude" better than the plain FAE.
- Fiedler, F. E., Mitchell, T., & Triandis, H. C. (1971). The culture assimilator: An approach to cross-cultural training. *Journal of Applied Psychology, 55*(2), 95–102. https://doi.org/10.1037/h0030704 **[CR]**.
- Mitchell, T. R., Dossett, D. L., Fiedler, F. E., & Triandis, H. C. (1972). Culture training: Validation evidence for the culture assimilator. *International Journal of Psychology, 7*(2), 97–104. https://doi.org/10.1080/00207597208246703 **[OA]**. Improved adjustment and relations in mixed-culture groups.
- Bhawuk, D. P. S. (2001). Evolution of culture assimilators: Toward theory-based assimilators. *International Journal of Intercultural Relations, 25*(2), 141–163. https://doi.org/10.1016/S0147-1767(00)00048-1 **[OA]**. Cite this for **isomorphic attributions** (Triandis's 1975 chapter was not verified).
- Morris, M. W., & Peng, K. (1994). Culture and cause: American and Chinese attributions for social and physical events. *Journal of Personality and Social Psychology, 67*(6), 949–971. https://doi.org/10.1037/0022-3514.67.6.949 **[CR]**. Dispositional attribution varies by culture, so classmates start from different baselines.
- **Malle, B. F. (2006). The actor-observer asymmetry in attribution: A (surprising) meta-analysis. *Psychological Bulletin, 132*(6), 895–919. https://doi.org/10.1037/0033-2909.132.6.895 [OA].** 173 studies, overall d ≈ 0, but the asymmetry *does* appear for **negative events** and **free-response coding**, which is the planned design. Methodological justification for the measure.
- Fletcher, G. J. O., Danilovics, P., Fernandez, G., Peterson, D., & Reeder, G. D. (1986). Attributional complexity: An individual differences measure. *Journal of Personality and Social Psychology, 51*(4), 875–884. https://doi.org/10.1037/0022-3514.51.4.875 **[OA]**. Trait scale; use as a control variable, not a pre/post outcome.
- Rockstuhl, T., Ang, S., Ng, K.-Y., Lievens, F., & Van Dyne, L. (2015). Putting judging situations into situational judgment tests: Evidence from intercultural multimedia SJTs. *Journal of Applied Psychology, 100*(2), 464–480. https://doi.org/10.1037/a0038098 **[CR]**. Situation interpretation can be measured validly; closest validated relative of "why did your teammate do X?".

**Team charters, launches and norms**
- Mathieu, J. E., & Rapp, T. L. (2009). Laying the foundation for successful team performance trajectories: The roles of team charters and performance strategies. *Journal of Applied Psychology, 94*(1), 90–103. https://doi.org/10.1037/a0013257 **[OA]**. 32 MBA teams: best sustained performance when both **charter quality** and strategy quality were high.
- Courtright, S. H., McCormick, B. W., Mistry, S., & Wang, J. (2017). Quality charters or quality members? A control theory perspective on team charters and team performance. *Journal of Applied Psychology, 102*(10), 1462–1470. https://doi.org/10.1037/apl0000229 **[OA]**. 239 student teams: charter quality works through task cohesion, mainly for teams low in conscientiousness.
- Egeland, T., Schei, V., & Tjølsen, Ø. A. (2017). Expecting the unexpected: Using team charters to handle disruptions and facilitate team performance. *Group Dynamics: Theory, Research, and Practice, 21*(1), 53–59. https://doi.org/10.1037/gdn0000059 **[CR]**. First author often cited as Sverdrup, T. E.; check the PDF byline. Charters helped teams handle disruptions.
- Gersick, C. J. G. (1988). Time and transition in work teams. *Academy of Management Journal, 31*(1), 9–41. https://doi.org/10.5465/256496 **[OA]**. The first meeting sets a framework that lasts until the midpoint, so a launch-time charter is well timed.
- Hackman, J. R., & Wageman, R. (2005). A theory of team coaching. *Academy of Management Review, 30*(2), 269–287. https://doi.org/10.5465/amr.2005.16387885 **[CR]**. Book alternative: Hackman, J. R. (2002). *Leading teams*. Harvard Business School Press. **[CAT]**.
- Feldman, D. C. (1984). The development and enforcement of group norms. *Academy of Management Review, 9*(1), 47–53. https://doi.org/10.5465/amr.1984.4277934 **[CR]**. Explicit statements and early "primacy" events shape norms. **Academic basis for the norm dimensions that doesn't depend on Meyer.**

**Culture frameworks and their critiques**
- Hall, E. T. (1976). *Beyond culture*. Anchor Press/Doubleday. **[CAT], book.**
- Cardon, P. W. (2008). A critique of Hall's contexting model: A meta-analysis of literature on intercultural business and technical communication. *Journal of Business and Technical Communication, 22*(4), 399–428. https://doi.org/10.1177/1050651908320361 **[CR]**. 224 articles: few propositions tested, and those tested most often fail, **especially on directness**, the game's core rule type.
- Kittler, M. G., Rygl, D., & Mackinnon, A. (2011). Beyond culture or beyond control? Reviewing the use of Hall's high-/low-context concept. *International Journal of Cross Cultural Management, 11*(1), 63–82. https://doi.org/10.1177/1470595811398797 **[OA]**. Country rankings "flawed or, at best, very limited".
- Hofstede, G. (2001). *Culture's consequences* (2nd ed.). Sage. **[CAT], book.**
- McSweeney (2002): see section 7.
- Taras, V., Kirkman, B. L., & Steel, P. (2010). Examining the impact of *Culture's consequences*: A three-decade, multilevel, meta-analytic review of Hofstede's cultural value dimensions. *Journal of Applied Psychology, 95*(3), 405–439. https://doi.org/10.1037/a0018938 **[OA]**. 598 studies, ρ = .18: dimensions predict outcomes, modestly. Balances McSweeney.
- Taras, V., Steel, P., & Kirkman, B. L. (2016). Does country equate with culture? Beyond geography in the search for cultural boundaries. *Management International Review, 56*(4), 455–487. https://doi.org/10.1007/s11575-016-0283-x **[CR]**. Most variation in work values lies *within* countries. **Justifies fictional, nationality-free rules.**
- Meyer, E. (2014). *The culture map*. PublicAffairs. **[CAT], trade book.**

**Prediction phase and live voting**
- Ross, L., Greene, D., & House, P. (1977). The "false consensus effect": An egocentric bias in social perception and attribution processes. *Journal of Experimental Social Psychology, 13*(3), 279–301. https://doi.org/10.1016/0022-1031(77)90049-X **[CR]**. Theory behind "predict the room split".
- Prentice, D. A., & Miller, D. T. (1993). Pluralistic ignorance and alcohol use on campus. *Journal of Personality and Social Psychology, 64*(2), 243–256. https://doi.org/10.1037/0022-3514.64.2.243 **[CR]**. People misperceive group norms; an anonymous reveal can correct them.
- Hunsu, N. J., Adesope, O., & Bayly, D. J. (2016). A meta-analysis of the effects of audience response systems (clicker-based technologies) on cognition and affect. *Computers & Education, 94*, 102–119. https://doi.org/10.1016/j.compedu.2015.11.013 **[CR]**. Small cognitive, near-medium non-cognitive effects (numbers not retrieved).
- Wang, A. I., & Tahir, R. (2020). The effect of using Kahoot! for learning – A literature review. *Computers & Education, 149*, Article 103818. https://doi.org/10.1016/j.compedu.2020.103818 **[OA]**. 93 studies, mostly positive; **speed-based scoring reduces reflection.**

**Verdict: Concept 1**

| Criterion | Rating | Why |
|---|---|---|
| Business problem documented | **Moderate** | Diversity process losses are documented (Stahl et al., 2010), but so are gains. "Teams lose months" has no source. |
| Mechanism produces learning | **Moderate** | Artificial-culture simulations improve adaptation and CQ (Heidemann & Søndergaard, 2023; Bücker & Korzilius, 2015); one game session reduced the FAE (Morewedge et al., 2015). But experiential methods don't clearly beat lectures on learning, only on reactions (Gannon & Poon, 1997); the best results come from combining them (Earley, 1987). Charter evidence covers *quality*, in student teams. |
| Novelty | **Clear gap** | No study pairs a hidden-rules simulation with a binding team charter; none measures attribution shift as a Barnga outcome; digital Barnga has no learning evaluations. |
| Risks | | Backfire on ethnocentrism (Bruschke et al., 1993); frustration (Hofstede et al., 2010); Hall/Meyer dimensions invite stereotyping; FAE varies by culture; demand effects in the pre/post question. |

### 5.2 Concept 2: *First Week in the Wild*

**Onboarding and socialisation**
- **Bauer, T. N., Bodner, T., Erdogan, B., Truxillo, D. M., & Tucker, J. S. (2007). Newcomer adjustment during organizational socialization: A meta-analytic review of antecedents, outcomes, and methods. *Journal of Applied Psychology, 92*(3), 707–721. https://doi.org/10.1037/0021-9010.92.3.707 [OA].** 70 samples: **role clarity, self-efficacy and social acceptance** mediate the effects of socialisation on satisfaction, commitment, performance and turnover. Use these three as KPIs.
- Bauer, T. N. (2010). *Onboarding new employees: Maximizing success*. SHRM Foundation. **Existence verified via SHRM; practitioner report, not peer-reviewed.** The widely quoted "58% more likely to stay" figure comes from a vendor, not from Bauer. Don't attribute it to her.
- Bauer, T. N., Erdogan, B., Caughlin, D., Ellis, A. M., & Kurkoski, J. (2021). Jump-starting the socialization experience: The longitudinal role of day 1 newcomer resources on adjustment. *Journal of Management, 47*(8), 2226–2261. https://doi.org/10.1177/0149206320962835 **[CR]**. 985 hires: **meeting one's manager on Day 1** predicted early social acceptance.
- Cable, D. M., Gino, F., & Staats, B. R. (2013). Breaking them in or eliciting their best? Reframing socialization around newcomers' authentic self-expression. *Administrative Science Quarterly, 58*(1), 1–36. https://doi.org/10.1177/0001839213477098 **[CR]**. Identity-focused onboarding improved six-month retention and customer satisfaction.
- Morrison, E. W. (1993a). Newcomer information seeking: Exploring types, modes, sources, and outcomes. *Academy of Management Journal, 36*(3), 557–589. https://doi.org/10.5465/256592 **[OA]**.
- Morrison, E. W. (1993b). Longitudinal study of the effects of information seeking on newcomer socialization. *Journal of Applied Psychology, 78*(2), 173–183. https://doi.org/10.1037/0021-9010.78.2.173 **[OA]**. Information seeking predicted task mastery, role clarity, cultural knowledge and social integration.
- Morrison, E. W. (2002). Newcomers' relationships: The role of social network ties during socialization. *Academy of Management Journal, 45*(6), 1149–1160. https://doi.org/10.5465/3069430 **[OA]**. Network size and range predicted learning; supports a cross-team-contacts KPI.
- Saks, A. M., & Ashforth, B. E. (1997). Organizational socialization: Making sense of the past and present as a prologue for the future. *Journal of Vocational Behavior, 51*(2), 234–279. https://doi.org/10.1006/jvbe.1997.1614 **[OA]**. Review.
- Saks, A. M., Uggerslev, K. L., & Fassina, N. E. (2007). Socialization tactics and newcomer adjustment: A meta-analytic review and test of a model. *Journal of Vocational Behavior, 70*(3), 413–446. https://doi.org/10.1016/j.jvb.2006.12.004 **[CR] metadata only.** Cite only for scope.
- Klein, H. J., & Polin, B. (2012). Are organizations on board with best practices onboarding? In C. R. Wanberg (Ed.), *The Oxford handbook of organizational socialization*. Oxford University Press. https://doi.org/10.1093/oxfordhb/9780199763672.013.0014 **[CR]**, book chapter; pages unverified.
- Klein, H. J., Polin, B., & Sutton, K. L. (2015). Specific onboarding practices for the socialization of new employees. *International Journal of Selection and Assessment, 23*(3), 263–283. https://doi.org/10.1111/ijsa.12113 **[OA]**. Tests the Inform–Welcome–Guide framework (10 organisations, N = 373).
- Rodeghero, P., Zimmermann, T., Houck, B., & Ford, D. (2021). Please turn your cameras on: Remote onboarding of software developers during a pandemic. In *Proceedings of ICSE-SEIP 2021* (pp. 41–50). IEEE. https://doi.org/10.1109/ICSE-SEIP52600.2021.00013 **[OA]**. 267 Microsoft hires: building social connection was the main remote-onboarding challenge.

**Transactive memory ("who knows what")**
- Wegner, D. M. (1987). Transactive memory: A contemporary analysis of the group mind. In B. Mullen & G. R. Goethals (Eds.), *Theories of group behavior* (pp. 185–208). Springer. https://doi.org/10.1007/978-1-4612-4634-3_9 **[CR]**.
- Lewis, K. (2003). Measuring transactive memory systems in the field: Scale development and validation. *Journal of Applied Psychology, 88*(4), 587–604. https://doi.org/10.1037/0021-9010.88.4.587 **[CR]**. 15-item scale (specialisation, credibility, coordination).
- DeChurch, L. A., & Mesmer-Magnus, J. R. (2010). The cognitive underpinnings of effective teamwork: A meta-analysis. *Journal of Applied Psychology, 95*(1), 32–53. https://doi.org/10.1037/a0017328 **[CR]**. Team cognition predicts performance beyond behaviour and motivation.
- Bachrach, D. G., Lewis, K., Kim, Y., Patel, P. C., Campion, M. C., & Thatcher, S. M. B. (2019). Transactive memory systems in context: A meta-analytic examination of contextual factors in transactive memory systems development and team performance. *Journal of Applied Psychology, 104*(3), 464–493. https://doi.org/10.1037/apl0000329 **[CR]**. 76 studies; the link is stronger in high power-distance, collectivist cultures.
- Liang, D. W., Moreland, R. L., & Argote, L. (1995). Group versus individual training and group performance: The mediating role of transactive memory. *Personality and Social Psychology Bulletin, 21*(4), 384–393. https://doi.org/10.1177/0146167295214009 **[OA]**. Training together builds transactive memory; supports playing in pairs.
- Moreland, R. L., & Myaskovsky, L. (2000). Exploring the performance benefits of group training: Transactive memory or improved communication? *Organizational Behavior and Human Decision Processes, 82*(1), 117–133. https://doi.org/10.1006/obhd.2000.2891 **[OA]**. Information about each other's skills alone was enough, which cuts against chats being the only route.
- Lewis, K., Belliveau, M., Herndon, B., & Keller, J. (2007). Group cognition, membership change, and performance: Investigating the benefits and detriments of collective knowledge. *Organizational Behavior and Human Decision Processes, 103*(2), 159–178. https://doi.org/10.1016/j.obhdp.2007.01.005 **[CR]**. After membership change, veterans keep relying on the old system. Transactive memory is team-specific.

**Game-based onboarding, investigation games and safe failure**
- Heimburger, L., Buchweitz, L., Gouveia, R., & Korn, O. (2020). Gamifying onboarding: How to increase both engagement and integration of new employees. In R. H. M. Goossens & A. Murata (Eds.), *Advances in social and occupational ergonomics* (pp. 3–14). Springer. https://doi.org/10.1007/978-3-030-20145-6_1 **[CR]**. N = 98, mostly students: preferred the gamified app; no adjustment outcomes measured.
- Palmquist, A. (2023). Design elements of conflict: A design study of a gamified smartphone application for employee onboarding. *Technology, Knowledge and Learning, 28*(3), 1133–1173. https://doi.org/10.1007/s10758-023-09657-7 **[OA]**. 60-week ethnography; confirms "little research" on gamified onboarding.
- Veldkamp, A., van de Grint, L., Knippels, M.-C. P. J., & van Joolingen, W. R. (2020). Escape education: A systematic review on escape rooms in education. *Educational Research Review, 31*, Article 100364. https://doi.org/10.1016/j.edurev.2020.100364 **[OA]**. Gap between perceived and actual learning.
- Taraldsen, L. H., Haara, F. O., Lysne, M. S., Jensen, P. R., & Jenssen, E. S. (2022). A review on use of escape rooms in education – touching the void. *Education Inquiry, 13*(2), 169–184. https://doi.org/10.1080/20004508.2020.1860284 **[CR]**. Mostly descriptive research.
- Alfieri, L., Brooks, P. J., Aldrich, N. J., & Tenenbaum, H. R. (2011). Does discovery-based instruction enhance learning? *Journal of Educational Psychology, 103*(1), 1–18. https://doi.org/10.1037/a0021017 **[CR]**. Unassisted discovery d = −0.38 vs. explicit instruction; **guided** discovery d = 0.30.
- Sinha, T., & Kapur, M. (2021). When problem solving followed by instruction works: Evidence for productive failure. *Review of Educational Research, 91*(5), 761–798. https://doi.org/10.3102/00346543211019105 **[OA]**. Problem solving *before* instruction g = 0.36; supports "investigate first, debrief after".
- Keith & Frese (2008), see 5.3: errors must be explicitly encouraged and framed as learning.

**Situational judgement tests (SJTs) as the measure**
- McDaniel, M. A., Morgeson, F. P., Finnegan, E. B., Campion, M. A., & Braverman, E. P. (2001). Use of situational judgment tests to predict job performance: A clarification of the literature. *Journal of Applied Psychology, 86*(4), 730–740. https://doi.org/10.1037/0021-9010.86.4.730 **[CR]**. ρ = .34.
- McDaniel, M. A., Hartman, N. S., Whetzel, D. L., & Grubb, W. L., III. (2007). Situational judgment tests, response instructions, and validity: A meta-analysis. *Personnel Psychology, 60*(1), 63–91. https://doi.org/10.1111/j.1744-6570.2007.00065.x **[OA]**. "Knowledge" and "would do" instructions measure different constructs.
- Christian, M. S., Edwards, B. D., & Bradley, J. C. (2010). Situational judgment tests: Constructs assessed and a meta-analysis of their criterion-related validities. *Personnel Psychology, 63*(1), 83–117. https://doi.org/10.1111/j.1744-6570.2009.01163.x **[OA]**. Teamwork SJTs relatively valid; video beats paper.
- Lievens, F., & Motowidlo, S. J. (2016). Situational judgment tests: From measures of situational judgment to measures of general domain knowledge. *Industrial and Organizational Psychology, 9*(1), 3–22. https://doi.org/10.1017/iop.2015.71 **[CR]**. SJTs measure trainable domain knowledge, so they're defensible as a learning measure.

**Verdict: Concept 2**

| Criterion | Rating | Why |
|---|---|---|
| Business problem documented | **Strong** | Bauer et al. (2007), Morrison (1993b, 2002), Rodeghero et al. (2021). |
| Mechanism produces learning | **Weak–moderate** | Generic simulation evidence is good, and error management and productive failure support safe-to-fail design, but there is **no controlled study of game-based onboarding** measuring adjustment; transactive memory evidence comes from lab tasks. |
| Novelty | **Large gap** | Could be framed as a simulation that trains **expertise-locating and information-seeking strategies**, measured with SJTs and Bauer's adjustment scales. |
| Risks | | "Who knows what" in a *fictional* company doesn't transfer (Lewis et al., 2007), only the strategy does; unguided false leads hurt learning (Alfieri et al., 2011); perceived ≠ actual learning (Veldkamp et al., 2020); heaviest content load. |

### 5.3 Concept 3: *Incident Zero*

**Psychological safety**
- Edmondson, A. (1999). Psychological safety and learning behavior in work teams. *Administrative Science Quarterly, 44*(2), 350–383. https://doi.org/10.2307/2666999 **[CR][A]**. In 51 teams, psychological safety → learning behaviour → performance. Core theory anchor.
- Edmondson, A. C. (1996). Learning from mistakes is easier said than done: Group and organizational influences on the detection and correction of human error. *The Journal of Applied Behavioral Science, 32*(1), 5–28. https://doi.org/10.1177/0021886396321001 **[CR][A]**. Units differed in how likely errors were to be *detected and learned from*, not just how often they happened. Empirical basis for the Blame Trap.
- Frazier, M. L., Fainshmidt, S., Klinger, R. L., Pezeshkan, A., & Vracheva, V. (2017). Psychological safety: A meta-analytic review and extension. *Personnel Psychology, 70*(1), 113–165. https://doi.org/10.1111/peps.12183 **[CR][A]**. 136 samples, 22,000+ individuals, ~5,000 groups. Predicts task performance and citizenship behaviour beyond leader relations and engagement. Take ρ values from the paper's tables before quoting.
- Edmondson, A. C., & Lei, Z. (2014). Psychological safety: The history, renaissance, and future of an interpersonal construct. *Annual Review of Organizational Psychology and Organizational Behavior, 1*, 23–43. https://doi.org/10.1146/annurev-orgpsych-031413-091305 **[CR][A]**. Review.
- Edmondson, A. C., & Bransby, D. P. (2023). Psychological safety comes of age: Observed themes in an established literature. *Annual Review of Organizational Psychology and Organizational Behavior, 10*, 55–78. https://doi.org/10.1146/annurev-orgpsych-120920-055217 **[CR][A]**. Recent review.
- O'Donovan, R., & McAuliffe, E. (2020). A systematic review exploring the content and outcomes of interventions to improve psychological safety, speaking up and voice behaviour. *BMC Health Services Research, 20*, Article 101. https://doi.org/10.1186/s12913-020-4931-2 **[CR][A]**. 14 interventions, including simulation, with mixed results. **Counter-evidence: don't claim the game builds psychological safety.**

**Error management and disclosure**
- Keith, N., & Frese, M. (2008). Effectiveness of error management training: A meta-analysis. *Journal of Applied Psychology, 93*(1), 59–69. https://doi.org/10.1037/0021-9010.93.1.59 **[CR][A]**. Overall d = 0.44 (24 studies, N = 2,183); post-training transfer d = 0.56; adaptive transfer d = 0.80. **Strongest evidence that safe failure works.**
- van Dyck, C., Frese, M., Baer, M., & Sonnentag, S. (2005). Organizational error management culture and its impact on performance: A two-study replication. *Journal of Applied Psychology, 90*(6), 1228–1240. https://doi.org/10.1037/0021-9010.90.6.1228 **[CR][A]**. Error management culture correlated with goal achievement and profitability in 65 Dutch and 47 German organisations (cross-sectional).
- Frese, M., & Keith, N. (2015). Action errors, error management, and learning in organizations. *Annual Review of Psychology, 66*, 661–687. https://doi.org/10.1146/annurev-psych-010814-015205 **[CR][A]**. Learning from errors depends on an error-accepting mindset.
- Klamar, A., Horvath, D., Frese, M., & Keith, N. (2024). Different approaches to learning from errors: Comparing the effectiveness of high reliability and error management approaches. *Safety Science, 177*, Article 106578. https://doi.org/10.1016/j.ssci.2024.106578 **[CR][A]**. N = 359: both error management and high-reliability training beat error-avoidant training.
- Zhao, B., & Olivera, F. (2006). Error reporting in organizations. *Academy of Management Review, 31*(4), 1012–1030. https://doi.org/10.5465/amr.2006.22528167 **[CR][A]**. Reporting as detection → situation assessment → choice of response. Use it as the design map for the disclosure decision.
- Reason, J. (1997). *Managing the risks of organizational accidents*. Ashgate. **[ISBN], book.** Routledge reissue 2016: https://doi.org/10.4324/9781315543543.
- Dekker, S. (2025). *Restorative just culture: From disciplinary action to meaningful accountability* (4th ed.). CRC Press. https://doi.org/10.1201/9781003531562 **[CR], book.** Current, retitled edition of *Just Culture*.
- Lunney, J., & Lueder, S. (2016). Postmortem culture: Learning from failure. In B. Beyer, C. Jones, J. Petoff, & N. R. Murphy (Eds.), *Site reliability engineering: How Google runs production systems* (Ch. 15). O'Reilly. https://sre.google/sre-book/postmortem-culture/ **[WEB][ISBN], industry.** Blameless postmortems look for contributing causes "without indicting any individual or team".

**Metrics and incentives (private KPIs)**
- Goodhart, C. A. E. (1976). Problems of monetary management: The U.K. experience. In *Papers in monetary economics* (Vol. 1). Reserve Bank of Australia. **[WEB]** (RBA bibliography; conference July 1975). Reprinted in Goodhart, C. A. E. (1984). *Monetary theory and practice* (pp. 91–121). Palgrave Macmillan. https://doi.org/10.1007/978-1-349-17295-5_4 **[CR]**.
- Strathern, M. (1997). 'Improving ratings': Audit in the British University system. *European Review, 5*(3), 305–321. https://doi.org/10.1002/(SICI)1234-981X(199707)5:3<305::AID-EURO184>3.0.CO;2-4 **[CR]**. Source of the popular "when a measure becomes a target…" wording. Check the page number in the PDF before quoting.
- Campbell, D. T. (1979). Assessing the impact of planned social change. *Evaluation and Program Planning, 2*(1), 67–90. https://doi.org/10.1016/0149-7189(79)90048-X **[CR]**. Campbell's law; exact quote not verified.
- Kerr, S. (1975). On the folly of rewarding A, while hoping for B. *Academy of Management Journal, 18*(4), 769–783. https://doi.org/10.5465/255378 **[CR]**.
- Ordóñez, L. D., Schweitzer, M. E., Galinsky, A. D., & Bazerman, M. H. (2009). Goals gone wild: The systematic side effects of overprescribing goal setting. *Academy of Management Perspectives, 23*(1), 6–16. https://doi.org/10.5465/amp.2009.37007999 **[CR][A]**. Narrow focus, distorted risk-taking, unethical behaviour, inhibited learning. Best citation for private KPIs. Debated; see the authors' rejoinder at https://doi.org/10.5465/amp.2009.43479265.

**Interdependence and information sharing (shared meter, role packets)**
- Deutsch, M. (1949). A theory of co-operation and competition. *Human Relations, 2*(2), 129–152. https://doi.org/10.1177/001872674900200204 **[CR]**.
- Johnson, D. W., & Johnson, R. T. (2009). An educational psychology success story: Social interdependence theory and cooperative learning. *Educational Researcher, 38*(5), 365–379. https://doi.org/10.3102/0013189X09339057 **[CR][A]**. 1,200+ studies. Supports the shared meter and "everyone loses" rule.
- Stasser, G., & Titus, W. (1985). Pooling of unshared information in group decision making: Biased information sampling during discussion. *Journal of Personality and Social Psychology, 48*(6), 1467–1478. https://doi.org/10.1037/0022-3514.48.6.1467 **[CR]**.
- Lu, L., Yuan, Y. C., & McLeod, P. L. (2012). Twenty-five years of hidden profiles in group decision making: A meta-analysis. *Personality and Social Psychology Review, 16*(1), 54–75. https://doi.org/10.1177/1088868311417243 **[CR][A]**. 65 studies, 3,189 groups: shared information discussed two SDs more than unique information; hidden-profile groups 8× less likely to find the solution. Supports asymmetric role packets.
- Toma, C., & Butera, F. (2009). Hidden profiles and concealed information: Strategic information sharing and use in group decision making. *Personality and Social Psychology Bulletin, 35*(6), 793–806. https://doi.org/10.1177/0146167209333176 **[CR][A]**. Under competition, members withheld unshared information out of mistrust. Predicts what private KPIs will do, so make it a debrief target.

**Simulation and training**
- Salas, E., DiazGranados, D., Klein, C., Burke, C. S., Stagl, K. C., Goodwin, G. F., & Halpin, S. M. (2008). Does team training improve team performance? A meta-analysis. *Human Factors, 50*(6), 903–933. https://doi.org/10.1518/001872008X375009 **[CR][A]**. 93 effect sizes, 2,650 teams: moderate positive effects on all outcome types.
- McEwan, D., Ruissen, G. R., Eys, M. A., Zumbo, B. D., & Beauchamp, M. R. (2017). The effectiveness of teamwork training on teamwork behaviors and team performance: A systematic review and meta-analysis of controlled interventions. *PLOS ONE, 12*(1), e0169604. https://doi.org/10.1371/journal.pone.0169604 **[CR][A]**. 72 controlled interventions, 8,439 participants: medium effects.
- O'Dea, A., O'Connor, P., & Keogh, I. (2014). A meta-analysis of the effectiveness of crew resource management training in acute care domains. *Postgraduate Medical Journal, 90*(1070), 699–708. https://doi.org/10.1136/postgradmedj-2014-132800 **[CR][A]**. Knowledge d = 1.05, attitudes d = 0.22, behaviour d = 1.25; insufficient evidence for patient outcomes.
- Skryabina, E., Reedy, G., Amlôt, R., Jaye, P., & Riley, P. (2017). What is the value of health emergency preparedness exercises? A scoping review study. *International Journal of Disaster Risk Reduction, 21*, 274–283. https://doi.org/10.1016/j.ijdrr.2016.12.010 **[CR][A]**. 86 studies: exercises improved knowledge, confidence and role understanding and exposed gaps in plans; transfer to real responses "very limited".
- Angafor, G. N., Yevseyeva, I., & He, Y. (2020). Game-based learning: A review of tabletop exercises for cybersecurity incident response training. *Security and Privacy, 3*(6), e126. https://doi.org/10.1002/spy2.126 **[CR][A]**. Mostly descriptive evidence of improved awareness and decision-making.
- Sterman, J. D. (1989). Modeling managerial behavior: Misperceptions of feedback in a dynamic decision making experiment. *Management Science, 35*(3), 321–339. https://doi.org/10.1287/mnsc.35.3.321 **[CR][A]**. Beer Game: sensible local decisions hurt the whole system. Classic management-simulation precedent.
- GDPR Art. 33 **[OJ]** (full reference in 5.5): a personal-data breach must be notified "where feasible, not later than 72 hours" after awareness. A real deadline for the Legal/Comms role.

**Verdict: Concept 3**

| Criterion | Rating | Why |
|---|---|---|
| Business problem documented | **Strong** | Error under-reporting depends on team climate (Edmondson); goal side effects are documented (Ordóñez; Kerr). KPI conflict between departments is argued more than measured (moderate). |
| Mechanism produces learning | **Moderate** | Team training, CRM and error management training have meta-analytic support; tabletop exercises show short-term gains only; psychological-safety interventions are mixed. |
| Novelty | **Clear gap** | No evaluated game found that rewards early self-disclosure while players hold conflicting private KPIs. |
| Risks | | Players will conceal (Toma & Butera); one session won't change climate; real-world disclosure KPIs can be gamed. |

### 5.4 Concept 4: *Pitch Pit*

**Prediction and idea markets**
- Cowgill, B., & Zitzewitz, E. (2015). Corporate prediction markets: Evidence from Google, Ford, and Firm X. *The Review of Economic Studies, 82*(4), 1309–1341. https://doi.org/10.1093/restud/rdv014 **[CR][A]**. Beat expert forecasts (up to 25% lower mean-squared error) despite few traders; optimism bias was the main flaw.
- Wolfers, J., & Zitzewitz, E. (2004). Prediction markets. *Journal of Economic Perspectives, 18*(2), 107–126. https://doi.org/10.1257/0895330041371321 **[CR][A]**. Accurate for well-defined future events.
- Soukhoroukova, A., Spann, M., & Skiera, B. (2012). See section 7. **[CR][A]**. 500+ employees in 17 countries: idea markets are a workable way to collect and filter ideas.
- Blohm, I., Riedl, C., Füller, J., & Leimeister, J. M. (2016). Rate or trade? Identifying winning ideas in open idea sourcing. *Information Systems Research, 27*(1), 27–48. https://doi.org/10.1287/isre.2015.0605 **[CR][A]**. Randomized (N = 120): **a rating scale beat a preference market** on ease of use and decision quality. Counter-evidence.
- Healy, P. J., Linardi, S., Lowery, J. R., & Ledyard, J. O. (2010). Prediction markets: Alternative mechanisms for complex environments with few traders. *Management Science, 56*(11), 1977–1996. https://doi.org/10.1287/mnsc.1100.1226 **[CR][A]**. With few traders, an iterated poll beat a double-auction market.
- Hanson, R., & Oprea, R. (2009). A manipulator can aid prediction market accuracy. *Economica, 76*(302), 304–314. https://doi.org/10.1111/j.1468-0335.2008.00734.x **[CR][A]**. Theory paper.
- Servan-Schreiber, E., Wolfers, J., Pennock, D. M., & Galebach, B. (2004). Prediction markets: Does money matter? *Electronic Markets, 14*(3), 243–251. https://doi.org/10.1080/1019678042000245254 **[CR]** (finding from a secondary abstract mirror; re-check). Play-money and real-money markets about equally accurate, so credits are defensible.
- Salganik, M. J., Dodds, P. S., & Watts, D. J. (2006). Experimental study of inequality and unpredictability in an artificial cultural market. *Science, 311*(5762), 854–856. https://doi.org/10.1126/science.1121066 **[CR][A]**.
- Muchnik, L., Aral, S., & Taylor, S. J. (2013). Social influence bias: A randomized experiment. *Science, 341*(6146), 647–651. https://doi.org/10.1126/science.1240466 **[CR][A]**. Visible prior ratings raised positive ratings by 32% and final ratings by 25%. With Salganik: **visible signals cause herding.**

**Idea management**
- Reitzig, M., & Sorenson, O. (2013). Biases in the selection stage of bottom-up strategy formulation. *Strategic Management Journal, 34*(7), 782–799. https://doi.org/10.1002/smj.2047 **[CR][A]**. Evaluators favour ideas from their own unit. Supports "cannot invest in your own team".
- Criscuolo, P., Dahlander, L., Grohsjean, T., & Salter, A. (2017). Evaluating novelty: The role of panels in the selection of R&D projects. *Academy of Management Journal, 60*(2), 433–460. https://doi.org/10.5465/amj.2014.0861 **[CR][A]**. Panels favour intermediate novelty; heavy workload reduces preference for novel ideas.
- Piezunka, H., & Dahlander, L. (2019). Idea rejected, tie formed: Organizations' feedback on crowdsourced ideas. *Academy of Management Journal, 62*(2), 503–530. https://doi.org/10.5465/amj.2016.0703 **[CR][A]**. 70,159 organisations: explained rejection made first-time contributors more likely to submit again.
- Deichmann, D., & van den Ende, J. (2014). Rising from failure and learning from success: The role of past experience in radical initiative taking. *Organization Science, 25*(3), 670–690. https://doi.org/10.1287/orsc.2013.0870 **[CR][A]**. 1,792 ideas: past failure increased later proposals.
- Gerlach, S., & Brem, A. (2017). Idea management revisited: A review of the literature and guide for implementation. *International Journal of Innovation Studies, 1*(2), 144–161. https://doi.org/10.1016/j.ijis.2017.10.004 **[CR][A]**.
- Terwiesch, C., & Ulrich, K. T. (2009). *Innovation tournaments: Creating and selecting exceptional opportunities*. Harvard Business Press. **[ISBN] 9781422152225, book.**
- Boudreau, K. J., Lacetera, N., & Lakhani, K. R. (2011). Incentives and problem uncertainty in innovation contests: An empirical analysis. *Management Science, 57*(5), 843–863. https://doi.org/10.1287/mnsc.1110.1322 **[CR][A]**. 9,661 contests: more rivals reduced effort, except for highly uncertain problems.
- Patrício, R., Moreira, A. C., & Zurlo, F. (2018). Gamification approaches to the early stage of innovation. *Creativity and Innovation Management, 27*(4), 499–511. https://doi.org/10.1111/caim.12284 **[CR][A]**. Qualitative case comparison.
- Barbosa, B., & Santos, A. F. (2026). The role of gamification in fostering employee involvement in innovation. *European Journal of Innovation Management, 29*(11), 254–274. https://doi.org/10.1108/EJIM-05-2025-0678 **[CR][A]**. Qualitative: built ownership but needed a continuous process and transparent metrics.

**Creativity, constraints and rewards**
- Acar, O. A., Tarakci, M., & van Knippenberg, D. (2019). Creativity and innovation under constraints: A cross-disciplinary integrative review. *Journal of Management, 45*(1), 96–121. https://doi.org/10.1177/0149206318805832 **[CR][A]**. Constraints can help or hurt; findings conflict.
- Baer, M., & Oldham, G. R. (2006). The curvilinear relation between experienced creative time pressure and creativity. *Journal of Applied Psychology, 91*(4), 963–970. https://doi.org/10.1037/0021-9010.91.4.963 **[CR][A]**. Inverted U, only for people high in openness who had support.
- Amabile, T. M., Hennessey, B. A., & Grossman, B. S. (1986). Social influences on creativity: The effects of contracted-for reward. *Journal of Personality and Social Psychology, 50*(1), 14–23. https://doi.org/10.1037/0022-3514.50.1.14 **[CR][A]**. Contracted-for rewards reduced creativity.
- Byron, K., & Khazanchi, S. (2012). Rewards and creative performance: A meta-analytic test of theoretically derived hypotheses. *Psychological Bulletin, 138*(4), 809–830. https://doi.org/10.1037/a0027652 **[CR][A]**. Rewards tied specifically to creativity increased it, especially with feedback and choice.
- Deci et al. (1999) and Cerasoli et al. (2014): see section 2.

**Verdict: Concept 4**

| Criterion | Rating | Why |
|---|---|---|
| Business problem documented | **Moderate** | Biased idea selection and feedback effects are documented; "low portal engagement" itself was not evidenced. |
| Mechanism produces outcome | **Weak–moderate** | Markets work for outcomes that resolve later; for judging ideas, rating scales can beat markets, and a classroom market is thin. |
| Novelty | **Some** | No evaluation found of constraint cards + idea market + shocks in one loop. A playtest could compare hidden vs. visible ticker. |
| Risks | | Herding, optimism bias, thin market; nothing resolves in 20 minutes, so it can become a popularity contest. |

### 5.5 Concept 5: *Shadow AI Dilemma*

**Shadow IT and shadow AI**
- Haag, S., & Eckhardt, A. (2017). Shadow IT. *Business & Information Systems Engineering, 59*(6), 469–473. https://doi.org/10.1007/s12599-017-0497-x **[CR]** (metadata only).
- Kirlappos, I., Parkin, S., & Sasse, M. A. (2014). Learning from "shadow security": Why understanding non-compliant behaviors provides the basis for effective security. *Proceedings 2014 Workshop on Usable Security*. https://doi.org/10.14722/usec.2014.23007 **[CR][A]**. 118 interviews: staff build workarounds to balance productivity and risk; organisations should learn from them.
- Beautement, A., Sasse, M. A., & Wonham, M. (2008). The compliance budget: Managing security behaviour in organisations. In *Proceedings of the 2008 New Security Paradigms Workshop* (pp. 47–58). ACM. https://doi.org/10.1145/1595676.1595684 **[CR][A]**. Employees weigh personal compliance cost against benefit. Theory behind the Hours Saved vs. risk trade-off.
- Silic, M., Silic, D., & Kind-Trüller, K. (2025). From shadow IT to shadow AI—Threats, risks and opportunities for organizations. *Strategic Change*. Advance online publication. https://doi.org/10.1002/jsc.2682 **[CR][A]**. 140 professionals + 10 executive interviews: a "governance drift zone" where policies exist but have little traction; recommends controlled enablement over restriction.
- Petersson, L., Irgang, L., Mauritzon, I., & Holmén, M. (2026). Shadow AI in Swedish health care: Qualitative analysis of physicians' free-text answers. *Journal of Medical Internet Research, 28*, e93484. https://doi.org/10.2196/93484 **[CR][A]**. 357 physicians used unauthorised AI for clinical, administrative and research work.
- Hussain, A., Ehsan, M., & Rauf, A. (2026). Shadow AI usage and ethical AI adoption: The moderating role of chief AI officer governance. *International Journal of Organizational Analysis*. Advance online publication. https://doi.org/10.1108/IJOA-03-2026-6718 **[CR][A]**. 665 respondents, cross-sectional.
- Reif, J. A., Larrick, R. P., & Soll, J. B. (2025). Evidence of a social evaluation penalty for using AI. *PNAS, 122*(19), e2426766122. https://doi.org/10.1073/pnas.2426766122 **[CR][A]**. 4 preregistered experiments (N = 4,439): AI users are judged as less competent and motivated. Explains why use is hidden.
- Humlum, A., & Vestergaard, E. (2025). The unequal adoption of ChatGPT exacerbates existing inequalities among workers. *PNAS, 122*(1), e2414972121. https://doi.org/10.1073/pnas.2414972121 **[CR][A]**. 18,000 workers: employer restrictions and training needs held back use.
- Microsoft & LinkedIn. (2024). *AI at work is here. Now comes the hard part* (2024 Work Trend Index). https://www.microsoft.com/en-us/worklab/work-trend-index/ai-at-work-is-here-now-comes-the-hard-part **[WEB], industry report.** ~31,000 respondents: 75% use AI at work, 78% of users bring their own tools, 52% reluctant to admit using it for important tasks.

**Compliance theory**
- Bulgurcu, B., Cavusoglu, H., & Benbasat, I. (2010). Information security policy compliance: An empirical study of rationality-based beliefs and information security awareness. *MIS Quarterly, 34*(3), 523–548. https://doi.org/10.2307/25750690 **[CR][A]**. Attitude to compliance depends on its benefits, the cost of complying, and the cost of not complying.
- Rogers, R. W. (1975). A protection motivation theory of fear appeals and attitude change. *The Journal of Psychology, 91*(1), 93–114. https://doi.org/10.1080/00223980.1975.9915803 **[CR][A]**.
- Boss, S. R., Galletta, D. F., Lowry, P. B., Moody, G. D., & Polak, P. (2015). What do systems users have to fear? Using fear appeals to engender threats and fear that motivate protective security behaviors. *MIS Quarterly, 39*(4), 837–864. https://doi.org/10.25300/MISQ/2015/39.4.5 **[CR][A]**. Full PMT model predicted actual security behaviour.
- Cram, W. A., D'Arcy, J., & Proudfoot, J. G. (2019). Seeing the forest and the trees: A meta-analysis of the antecedents to information security policy compliance. *MIS Quarterly, 43*(2), 525–553. https://doi.org/10.25300/MISQ/2019/15117 **[CR][A]**. 95 papers; field "plagued by suboptimal theoretical framing".
- Fogg (2009): see section 2. Conceptual, little empirical testing.

**Does security training work?**
- Prümmer, J., van Steen, T., & van den Berg, B. (2024). A systematic review of current cybersecurity training methods. *Computers & Security, 136*, 103585. https://doi.org/10.1016/j.cose.2023.103585 **[CR][A]**. 142 studies: game-based training most common, mostly positive, but mostly simple pre/post designs with small, often non-employee samples.
- Hendrix, M., Al-Sherbaz, A., & Bloom, V. (2016). Game based cyber security training: Are serious games suitable for cyber security training? *International Journal of Serious Games, 3*(1). https://doi.org/10.17083/ijsg.v3i1.107 **[CR][A]**. Positive early results, not enough evidence to conclude.
- Hart, S., Margheri, A., Paci, F., & Sassone, V. (2020). Riskio: A serious game for cyber security awareness and education. *Computers & Security, 95*, 101827. https://doi.org/10.1016/j.cose.2020.101827 **[CR][A]**. Tabletop game where staff play attacker and defender; closest precedent for "Audit!".
- Lain, D., Kostiainen, K., & Čapkun, S. (2022). Phishing in organizations: Findings from a large-scale and long-term study. In *2022 IEEE Symposium on Security and Privacy* (pp. 842–859). https://doi.org/10.1109/SP46214.2022.9833766 **[CR][A]**. 15 months, 14,000+ employees: "gotcha" training after a failed simulation did not help and could increase susceptibility; **collective reporting worked well.**
- Ho, G., Mirian, A., Luo, E., Tong, K., Lee, E., Liu, L., Longhurst, C. A., Dameff, C., Savage, S., & Voelker, G. M. (2025). Understanding the efficacy of phishing training in practice. In *2025 IEEE Symposium on Security and Privacy* (pp. 37–54). https://doi.org/10.1109/SP61157.2025.00076 **[CR][A]**. Randomized, 19,500 employees: annual training not linked to phishing failure; embedded training had extremely small effects.
- Silic & Lowry (2020) and Baxter et al. (2016): see section 1.

**Automation bias and generative AI**
- Parasuraman, R., & Manzey, D. H. (2010). Complacency and bias in human use of automation: An attentional integration. *Human Factors, 52*(3), 381–410. https://doi.org/10.1177/0018720810376055 **[CR][A]**. Automation bias "cannot be prevented by training or instructions". Key counter-evidence.
- Goddard, K., Roudsari, A., & Wyatt, J. C. (2012). Automation bias: A systematic review of frequency, effect mediators, and mitigators. *JAMIA, 19*(1), 121–127. https://doi.org/10.1136/amiajnl-2011-000089 **[CR][A]**. Training and stressing accountability reduced it.
- Buçinca, Z., Malaya, M. B., & Gajos, K. Z. (2021). To trust or to think: Cognitive forcing functions can reduce overreliance on AI in AI-assisted decision-making. *Proceedings of the ACM on Human-Computer Interaction, 5*(CSCW1), 1–21. https://doi.org/10.1145/3449287 **[CR][A]**. N = 199: cognitive forcing reduced overreliance but was liked least.
- Lee, H.-P., Sarkar, A., Tankelevitch, L., Drosos, I., Rintel, S., Banks, R., & Wilson, N. (2025). The impact of generative AI on critical thinking. In *CHI '25* (pp. 1–22). ACM. https://doi.org/10.1145/3706598.3713778 **[CR][A]**. 319 knowledge workers: more confidence in genAI, less critical thinking.
- Dell'Acqua, F., McFowland, E., Mollick, E., Lifshitz, H., Kellogg, K. C., Rajendran, S., Krayer, L., Candelon, F., & Lakhani, K. R. (2026). Navigating the jagged technological frontier. *Organization Science, 37*(2), 403–423. https://doi.org/10.1287/orsc.2025.21838 **[CR][A]**. Inside AI's capabilities: 12.2% more tasks, 25.1% faster; outside: 19% less likely to be correct. Cite this version, not the 2023 working paper.
- Noy, S., & Zhang, W. (2023). Experimental evidence on the productivity effects of generative artificial intelligence. *Science, 381*(6654), 187–192. https://doi.org/10.1126/science.adh2586 **[CR][A]**. Time −40%, quality +18%.
- Brynjolfsson, E., Li, D., & Raymond, L. (2025). Generative AI at work. *Quarterly Journal of Economics, 140*(2), 889–942. https://doi.org/10.1093/qje/qjae044 **[CR][A]**. +15% issues resolved per hour.
- Ji, Z., Lee, N., Frieske, R., Yu, T., Su, D., Xu, Y., Ishii, E., Bang, Y., Madotto, A., & Fung, P. (2023). Survey of hallucination in natural language generation. *ACM Computing Surveys, 55*(12), 1–38. https://doi.org/10.1145/3571730 **[CR][A]**.
- Long, D., & Magerko, B. (2020). What is AI literacy? Competencies and design considerations. In *CHI '20* (pp. 1–16). https://doi.org/10.1145/3313831.3376727 **[CR][A]**. Useful for learning objectives.

**Regulation (primary sources)**
- Regulation (EU) 2024/1689 (Artificial Intelligence Act). *OJ L*, 2024/1689, 12.7.2024. http://data.europa.eu/eli/reg/2024/1689/oj **[OJ]**. Original Art. 4 required "a sufficient level of AI literacy"; applicable from 2 February 2025 (Art. 113(a)).
- **Regulation (EU) 2026/1744 (Digital Omnibus on AI).** *OJ L*, 2026/1744, 24.7.2026. http://data.europa.eu/eli/reg/2026/1744/oj **[OJ]**. In force 27 July 2026; **replaced Art. 4**: providers and deployers now "shall take measures to support the development of AI literacy", without having to "guarantee any specific level of AI literacy of any individual".
- Regulation (EU) 2016/679 (GDPR). *OJ L 119*, 4.5.2016, 1–88. http://data.europa.eu/eli/reg/2016/679/oj **[OJ]**. Relevant: Art. 5, 6, 9 (special categories, e.g. HR/health), 25, 28 (processors), 32, 33 (72-hour breach notice), 35, 44 ff. (transfers), 88 (employment). A GDPR omnibus amendment is reportedly pending but unverified; cite the 2016 text.

**Verdict: Concept 5**

| Criterion | Rating | Why |
|---|---|---|
| Business problem documented | **Moderate–strong** | Peer-reviewed shadow-AI studies exist (2025–26) but are cross-sectional or qualitative; prevalence figures are industry data; regulation verified. |
| Mechanism produces behaviour change | **Weak–moderate** | Awareness and phishing training barely change real behaviour; game-based studies use weak designs. Best-supported levers: cognitive forcing and accountability. |
| Novelty | **Clear gap** | No peer-reviewed evaluation found of a game that trains genAI data-handling decisions. |
| Risks | | "Gotcha" effects, peer policing, automation bias that resists training, fast-changing tools. Weaker Art. 4 means the business case should rest on data-loss risk and productivity, not a legal mandate. |

## 6. Recommendation

### Ranking

| Rank | Concept | Business problem | Mechanism evidence | Novelty | Classmates play it for real | Fit with this course |
|---|---|---|---|---|---|---|
| **1** | **Incident Zero** | Strong | Moderate (error management, team training, debrief) | Clear gap | Yes | **Very strong**: matches the professor's own research on gamified risk-management workshops |
| 2 | The Unwritten Rules | Moderate | Moderate | Clear gap | Yes | Strong, but must answer "isn't this Barnga?" |
| 3 | Shadow AI Dilemma | Moderate–strong | Weak–moderate | Clear gap | Yes | Timely, but awareness training barely changes behaviour |
| 4 | First Week in the Wild | Strong | Weak–moderate | Large gap | As role-play | Learning doesn't transfer from a fictional company; heaviest content load |
| 5 | Pitch Pit | Moderate | Weak–moderate | Some | Partly | Classroom market too thin; turns into a popularity vote |

### Why *Incident Zero*

1. **The design matches the strongest evidence in this review.**
   - Error management training: d = 0.44 overall, d = 0.80 for adaptive transfer (Keith & Frese, 2008).
   - Team training works (Salas et al., 2008; McEwan et al., 2017).
   - Debriefs with an objective replay are the largest effect found: d = 0.67–0.92 (Tannenbaum & Cerasoli, 2013; Keiser & Arthur, 2021, 2022). The dashboard can log every decision and replay it in the debrief.
2. **It builds on the professor's own work.** Schönbohm & Jülich (2016) found that gamified risk-management workshops in German SMEs increased knowledge and reduced cognitive and group biases. *Incident Zero* is a gamified risk and crisis workshop, so the report can position itself as extending that study.
3. **There's plenty of theory for the 10% + 5% theory criteria:**
   - psychological safety (Edmondson, 1999) and error reporting (Zhao & Olivera, 2006);
   - Goodhart's Law, Kerr's "folly" and goal side effects (Ordóñez et al., 2009);
   - social interdependence (Johnson & Johnson, 2009) and hidden profiles (Lu et al., 2012);
   - MDA aesthetics Challenge, Fellowship and Discovery, plus SDT.
4. **The change is measurable in Week 12 with objective data.** The dashboard logs time-to-disclosure and what each role shared. Add a disclosure-intention vignette before and after play, and SIMS plus BPNSFS after.
5. **It's new.** No evaluated game was found that rewards early self-disclosure while players hold conflicting private KPIs.
6. **The ethics section has clear material:** stress vs. anxiety, a blameless debrief, consent (Mollick & Rothbard, 2014), and Kim & Werbach's (2016) four checks.
7. **It suits the team.** The developer builds the dashboard; the other three write role packets, events and the debrief, run the playtest and write the report.

### Changes the research calls for (*Incident Zero*)

- **Frame errors as learning before play starts** (Keith & Frese, 2008).
- **Log every decision and replay the timeline in the debrief** (Keiser & Arthur, 2021).
- **Run two or more "companies" in parallel in Week 12**, so there's competition *between teams* and cooperation *within* them (Morschheuser et al., 2019; Sailer & Homner, 2020).
- **Expect players to hide information, and make that the debrief lesson** (Toma & Butera, 2009).
- **Claim that it rehearses disclosure, not that it builds psychological safety** (O'Donovan & McAuliffe, 2020).
- **Define the metric** as time from becoming aware of an error to disclosing it (Zhao & Olivera, 2006), and treat *rising* near-miss reports as success (Edmondson, 1996).
- **Give Legal/Comms the real GDPR Art. 33 72-hour breach deadline.**
- **Make participation opt-in and explain why it's legitimate** (Mollick & Rothbard, 2014; Hammedi et al., 2021).

### When to pick *The Unwritten Rules* instead

Pick it if the group wants to stay with its onboarding and multicultural interest. The evidence for it is real: artificial-culture simulations improve behavioural adaptation (Heidemann & Søndergaard, 2023), one game session reduced the fundamental attribution error (Morewedge et al., 2015), and charter quality predicts team performance (Mathieu & Rapp, 2009).

It carries more risk, though:
- Barnga is the direct precedent.
- BaFá BaFá once *increased* ethnocentrism (Bruschke et al., 1993).
- Hall's directness dimension, the core rule type, is the weakest-supported part of his model (Cardon, 2008).
- Experiential methods beat lectures on reactions, not on learning (Gannon & Poon, 1997).

If chosen, it must:
- pair the game with a short concept input (Earley, 1987; Heidemann & Søndergaard, 2023);
- measure attribution shift with a new transfer vignette and two blind coders (Malle, 2006);
- ground the norm dimensions in Feldman (1984) and Taras et al. (2016), not in Meyer.

### Open questions for the team

- **Ask Prof. Schönbohm what "MVE" means** (section 3).
- Decide the business setting. A German SME or the anonymised part-time company both fit, and the professor's own study was set in SMEs.

## 7. Corrections for project-ideas.md (found so far)

1. **Kolb (Concept 1):** "experience → reflect → apply" skips *abstract conceptualization*. Use all four stages.
2. **Pitch Pit, overjustification:** the meta-analysis shows *any* expected, performance-contingent reward undermines intrinsic motivation (d = −0.28), not only cash. "2-Week Protected Sandbox Time" is such a reward. What matters is whether it feels controlling or informational. Cerasoli et al. (2014) show incentives and intrinsic motivation can coexist.
3. **Pitch Pit as a "prediction market":** with no outcome that later resolves, it is an **idea market** (Soukhoroukova, Spann & Skiera, 2012, *Journal of Product Innovation Management, 29*(1), 100–112, https://doi.org/10.1111/j.1540-5885.2011.00881.x [CR][A]). Prices would then track expected popularity, which conflicts with the stated aim of preventing popularity bias (our inference, not the paper's finding).
4. **Meyer's *Culture Map* (Concept 1):** trade book (Meyer, E., 2014, PublicAffairs), and its scales place countries on each dimension, which sits uneasily with "never tied to real nationalities". Cite with care.
5. **Concept 3, Goodhart's Law:** Goodhart's point was about monetary statistics. Cite Goodhart (1976), Strathern (1997) for the popular wording, plus Campbell (1979) and Kerr (1975).
6. **Concept 3, "40-page crisis playbooks go unread":** no source found. Replace with: exercises expose gaps in plans and roles that documents alone do not (Skryabina et al., 2017).
7. **Concept 3, "MTTE":** not an established metric. Define it (time from awareness of an error to disclosure) and ground it in Zhao & Olivera (2006).
8. **Concept 3, precedent and psychological safety:** blameless postmortems are industry practice, and tabletop exercises show short-term gains only. Don't claim the game builds psychological safety; claim it rehearses disclosure and makes the cost of hiding visible, and measure disclosure intention before and after.
9. **Concept 3, near-miss KPI:** state that *rising* reports count as success (Edmondson, 1996), or managers will push the number down.
10. **Concept 3, interdependence:** mixing cooperative and competitive goals will cause concealment (Toma & Butera, 2009). Present it as the intended debrief lesson.
11. **Concept 4, business problem:** replace "portals get little engagement" with what is documented: own-unit bias (Reitzig & Sorenson, 2013), panels screening out novelty (Criscuolo et al., 2017), missing feedback reducing repeat submissions (Piezunka & Dahlander, 2019).
12. **Concept 4, rewards:** creativity-contingent rewards can increase creativity (Byron & Khazanchi, 2012). Justify sandbox time as autonomy-supportive and creativity-contingent.
13. **Concept 4, live ticker:** herding is driven by visible aggregate signals (Salganik et al., 2006; Muchnik et al., 2013). Hide the ticker during the first trading window. Use a simple automatic pricing rule instead of an order book, since a classroom market is thin (Healy et al., 2010). Optionally settle trades against a jury score revealed at the end.
14. **Concept 4, constraints and timer:** evidence is mixed (Acar et al., 2019; Baer & Oldham, 2006). Call them moderate constraints and test them.
15. **Concept 5, "30-page compliance PDFs are unreadable":** no source found. The evidence points to productivity gains (Noy & Zhang, 2023; Dell'Acqua et al., 2026), employer restrictions (Humlum & Vestergaard, 2025), personal compliance cost (Bulgurcu et al., 2010; Beautement et al., 2008) and AI-use stigma (Reif et al., 2025).
16. **Concept 5, "Audit!":** frame it as collective detection (Lain et al., 2022) plus cognitive forcing (Buçinca et al., 2021). "Gotcha" designs fail (Lain et al., 2022; Ho et al., 2025). Audits target scenario cards, never people's real behaviour.
17. **Concept 5, "hallucination landmine":** an accuracy and automation-bias issue, not GDPR or IP. Cite Ji et al. (2023), Parasuraman & Manzey (2010), Dell'Acqua et al. (2026).
18. **Concept 5, Fogg:** conceptual; add protection motivation theory and the compliance budget.
19. **Concept 5, "Reduction in DLP violations" KPI:** fewer alerts can mean use moved to personal devices. Pair it with approved-tool adoption; monitoring raises GDPR Art. 88 and works-council issues.
20. **Concepts 4 and 5, AI Act:** since 27 July 2026, Art. 4 only requires measures that *support* AI literacy (Regulation (EU) 2026/1744). Don't say the AI Act requires certified AI training.
21. **Concept 1, "teams lose months to unspoken friction":** no source. Replace with Stahl et al. (2010): diversity brings process losses *and* gains.
22. **Concept 1, "understand from slide decks but revert to habit":** only partly supported. Say "knowledge alone is insufficient" (Eisenberg et al., 2013), not "lectures fail" (Rehg et al., 2012 show they work).
23. **Concept 1, "personality surveys don't fix this":** opinion with no source. Label it as design rationale.
24. **Concept 1, attribution theory:** add Pettigrew (1979) and isomorphic attributions (Fiedler et al., 1971; Bhawuk, 2001); note the FAE varies by culture (Morris & Peng, 1994).
25. **Concept 1, pre/post "Why did your teammate do X?":** not a validated instrument, and asking it right after the reveal invites demand effects. Use a *new* transfer vignette, code free responses as dispositional vs. situational with two blind raters and Cohen's κ, justify with Malle (2006). Optionally add the CQS (Ang et al., 2007) or an intercultural SJT (Rockstuhl et al., 2015).
26. **Concept 1, Hall:** directness is the least supported part of his model (Cardon, 2008; Kittler et al., 2011). Use Hall only as vocabulary and cite the critiques.
27. **Concept 1, Meyer:** ground the norm dimensions in Feldman (1984) and flag Meyer as a practitioner source.
28. **Concept 1, Hofstede "only with McSweeney":** one-sided. Add Taras et al. (2010, 2016); the 2016 paper also supports the nationality-free design.
29. **Concept 1, charter "the team keeps using":** persistence isn't shown; the evidence is about charter *quality*. A 5-minute vote may produce a weak charter, so score charter quality following Mathieu & Rapp (2009).
30. **Concept 1, prediction and voting:** cite Ross et al. (1977) and Prentice & Miller (1993); don't score voting speed (Wang & Tahir, 2020).
31. **Concept 2, "new hires skim handbooks":** no source. Reframe around information seeking and network building (Morrison, 1993b, 2002) and the remote-onboarding social gap (Rodeghero et al., 2021).
32. **Concept 2, KPI "reduction in Month-1 manager coaching hours":** conflicts with Bauer et al. (2021), where manager contact helps. Use role clarity, self-efficacy and social acceptance (Bauer et al., 2007).
33. **Concept 2, Coffee Chat Tokens:** "who knows what" doesn't transfer from a fictional company (Lewis et al., 2007), and scarce tokens may teach that asking is costly, the opposite of Morrison's findings. Reframe the goal as an expertise-locating *strategy*; debrief the scarcity or make tokens regenerate.
34. **Concept 2, safe failure with hidden scores and false leads:** only supported with explicit error framing and scaffolding (Keith & Frese, 2008; Alfieri et al., 2011). Add hints and reveal the hidden scores at the debrief.
35. **Concept 2, "blunt lead / indirect overseas partner":** same stereotyping risk as Concept 1. Keep characters fictional and not tied to nationalities.
36. **Concept 2, measurement:** add an SJT with parallel pre/post forms and knowledge-type instructions (McDaniel et al., 2007).
37. **Correct as written:** McSweeney (2002), *Human Relations, 55*(1), 89–118, https://doi.org/10.1177/0018726702551004 [CR]; Edmondson (1999), *Administrative Science Quarterly, 44*(2), 350–383, https://doi.org/10.2307/2666999 (OpenAlex only); "Discovery" as an MDA aesthetic; Barnga (Thiagarajan, S., 1990, Intercultural Press; Open Library).
