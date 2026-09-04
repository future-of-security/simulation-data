# Exercise Hokie Stone — Phase 0 Decision Tree

A 60-minute phase. One backhoe, one severed Shentel trunk under I-81 near
Radford, and eight boards lit up at the start. Most of the tree is not on the
board yet — six incidents are hidden and only surface when a team either
closes an incident **or lets it rot**. That contrast is the point: the
instructor reviews, and the class later builds, trees where *what actually
gets fixed* determines *which board the teams see next*.

Three decisions carry real forks, each with two different children:

| Parent | Resolved child | Escalated child |
|--------|----------------|-----------------|
| #1 911 circuits | #9 single-reroute resilience choice | #10 call-drop surge forces backup dispatch |
| #5 cyber cause | #11 written all-clear unblocks 9:00 | #12 intrusion — federal threshold |
| #8 Richmond number | #13 verified figure filed | #14 9:00 happens on a draft |

---

## The board at the start — live incidents (owners in bold)

Every team opens the phase with something they hold the authority and budget
to fix. All eight are live from 0:00.

- **#1 — Regional 911 Center Primary Circuits Down** (sev 4, 100 pts, 20 min)
  Owned by **Shentel** (reroute, A2) and **SW Virginia EMA / Sheriff** (backup
  dispatch, A3). The lead incident; its outcome drives Nodes 9 and 10.
- **#2 — Stillwater Medical Center Loses Records Link** (sev 3, 75 pts)
  Owned by **Carilion** (temporary workaround, A4; mobile relay with Shentel, A9).
- **#3 — Traffic Signals Dark at I-81/I-77** (sev 3, 75 pts)
  Owned by **VDOT** (flaggers, A5) and **AEP** (power verification, A6) —
  network fault vs. grid fault is itself a decision.
- **#4 — 'EMP Attack!' Rumor Spreading Online** (sev 2, 50 pts)
  Owned by **Governor's Liaison / Sheriff** (joint statement, A8) and
  **Faith Network** (call-back, A7). If it is not killed in the window, the
  story it feeds is what Richmond's office reads at 8:59.
- **#5 — VT Alerts Degraded, Cyber Cause Unruled-Out** (sev 3, 75 pts)
  Owned by **CISA** (attribution, A11) and **Virginia Tech** (campus failover,
  A12). The yes/no Governor's office is waiting on starts here. Drives 11/12.
- **#6 — Hydraulic Release, Right-of-Way Held** (sev 2, 50 pts)
  Owned by **DEQ** (containment and clearance, A13). The smallest inject gates
  the splice that repairs everything else.
- **#7 — Food City Stores Cash-Only** (sev 2, 50 pts)
  Owned by **Food City** (offline auth + pharmacy verification, A14).
- **#8 — Richmond Wants One Number Before 9:00** (sev 2, 50 pts)
  Owned by **Governor's Liaison** (consolidated report, A16). No independent
  feed — every number must be borrowed from a team that verified one. Drives
  13/14.

---

## The hidden tree — one section per node

### Node 9 — 911 Backup Verified: Single Reroute Holds the Region
- **Opens after:** #1, when the parent is **resolved** (A2 reroute done).
- **Owner of the decision:** **Shentel Communications**, with **SW Virginia
  EMA** holding the budget for the resilience option (A3, $60K).
- **Why this path leads here:** the teams *did* fix 911, so the consequence is
  not a failure — it is a *narrow* success. 911 returns on a single protected
  path while the trunk stays cut. The decision is whether that fragile success
  is good enough until the splice, or whether EMA spends on backup dispatch now
  so one more fault on the shared corridor cannot darken dispatch outright.

### Node 10 — 911 Call-Drop Surge: Backup Dispatch or Silence
- **Opens after:** #1, when the parent is **escalated** (still live past its
  20-minute deadline — no reroute, no backup dispatch).
- **Owner of the decision:** **SW Virginia EMA**, with the **Sheriff's
  Coalition** sharing the budget. Both can pay for A3 ($60K).
- **Why this path leads here:** the window passed with calls degrading, so a
  third caller hung up and silence grew to five seconds. Backup dispatch is now
  the only lever that stops dropped 911 calls; the decision is whether to
  commit the money against a fault that still is not explained.

