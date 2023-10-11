---
# Configuration for the Jekyll template "Just the Docs"
parent: Decisions
title: hybrid app

# status: {accepted}
# date: {2023-10-10}
# deciders: {Gabriel Leclerc}
---
# Hybrid app

## Context and Problem Statement

You are a team responsible for developing a new mobile app for a retail company. The app will allow customers to browse and purchase products, view their order history, and track the status of their deliveries. Additionally, the app will have a loyalty program feature, where customers can earn and redeem points for discounts on future purchases. The 

## Decision Drivers

* We would like to use a single codebase to simplify things.

## Considered Options

* React Native
* Flutter
* Xamarin

## Decision Outcome

Chosen option: "React Native", because it allows the team to work with a single codebase while still being time and cost effective. This allows the app to feel natural to use.

### Consequences

* Good, because of time and cost efficiency.
* Good, because it gives a Native look and feel to the app.
* Good, because it shares a codebase.
* Good, because it has great performance.
* Bad, because it need expertise from a native developer for some platform-specific modules.

## Pros and Cons of the Options

### Flutter

* Good, because consistent.
* Good, because of stateful hot reload.
* Good, because open source.
* Good, because great documentation.
* Bad, because of limited plugins and packages.

### Xamarin

* Good, because low maintenance.
* Good, because of native user experience.
* Good, because cost effective.
* Bad because high costs.
