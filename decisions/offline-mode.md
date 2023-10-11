---
# Configuration for the Jekyll template "Just the Docs"
parent: Decisions
title: Offline Mode
# status: {accepted}
# date: {2023-10-10}
# deciders: {Gabriel Leclerc}
---

# Offline mode support with data sync.

## Context and Problem Statement

The retail company want to allow customers to browse products and view their order history even when they are not connected to the internet. The app should sync data with the server once an internet connection is available.

## Decision Drivers

- The retail company wants the app to support offline mode.

## Considered Options

- Firebase
- SQLite
- Realm
- AWS AppSync
- Couchbase Mobile
- PouchDB

## Decision Outcome

Chosen option: "{title of option 1}", because
{justification. e.g., only option, which meets k.o. criterion decision driver | which resolves force {force} | … | comes out best (see below)}.

### Consequences

- Good, because {positive consequence, e.g., improvement of one or more desired qualities, …}
- Bad, because {negative consequence, e.g., compromising one or more desired qualities, …}
- … <!-- numbers of consequences can vary -->

## Pros and Cons of the Options

### {title of option 1}

{example | description}

- Good, because {argument a}
- Good, because {argument b}
- Neutral, because {argument c}
- Bad, because {argument d}
- … <!-- numbers of pros and cons can vary -->

### {title of option 2}

{example | description}

- Good, because {argument a}
- Good, because {argument b}
- Neutral, because {argument c}
- Bad, because {argument d}
- …

## More Information

{You might want to provide additional evidence/confidence for the decision outcome here and/or
document the team agreement on the decision and/or
define when this decision when and how the decision should be realized and if/when it should be re-visited and/or
how the decision is validated.
Links to other decisions and resources might here appear as well.}
