---
title: "Shift Left Security"
layout: default
parent: "We get things done"
---


In #superagile, we we place a high emphasis on speed and innovation. However, in our pursuit of these objectives, security cannot be an afterthought.  "Shift-left security" addresses this by embedding security practices early in the software development lifecycle. By "shifting" these security practices "left" towards the beginning of the development process, vulnerabilities can be identified and fixed sooner, reducing risks and costs.

Although we emphasize the importance of early-stage security measures, it's crucial to ensure that these measures complement, rather than hinder, the development process. As software progresses through its lifecycle, the costs and complexities of addressing vulnerabilities increase exponentially. Early detection of flaws not only prevents the amplified costs associated with fixing them at a later stage but also avoids potential reputation damage and regulatory penalties that might arise from breaches.

In practical terms, at the code repository level, we ensure that sensitive data like API keys or passwords aren’t accidentally committed by implementing automated secret scanning. We also regularly check library and framework versions for known vulnerabilities through automated dependency scanning. We evaluate the robustness and maintainability of code with automatic code quality scans. For containerized images, we conduct vulnerability scans, check for misconfigurations, and ensure no embedded secrets are present in the images.

In addition to code vulnerabilities, the human factor is also a critical component of cybersecurity. Advanced security protocols can be undone by human error or ignorance. Our ethos is clear: while our machines scan for vulnerabilities, our people must be equally vigilant. Every team member is a guardian of security, no matter their primary role.
