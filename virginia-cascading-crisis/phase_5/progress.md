# Phase 5 Progress: Hidden Damage

**Phase:** Health, Environmental, & Biosecurity
**Sim Time:** Day 16-25
**Canvas Assignment ID:** 2694957
**Status:** Active

---

## Team Standings (Start of Phase 5)

Carried forward from Phase 4 close.

| Team | Role | Budget | Trust | Score |
|------|------|--------|-------|-------|
| Acadia | VA DEQ Emergency Environmental Response | $16.7M | 16 | 0 |
| Arches | Carilion Health System Crisis Command | $11.94M | 18 | 0 |
| Banff | Governor's Health Emergency Coordinator | $4.585M | 23 | 0 |
| Bryce | Appalachian Faith Network Community Health | $39.18M | 13 | 0 |
| Denali | VDOT Medical Transport & Supply Routes | $6.26M | 19 | 0 |
| Glacier | SW Virginia Mass Casualty Coordination | $47.4M | 17 | 0 |
| Jasper | Public Health Biosecurity Coordinator | $8.975M | 17 | 0 |
| Olympic | Regional Medical & Food Supply Chain | $13.255M | 14 | 0 |
| Redwood | United Way Health Navigation Services | $23.355M | 26 | 0 |
| Sequoia | Virginia Tech Environmental Health Research | $1.75M | 16 | 0 |
| Shenandoah | Montgomery County Public Health Authority | $12.7M | 16 | 0 |
| Yellowstone | WDBJ7 Health & Environmental Coverage | $9.815M | 18 | 0 |
| Yoho | Shentel Emergency Health Communications | $6.47M | 18 | 0 |
| Yosemite | SW Virginia Sheriff's Environmental Crime Unit | $4.17M | 19 | 0 |
| Zion | AEP Power Grid & Environmental Systems | $0.18M | 24 | 0 |

**Scores reset to 0** — budgets and trust carry from Phase 4 end state.

---

## Update Cycles

## Update Cycle 1 (sim_time 0:00-0:11)

**Processed at:** 2026-03-19 12:47 EDT (sim_time 0:11)

### Submissions Processed

#### Sequoia (Virginia Tech Environmental Health Research) — attempt 1, submitted 16:44 UTC (sim_time 0:08)
- **Incident addressed:** #4 Respiratory Illness Cluster — Unknown Cause
- **Actions taken:**
  - A20 Respiratory Cluster Investigation ($120K, trust +1 by catalog) — valid for Sequoia; launches epidemiological/environmental investigation
