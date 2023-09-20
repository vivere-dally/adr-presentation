# 4. Should you use ADRs?

* Status: accepted
* Date: 2023-09-20

## Context and Problem Statement

Should you use ADRs?

## Decision Drivers <!-- optional -->

* As a developer, I want to have the needed resources close to the source code.
* Project members come and go and past decisions and contexts get lost.

## Considered Options

* Confluence
* Word documents...
* Scattered documents across multiple services
* ADRs

## Decision Outcome

Chosen option: ADRs, because they are close to the source code.

### Positive Consequences <!-- optional -->

* I have a log of important project decision.
* I have a single source of truth.

### Negative Consequences <!-- optional -->

* People might need to be upskilled in Markdown and Git.

## Pros and Cons of the Options <!-- optional -->

### Confluence

* Good, because it is widely used.
* Good, because it is user friendly.
* Bad, because it is a different system that needs to be maintained.
* Bad, because it costs money.

### Word documents

* Bad, because Microsoft.

### Scattered documents across multiple services

* Bad, because I have to remember what information is where.
* Bad, because I want to get to coding ASAP.

### ADRs

* Good, because I have a standard for decision making.
* Good, because I have the documents close to the source code.
* Good, because I don't have to remember where to search for contexts.
* Bad, because it might not be user friendly.

## Links <!-- optional -->

* [ADR](https://adr.github.io/)
* [MADR](https://adr.github.io/madr/)
* [Michael Nygard proposal](https://cognitect.com/blog/2011/11/15/documenting-architecture-decisions)
* [ISO/IEC 42010](https://wikipedia.org/wiki/ISO/IEC_42010)
* [ThoughtWorks technology radar](https://www.thoughtworks.com/radar/techniques/lightweight-architecture-decision-records)
