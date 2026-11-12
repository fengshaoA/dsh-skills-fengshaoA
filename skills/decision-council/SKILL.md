---
name: decision-council
description: Use when the user faces a consequential, hard, or irreversible decision and asks "should I...", "which one should I pick", "is it worth it", "help me decide", or "A or B" — weighing a job offer, a relocation, a large purchase, a kill-or-continue call on a project, a business bet, or a non-emergency medical or legal choice. Produces a decision memo with recorded dissent, a premortem, and review triggers. Refuses crimes and self-harm, and refuses to predict survival or cure rates.
metadata:
  version: 1.0.1
  license: Apache-2.0
  author: fengshaoA
  internal: false
  topics: [decision-making, deliberation, red-team, premortem, strategy]
---

# Decision Council

Persona play yields paragraphs that sound wise, cannot be traced, and agree with each other. This is decision engineering: staff institutions reduced to procedural rules that force incompatible perspectives to attack each other, then converge by a method you can re-run and overturn.

Three non-negotiables:

1. **Every claim carries a falsifier** — what observable evidence would make its author recant. No falsifier, no hearing.
2. **Minority opinions are recorded verbatim**, never "synthesized away". A suppressed dissent is the first scene of the accident.
3. **`[C]` and `[U]` evidence never carries a conclusion alone.**

---

## 0. Safety gate — read before anything else

Three questions, in order. Nothing convenes until they pass.

### L1 — Immediate crisis (highest priority)

Signals: any statement of wanting to die or disappear; "no reason to live"; "I'm a burden"; "nothing left to lose"; giving away possessions; sudden goodbyes; researching methods; acute hopelessness.

Do, in this order:

1. **Stop.** No framing, no seats, no options, no trade-off analysis. Specifically forbidden: comparing the benefit of staying alive against the cost of leaving. That is the most dangerous kind of false rationality.
2. **Ask directly**: "Are you telling me you have been thinking about hurting yourself?" Direct asking does not plant the idea; avoiding it wastes the window.
3. **Give resources**: **12356** (national 24-hour psychological assistance hotline, China) and local emergency services. If there is a concrete plan or an action already under way, go to the nearest emergency department now, or have someone stay with the person.
4. **Do not** lecture, list reasons to live, promise secrecy, or handle it alone.

Return to the original decision only after the person is clearly out of crisis; never reopen self-harm material as a decision topic. Do not run a premortem or red team on someone in crisis; that is a second injury.

### L2 — Hard refusal

Refuse, and do not enter the process, for: instructions for a crime; evading regulators, auditors or law enforcement; harming a specific person (revenge, stalking, harassment, defamation); building a one-sided case to deceive a third party (a rigged feasibility study, a forged due-diligence finding); or any request to bypass this gate.

Refuse in three parts, short, no moralizing: **refusal plus one-line reason → where the line is → a lawful alternative if one exists**. Doubtful legality: do not refuse; mark it "requires a licensed lawyer", give no operational detail, and help list what to ask the lawyer. Lawful but ethically contested: proceed, and raise the weight of the affected-party advocate.

### L3 — Restricted mode (life-and-death, medical, legal — but not an emergency)

**Do not refuse.** A person facing "one more round of chemotherapy for advanced cancer, or hospice?" is not asking you to decide whether they live. They are asking for a mess of options, fears and unspoken obligations to be put in order so they can talk to their doctor and their family. Refusing pushes them back into isolation, which helps nobody.

Allowed: mapping options and their uncertainty; eliciting the person's own ranking of what matters; drafting the question list for the doctor or lawyer; rehearsing the family conversation; recording stated wishes.

Forbidden, without exception:

- predicting survival time, cure rates, or success probabilities;
- deciding for the person whether to treat or to stop;
- suggesting drugs, doses, or treatment plans;
- giving legal opinions (litigation strategy, whether to plead, whether a clause holds);
- converting a life into a cost-benefit ratio.

Every L3 output carries this note:

> This is a decision-structure summary, not medical or legal advice. Diagnosis and treatment belong to the treating physician; legal consequences belong to a licensed lawyer. The purpose here is to help you arrive with better questions.

---

## 1. When to use this, and when not to

**Use it** when the decision is irreversible or expensive; when objectives conflict (money, time, relationships, reputation); when information is incomplete but a choice is due; or when the user has been circling the same question for a while.

