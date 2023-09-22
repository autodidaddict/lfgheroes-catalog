---
name: GroupSessionCreated
summary: "A signal that a user has created a new call for help"
version: 1.0.0
producers:
    - 'Group Session Aggregate'
consumers:
    - 'Group Session Aggregate'
    - 'Group Session Projector'
    - 'Group Session Process Manager'
tags:
    - label: 'event'
externalLinks: []
badges: []
---
This event is created when a user has successfully requested aid in a game, effectively establishing a new LFG session.

<Mermaid />

## Schema
<SchemaViewer />