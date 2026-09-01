# Phase 0: Practice Round — Exercise Hokie Stone

**Course Topic:** Simulation Kickoff (teams, roles, and how the loop works)

**Time Period:** A declared regional exercise in a quiet Saturday window, before Day 1 of the main crisis (about 30 minutes real time).

---

## Context

The Southwest Virginia Emergency Management Agency has declared **Exercise Hokie Stone**: a quarterly full-scale drill built around a single, contained cause — a severed fiber trunk. Every rule of a real phase is in force: budgets, trust, approvals, the report format, collaboration, and transfers. The only difference is the stakes: this is practice, scores are kept but not graded, and the hotwash at the end tells you how you did.

Combine during the exercise: the dashboard is your only live picture; the response report is the only thing a facilitator reads; and an incident nobody claims is an incident that escalates.

At 7:52 AM a contractor's backhoe severs the primary Shentel fiber trunk under I-81 near Radford. The regional 911 center drops to a single degraded path, Stillwater Medical Center in Radford loses telehealth and remote-records access, traffic signals go dark at the I-81/I-77 interchange in Wytheville, VT Alerts stops confirming delivery to a third of the Blacksburg campus, four Food City stores go cash-only with their pharmacy counters unable to verify prescriptions, hydraulic fluid from the backhoe itself starts pooling forty feet from a storm drain, and within minutes a rumor that this is an EMP attack starts moving through churches and sheriff's-department social feeds. Twenty minutes later Richmond asks for one consolidated regional number and a written yes-or-no on cyber before the Governor's 9:00 press availability, and the Governor's office has no feed of its own to build either from.

Nothing about this is complicated. That is the point: a simple, single-cause incident is the cheapest way to learn the mechanics you will need when the real crisis starts.

---

## Crisis Engine Analysis

### What just changed unexpectedly?
A single physical cause — a severed fiber trunk — is producing seven parallel effects across dispatch, healthcare, transportation, campus operations, retail payment and pharmacy, the excavation site itself, and public information. The exercise is deliberately one cause, many effects, so teams can learn to trace a cascade without drowning in one. The eighth incident is not an effect at all: the state wants one answer, and it can only be assembled out of what the other eleven teams report.

### Which system is now stressed?
- [x] Infrastructure: 911 circuits, clinic records link, traffic signal controllers, VT Alerts and a research data center
- [x] Information: a rumor is moving faster than any official statement, and the cyber question is still open
- [x] Health: dialysis protocols cannot be verified remotely, and pharmacy counters cannot verify prescriptions
- [x] Economy: four stores cash-only — an access failure, not a supply failure, and reporting it as the smaller thing it is counts
- [x] Environment: roughly 12 gallons of hydraulic fluid in the trench, 40 feet from a storm drain to a New River tributary
- [x] Governance: multi-agency coordination required across 911, clinic, VDOT, AEP, DEQ, CISA, and the university

### Who experiences immediate harm?
- [x] Individuals: callers who hang up on a degraded 911 path, dialysis patients, shoppers at a cash-only pharmacy counter
- [x] Vulnerable communities: elderly residents reached through the faith network, households without cash on hand
- [x] Institutions: 911 center, Stillwater Medical Center, VDOT, Virginia Tech, four Food City stores
- [ ] Cross-border populations: not yet (emerges in later phases)

### What decision must be made within limited time?
**Restore the public path first, or protect the backup?** The 911 reroute and the clinic link both want Shentel's technicians; the interchange wants VDOT and AEP to agree on whether it is power or network; the rumor wants an authoritative statement nobody has drafted, and that statement cannot honestly say "not an attack" until CISA has ruled the cyber question out in writing. Underneath all of it the splice itself is blocked: DEQ holds the right-of-way until the hydraulic release is contained, so the team with the smallest inject on the board is gating everyone else's repair. Money is the second squeeze: Carilion, Shentel, and the Sheriff's Coalition each hold less than their own action list costs, and the one pot that can close the gap — the Governor's — covers two of the three shortfalls, not all three. The exercise is designed to be fully resolvable in the window — if teams coordinate instead of each solving their own corner.

