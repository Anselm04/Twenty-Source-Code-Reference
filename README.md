# Twenty CRM — TrillionAI Engineering Research Reference

Independent source research snapshot for [Twenty CRM](https://github.com/twentyhq/twenty), supporting TrillionAI Marketing and Manager engineering work on customer records, CRM workflows, multi-tenancy and event-driven operations.

## Licence boundary: filtered research snapshot

**The repository is deliberately NOT a verbatim copy of all upstream files.** The original Twenty `LICENSE` specifies AGPL-3.0 for most source, MIT for identified packages, and a **separate commercial licence** for source files marked `@license Enterprise`. The commercial text prohibits ordinary copying and redistribution of that material. Our import workflow excludes those marked files from the public research snapshot. Their original code remains available for review at the upstream GitHub repository, subject to the original licence.

- Original source: `twentyhq/twenty`
- Pinned upstream commit: `1dd1c249ad213de6883be5296deb3bbba8420a22`
- Unfiltered upstream Git tree: `fd0a944992c11571bd422ec9a3bf60907b18fa39`
- Proposed source branch: [`twenty-upstream-snapshot`](https://github.com/Anselm04/Twenty-Source-Code-Reference/tree/twenty-upstream-snapshot/upstream)
- [Import and verification workflow](https://github.com/Anselm04/Twenty-Source-Code-Reference/actions/workflows/import-twenty-source.yml)

**The import is not complete until GitHub Actions passes.** Because excluded files change the tree, the retained source subtree's Git hash will differ from the unfiltered upstream tree; the workflow instead verifies the pinned upstream commit/tree and the exact, independently fetched retained tree.

## Separation rules

Source snapshots are independent research, not TrillionAI production code. Do not merge them into AppForge, Marketing or Manager. Implement and test original Flutter/Node.js solutions, preserving relevant legal obligations. This repository does not build or execute upstream source and does not activate paid services. A verified Git tree only covers tracked files, not upstream private cloud systems, complete history or separate LFS/submodule objects.
