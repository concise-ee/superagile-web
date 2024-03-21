---
title: "Trunk based development"
layout: default
parent: "We get things done"
---

# Trunk-based development

A source-control branching model, where developers collaborate on code in a single branch called ‘trunk’ ("master" in Git nomenclature), resist any pressure to create other long-lived development branches by employing documented techniques. They, therefore, avoid merge hell, do not break the build, and live happily ever after.

We like to keep the feedback loop from end-users to developers as short as possible. For that, we need to practice continuous deployment (CDP). Trunk based development is the fundamental cornerstone to pull off these frequent releases.

When doing smaller commits often and releasing them as soon as they are ready, we minimize the change failure rate and mean time to recovery (MTTR). It has been measured that in total you get five times fewer problems when you release more often vs only once per week. And if you get into trouble, then MTTR is up to 100 times faster.

## What it feels like

### Trunk-based development (TBD)

- **One main branch:**  Everyone commits their changes to a single primary branch, usually called "main", "trunk", or "master".
- **Short-lived branches:** Feature branches exist but are small, focused on a single change, and merged back into the main branch as quickly as possible (ideally within a day).
- **Frequent commits:** Developers make small, incremental commits to the main branch multiple times a day.
- **Quick merges:** Merging feature branches back into the main branch is a smooth and simple process, typically not requiring extensive code reviews or manual intervention.

### Long-lived feature branches

- **Long-lived feature branches:** Developers work in isolation on branches that remain separate from the main branch for weeks or even months.
- **Complex merges:** Merging feature branches back into the main branch is often difficult, time-consuming, and prone to conflicts due to the large amount of diverging code.
- **Infrequent commits:** Developers make infrequent, large commits containing many code changes at once.
- **Release branches:** The codebase has dedicated, long-lived branches for specific releases (e.g., "release-1.0" ). Hotfixes often happen on these branches rather than directly on the main branch.
- **"Code freeze" periods:** The team designates times where no changes can be merged to a main branch in order to stabilize a release.
- **Fear of breaking the build:** Developers are hesitant to merge frequently due to the risk of introducing errors into the main branch.