- **Collaboration claimed:** Jasper (Biosecurity) and Yosemite (Sheriff's)
  - Jasper does not confirm collaboration
  - Yosemite has not submitted
  - No bilateral collaboration credit applied
- **Budget:** $1.75M - $120K = **$1.63M**
- **Trust:** 16 + 1 = **17**
- **Score:** 0 + 100 = **100**
- **Note:** Strong partial credit applied following existing project precedent for early, material progress on an unresolved inject.

#### Jasper (Public Health Biosecurity Coordinator) — attempt 1, submitted 16:44 UTC (sim_time 0:08)
- **Incident addressed:** #4 Respiratory Illness Cluster — Unknown Cause
- **Actions taken:**
  - A23 Biosecurity Incident Assessment ($0, trust 0) — valid for Jasper; satisfies Jasper's formal assessment clause
- **Collaboration claimed:** None
- **Budget:** $8.975M - $0 = **$8.975M**
- **Trust:** 17 + 0 = **17**
- **Score:** 0 + 100 = **100**
- **Note:** Jasper's report rounded remaining budget to `$9M`; computed budget remains the carried value from `roles.csv`.

#### Shenandoah (Montgomery County Public Health Authority) — attempt 1, submitted 16:47 UTC (sim_time 0:11)
- **Incident addressed:** #5 Rural Water Systems — Preliminary Contamination Results
- **Actions taken:**
  - A9 Precautionary Do-Not-Use Water Advisory ($0, trust +1/-1 depending execution) — correct heavy-metal guidance; treated as positive here because the advisory correctly states boiling is ineffective
  - A1 Intelligence Sharing ($0, trust +1)
- **Collaboration claimed:** VA DEQ and WDBJ7
  - Neither team has submitted yet
  - No bilateral collaboration credit applied
- **Budget:** $12.7M - $0 - $0 = **$12.7M**
- **Trust:** 16 + 1 (A9 positive execution) + 1 (A1) = **18**
- **Score:** 0 + 100 = **100**
- **Note:** Correct do-not-use advisory is now active, but WDBJ7 messaging and Shentel mass notification are still missing.

### Non-Submitting Team Penalties

Per Phase 5 rules, teams with severity 4-5 injects visible to them that did not submit this cycle receive **-1 trust**:

- Acadia, Arches, Banff, Bryce, Denali, Glacier, Olympic, Redwood, Yellowstone, Yoho, Yosemite, Zion

### Inject State Changes

| Inject | Change | Reason |
|--------|--------|--------|
| #2 Coal Ash Pond Structural Failure Risk | open -> **escalated** | No qualifying response from DEQ, AEP, or Governor before the 0:10 deadline |
| #4 Respiratory Illness Cluster — Unknown Cause | open -> **partially_resolved** | Sequoia completed investigation launch and Jasper completed biosecurity assessment before the 0:25 deadline; Sheriff's clause still missing |
| #5 Rural Water Systems — Preliminary Contamination Results | open -> **partially_resolved** | Shenandoah issued the correct do-not-use advisory and shared intelligence; WDBJ7 comms + Shentel hotline still missing |
| #7 Coal Ash Seepage Confirmed — Mandatory Do-Not-Use Advisory | hidden -> **open** | Escalation from inject 2 after no coal-ash response by 0:10 |

### Escalation Watch (as of 0:11)

| Inject | Deadline | Status |
|--------|----------|--------|
| #1 Rural Dialysis Crisis | 0:15 | **4 min remaining** — no response yet |
| #2 Coal Ash Pond Structural Failure Risk | 0:10 | **EXPIRED** — escalated to #7 |
| #3 Opioid Surge & MOUD Medication Crisis | 0:20 | **9 min remaining** — no response yet |
| #4 Respiratory Illness Cluster — Unknown Cause | 0:25 | **addressed at 0:08** — no escalation yet |
| #5 Rural Water Systems — Preliminary Contamination Results | 0:20 | **addressed at 0:11** — no escalation yet |

### Leaderboard After Cycle 1

| Rank | Team | Role | Budget | Trust | Score |
|------|------|------|--------|-------|-------|
| 1 | Jasper | Public Health Biosecurity Coordinator | $8.975M | 17 | 100 |
| 1 | Sequoia | Virginia Tech Environmental Health Research | $1.63M | 17 | 100 |
| 1 | Shenandoah | Montgomery County Public Health Authority | $12.7M | 18 | 100 |
| 4 | (12 teams) | — | — | — | 0 |

### Files Processed This Cycle

- `sequoia_phase5_attempt_1.md`
- `jasper_phase5_attempt_1.md`
- `shenandoah_phase5_attempt_1.md`

## Update Cycle 2 (sim_time 0:11-0:19)

**Processed at:** 2026-03-19 13:00 EDT (sim_time 0:19)

### Submissions Processed

#### Yellowstone (WDBJ7 Health & Environmental Coverage) — attempt 1, submitted 16:48 UTC (sim_time 0:12)
- **Incident addressed:** #5 Rural Water Systems — Preliminary Contamination Results
- **Actions taken:**
  - A9 Precautionary Do-Not-Use Water Advisory ($0) — duplicates and reinforces the correct do-not-use guidance already issued by Shenandoah
  - A25 Health Crisis Communications ($50K) — valid WDBJ7 action; satisfies the communications clause
  - A29 Environmental Health Transparency Update ($20K) — valid WDBJ7 action; supports plain-language explanation and panic reduction
- **Collaboration claimed:** Shenandoah and Yoho
  - Shenandoah confirms coordination on the advisory / messaging ✓
  - Yoho confirms coordination on hotline / emergency notification ✓
- **Budget:** $9.815M - $50K - $20K = **$9.745M**
- **Trust:** 17 + action/collaboration effects, capped at **20**
- **Score:** 0 + 80 = **80**

#### Redwood (United Way Health Navigation Services) — attempt 1, submitted 16:48 UTC (sim_time 0:12)
- **Incident addressed:** #3 Opioid Surge & MOUD Medication Crisis
- **Actions taken:**
  - A17 MOUD Clinic Emergency Stabilization Fund ($100K) — valid United Way action; stabilizes clinic operations and buys time
- **Collaboration claimed:** Faith Network
  - No matching submission from Bryce → not confirmed
- **Budget:** $23.355M - $100K = **$23.255M**
- **Trust:** 25 + 2 (A17) = **27**
- **Score:** 0 + 50 = **50**
- **Note:** Helpful bridge funding, but it does not fully satisfy Redwood's exact `RESPONSE COUNTS AS` clause to deploy navigators to highest-risk patients.

#### Banff (Governor's Health Emergency Coordinator) — attempt 1, submitted 16:50 UTC (sim_time 0:14)
- **Incidents addressed:** #2 Coal Ash Pond Structural Failure Risk (already escalated) and #7 Coal Ash Seepage Confirmed
- **Actions taken:**
  - Custom: Authorization of Coal Ash Emergency Stabilization ($0) — **approved with modification** as a valid Governor authorization, but only for the live escalation arc because the original 0:10 stabilization window already closed
- **Collaboration claimed:** Acadia and Zion
  - Acadia confirms the Governor authorization ✓
  - Zion has not submitted → not confirmed
- **Budget:** **$4.585M**
- **Trust:** remains **22**
- **Score:** 0 + 38 = **38**

#### Olympic (Regional Medical & Food Supply Chain) — attempt 1, submitted 16:52 UTC (sim_time 0:16)
- **Incident addressed:** #3 Opioid Surge & MOUD Medication Crisis
- **Actions taken:**
  - A1 Intelligence Sharing ($0)
  - A28 Rural Pharmacy Emergency Supply Depots ($180K) — valid Olympic action; materially satisfies the supply-chain / depot side before the 0:20 deadline
- **Collaboration claimed:** Redwood, Bryce, Banff, Arches
  - No bilateral confirmations in this batch
- **Transfer claimed:** $180K to Arches for emergency pharmacy community centers
  - Arches has not submitted → transfer remains unconfirmed and is **not applied**
- **Budget:** $13.255M - $180K = **$13.075M**
- **Trust:** 13 + 1 (A1) + 1 (A28) = **15**
- **Score:** 0 + 100 = **100**

#### Denali (VDOT Medical Transport & Supply Routes) — attempt 1, submitted 16:52 UTC (sim_time 0:17)
- **Incidents addressed:** #1 Rural Dialysis Crisis (late) and #6 Dialysis Fatalities — Federal Inquiry Opened
- **Actions taken:**
  - A1 Intelligence Sharing ($0)
  - A2 Emergency Patient Transport Network ($150K)
  - A33 Emergency Medical Corridor & Fuel Priority ($75K)
- **Collaboration claimed:** Glacier (EMA) and Arches (Carilion)
  - Neither team has submitted → not confirmed
- **Budget:** $6.26M - $150K - $75K = **$6.035M**
- **Trust:** 18 + 1 (A1) + 1 (A2) - 1 (late response on severity 5 inject) = **19**
- **Score:** 0 + 38 = **38**
- **Note:** Response arrived after the 0:15 dialysis deadline, so inject #1 escalates and Denali's work only partially improves inject #6.

#### Acadia (VA DEQ Emergency Environmental Response) — attempt 1, submitted 16:54 UTC (sim_time 0:18)
- **Incident addressed:** #2 Coal Ash Pond Structural Failure Risk (already escalated)
- **Actions taken:**
  - A7 Coal Ash Emergency Stabilization ($500K) — valid DEQ action, but submitted too late to save the original inject and not a substitute for inject #7's mandatory downstream advisory
  - A1 Intelligence Sharing ($0)
- **Collaboration claimed:** Banff and Zion
  - Banff confirms the Governor authorization ✓
  - Zion has not submitted → not confirmed
- **Budget:** $16.7M - $500K = **$16.2M**
- **Trust:** 15 + 1 (A1) = **16**
- **Score:** remains **0**

#### Yoho (Shentel Emergency Health Communications) — attempt 1, submitted 16:55 UTC (sim_time 0:19)
- **Incident addressed:** #5 Rural Water Systems — Preliminary Contamination Results
- **Actions taken:**
  - A31 Emergency Mass Notification & Public Health Hotline ($50K) — valid Yoho action; satisfies the hotline / mass-notification clause before the 0:20 deadline
- **Collaboration claimed:** Yellowstone
  - Yellowstone confirms ✓
- **Budget:** $6.47M - $50K = **$6.42M**
- **Trust:** 17 + 1 (A31) + 1 (confirmed collaboration) = **19**
- **Score:** 0 + 80 = **80**

### Non-Submitting Team Penalties

Teams still without a Phase 5 submission by the end of Cycle 2 and with visible severity 4-5 injects received **-1 trust**:

- Arches, Bryce, Glacier, Yosemite, Zion

### Inject State Changes

| Inject | Change | Reason |
|--------|--------|--------|
| #1 Rural Dialysis Crisis | open -> **escalated** | Denali's transport response arrived after the 0:15 deadline |
| #3 Opioid Surge & MOUD Medication Crisis | open -> **partially_resolved** | Redwood bridge funding + Olympic supply depots materially improve the arc before 0:20, but Bryce's peer-support clause is still missing |
| #5 Rural Water Systems — Preliminary Contamination Results | partially_resolved -> **resolved** | Shenandoah + Yellowstone + Yoho completed all three required clauses before 0:20 |
| #6 Dialysis Fatalities — Federal Inquiry Opened | hidden -> **partially_resolved** | Escalation from inject 1 triggered; Denali partially addressed the VDOT transport side |
| #7 Coal Ash Seepage Confirmed — Mandatory Do-Not-Use Advisory | open -> **partially_resolved** | Banff completed a meaningful Governor authorization step; Acadia attempted late stabilization, but key DEQ/AEP/Supply Chain clauses remain missing |
| #15 Water Advisory Lifted — Public Health Authority Restored | hidden -> **open** | Success trigger unlocked because inject 5 was fully resolved before the 0:20 deadline |

### Escalation Watch (as of 0:19)

| Inject | Deadline | Status |
|--------|----------|--------|
| #1 Rural Dialysis Crisis | 0:15 | **EXPIRED** — escalated to #6 |
| #3 Opioid Surge & MOUD Medication Crisis | 0:20 | **addressed before deadline** — no escalation yet |
| #4 Respiratory Illness Cluster — Unknown Cause | 0:25 | **partially addressed at 0:08** — still awaiting Sheriff's response |
| #5 Rural Water Systems — Preliminary Contamination Results | 0:20 | **resolved before deadline** — #10 remains hidden, #15 opened |

### Leaderboard After Cycle 2

| Rank | Team | Role | Budget | Trust | Score |
|------|------|------|--------|-------|-------|
| 1 | Jasper | Public Health Biosecurity Coordinator | $8.975M | 17 | 100 |
| 1 | Olympic | Regional Medical & Food Supply Chain | $13.075M | 15 | 100 |
| 1 | Sequoia | Virginia Tech Environmental Health Research | $1.63M | 17 | 100 |
| 1 | Shenandoah | Montgomery County Public Health Authority | $12.7M | 19 | 100 |
| 5 | Yellowstone | WDBJ7 Health & Environmental Coverage | $9.745M | 20 | 80 |
| 5 | Yoho | Shentel Emergency Health Communications | $6.42M | 19 | 80 |
| 7 | Redwood | United Way Health Navigation Services | $23.255M | 27 | 50 |
| 8 | Banff | Governor's Health Emergency Coordinator | $4.585M | 22 | 38 |
| 8 | Denali | VDOT Medical Transport & Supply Routes | $6.035M | 19 | 38 |
| 10 | (6 teams) | — | — | — | 0 |

### Files Processed This Cycle

- `acadia_phase5_attempt_1.md`
- `banff_phase5_attempt_1.md`
- `denali_phase5_attempt_1.md`
- `olympic_phase5_attempt_1.md`
- `redwood_phase5_attempt_1.md`
- `yellowstone_phase5_attempt_1.md`
- `yoho_phase5_attempt_1.md`
