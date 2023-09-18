---
name: UserCreated
summary: "Indicates a new application user has been created"
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
When a user first logs into the application site, an initial record will be created for them. Note that the identity the person used for the first login will become their default identity until and unless they change their profile later.

<Mermaid />

## Schema
<SchemaViewer />