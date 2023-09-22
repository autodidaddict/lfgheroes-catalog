---
name: GroupSessionExpired
summary: "A group session has expired without meeting requirements"
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
If the player has set an expiration period for the session, or the app's default maximum life for a given session has occurred, the group session will expire.

<Mermaid />

## Schema
<SchemaViewer />