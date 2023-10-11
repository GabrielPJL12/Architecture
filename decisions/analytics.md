---
# Configuration for the Jekyll template "Just the Docs"
parent: Decisions
title: Analytics
# status: {accepted}
# date: {2023-10-10}
# deciders: {Gabriel Leclerc}
---

# Analytics

## Context and Problem Statement

You are a team responsible for developing a new mobile app for a retail company. The app will allow customers to browse and purchase products, view their order history, and track the status of their deliveries. Additionally, the app will have a loyalty program feature, where customers can earn and redeem points for discounts on future purchases. 

## Decision Drivers

- We would like to create a mobile app with consistent performance with the ability to store data.

## Considered Options

- Firebase
- SQLite
- Realm
- Couchbase Mobile

## Decision Outcome

Chosen option: "Firebase", because it is compatible with React Native, can store date such as the user's order history, and the catalog of products from the retail store. We can also eliminate redundancies by using this for our push notification service.

### Consequences

- Good, because of push notification service.
- Good, because of a free basic plan.
- Good because of concise documentation.
- Good because of quick and easy integration and setup.
- Bad, because of limited querying capabilities.
- Bad, because of limited data migration.
- Bad, because of being Android centered and has less support for iOS.

## Pros and Cons of the Options

### SQLite

- Good, because lightweight.
- Good, because no installation needed.
- Good, because reliable.
- Good, because portable.
- Good, because accessible.
- Bad, because Database size is restricted to 2GB in most cases.
- Bad, because slow.
- Bad, because not suitable for large scale apps.

### Realm

- Good, because high speed.
- Good, because of well written documentation.
- Good, because offline mode if free.
- Bad, because no support for auto-incrementing ID's and composite keys

### Couchbase

- Good, because high speed.
- Good, because reliable
- Good, because it allows you to analyze data.
- Good, because easy setup
- Bad, because querying can take a while.
- Bad, because indexing can take too long.
  .
