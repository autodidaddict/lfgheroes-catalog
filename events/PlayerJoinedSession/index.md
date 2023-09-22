---
name: PlayerJoinedSession
summary: "Indicates that a player has joined the session"
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
This event occurs when any player joins an active group session. Note that this event will _also_ occur when the originator of the session joins in-game.

<Mermaid />

## Schema
<SchemaViewer />