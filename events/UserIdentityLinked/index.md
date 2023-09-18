---
name: UserIdentityLinked
summary: "Indicates that an application user has been linked with an external authentication identity"
version: 1.0.0
producers:
    - 'User Aggregate'
consumers:
    - 'User Aggregate'
tags:
    - label: 'event'
externalLinks: []
badges: []
---
The first time a user logs in with a new identity, or manually associates a new identity with their site account, this event occurs.

<Mermaid />

## Schema
<SchemaViewer />