# Phase 1: System Breach

**Course Topic:** Cybersecurity & AI Threats

**Time Period:** Day 1 of the main crisis — a Tuesday morning, 60 minutes of simulated time.

---

## Context

At 06:20 a scheduled job on a Virginia Tech research cluster ran three minutes long and then ran again. Nothing alerted: the process was signed, the traffic looked like the traffic that machine always makes, and the endpoint agent scored it clean four times in a row. What is on that cluster tunes itself to the environment it lands in — it watches for a week, learns what normal looks like on the host it is on, and then imitates it.

It did not stay on the cluster. Virginia Tech and Carilion Clinic share a research connection — de-identified imaging for a stroke study, a link both institutions' security reviews approved in 2024 and neither has looked at since. By 07:40 the malware is inside Carilion's clinical network. By 08:05 the electronic health record is returning records that do not match their patients, and the infusion pumps, imaging units and monitors that live on the same VLAN are logging configuration changes nobody made.

Six Carilion rural clinics — Grundy, Tazewell, Wise, Lebanon, Marion, and Big Stone Gap — lose their records link entirely and open their doors anyway, because the patients are already in the parking lot. Food City's pharmacy counters cannot verify a prescription against a system that is not answering. VITA sees scanning from regional addresses against the Commonwealth's shared services, which is what county government in nine counties runs on. And in Richmond, the Governor's office wants one thing before a 10:00 availability: is patient data gone, and is it safe to go to a clinic today.

Nobody has yet answered the question every other decision depends on: what is this, and is it still spreading.

---

## Crisis Engine Analysis

### What just changed unexpectedly?
An intrusion that has been in place for at least a week became visible only when it crossed institutional boundaries. The change is not the malware — it is the discovery, and the discovery arrives at the worst possible point in its spread: already inside a hospital that cannot stop admitting patients, already inside the network six rural clinics depend on, and already looking at the connection between a region and its state government. Every team learns about it from a different symptom, and no team's symptom explains the others.

### Which system is now stressed?
- [x] Infrastructure: the research cluster, the clinical network, the shared research link, the Commonwealth's shared services
- [x] Health: the electronic health record, networked medical devices, six clinics running blind, prescription verification chain-wide
- [x] Information: nobody yet knows what the malware is, what it took, or whether it is still moving — and Richmond wants an answer at 10:00
- [x] Governance: county government runs on state shared services that may have to be cut off to be saved
- [ ] Economy: not the pressure point this phase; it arrives in phase 3
- [x] Cross-institutional: a university, a health system, a telecom, a state agency and two federal agencies all hold a piece and none holds the picture

### Who experiences immediate harm?
- [x] Individuals: patients whose records return wrong, dialysis and oxygen patients whose schedules live in a system that is down, anyone at a pharmacy counter with a prescription that cannot be verified
- [x] Vulnerable communities: households in the coalfield counties whose only clinic is one of the six, patients with no transport to a facility that is still online
- [x] Institutions: Carilion, Virginia Tech, Food City, nine county governments
- [ ] Cross-border populations: not yet

### What decision must be made within limited time?
**Contain, or keep operating?** Almost every action that stops the spread also stops care. Cutting the shared research link protects the clinical network and strands whatever still rides it. Taking the EHR down protects the record and puts six clinics on paper. Quarantining the devices protects the devices and takes a clinician away from a patient to do it. Imaging the compromised hosts preserves a federal case and keeps those hosts down for hours a clinic does not have. Cutting the region off the Commonwealth's shared services protects the state and takes county government offline.

Underneath all of it is a sequencing problem: nobody can size any of these decisions until CISA and Virginia Tech characterise what the malware actually is, and that analysis takes fifteen minutes nobody wants to spend. Teams that contain first and analyse afterwards will contain the wrong thing; teams that analyse first and contain afterwards will analyse a wider blast radius.

### What future risk is created by this decision?
- **Speed over thoroughness:** a rushed restoration reconnects a clinic to a path that was never verified, and phase 2 opens with stolen patient data on a forum and no answer about how much.
- **Thoroughness over speed:** a careful, evidence-preserving response leaves six clinics on paper into the afternoon, and phase 2's rumor is about a health system that abandoned the coalfields, not about a breach.
- **Either way:** what the region says today is what phase 2's disinformation will be built out of. A statement that overpromises — "no patient data was affected" — is the single most expensive sentence available this phase.

### Who makes the decision, and who is left out?
- **Decision makers:** Everglades (VT IT), Yellowstone (Carilion InfoSec), Denali (rural clinics), Zion (CISA), Glacier (FBI), Banff (VITA), Redwood (Shentel), Shenandoah (VDH), Katmai (Food City pharmacy), Acadia (EMA), Olympic (Governor's Liaison), Teton (faith network)
- **Stakeholders excluded:** the patient whose record came back wrong, the clinician who has to decide whether to trust a pump, the pharmacist deciding whether to dispense, the researcher whose seven-year dataset is on the cluster somebody is about to power off, the county clerk whose systems go dark to protect a state network
- **Why this matters:** every decision this phase is made by someone technical, on behalf of someone who will never be told it was made.

---

## Team Roles This Phase

**All 12 teams are active**, and every team holds a different sector than it held in phase 0.

| Team | Role | Focus This Phase |
|------|------|------------------|
| Acadia | SW Virginia EMA | County government continuity, and the call on whether a cyber incident is an emergency before anyone has proof |
| Banff | VITA Commonwealth CIO | The state's own exposure, and whether to cut the region off from the services it runs on |
| Denali | Carilion Rural Clinic Network | Six clinics with no records, doors open, patients waiting |
| Everglades | Virginia Tech Division of IT | Patient zero: the research network, the shared link, and the researchers who will not accept an offline cluster |
| Glacier | FBI Richmond Cyber Task Force | Attribution and evidence — what is preserved, and what gets wiped in the hurry to recover |
| Katmai | Food City Pharmacy Systems | What a pharmacist may dispense when nothing can be verified |
| Olympic | Governor's SW Virginia Liaison | One consolidated answer for Richmond, and the only budget that can underwrite another team's action |
| Redwood | Shentel Communications | The network the spread travels on: segmentation, and the clinic links |
| Shenandoah | VA Department of Health SW District | Care continuity across the district, and what the public is told about patient safety |
| Teton | Appalachian Faith & Community Network | The patients no working system can reach today |
| Yellowstone | Carilion Clinic Information Security | Containment inside a hospital that cannot stop admitting |
| Zion | CISA Regional Coordinator | What this malware is, and what the region is allowed to be told |

---

## Phase Rules

- Every rule from phase 0 is in force: the dashboard is the live picture, the response report is what a facilitator reads, and an incident nobody claims escalates on its own clock.
- Budgets carry: what a team did not spend in phase 0 is still there, plus this phase's allocation for the role it now holds.
- **Scores count from this phase on.**

## Learning Objectives

- Trace a cascade that crosses institutional boundaries nobody was watching.
- Weigh containment against continuity when both are real and the evidence is incomplete.
- Sequence analysis and action under time pressure, and pay for getting the order wrong.
- Say something true and useful in public before the facts are complete — and understand what phase 2 does with anything said carelessly here.
