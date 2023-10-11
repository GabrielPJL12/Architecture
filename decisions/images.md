---
# Configuration for the Jekyll template "Just the Docs"
parent: Decisions
title: images
# status: {accepted}
# date: {2023-10-10}
# deciders: {Gabriel Leclerc}
---

# Images

## Context and Problem Statement

You are a team responsible for developing a new mobile app for a retail company. The app will allow customers to browse and purchase products, view their order history, and track the status of their deliveries. Additionally, the app will have a loyalty program feature, where customers can earn and redeem points for discounts on future purchases.

## Decision Drivers

- The app will display product images, which may vary in size and resolution. To ensure optimal performance, the team needs to decide on an image storage solution and implement image optimization techniques such as caching, lazy loading, and compression.

## Considered Options

- react-native-image-offline
  -- decencies with react-native-fetch-blob.

## Decision Outcome

Chosen option: "react-native-image-offline", because it is a React Native library.

### Consequences

- Good, because of time and cost efficiency.
- Bad, because of may be difficult to develop.
