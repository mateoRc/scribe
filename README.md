# Scribe

Scribe unifies authored and external source data into versioned Markdown
snapshots.

**Status:** Proposal; implementation has not started.

Scribe will fetch provider data on a schedule, merge it with authored content,
and atomically publish a cached snapshot. Consumers read the last valid
snapshot without making live provider calls.

The Backend Lab integration roadmap remains in the
[Lab repository](https://github.com/mateoRc/lab/blob/main/content/docs/projects/roadmaps/scribe.md).
