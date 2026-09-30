# kp-sum-up · Sum Up

> **KP Pure Tools**: runs standalone — not part of the Knowledge Palace mounted system.
> Member ④ of the lightweight **“X yixia”** skill family — turn records over a period into a summary and a plan.
> Version 1.0 · 2026-09-30 · Author: 王亚宁 (kp-wyn)

## Family Navigation

| Command | Skill | Status | What it does |
| --- | --- | --- | --- |
| 记一下 (Capture) | [kp-remember](https://github.com/kp-wyn/kp-remember) | Released | Stores content as-is, zero processing |
| 收拾一下 (Tidy up) | [kp-tidy-up](https://github.com/kp-wyn/kp-tidy-up) | Released | Batch-organizes a backlog of old notes |
| 消化一下 (Digest) | kp-digest | Mounted version ready; standalone coming soon | Distills fresh fragments on the spot |
| 理一下 (Sum up) | [kp-sum-up](https://github.com/kp-wyn/kp-sum-up) | Released (this skill) | Turns records into a summary and plan |

## Features

- **Auto-classify**: completed items, to-dos, schedules and key agreements — no manual sorting;
- **Visual + PDF**: produce a clean HTML and export a ready-to-send PDF;
- **Periodic review**: weekly / monthly / project phase / client-communication summaries;
- **Standalone**: no Knowledge Palace required; pairs best with `kp-remember`.

## Quick Start

Say “sum up this week” — it reads your records, categorizes them, and outputs a visual HTML page plus a shareable PDF.

## Installation

1. On the repo page click **Code → Download ZIP**;
2. Unzip; copy the skill folder (drop any `-main` suffix, name it `kp-sum-up`) into your AI’s `.user_skills/` directory;
3. Restart your AI — it is ready to use.

## Output

```
summary_projectname_20260920.html   # visual web version
summary_projectname_20260920.pdf    # shareable PDF version
```

The HTML includes: an overview, completed items, to-dos (with priority), schedules and key agreements.

## Supported Types

Weekly / monthly summaries and plans, project-phase summaries, and client-communication summaries.

## Notes

- A **KP Pure Tool** — not part of the Knowledge Palace mounted system;
- It only organizes and formats — it never creates content out of thin air;
- Data comes from kp-remember records; with no records it prompts you to capture first;
- Generated locally; no API key.

## Relation to the Knowledge Palace

Sum up is the periodic close of the information chain. With Knowledge Palace KP-4+1, key conclusions can be turned into knowledge cards and fed into the review loop.

- Knowledge Palace KP-4+1 white paper and full methodology: <https://github.com/kp-wyn/knowledge-palace>

## License

MIT License — Author: 王亚宁 (kp-wyn). See [LICENSE](LICENSE).
