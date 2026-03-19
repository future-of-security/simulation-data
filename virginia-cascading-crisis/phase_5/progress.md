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
