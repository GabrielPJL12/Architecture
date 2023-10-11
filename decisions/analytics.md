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

- The retail company wants to track user behavior, such as product views, purchases, and loyalty program interactions. The team should select an analytics tool or service that provides detailed insights and metrics to help improve the app's performance and user experience.

## Considered Options

- Firebase Anaytics

## Decision Outcome

Chosen option: "Firebase Analytics", because it is compatible with React Native, can analyze data. We are already using Firebase for a lot of our stack.

### Consequences

- Good, because of a free basic plan.
- Good because of concise documentation.
- Good because of quick and easy integration and setup.
- Bad, because of being Android centered and has less support for iOS.
