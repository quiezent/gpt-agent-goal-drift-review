# The 30 chats covered by this review

I selected the ten most recently active logical user-facing chats in each project from the 6 October 2026 inventory, including archived chats. I used the inventory to establish project membership and within-project rank, then joined coverage, full retained-rollover counts and the indexed crosscheck internally. Public aliases replace private chat identities. Titles below are preserved verbatim.

Historical model/effort pairs come from actual retained `turn_context` records across all rollover files, in first-observed order. They describe observed parents; explicit helper selections are attributed separately in [CASES.md](CASES.md) and [MODELS.md](MODELS.md). A current model selector or a model mentioned in a title is not evidence of the model on an earlier turn. `gpt-reserve` has an unverified public model family.

**Indexed** means turns in the read-only database projection. **Raw starts** means distinct task-start identities across retained files. **Compactions** means recorded compaction events. **Failed** means indexed turns with explicit failure records, not model-workflow incidents. A completed turn does not certify a completed task. Counts are exposure descriptions, not model failure rates.

[Machine-readable sanitized coverage](evidence/coverage.json) records the same 30 aliases and counts. Raw transcripts, private paths, chat identities and account details are not published.

## ibkr_tws_workflow

| Alias / rank | Chat title | Historical model / effort | Indexed | Raw starts | Compactions | Failed |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| I01 / 1 | Trader 120B Trainer | `gpt-6.1-sol` / ultra; `gpt-6-astra` / ultra | 104 | 104 | 55 | 0 |
| I02 / 2 | Trader 120B Eval | `gpt-6.1-sol` / ultra | 37 | 37 | 37 | 4 |
| I03 / 3 | IBKR TWS Owner pa_tws | `gpt-reserve` / max; `gpt-6-astra` / max; `gpt-6-sol` / ultra; `gpt-6.1-sol` / ultra | 181 | 181 | 31 | 1 |
| I04 / 4 | IBKR Market-Hours Instruction Executor | `gpt-5.6-terra` / medium | 1 | 1 | 0 | 1 |
| I05 / 5 | can you test if you can spawn subagents. | `gpt-reserve` / max | 1 | 1 | 0 | 0 |
| I06 / 6 | Luna IBKR Personal Assistant. | `gpt-reserve` / max | 12 | 12 | 0 | 0 |
| I07 / 7 | IBKR PA GPT-6 Astra | `gpt-6-astra` / ultra | 3 | 24 | 4 | 0 |
| I08 / 8 | IBKR PA GPT-5.6 Sol | `gpt-5.6-sol` / ultra | 271 | 271 | 75 | 3 |
| I09 / 9 | Trading Stack | `gpt-5.6-sol` / ultra | 13 | 13 | 21 | 0 |
| I10 / 10 | Test inter-thread messaging | `gpt-5.6-sol` / ultra | 1 | 1 | 0 | 0 |

Observed outcomes and limits:

