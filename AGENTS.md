# AI Workflow Pro playbooks hub

This repo is an index, not a playbook. It lists every AI Workflow Pro video and the repo that
ships with it.

## Where things are

| Path | What it is |
|---|---|
| `README.md` | The human index, one table per series |
| `course.yaml` | The same index, machine-readable: series, topic, video id, repo, repo type |
| `concepts/` | Pages for explainer videos that have no repo of their own |
| `tips/` | Pages for short videos, named after the short's number |
| `talks/` | Notes from conversations and interviews |

## If a user asks you to set up a playbook

1. Find the video by topic in `course.yaml` and read its `repo`.
2. Clone `https://github.com/aiworkflowpro/<repo>` into the folder the user chooses.
3. Open that repo's `AGENTS.md` and follow it. Each playbook explains its own setup.

## Rules

- Keep `README.md` and `course.yaml` in sync: every row in one has an entry in the other.
- Only link to repos that are public; unreleased playbooks say "coming soon".
