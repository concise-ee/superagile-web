---
title: "Trunk Based Development"
layout: default
parent: "We get things done"
---

# Trunk-based development

A source-control branching model, where developers collaborate on code in a single branch called ‘trunk’ ("master" in Git nomenclature), resist any pressure to create other long-lived development branches by employing documented techniques. They, therefore, avoid merge hell, do not break the build, and live happily ever after.

We like to keep the feedback loop from end-users to developers as short as possible. For that, we need to practice continuous deployment (CDP). Trunk based development is the fundamental cornerstone to pull off these frequent releases.

When doing smaller commits often and releasing them as soon as they are ready, we minimize the change failure rate and mean time to recovery (MTTR). It has been measured that in total you get five times fewer problems when you release more often vs only once per week. And if you get into trouble, then MTTR is up to 100 times faster.

**KPIs to measure:**

- How long does it take from code push to production?
- If you have short-lived branches, what is their mean time of living and how do you detect if they are short-lived in practice?
