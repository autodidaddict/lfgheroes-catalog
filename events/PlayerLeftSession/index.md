---
name: PlayerLeftSession
summary: "Indicates that a player has left the session"
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
This event indicates that a player has left the session. Note that entry and departure from a session are self-reporting and there's no integration with the actual connectivity data from the game.

<Mermaid />

## Schema
<SchemaViewer />