---
name: GroupSessionCompleted
summary: "A group session has finished"
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
This event indicates that a group session successfully completed

<Mermaid />

## Schema
<SchemaViewer />