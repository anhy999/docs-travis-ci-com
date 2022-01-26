---
title: Security
layout: en_insights

---

We take security very seriously at Travis Insights.  Due to the sensitive nature of the information we handle, we work hard to minimize risk in everything we do.

## Credential Management

On accepting credentials, we encrypt your passwords/secret keys on the client side using our PKI.  This ensures that your credentials never touch our publicly-exposed servers unencrypted.  The key to decrypt your credentials is stored on a separate cluster of servers with no public endpoints.  These keys are rotated on a regular basis.

## Data Management

While we maintain an internal representation of your environment, the majority of your data is handled only on our **secure cluster** of servers with no public endpoints and then it is securely destroyed.