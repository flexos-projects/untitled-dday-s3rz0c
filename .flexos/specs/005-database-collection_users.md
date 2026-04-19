---
id: database-collection-users
title: "Users Collection"
type: database
subtype: collection
status: active
sequence: 13
description: "Users schema"
relatesTo: [docs/004-database.md]
createdAt: "2026-04-19"
---

# Users Collection

<flex_block type="data-schema" id="blk-003" name="users">
{
  "collection": "users",
  "fields": [
    { "name": "id", "type": "string", "required": true },
    { "name": "email", "type": "string", "required": true },
    { "name": "name", "type": "string" }
  ]
}
</flex_block>
