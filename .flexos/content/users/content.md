---
id: collection-users
title: "Users"
type: content
subtype: collection
status: active
sequence: 15
description: "Users content"
relatesTo: [specs/005-database-collection_users.md]
createdAt: "2026-04-19"
---

# Users Content Collection

<flex_block type="data-schema" id="blk-005" name="users-content">
{
  "collection": "users",
  "fields": [
    { "name": "id", "type": "string", "required": true },
    { "name": "email", "type": "string", "required": true },
    { "name": "name", "type": "string" }
  ]
}
</flex_block>