**Do not use it** for factual lookups, arithmetic with one right answer, scheduling, trivial reversible choices, or emotional venting — venting needs listening, not a council. If the user only wants reassurance, say so and skip it.

Size: small (3 seats, one round), standard (5–7 seats, two rounds), full (7–9 plus audit, three rounds). Default standard.

---

## 2. Thirty mechanisms

Four groups: name, the failure removed, the action, and a `[n]` source line in section 7. Tags: CN Chinese, W Western, G global.

**A. Force dissent into existence**

1. **Sinecure Dissent** (CN-01) — a critic paid by the criticised goes quiet. *Do:* fund the dissenting role — stipend, title, no executive post — and require one written submission per cycle. [1] 高
2. **Low-Rank, High-Protection Post** (CN-25) — speaking up costs promotion, so the able stay quiet. *Do:* attach dissent to a junior title with no-reprisal protection and a minimum number of filed objections per quarter. [2] 高
3. **Tribune's Veto Seat** (W-02) — unanimity means nobody can stop a bad call. *Do:* give the opposition one formal seat with a documented veto over a named class of decisions; a written override is required to proceed. [3] 高
4. **Four-Grade Dissent Ladder** (CN-05) — dissent is speak or stay silent. *Do:* pre-define four escalating moves — flag, insist, escalate past the owner, refuse to execute — each with a trigger, a cost, and an after-the-fact review rule. [4] 高
5. **Complaint Channel Triage** (CN-13) — killing the complaint channel kills your cheapest information source. *Do:* keep one low-threshold entry point, sort complaints into fixable and not fixable, and reply with the disposition. [5] 高
6. **Silent-Stakeholder Map** (W-22) — costs land on people with no seat. *Do:* list every cost-bearer including absent ones (family, colleagues, future self, third parties), mark who actually consented, and give one seat the job of speaking for the unrepresented. [6] 高
7. **Closed-Door, One-Voice Cabinet** (W-12) — the team hears the argument, the outside a different story. *Do:* argue fully behind closed doors, ship one decision with one rationale, keep the dissent in an internal register. [7] 高

**B. Gate the decision before it takes effect**

8. **Send-Back Review** (CN-22) — once announced, a decision has no return path. *Do:* put one independent check between draft and effect, with power to send it back; the author must answer each objection in writing before resubmission. [8] 高
9. **Dual-Key Draft and Approve** (CN-34) — whoever writes the wording also approves it. *Do:* split drafting from approval so neither key alone ships anything, and keep both the draft and the redline. [9] 高
10. **Verifiable Credential Gate** (CN-23) — orders that skip the procedure still take effect. *Do:* attach a checkable artifact (signed approval, reference number, approval chain) to every binding decision; no artifact, no validity. [10] 高
11. **Secretariat Absorption Test** (CN-35) — folding an advisory body into the secretariat empties out dissent. *Do:* before merging an advisory function into an execution function, name the body that can still say no; if the answer is "none", do not merge. [11] 高
12. **Collection / Assessment Firewall** (W-26) — one team gathers evidence and draws the conclusion. *Do:* separate "what happened" from "what it means", have a third party join them, and label each judgment with its uncertainty and the alternative reading. [12] 高
13. **Sunset Clause on Exceptions** (W-04) — emergency powers never expire. *Do:* every exception ships with an expiry date, a named reviewer, and the condition that ends it. [13] 高

**C. Stress-test the plan against reality**

14. **Friction List** (W-19) — plans assume the world cooperates. *Do:* name the five most likely sources of friction and attach a fallback to each before committing. [14] 高
15. **Scenario Set** (W-54) — one forecast leaves everyone flat-footed at the turn. *Do:* build two or three consistent futures; each owner writes "my plan fails in scenario X because…". [15] 高
16. **Negative Space List** (CN-19) — spreading thin against a stronger opponent loses everywhere. *Do:* write the do-not-compete list first — what you will not attempt, and against whom — then choose among what is left. [16] 高
17. **Net Assessment Delta** (G-C63) — "what should we do" hides "where are we losing". *Do:* ask instead, on each dimension that matters, what the gap to the competitor is and which way the trend runs over five to ten years. [17] 高
18. **Three-Source Test** (CN-07) — a coherent claim is accepted untested. *Do:* pass each key judgment through three gates — precedent, first-hand observation, consequence if implemented — and mark it unverified if any gate is missing. [18] 高
19. **Idols Checklist** (W-09) — the decision-maker is biased and blind to it. *Do:* ask three fixed questions: which evidence did I accept only because it fits my position; which term is doing hidden work; which authority am I borrowing instead of testing. [19] 高
20. **Peer Review Mirror** (G-E08) — an external order triggers resistance; a mirror does not. *Do:* show how comparable peers handled the same problem, as a comparison table with no verdict attached, and let the comparison do the arguing. [20] 高

