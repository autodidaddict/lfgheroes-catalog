---
name: GroupSessionCanceled
summary: "A group session has been canceled by its creator"
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
This event occurs when the session creator cancels it. Note that sessions canceled with other players still marked as being in the session can potentially be used to negatively impact a player's profile.

<Mermaid />

## Schema
<SchemaViewer />