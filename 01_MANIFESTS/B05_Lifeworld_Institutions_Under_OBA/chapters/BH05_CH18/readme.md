| id              | book | chapter | type   | status |
|-----------------|------|---------|--------|--------|
| B05.CH18.README | B05  | CH18    | readme | draft  |

<a id="b05ch18readme"></a>
# B05.CH18 — Failure modes in the lifeworld: resentment, sabotage, evasion, bureaucratic drift, capture

This chapter defines **lifeworld failure modes** as a normative early-warning and stop-rule system for OBA implementations. It targets a
recurrent pattern: institutions “formally comply” with written rules while the lifeworld degrades through friction, opacity, selective
execution, extraction shifts, or capture. CH18 makes this pattern executable: it specifies a taxonomy, detection indicators, escalation
paths, and **FAIL-CLOSED** stop rules that block scaling and force remediation.

CH18 binds directly to the lifeworld test (**B,T,N,L,R + tails + time friction**) and to OBA rails for **contestability, auditability,
anti-evasion, and crisis handling**. Narrative and communications management are explicitly insufficient. The truth condition is: **measured
lifeworld integrity + visible repair**.

---

## Conformance gates (chapter-level)

A conform implementation **MUST**:
- Run continuous lifeworld tests (B,T,N,L,R + tails) and publish early-warning dashboards in aggregated form.
- Treat repeated breach indicators as stop conditions (FAIL-CLOSED): scaling blocked until remediation passes re-test.
- Preserve contestability (appeals, interim relief, anti-retaliation) and auditability (tamper-evident logs, restatements).
- Maintain anti-evasion capability (shift taxonomy, channel controls, presumptions under opacity).
- Prevent drift/capture (audit-on-the-auditor, procurement discipline, privacy rails, exception controls).

A conform implementation **MUST NOT**:
- Substitute narrative, symbolism, or KPI theater for material L/tail improvement and repair paths.
- Use surveillance/data maximalism as “measurement”; microdata publication is prohibited.
- Allow carve-outs, shadow regimes, selective enforcement, or silent rule/method drift.

---

## Scope

CH18 covers five failure mode classes across local/national/sector implementations:
- **Resentment** (experienced injustice/friction despite macro claims)
- **Sabotage** (active interference: slow-roll, strikes, data degradation, vandalism, political vetoes)
- **Evasion** (extraction shifts into new forms/channels)
- **Bureaucratic drift** (Goodhart, procedure inflation, data maximalism, tooling capture)
- **Capture** (economic/political/epistemic/cultural)

---

## How to use this chapter

- If you are **auditing an implementation**: treat CH18 as the stop-rule framework. If indicators repeat, scaling halts and remediation is
  mandatory (P20).
- If you are **building sector cases (CH17)**: embed CH18 checks in every sector template instance (P18.S01). A sector case must carry
  its own early-warning triggers and stop rules.
- If you are **using day-in-the-life cases (CH14–CH16)**: treat them as regression tests. “After” cases must not worsen tails, time
  poverty, integrity, or privacy (P18.S02).
- If you are **operating institutions (CH12)**: contestability and auditability are primary design constraints, not optional features
  (P18.S03).
- If you are **handling transition conflict (Book 2)**: sabotage and retaliation scenarios are pre-modeled and linked (P18.S04).

---

## Structure

P01 — Purpose, scope, and normative status of lifeworld failure modes  
P02 — Failure-mode taxonomy: five classes and their causal logic  
P03–P05 — Resentment: mechanism → detection → mitigation  
P06–P08 — Sabotage: mechanism → detection/escalation → mitigation/hard stops  
P09–P11 — Evasion: logic → detection → remedies (reclassification + channel control + versioning)  
P12–P13 — Bureaucratic drift: mechanism → detection/correction  
P14–P15 — Capture: forms → detection/evidence/hard stops  
P16 — Human agency: why failure modes cannot be “measured away”  
P17 — Evolutionary infrastructure: controlled iteration (patch cycle, rollback, backward compatibility)  
P18 — Integration: how CH18 makes the rest of Book 5 enforceable  
P19 — Measurement and publication requirements (early-warning dashboard)  
P20 — Close: stop rules and minimal repair paths  

---

## Status

This chapter is **normative** for OBA implementation integrity. It defines what counts as a breach even when formal compliance exists:
persistent friction, rising L volatility, worsening tails, integrity/privacy failures, selective enforcement, shadow regime growth, drift,
or capture.

CH18 is also **enforcement-enabling**: it provides the stop rules and minimal repair paths required to keep OBA compatible under adversarial
conditions. If an implementation cannot instantiate CH18 (publish early-warning proxies, run audits/restatements, enforce rollback and
governance resets), then it is structurally unable to maintain conformance over time and must be treated as **NON-CONFORM** or restricted
to auditable scope (fail-closed).