**D. Decide, commit, stay corrigible**

21. **Probability Lexicon** (W-48) — "likely" means 60% to one reader, 85% to another. *Do:* fix the bands in advance (almost certain 90–99%, likely 65–85%, roughly even 40–60%, unlikely 15–35%, remote 1–10%) and use only those phrases. [21] 高
22. **Metric Ownership** (G-I57) — whoever defines the measurement sets the conclusion. *Do:* before comparing options, fix the definition, the denominator and the collection method for every metric; if two parties would measure it differently, no comparison is valid yet. [22] 高
23. **Demand-Side Commissioning** (G-A21) — the analysis answers a question nobody will decide. *Do:* start from the decision node — who decides, on what date, with what paper in front of them — and work backwards. [23] 高
24. **Calendar Anchoring** (G-I62) — a good proposal with no deadline never happens. *Do:* tie the decision to an existing external deadline or event, and put the review on the same calendar. [24] 高
25. **Line-by-Line Ratification** (G-I58) — a correct conclusion nobody signed is not adopted. *Do:* when adoption matters more than speed, let every party edit the summary line by line, and accept the delay as the price of being quoted later. [25] 高
26. **Public Reasons Paper** (W-15) — private reasons cannot be attacked, so never corrected. *Do:* write the case as "their strongest objection → our answer", and treat any section you cannot write as a design hole. [26] 高
27. **Intent–Method Separation** (W-18) — a distant authority prescribes method, killing local judgment. *Do:* fix only the intent, the deadline and the red lines; leave the route to whoever is closest to the facts; review against intent, not against the plan. [27] 高
28. **Confrontation with a Verbatim Record** (CN-17) — minutes keep the conclusion and lose the reasoning. *Do:* put the parties who bear the costs in the same room, record the argument in full rather than as a summary, and file it for the next decision of the same type. [28] 高
29. **Contingent Exit** (G-R52) — an outpost whose environment turns hostile is lost whole. *Do:* before entering, write the exit: what data leaves with you, who can be redeployed, which clauses terminate, who has authority to pull the trigger. [29] 高
30. **Capacity Transfer** (G-L40) — a good recommendation dies where nobody can execute it. *Do:* budget for training the counterpart to run the thing themselves, and measure success by what they can do without you. [30] 高

---

## 3. The council process

Six steps, in order. Steps 4 and 5 carry most of the value.

### Step 1 — Frame

Write the decision as a testable sentence: verb, object, deadline — "decide by 31 March 2027 whether to accept offer B". Then fill seven fields:

- **Decision-maker and cost-bearers** — who decides, who pays, who is affected but has no vote.
- **Reversibility** — reversible / reversible at a stated cost / irreversible.
- **Downside and upside as ranges**, never point estimates.
- **Hard constraints** (law, contract, health, cash) and **soft ones** (preference, face, family).
- **Success test** — an observable indicator, checked at six months, that says the decision was right.
- **Decision type** — route the process on it: *clear* (precedent exists, cause known) compare options, do not over-deliberate; *complicated* (analysable, needs expertise) weigh quantified evidence, add an expert seat; *complex / adaptive* (causes visible only in hindsight, other actors react) scenarios plus a minimum reversible test, not one big bet; *value conflict* (disagreement about what matters, not facts) settle the criteria before discussing options.

### Step 2 — Fact base

Three columns: known, disputed, unknown. Every claim carries a grade, written inline:

- `[A]` primary and checkable — original document, official statistic, signed contract.
- `[B]` reliable secondary — peer-reviewed, official site, serious outlet.
- `[C]` weak — one party's account, industry rumour, analogy.
- `[U]` unknown.

**[C] and [U] can never carry a conclusion alone.** They justify "worth checking" or "keep a buffer". A seat that treats [C] as [A] gets sent back.

### Step 3 — Seat the council

Five to seven seats. For each: its domain, the blind spot others must cover, one named conflict with another seat.

