# X-thread AI skills pack — 2026-11-09

## Provenance

| Field | Value |
|---|---|
| Author | Scout · Talent and Development Director |
| Ask | Christian in Scout chat t415u 2026-11-09 ~6:29 AM CT ("Put those skills in a zip file") |
| Source post | https://x.com/danikkk_wqs/status/2119535297541070962 (repo names read off the post video) |
| Built | 2026-11-09 06:34:58 CST (America/Chicago) |
| Evidence | checked via GitHub API + public codeload tarballs |
| Method | Verified each candidate repo; corrected video misreads; downloaded default-branch `tar.gz` (no git auth, no installs, no spend); kept whole repo (skills + LICENSE/README); stripped `.git`; secrets scan for `sk-`, `ghp_`, `AKIA`, `BEGIN PRIVATE KEY` — **0 hits** |

## Included repos

| Repo | URL | Stars (check) | License | Default branch | Last push (America/Chicago) | Skills (`SKILL.md` folders) |
|---|---|---|---|---|---|---|
| mattpocock/skills | https://github.com/mattpocock/skills | 319163 | MIT | main | 2026-11-05 04:40:01 CST | 39 — ask-matt, code-review, codebase-design, diagnosing-bugs, domain-modeling, grill-with-docs, implement-spec, implement, improve-codebase-architecture, pr, prototype, research, retro, setup-matt-pocock-skills, tdd, to-spec, to-tickets, triage, wayfinder, wizard; in-progress: chief-of-staff, claude-handoff, loop-me, setup-ts-deep-modules, software-factory, writing-beats, writing-fragments, writing-shape; misc: git-guardrails-claude-code, migrate-to-shoehorn, scaffold-exercises, setup-pre-commit; productivity: grill-me, grilling, handoff, teach, to-questionnaire, wait-what, writing-for-agents |
| addyosmani/agent-skills | https://github.com/addyosmani/agent-skills | 114340 | MIT | main | 2026-11-01 13:24:49 CST | 25 — api-and-interface-design, browser-testing-with-devtools, ci-cd-and-automation, code-review-and-quality, code-simplification, constraint-driven-development, context-engineering, debugging-and-error-recovery, deprecation-and-migration, documentation-and-adrs, doubt-driven-development, frontend-ui-engineering, git-workflow-and-versioning, idea-refine, incremental-implementation, interview-me, observability-and-instrumentation, performance-optimization, planning-and-task-breakdown, security-and-hardening, shipping-and-launch, source-driven-development, spec-driven-development, test-driven-development, using-agent-skills |
| cloudflare/security-audit-skill | https://github.com/cloudflare/security-audit-skill | 67447 | MIT | main | 2026-09-14 14:29:02 CDT | 1 — security-audit |
| kepano/obsidian-skills | https://github.com/kepano/obsidian-skills | 51212 | MIT | main | 2026-09-15 09:43:57 CDT | 6 — defuddle, json-canvas, knap, obsidian-bases, obsidian-cli, obsidian-markdown |
| google/elephant-goldfish-model | https://github.com/google/elephant-goldfish-model | 15886 | Apache-2.0 | main | 2026-11-08 20:35:53 CST | 7 unique under `skills/` (also mirrored under `distributions/claude/skills/`) — egm-bootstrap, egm-brainstorm, egm-draft, egm-drift-report, egm-resolve, egm-review, egm-review-loop |

## Corrections and exclusions

| Video / candidate name | Outcome |
|---|---|
| mattpocock/skills (Matt Pocock) | Included as shown |
| "adymosman/agent-skills" / Adyn Osman | **Corrected** → `addyosmani/agent-skills` (Addy Osmani). `adymosman/agent-skills` returned GitHub HTTP 404 |
| cloudflare/security-audit-skill | Included as shown |
| kepano/obsidian-skills | Included as shown |
| google/elephant-goldfish-model | Included as shown (exists; Apache-2.0) |

## Layout

```
skills/
  README.md
  mattpocock__skills/
  addyosmani__agent-skills/
  cloudflare__security-audit-skill/
  kepano__obsidian-skills/
  google__elephant-goldfish-model/
```

Each `<owner>__<repo>/` directory is the full default-branch tree (skills plus LICENSE/README and other repo files). No `.git` directory.

## Notes

- Stars and last-push times are from GitHub API at build time (checked), not from the X post.
- The X post's star/install claims were not used.
- google/elephant-goldfish-model ships the same skill set twice (canonical `skills/` and Claude distribution copy); count of unique skill names is 7.
