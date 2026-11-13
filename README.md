# renovate-config

A [Renovate](https://www.npmjs.com/package/renovate) shareable config preset for
the [@nlibjs](https://github.com/nlibjs) project.

https://docs.renovatebot.com/

Dependency pull requests are opened immediately after Renovate creates a branch.
This lets repositories that run CI only on pull requests and pushes to `main`
start their checks. Non-major updates still require passing checks before
automerge; the Monday morning branch-creation schedule is unchanged.
