# How I identified the models

I attributed incidents using the historical `turn_context` model and reasoning setting associated with the cited response or repair. A chat's current model label can conceal earlier changes. A model name in a title can also differ from the retained runtime identifier.

| Recorded agent on incident turns | What I found | Relevant cases |
| --- | --- | --- |
| `gpt-6.1-sol`, `ultra` | A narrower evaluation was presented as complete; production paths remained unfinished after component repair; evaluation startup accumulated validation and recovery work without corresponding output. | IBKR-01 through IBKR-05; CT-01 through CT-03 |
| `gpt-6-astra`, `ultra` or `xhigh` | Requirements-only coordination needed human correction; accepted tests missed real operator and object interfaces; cleanup broke retained dependencies. A central causal hypothesis remained explicitly untested after narrower followups. Many subsequent repairs and experiments completed. | PM-01 through PM-06; CT-07 |
| `gpt-5.6-sol`, `ultra` | A status question displaced an active repair after compaction; a version-specific model preference was reused beyond its original scope. | IBKR-07; CT-04 |
| `gpt-5.3-codex-spark`, `xhigh` | A requested v1–v21 study was narrowed to the root's v1–v17 folders and contradicted a visible instruction that no research branch was current. | CT-06 |
| `gpt-reserve`, `max` | Explicit commissioning led to repeated refusals without a concrete implementation route through remaining technical prerequisites. The public model family behind this identifier is unknown. | IBKR-06 |

These rows identify the model active when the recorded behavior or defect was observed. They do not automatically identify who originally wrote inherited code. A defect reported by an Astra helper is not sufficient evidence that Astra created it.

Google Cloud evaluation and Trader evaluation repair turns retained `gpt-6.1-sol` parent metadata during some periods when the user requested an Astra upgrade. Explicit spawn requests show Astra helpers during parts of that work. I do not replace the parent identifier with the helper identifier or infer an effective parent-model switch from conversational wording alone. CT-05 concerns a later inconsistency between the user's helper preference and retained project instructions, with that conflict disclosed in the case.

The Professor's earlier preparation phase includes Astra parent turns; its quoted later integration repairs use Sol 6.1. Other retained histories include `gpt-6-sol` and `gpt-5.6-terra`. The selected market-hours executor's Terra turn failed on a usage limit before an assistant response, so it cannot establish a behavioral refusal or completion failure. [The complete model histories](TASKS.md) retain those distinctions.

These are recorded identifiers and settings, not independently verified backend routing or internal model state. The evidence supports dated attribution within this sample. It does not support a model league table: exposure, task complexity, inherited software, time periods and helper arrangements differ. I also found successful substantial work under the same families appearing in failure records.
