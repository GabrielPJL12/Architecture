---
# Configuration for the Jekyll template "Just the Docs"
parent: Decisions
title: Push notifications
# status: {accepted}
# date: {2023-10-10}
# deciders: {Gabriel Leclerc}
---

# Push notifications

## Context and Problem Statement

You are a team responsible for developing a new mobile app for a retail company. The app will allow customers to browse and purchase products, view their order history, and track the status of their deliveries. Additionally, the app will have a loyalty program feature, where customers can earn and redeem points for discounts on future purchases.

## Decision Drivers

- The retail company wants to send push notifications to customers to notify them about order updates, new product arrivals, and exclusive offers. The app should integrate with a push notification service to handle the delivery of notifications.

## Considered Options

- RN Firebase

## Decision Outcome

Chosen option: "RN Firebase", because it is compatible with React Native, and we can also eliminate redundancies by using this for our data storage.

### Consequences

- Good, because of a free basic plan.
- Good because of concise documentation.
- Good because of quick and easy integration and setup.
- Bad, because of being Android centered and has less support for iOS.
