---
title: "Loosely coupled architecture"
layout: default
parent: "We get things done"
---

# Loosely couple architecture

As organizations grow, so does the software they produce. The classical way to evolve software is to keep adding new features to the existing one. This is called monolithic architecture.

Microservices, on the other hand, are small, autonomous, independently deployable, and releasable pieces of software that work together via well-defined APIs. This means that instead of a big monolithic application, we have many smaller components.

At first glance, it might seem more complex to have more moving parts. Microservices indeed introduce their own set of challenges, but they help you grow your organization and provide value to your customers faster.

> **Summary of Jeff Bezos' memo to Amazon technical staff:**
>
> 1. All teams will henceforth expose their data and functionality through service interfaces.
> 2. Teams must communicate with each other through these interfaces.
> 3. There will be no other form of inter-process communication allowed: no direct linking, no direct reads of another team’s data store, no shared- memory model, no back-doors whatsoever. The only communication allowed is via service interface calls over the network.
> 4. It doesn’t matter what technology they use. HTTP, CORBA, Pubsub, custom protocols—doesn’t matter. Bezos doesn’t care.
> 5. All service interfaces, without exception, must be designed from the ground up to be externalizable. That is to say, the team must plan and design to be able to expose the interface to developers in the outside world. No exceptions.
> 6. Anyone who doesn’t do this will be fired.

## What does good look like

**Lead with context not control.** To best achieve the independence that microservices offer, practice a context-based leadership model to inspire innovation, creativity and end-to-end ownership within teams. In practice, this means that managers provide all important information to the developers, but decisions regarding implementation and technology are left for the developers to work out. Teams can decide what projects to take on and how to prioritize work - this, of course, demands a lot of trust from all management levels of the organization. Funnily enough, micromanaging doesn’t mix well with microservices.