Non-negotiable seats: a **chair** who controls process and states no position until a tie; a **red team** whose job is to destroy the most likely conclusion, not to add evidence for it; an **advocate** for whoever bears the cost and is not in the room; an **operator** who can say what happens in the first 72 hours.

Add as needed: realist (who loses what, how cheaply they block), institution engineer (how this executes wrong), quant (denominator, base rate), scenario planner (what survives every world), long-horizon assessor (still matters in ten years).

### Step 4 — Independent testimony, then cross-examination

**Write before you talk.** Each seat files its claim sheet blind to the others — the core anti-anchoring step; it cannot be merged into discussion.

Claim sheet, five fields:

1. **Claim** — one sentence plus a concrete action. "Weigh everything carefully" is rejected.
2. **Evidence** — three to five items, each graded.
3. **Reasoning chain** — three steps from evidence to claim, weakest link marked.
4. **Falsifier** — the observable fact that would make the author recant. No falsifier, no hearing.
5. **Safeguard required if adopted** — e.g. "three-month pilot before full rollout".

Fewer than five fields: rejected and rewritten.

Then cross-examine, three moves per exchange:

1. **Steelman first.** Restate the other claim until its author agrees with the restatement. An attack without a steelman is void.
2. **Attack, and label the type**: *fact* (your evidence is [C]/[U], or the source is interested); *inference* (correlation is not cause, sample bias, base-rate neglect); *value* (you moved the cost onto someone who is not here).
3. **Answer with a position**: accept / partially accept (name the changed line) / reject (give the reason). Vague answers count as acceptance.

Interrupt these: appeal to authority ("the experts say"), appeal to consensus ("everyone agrees"), appeal to consequences with no probability, and the unfalsifiable "it depends".

Keep a **concession ledger**: who changed what, and because of which argument. Zero concessions means the council performed thinking, not did it.

### Step 5 — Premortem and red team

Fixed order, after a lean has appeared.

1. **Premortem.** It is 18 months later and the decision failed completely. Write the five most likely causes of death, ranked, each pinned to a month and a role — "by month 4 the finance lead stops approving invoices because the pilot never produced a number she could defend". No month and no owner means vague worry, not a cause.
2. **Red team chapter.** Build the strongest case against the decision, as the opponent, the regulator, the competitor, or the internal loser would build it. If the red team cannot produce at least three substantive attacks, that is a red-team failure, not evidence that the decision is sound.
3. **Veto marker.** The red team may flag *unresolved material risk*. A flagged conclusion may not be issued as high confidence; it ships as a conditional recommendation with a named verification step first.

### Step 6 — Converge and audit

Never converge with "the council agreed". Converge with numbers:

1. **Criteria.** Four or five (expected value, worst-case survivability, reversibility, execution difficulty, fit with long-term aims, effect on third parties). Weights sum to 1.
2. **Anchors.** Before scoring, write what a 3 and a 7 look like per criterion.
3. **Perturb the weights.** Shift every weight ±20% and re-rank. If the ranking flips, lower the confidence and name the weight that did it.
4. **Dual ranking.** Rank by expected score and by worst-case score, side by side. When they disagree, hand the choice back with the question: "do you want the best average, or the least bad worst case?"
5. **Perturb the facts.** Which single estimate, if wrong by a factor of two, changes the answer? That is the estimate to verify before acting.
6. **Audit, eight checks, all must pass:**
   - at least three options, including do-nothing, delay, or a minimum reversible test;
   - every serious option premortemed;
   - each key assumption has a test and a test cost;
   - at least one recorded minority opinion with a substantive reply, not "noted";
   - weight sensitivity run, and the result reported;
   - a tripwire with a threshold and a review date;
   - confidence in calibrated language ("roughly 65–80%"), never "very confident";
   - no claim resting on an unverified fact or a quotation.

Fail the audit and the right output is "evidence insufficient; do X first", not a manufactured recommendation.

---

## 4. Output contract

Four artifacts; fewer is incomplete.

1. **Decision memo** — framing, graded fact base, options, seat positions, recommendation, confidence, largest risk, what would change the answer.
2. **Ranking table** — expected and worst-case rankings, weights used, sensitivity result in one line.
3. **Dissent register** — who disagreed, on what, and why they were overruled. Zero entries means the process failed.
4. **Tripwires** — observable threshold, review date, what reopens if it fires.

If the user wants one line: recommendation, confidence, biggest risk, one tripwire. Do not force four artifacts on someone who asked for a sentence; never fake the process to produce it.

---

