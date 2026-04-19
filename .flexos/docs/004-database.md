---
id: doc-database
title: "Database"
type: doc
status: active
sequence: 4
description: "Database schemas and collections"
relatesTo: [docs/003-pages.md]
createdAt: "2026-04-19"
---

# Database

## Users
Stores user authentication and profile data.

## Projects
Stores the generated projects.

<flex_block type="data-schema" id="blk-001" name="projects">
{
  "collection": "projects",
  "description": "User generated FlexOS projects",
  "fields": [
    { "name": "id", "type": "string", "required": true },
    { "name": "userId", "type": "reference", "ref": "users", "required": true },
    { "name": "name", "type": "string", "required": true },
    { "name": "status", "type": "string", "values": ["draft", "building", "deployed"] },
    { "name": "createdAt", "type": "date" }
  ]
}
</flex_block>
