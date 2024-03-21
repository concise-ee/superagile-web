---
title: Balanced testing
layout: default
parent: "We get things done"
---

# Balanced testing

Testing 100% of every single thing is impossible. Testing close to everything is expensive. Almost no business can afford it. The important thing is to find a balance between what to test, how much to test, and which way to test. This is so that you spend the minimum time possible on it while still guaranteeing maximum quality.

Test what is reasonable since the unthinkable will happen anyway - and when it does, you want to catch it before the user reports come in.

**How to be prepared:**

- Apply a zero-exception policy that detects all application problems
- Monitor performance in different layers of your system
- Add end-to-end tracing
- Use synthetic API / interface monitoring to detect happy flow problems

An important part of the testing strategy is to understand when it’s beneficial to test and when the monitoring will be more effective. However, you will need both anyway and both of them are critical to use together with CDP.

So in the end, testing and monitoring will give you the best quality and speed for the money.

## What it feels like

### Best case

- **Prioritization of high-risk areas:** You focus testing efforts on the areas of your system that are most likely to cause issues or have the most significant consequences if they fail.
- **Understanding when to test vs. monitor:** You recognize the value in both testing and monitoring, using them strategically where they make the most sense.
- **Realistic expectations:** You accept that 100% testing coverage is impossible, and focus on testing what's most important.
- **Proactive preparation:** You implement strategies like zero-exception policies, end-to-end tracing, static code analysis, and chaos engineering to catch potential problems early.
- **Focus on maintaining high quality:** You understand that balanced testing aims to identify and address critical quality issues before they impact users.

### Worst case

- **Testing everything:** You waste resources trying to test every single aspect of your system, regardless of its risk or importance.
- **Over-reliance on testing:** You neglect monitoring strategies, potentially missing issues that occur outside of your structured test cases.
- **Reactive problem-solving:**  You prioritize finding and fixing bugs after they are reported by users, rather than proactively preventing them.