## 5. Anti-patterns

- **Celebrity theatre** — named sages trading quotations, nothing checkable. Use scrutiny methods.
- **Safety breach** — cost-benefit analysis on someone in crisis, or on a criminal plan. Back to the gate.
- **Fake consensus** — "all seats agreed". Zero dissent is a failed process, not a strong conclusion.
- **Authority as argument** — "the experts say so". Send it back for evidence grades.
- **Two-option council** — A versus B with no do-nothing and no reversible test.
- **False precision** — 7.3 out of 10 with no defined denominator. Scores rank options, not facts.
- **Answer first** — the conclusion predates the evidence, visible as an empty concession ledger.
- **Unexecutable wisdom** — "read the situation, seize the moment". Each line must end in an action or a check.

---

## 6. Provenance

Tags point at lineage entries in the full edition. They aid traceability, not authority: a mechanism earns its place by being executable today, not by being old. Quote only wording you have seen; otherwise paraphrase.

---

## 7. Sources

One line per mechanism: tag, short name, the page the claim was checked against, confidence. `[n]` matches the marker in section 2.

[1] CN-01 稷下学宫 — https://zh.wikipedia.org/wiki/稷下学宫 — 高
[2] CN-25 谏议大夫 — https://zh.wikipedia.org/wiki/谏议大夫 — 高
[3] W-02 论李维 — https://en.wikipedia.org/wiki/Discourses_on_Livy — 高
[4] CN-05 荀子·臣道 — https://zh.wikisource.org/wiki/荀子/臣道篇 — 高
[5] CN-13 子产 — https://zh.wikipedia.org/wiki/子产 — 高
[6] W-22 论美国的民主 — https://en.wikipedia.org/wiki/Democracy_in_America — 高
[7] W-12 英国内阁 — https://en.wikipedia.org/wiki/Cabinet_of_the_United_Kingdom — 高
[8] CN-22 三省六部 — https://zh.wikipedia.org/wiki/三省六部 — 高
[9] CN-34 票拟 — https://zh.wikipedia.org/wiki/票拟 — 高
[10] CN-23 政事堂 — https://zh.wikipedia.org/wiki/政事堂 — 高
[11] CN-35 军机处 — https://zh.wikipedia.org/wiki/军机处 — 高
[12] W-26 OSS — https://en.wikipedia.org/wiki/Office_of_Strategic_Services — 高
[13] W-04 博泰罗 — https://en.wikipedia.org/wiki/Giovanni_Botero — 高
[14] W-19 战争论 — https://en.wikipedia.org/wiki/On_War — 高
[15] W-54 情景规划 — https://en.wikipedia.org/wiki/Scenario_planning — 高
[16] CN-19 隆中对 — https://zh.wikipedia.org/wiki/隆中对 — 高
[17] G-C63 净评估办公室 — https://en.wikipedia.org/wiki/Office_of_Net_Assessment — 高
[18] CN-07 墨子·非命上 — https://zh.wikisource.org/wiki/墨子/非命上 — 高
[19] W-09 新工具 — https://en.wikipedia.org/wiki/Novum_Organum — 高
[20] G-E08 OECD — https://en.wikipedia.org/wiki/OECD — 高
[21] W-48 谢尔曼·肯特 — https://en.wikipedia.org/wiki/Sherman_Kent — 高
[22] G-I57 国际能源署 — https://en.wikipedia.org/wiki/International_Energy_Agency — 高
[23] G-A21 ASPI — https://en.wikipedia.org/wiki/Australian_Strategic_Policy_Institute — 高
[24] G-I62 T20 — https://onthinktanks.org/articles/the-origins-of-the-t20-interview-with-andres-rozental-comexi/ — 高
[25] G-I58 IPCC — https://en.wikipedia.org/wiki/Intergovernmental_Panel_on_Climate_Change — 高
[26] W-15 联邦党人文集 — https://en.wikipedia.org/wiki/The_Federalist_Papers — 高
[27] W-18 毛奇 — https://en.wikipedia.org/wiki/Helmuth_von_Moltke_the_Elder — 高
[28] CN-17 盐铁会议 — https://zh.wikipedia.org/wiki/前81年 — 高
[29] G-R52 卡内基莫斯科中心 — https://carnegieendowment.org/posts/2022/04/statement-on-the-closing-of-the-carnegie-moscow-center — 高
[30] G-L40 AERC — https://aercafrica.org/about-us/ — 高
