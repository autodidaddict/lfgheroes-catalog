---
name: PlayerCommended
summary: "Indicates that one player has left a commendation for another"
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
This event indicates that a player has left a commendation for another player. Note that those answering the call and those originating the call are equally able to leave commendations.

The application aims to provide a positive experience, so there's no facility for leaving a 1-star or troll rating.

<Mermaid />

## Schema
<SchemaViewer />