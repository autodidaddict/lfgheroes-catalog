---
name: GameCreated
summary: "Indicates a new game has been created"
version: 1.0.0
producers:
    - 'Game Aggregate'
consumers:
    - 'Game Aggregate'
    - 'Game Projector'
tags:
    - label: 'event'
externalLinks: []
badges: []
---
Game profiles are required to exist before a user can request aid within one

<Mermaid />

## Schema
<SchemaViewer />