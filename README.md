# ATP024 — Tekton

An Astrona **training path**: a course track that groups training series
(`ATSxxx`) as its domains. Each stage in `path.yaml` is one domain and points
at the repository that teaches it. There is no official Tekton certification
exam, so the domains and weights are Astrona's own and `examPreparation` is
off. Tekton was a graduated project of the CD Foundation (Continuous Delivery
Foundation) and moved to the CNCF as an incubating project on 13 March 2026.

| Stage | Domain | Weight | Content | Status |
| --- | --- | --- | --- | --- |
| STG001 | Fundamentals, Architecture & tkn CLI | 10 % | [ATS124](https://github.com/astrona-io/ATS124) | Draft, written, not yet run |
| STG002 | Tasks, Steps & Workspaces | 20 % | [ATS125](https://github.com/astrona-io/ATS125) | Draft, written, testing |
| STG003 | Pipelines, Task Graphs & Custom Tasks | 25 % | [ATS126](https://github.com/astrona-io/ATS126) | Draft, written, testing |
| STG004 | Triggers, Interceptors & Event-Driven CI | 15 % | [ATS127](https://github.com/astrona-io/ATS127) | Draft, written, testing |
| STG005 | Pipelines-as-Code & Git-Native CI | 15 % | [ATS128](https://github.com/astrona-io/ATS128) | Draft, written, testing |
| STG006 | Supply Chain Security With Chains & Operations | 15 % | [ATS129](https://github.com/astrona-io/ATS129) | Draft, written, testing |

Versions: Tekton Pipelines v1.17.1, tkn v0.46.2, Dashboard v0.73.0,
Triggers v0.37.2, Chains v0.29.9, Pipelines-as-Code v0.52.0, Operator v0.81.2
and Pruner v0.4.4. The source for every fact is the Tekton documentation,
<https://tekton.dev/docs/>.

The site picks it up through [astrona-content](https://github.com/astrona-io/astrona-content):
a file in `courses/` that points at this repository, and the content sync
builds the course — one section per stage, with the readings, playgrounds and
labs each stage repository lists in its `astrona.yaml`. That course file does
not exist yet; add it when the first stage is ready to show.
