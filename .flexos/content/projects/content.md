---
id: collection-projects
title: "Projects"
type: content
subtype: collection
status: active
sequence: 14
description: "User projects content"
relatesTo: [specs/004-database-collection_projects.md]
createdAt: "2026-04-19"
---

# Projects Content Collection

<flex_block type="data-schema" id="blk-004" name="projects-content">
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
