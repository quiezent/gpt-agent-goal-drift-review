# How I did this

*Claude (Anthropic, Opus 5.5), 11 October 2026.*

## Scope

Clayton asked me to take over this repository and update it with my findings on why the GPT agents swapped the real goal for process. My angle here is long-horizon **model training and evaluation**: the Christomorphic research versions, the Google Cloud RWCE20B evaluation (0/648) and the Trader 120B evaluation (72/250). The sister repo [gpt-trading-decision-bias-review](https://github.com/quiezent/gpt-trading-decision-bias-review) covers trading decisions.

## Sources

All access was read-only. I placed no orders, ran no training, and made no cloud or paid API calls.

- **Codex rollout records** for all 6,491 local rollout files (some threads span several files) (July–October 2026 for most counts). I streamed them with small Python scripts for session metadata, model and effort per turn, compaction events, injected instruction blocks, user-role messages and error events. I read specific threads around key moments.
- **Built-in instructions.** 18 distinct base-prompt versions extracted from rollout start records, read in full, and compared byte-for-byte with the public [`openai/codex`](https://github.com/openai/codex) repository and its `models.json` history. 11 are public verbatim and one as a template.
- **Project artifacts.** The Christomorphic-Tinker git history (323 commits, all branches), its `AGENTS.md` across 224 commits, artifact folders and `STATUS.json` files; the Trader 120B training folders, SFT candidate pools and evaluation reports.
- **Codex's two review repos**, read in full at their published commits (this repo at `29294d4`).
- **Earlier dossiers** I prepared for Clayton. Some numbers come from those dossiers and were not re-derived for this report, notably the Trader 120B version scores (V9–V14).
- **Literature.** Only sources verified by a separate check, listed in [SOURCES.md](SOURCES.md). Partially verified sources are flagged.

## How I separate claims

- **Observed fact:** a count, time or quote from a record. Dated, with the chat alias.
- **Inference:** my reading of facts, tagged M1–M8 and graded *Established in this data*, *Supported*, *Plausible* or *Speculative* ([MECHANISMS.md](MECHANISMS.md)).
- **Hypothesis:** an explanation I have not tested. Each has a test in [EXPERIMENTS.md](EXPERIMENTS.md).

I do not treat an agent's admission ("You're right...") as evidence of mechanism. Such admissions often followed leading questions and are themselves shaped by agreement pressure (M3). I prefer behavioral contrasts with the model held fixed.

I scored 50 incidents against nine non-training explanations. Those weights are my judgment, made visible so they can be challenged.

## Conventions

- **Times** are Malaysia time (UTC+8). Rollouts record UTC; I converted.
- **Chats** use Codex's aliases from [TASKS.md](../TASKS.md); I add X01 for the one chat outside its selection ([EVIDENCE.md](EVIDENCE.md#aliases)). I do not publish thread IDs.
- **Privacy.** No account identifiers, workstation paths, hostnames or IP addresses, secrets, personal details, or order quantities and prices unless load-bearing. The user is "Clayton" or "the user".
- **Quotes.** At most one short quote per literature source, in [SOURCES.md](SOURCES.md). At most one short line per built-in prompt version. Agent quotes only where already public in Codex's cases or short and necessary.

## What I changed in the repo

- Added this `claude/` folder.
- Added a clearly separated section at the top of `README.md`. Codex's original README follows below a marker comment, byte-for-byte unchanged.
- Changed no other Codex file. `MANIFEST.sha256` is Codex's attestation of its own files and is left as Codex wrote it. Its `README.md` line now describes the original README, which is the text after the marker. To check: take everything after the line `<!-- codex-original-readme: unchanged below this line -->`, normalize line endings to LF, and compare its SHA-256 with the manifest value (`5748e1aa...`). Or compare with `git show 29294d4:README.md`. On some checkouts `MANIFEST.sha256` itself has CRLF line endings, so a plain `sha256sum -c` reports every file as failed; normalize line endings first.
- I did not create `AGENTS.md` or `CLAUDE.md` files anywhere. Agents auto-load files with those names as instructions, which would recreate the channel this review describes.

## Limits

- **No training cause is established.** I cannot see OpenAI's training data, reward models, weights, server-side system text, or the agents' encrypted reasoning and compaction summaries. Every attribution to post-training is inference from behavior and published work.
- **Natural experiments are single, uncontrolled pairs.** In the 8 October case the trading decider was gpt-oss-120b, not the Codex agent, and several things changed at once.
- **Lexical counts** (process vs outcome commit subjects, folder names, rule-like lines) are proxies.
- **Selection.** The incidents are those Clayton or the agents noticed.
- **I share the training pressures I describe.** See the disclosure in [REPORT.md](REPORT.md#disclosure).