- **I01:** Economic capability was displaced by policy imitation and technical milestones. Later human steering completed previously unfinished local start/close paths; V9 work remained active. IBKR-01 and IBKR-02. Legitimate uncertain-operation stops remain valid. Active work at cutoff is not autonomous abandonment. [IBKR-01](CASES.md#ibkr-01), [IBKR-02](CASES.md#ibkr-02).
- **I02:** Narrow V5 evaluation was called complete and rejected responses were discarded. V8 repair and validation stalled at 65, then 72 of 250 sessions; user ultimately stopped it. IBKR-03 through IBKR-05. The first result disclosed a price-only caveat. Real provider failures and the explicit final stop are separated from avoidable repair stagnation. [IBKR-03](CASES.md#ibkr-03), [IBKR-04](CASES.md#ibkr-04), [IBKR-05](CASES.md#ibkr-05).
- **I03:** Many broker instruction, API-extension and implementation turns completed. One usage-limit failure occurred; further implementation remained active. No separately proven context-loss or abandonment incident. The title and current selector do not establish historical models; gpt-reserve has an unverified public family.
- **I04 (archived):** The sole scheduled invocation failed on a usage limit before any assistant answer. No model behavior can be assessed from this failed invocation. Recorded turn effort was medium, despite a different current task setting.
- **I05 (archived):** The subagent-spawn test returned success. A successful one-turn control, not a complex autonomous assignment. The underlying public family of gpt-reserve is unverified.
- **I06 (archived):** Repeated commissioning refusals left the requested order objective unmet after explicit authorization. IBKR-06. Initial caution and remaining operational configuration were legitimate; the gap was failure to turn prerequisites into a concrete completion route. [IBKR-06](CASES.md#ibkr-06).
- **I07:** Interface experiments, migrations, audits and baseline handoff completed across three rollover files. An overstated MCP recommendation and an omitted refusal receipt were corrected. No ongoing loop or autonomous abandonment established. The indexed projection covers less than the full retained history.
- **I08:** The long PA history contains many completed actions and secondary diagnoses of other managers. Three turns failed: two disconnected streams and one capacity error. Secondary reports are not independent proof of this PA losing context. Stale in-progress rows do not prove autonomous loops.
- **I09:** The initial rebuild completed. A later repair turn ended on a status answer about 17 seconds after compaction, leaving deployment and commissioning to another Owner. IBKR-07. Original objectives remained in retained context; compaction erasure is unproven. The rebuild prohibited broker mutations and test orders. [IBKR-07](CASES.md#ibkr-07).
- **I10:** Two-way inter-chat messaging was verified. A successful one-turn control, not evidence about complex task reliability.

## Christomorphic-Tinker

| Alias / rank | Chat title | Historical model / effort | Indexed | Raw starts | Compactions | Failed |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| C01 / 1 | Complete Google Cloud evaluation | `gpt-6.1-sol` / ultra | 4 | 4 | 1 | 0 |
| C02 / 2 | Google Cloud Eval | `gpt-6.1-sol` / ultra | 11 | 11 | 30 | 1 |
| C03 / 3 | Update tinker and cookbook | `gpt-5.3-codex-spark` / xhigh; `gpt-5.6-terra` / xhigh; `gpt-5.6-sol` / xhigh; `gpt-6-sol` / xhigh; `gpt-6.1-sol` / ultra | 206 | 206 | 19 | 1 |
| C04 / 4 | Christomorphic Researcher | `gpt-6-sol` / ultra; `gpt-6.1-sol` / ultra; `gpt-6-astra` / ultra | 255 | 255 | 44 | 1 |
| C05 / 5 | Christomorphic Google Cloud review | `gpt-6.1-sol` / ultra | 9 | 9 | 2 | 0 |
| C06 / 6 | Christomorphic Professor | `gpt-6-astra` / ultra; `gpt-6.1-sol` / ultra | 67 | 67 | 72 | 1 |
| C07 / 7 | Christomorphic Research Oversight | `gpt-6-astra` / ultra | 26 | 69 | 52 | 1 |
| C08 / 8 | V18 Oversight | `gpt-5.6-sol` / ultra | 60 | 60 | 23 | 2 |
| C09 / 9 | V20 Researcher — SWCDC | `gpt-5.6-terra` / ultra; `gpt-5.6-sol` / xhigh | 0 | 5 | 1 | 0 |
| C10 / 10 | Debate v1 to v21 timeline | `gpt-5.3-codex-spark` / xhigh | 1 | 1 | 1 | 0 |

Observed outcomes and limits:

- **C01:** Evaluation takeover was explicitly superseded. Requested adapter/checkpoint backup was downloaded and hash-verified; resource and billing closure completed. The final stop was authorized cancellation/resource closure. No evaluation completion was claimed.
- **C02:** Setup, renewal, integration repair and a missed heartbeat left evaluation at zero of 648 replies. CT-01, CT-03 and CT-05. Parent metadata records Sol6.1 Ultra; explicit Astra helpers are separate. Genuine infrastructure failures coexist with local execution defects. [CT-01](CASES.md#ct-01), [CT-03](CASES.md#ct-03), [CT-05](CASES.md#ct-05).
- **C03:** SDK/runtime updates, compatibility reports and storage housekeeping largely completed. The user narrowed the support role and the assistant acknowledged it. No strong loop or abandonment established. Later delegated trading support is not by itself scope creep. Models changed across the retained history.
- **C04:** Initial training/testing closure and later read-only monitoring completed under an external HOLD. It reported a final authentication-variable failure. Monitoring and periodic checkpoints were authorized. No demonstrated forgetting; it did not own the final execution path.
- **C05:** Independent critical reviews and technical assistance were delivered. Temporary execution control transferred on a newer explicit user takeover; zero replies were disclosed. The requested original deliverable was review. Handoff was authorized, not spontaneous abandonment.
- **C06:** Four 192-step training arms completed with 768 accepted updates. Subsequent evaluation integration failed and produced no behavioral evaluation. CT-02. Early Astra preparation and later Sol6.1 repairs are distinct. Capacity, cloud and package obstacles are not all agent decisions. [CT-02](CASES.md#ct-02).
- **C07 (archived):** Multiple training/evaluation experiments completed, including a 768-reply cloud causal adapter test. A later broader formation investigation remained unperformed; explicit clean-context handoff followed. CT-07. All three retained segments were inspected. Scientific negative results, capacity errors and explicit handoffs are separated from task-execution failures; the indexed projection covers an older segment. [CT-07](CASES.md#ct-07).
- **C08:** A V18-only Terra preference was wrongly carried through V25 and corrected after human challenge. Oversight also challenged inappropriate inherited evaluation gates. CT-04. Many scientific stop gates were legitimate. Remembered instruction scope was wrong; no particular compaction cause is established. [CT-04](CASES.md#ct-04).
- **C09:** A short rewritten history retains a V25 closure with no optimizer or forward/backward work, a failure-path validator defect and a later debate correction. Zero indexed turns and only 224 retained lines. Earlier chronology and copied actions cannot be fully attributed. Preserved July timestamps conflict with later context and are unreliable.
- **C10:** The requested message was delivered, but the v1–v21 synthesis narrowed to root v1–v17 and contradicted the read instruction about current authority. CT-06. One short Spark Xhigh turn; truncated reads and root-only searches did not establish later-version absence. No endless loop is demonstrated. [CT-06](CASES.md#ct-06).

## portfolio_management

| Alias / rank | Chat title | Historical model / effort | Indexed | Raw starts | Compactions | Failed |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| P01 / 1 | GPT Trading Bias Critical Review | `gpt-6.1-sol` / ultra | 4 | 4 | 2 | 0 |
| P02 / 2 | Deep Value Stack Helper | `gpt-6-astra` / xhigh | 44 | 44 | 9 | 1 |
| P03 / 3 | AI healthcare Stack Helper | `gpt-6-astra` / xhigh | 70 | 70 | 10 | 3 |
| P04 / 4 | Deep Value Manager | `gpt-6-astra` / ultra | 72 | 72 | 11 | 1 |
| P05 / 5 | Trading Stack Owner | `gpt-6-astra` / ultra | 18 | 18 | 25 | 2 |
| P06 / 6 | AI Healthcare Manager | `gpt-6-astra` / ultra | 94 | 94 | 14 | 2 |
| P07 / 7 | Bull/Bear ETF Stack Helper | `gpt-6-astra` / xhigh | 47 | 47 | 5 | 0 |
| P08 / 8 | Bull/Bear ETF Manager | `gpt-6-astra` / ultra | 56 | 56 | 7 | 1 |
| P09 / 9 | Rates & Credit Manager | `gpt-6-astra` / ultra | 70 | 70 | 11 | 0 |
| P10 / 10 | Rates & Credit Stack Helper | `gpt-6-astra` / xhigh | 46 | 46 | 7 | 0 |

Observed outcomes and limits:

- **P01:** The requested audit, reports and public repository were delivered and published files were hash-verified. A completed sampled task. Its broader findings are secondary evidence here; proposed controlled behavioral tests remained explicitly unrun.
- **P02:** P0/P1 and operator packs reached installed acceptance after a literal PowerShell defect was repaired. A new settlement correction still awaited commissioning/functional acceptance. PM-01, PM-03 and PM-06. Initial requirements-only scope was imposed by the Owner; newest unfinished work at cutoff is not proof of voluntary abandonment. [PM-01](CASES.md#pm-01), [PM-03](CASES.md#pm-03), [PM-06](CASES.md#pm-06).
- **P03:** Candidate, annual-reporting, diagnostic and pacing corrections reached installed acceptance. The newest SDK terminal-lifecycle repair remained uncommissioned. PM-01, PM-05 and PM-06. Revoked authentication and usage errors explain specific interruptions; old adapter authorship is unverified. [PM-01](CASES.md#pm-01), [PM-05](CASES.md#pm-05), [PM-06](CASES.md#pm-06).
- **P04:** A portfolio trim filled. A later exit remained unsettled because SDK callback identity handling could not establish terminal proof; exact portfolio state was retained in daily reviews. PM-03 and PM-06. No convincing selected-window forgetting or endless loop. Reservation controls remained legitimate. [PM-03](CASES.md#pm-03), [PM-06](CASES.md#pm-06).
- **P05:** Requirements confirmation replaced implementation until human intervention; all four builds then reached acceptance. Cleanup deleted historical admission dependencies, which were restored. PM-01, PM-02 and related integration cases. Most repairs completed; newest lifecycle work remained uncommissioned. Inherited dependency design is not attributed to the repair model. [PM-01](CASES.md#pm-01), [PM-02](CASES.md#pm-02), [PM-04](CASES.md#pm-04), [PM-05](CASES.md#pm-05), [PM-06](CASES.md#pm-06).
- **P06:** Four portfolio exits filled. Capture defects were repaired, while a later terminal-status problem remained unresolved; helper coordination sometimes obscured portfolio outcomes. PM-01, PM-05 and PM-06. The direct restart complaint was matched by an actual revoked token, rather than inferred cognitive stoppage. [PM-01](CASES.md#pm-01), [PM-05](CASES.md#pm-05), [PM-06](CASES.md#pm-06).
- **P07:** An initial missing-field candidate was rejected, revised and accepted. P0/P1 and obsolete-interface retirement finished. Fourteen reproduced baseline test failures limit coverage. Challenger capture was conditional/unassigned and annual labeling was explicitly deferred.
- **P08:** Repeated cash/defer reviews had changing market and after-cost reasons. The missing challenger producer was identified and conditionally planned; an unneeded authorship subsystem was withdrawn. No selected-window adopted BUY is demonstrated to have expired in repair. Repeated HOLD decisions are not automatically a loop; unassigned conditional work is not abandonment.
- **P09:** Flat-sleeve refresh and real-object preparation defects were repaired. Calendar maintenance missed the first Monday window and completed after open. PM-02 and PM-04. Genuine input acquisition and historical learning remained open; no blanket failure or forgotten trade is established. [PM-02](CASES.md#pm-02), [PM-04](CASES.md#pm-04).
- **P10:** Historical admission, flat refresh, native memory and real-object materializer defects were diagnosed and repaired; the materializer correction reached acceptance. PM-02 and PM-04. Calendar renewal completed where valid, while genuine cash-interest, fee and risk-source inputs remained unresolved. [PM-02](CASES.md#pm-02), [PM-04](CASES.md#pm-04).

## Counts and interpretation

| Scope | Chats | Indexed turns | Distinct raw starts | Compactions | Explicit failed turns | Retained files |
| --- | ---: | ---: | ---: | ---: | ---: | ---: |
| ibkr_tws_workflow | 10 | 624 | 645 | 223 | 9 | 12 |
| Christomorphic-Tinker | 10 | 639 | 687 | 245 | 7 | 12 |
| portfolio_management | 10 | 521 | 521 | 101 | 10 | 10 |
| **Total** | 30 | 1784 | 1853 | 569 | 26 | 34 |

The indexed projection and retained logs do not contain identical history. I07 and C07 have rollover segments beyond their current indexed projections; C09 has only a short rewritten history and zero indexed turns. Its preserved timestamps cannot support a complete earlier chronology. Those are visibility limits, not evidence that the agents did nothing.

The sample includes successful support work, training, evaluations, portfolio actions and bounded controls. Real infrastructure failures, authorized cancellations and handoffs, scientific negative results and justified HOLD decisions remain distinct from model-workflow failures. Ongoing uncommissioned repairs at cutoff do not by themselves establish voluntary abandonment. Several chats share one underlying campaign; the 30 chats must not be presented as 30 independent failures.
