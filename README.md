# hermes-skills

Skills for [Hermes Agent](https://github.com/NousResearch/hermes-agent), learned the hard way on real projects.

## Install

```bash
hermes skills tap add rstephens11-ux/hermes-skills
hermes skills install rstephens11-ux/hermes-skills/skills/runpod
```

## Skills

| Skill | What it does |
|---|---|
| [runpod](skills/runpod/SKILL.md) | Rent RunPod GPU pods with a reusable model volume. Scan every datacenter, deploy, bootstrap, run, and **terminate and verify**. Built around not paying for idle pods. |

The `runpod` skill is also proposed as an official optional skill: [NousResearch/hermes-agent#133136](https://github.com/NousResearch/hermes-agent/pull/133136).

MIT licensed.
