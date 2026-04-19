---
id: database-collection-projects
title: "Projects Collection"
type: database
subtype: collection
status: active
sequence: 12
description: "Projects schema"
relatesTo: [docs/004-database.md]
createdAt: "2026-04-19"
---

# Projects Collection

<flex_block type="data-schema" id="blk-002" name="projects">
{
  "collection": "projects",
  "fields": [
    { "name": "id", "type": "string", "required": true },
    { "name": "userId", "type": "reference", "ref": "users", "required": true },
    { "name": "name", "type": "string", "required": true },
    { "name": "status", "type": "string", "values": ["draft", "building", "deployed"] },
    { "name": "createdAt", "type": "date" }
  ]
}
</flex_block>
