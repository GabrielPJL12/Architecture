---
# Configuration for the Jekyll template "Just the Docs"
parent: Decisions
title: localization
# status: {accepted}
# date: {2023-10-10}
# deciders: {Gabriel Leclerc}
---

# title: localization

## Context and Problem Statement

You are a team responsible for developing a new mobile app for a retail company. The app will allow customers to browse and purchase products, view their order history, and track the status of their deliveries. Additionally, the app will have a loyalty program feature, where customers can earn and redeem points for discounts on future purchases.

## Decision Drivers

- The retail company plans to expand its customer base internationally. The app should support multiple languages and adapt to various cultural preferences. The team needs to implement localization techniques and decide on the appropriate localization framework or libraries.

## Considered Options

- localizedString from react-native-localization
- expo-localization

## Decision Outcome

Chosen option: "localizedString from react-native-localization", because it is a React Native library and is easy to use.

### Consequences

- Good, because of time and cost efficiency.
- Bad, because of may be difficult to develop.
