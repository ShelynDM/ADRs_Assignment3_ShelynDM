# ADR5: Using Hybrid Storage

Date: February 16, 2024

**Status**

Proposed

**Context**

A hybrid or a combination of the rational database and NoSQL suits the need of a social networking application. MySQL handles the user profile and authentication, logging and analytics, schedule management, and enrollment information. MongoDB handles the user generated content like posts and comments. It also handle the user activities, personalization, messaging and notifications.

**Decision**

Looking through the user needs and features the application requires it is decided that using hybrid storage, specifically MySQL and MongoDB will be beneficial to fully manage the data and optimize the performance of the application.

**Consequence**

Multiple database adds another layer of complexity in terms of the app development. Synchronization can be challenging and promotes potential conflicts.