### What future risk is created by this decision?
- **If each team solves only its visible inject:** the rumor outruns the statement, and trust erodes everywhere.
- **If teams coordinate** (Shentel + EMA + Sheriff on 911; Shentel + Carilion on the clinic; VDOT + AEP on the interchange; DEQ + VDOT + AEP on the corridor, which unblocks the splice; CISA + VT + Shentel on the cause; Food City + Carilion on prescriptions; Governor + Faith + Sheriff on the rumor, and Governor + CISA + EMA on the number Richmond wants, both of them only once CISA's all-clear exists to cite): every inject resolves and everyone ends the exercise having practiced collaboration.

### Who makes the decision, and who is left out?
- **Decision makers:** Olympic (Shentel), Yellowstone (EMA), Banff (Sheriff), Glacier (Carilion), Shenandoah (VDOT), Everglades (AEP), Acadia (Governor), Zion (Faith), Denali (Virginia Tech), Teton (CISA), Katmai (DEQ), Redwood (Food City)
- **Stakeholders excluded:** the dialysis patient, the caller who hung up, the congregation reading the rumor, the customer at the cash-only pharmacy counter, the contractor whose backhoe started all of it
- **Why this matters:** exactly the same pattern as every real phase — technical decisions made in rooms far from the people they land on.

---

## Team Roles This Exercise

**All 12 teams are active.** Each team has real work, and every action catalog entry is available to someone.

| Team | Role | Focus In The Exercise |
|------|------|------------------------|
| Acadia | Governor's SW Virginia Liaison | Speak for the region: the authoritative voice on the rumor, the one consolidated answer Richmond wants, and the only budget that can underwrite another team's action |
| Banff | SW Virginia Sheriff's Coalition | Public order and safely rerouting 911 calls; co-signs the statement |
| Denali | Virginia Tech Crisis Response | Campus and research continuity; liaison to CISA on the cause |
| Everglades | AEP Appalachian Power | Confirm the interchange signals are network, not grid fault; share the corridor clearance with DEQ and VDOT |
| Glacier | Carilion Clinic System | Keep patient care whole while the records link is down — dialysis protocols and the pharmacy counters both |
| Katmai | VA DEQ SW Regional Office | Contain the release and clear the shared corridor; the splice cannot start until you do |
| Olympic | Shentel Communications | Own the severed trunk: 911 reroute and the clinic relay both sit here |
| Redwood | Food City / Regional Supply Chain | Card auth and prescription verification are down; report an access failure as the smaller thing it is |
| Shenandoah | VDOT SW Region | Traffic control at the interchange; coordinate with AEP and Sheriff |
| Teton | CISA Regional Coordinator | Verify there is no cyber component; confirm it is a mundane fiber cut |
| Yellowstone | SW Virginia EMA | Run the exercise; activate backup dispatch; set up the hotwash; hold county-government continuity |
| Zion | Appalachian Faith & Community Network | Reach the worried households; the trusted voice the rumor moves through |

**Roles rotate every phase.** Your team's role here is practice for the mechanism, not a permanent assignment.

---

## Exercise Rules

- Same report format as every phase: `REPORT.md`. File at least twice — an in-class draft and a final report this evening.
- Same budget, trust, and approval rules as `help.html`. Trust moves ±1 to ±2 per action, capped at ±3 per update cycle.
- **Your budget is smaller than your role's action list, on purpose.** Carilion is $40K short, Shentel $25K, the Sheriff's Coalition $10K. Three ways out, all of them already in the catalog: split a shared action and each side pays half (A9 Carilion + Shentel, A13 DEQ + VDOT + AEP, A14 Food City + Carilion); let the partner who is *not* short buy it alone; or ask Acadia to underwrite it with A15, which holds $50K against $75K of shortfall — so the Governor has to choose, in writing. Unspent money carries into phase 1.
- Scores are kept on the board but **not** graded and not posted to Canvas.
- The hotwash (Yellowstone's action A10) closes the exercise.

## Learning Objectives

By the end of the exercise every team should be able to:

1. Read the dashboard — your role, your visible incidents, the action catalog.
2. Write a response report that a facilitator can act on (actions, costs, authority, collaborations, transfers).
3. Budget from `roles.csv`, not self-report, and know what a transfer does and does not do.
4. Name what a bad report looks like — volume without decisions, claims without authority, incidents you cannot actually see.
5. Spend against a budget that does not cover everything you want, and say in the report what you gave up to afford what you chose.