### Node 11 — Cyber All-Clear Filed: Statements Unblocked
- **Opens after:** #5, when the parent is **resolved** (A11 written all-clear
  published, A12 campus failover confirmed).
- **Owner of the decision:** **CISA Regional Coordinator**, whose written
  finding every other team cites.
- **Why this path leads here:** the attribution check cleared the backhoe
  strike, so the Governor's office can get its written "no." The decision left
  is phrasing — a clean, unambiguous no, or qualified language that keeps the
  answer open — which only becomes visible when a reporter asks what the
  Governor means.

### Node 12 — Attribution Points to Intrusion: Federal Threshold
- **Opens after:** #5, when the parent is **escalated** (A11 does not clear —
  the failover predates a plausible physical cut and the probes repeat from a
  pre-strike address).
- **Owner of the decision:** **CISA Regional Coordinator** and **Governor's SW
  Virginia Liaison** jointly — the approvals table requires both for a federal
  emergency declaration.
- **Why this path leads here:** ruling out cyber was the job; not ruling it out
  converts a drill morning into a possible, active intrusion. The decision is
  escalation (federal declaration, national cyber response) versus containment
  and re-verification, and either way the 9:00 yes/no becomes "possible yes."

### Node 13 — Verified Number Filed: 9:00 Story Is Ready
- **Opens after:** #8, when the parent is **resolved** (A16 filed on time,
  built on verified team findings).
- **Owner of the decision:** **Governor's SW Virginia Liaison** — the only role
  that can release what Richmond reads.
- **Why this path leads here:** the teams handed the region one verified number
  and one written answer, so the Governor's 9:00 remarks rest on facts. The
  decision left is narrative — lead with cause and recovery, or with the
  reassurance that 911 is restored. Small, but it is the board the class should
  contrast with Node 14.

### Node 14 — 9:00 Without a Number: Richmond Speaks on a Draft
- **Opens after:** #8, when the parent is **escalated** (deadline passed with
  no verified figure and no written cyber answer).
- **Owner of the decision:** **Governor's SW Virginia Liaison**, who still holds
  the only channel into Richmond.
- **Why this path leads here:** because nothing verified was filed, the
  Governor's office drafts from news clips and the unverified rumor thread. The
  decision is whether the Liaison releases an unverified partial figure with
  caveats to beat the Governor to the mic, or formally says "not ready" and
  lets Richmond speak off the draft. Either way it becomes tomorrow's
  correction — the exact failure Node 13's path was built to avoid.

---

## Counterfactual branches — what the teams would have met instead

Each fork exists so that *clearing an incident* and *letting it rot* visibly
put different boards in front of the players.

- **Counterfactual A — 911 (parent #1).** Teams that reroute (A2) inside the
  window meet **Node 9**, a cheap confidence check with an optional resilience
  spend. Teams that guess wrong and let #1 escalate meet **Node 10** instead:
  a surge of dropped calls and a $60K backup-dispatch decision that was
  entirely avoidable. The difference in what the board looks like is the
  lesson.
- **Counterfactual B — the cyber question (parent #5).** Finish the
  attribution check and the board shows **Node 11**, a quiet phrasing decision
  that unblocks the whole Governor's pipeline. Let it rot or let the check
  surface a real finding, and the board instead shows **Node 12**, where the
  same role is deciding whether the state goes federal on a possible intrusion.
  One backhoe; two completely different crises.
- **Counterfactual C — the Richmond number (parent #8).** File a verified
  figure on time and the phase ends with the region *setting* the 9:00 story
  (**Node 13**). Miss the deadline and the region is *reacting* to it
  (**Node 14**), with the Liaison choosing between an unverified correction and
  a Governor who speaks off a draft. These are the two boards a 9:00 press
  availability can end with, and the only difference is what teams did before
  9:00.

Under the mechanics, Nodes 9–14 are hidden and open only on their parent's
outcome; all eight seed incidents stay open from phase start; every one of the
twelve roles in `roles.csv` holds a visible incident; and every hidden node's
`time_limit` resolves inside the 60-minute window (0:40–0:50 at the latest).
Severity and points track the existing scale: sev 2 = 50, sev 3 = 75,
sev 4 = 100.
