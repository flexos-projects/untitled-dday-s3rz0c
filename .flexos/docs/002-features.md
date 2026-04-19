---
id: doc-features
title: "Features"
type: doc
status: active
sequence: 2
description: "Core feature set for FlexOS"
relatesTo: [docs/001-vision.md]
createdAt: "2026-04-19"
updatedAt: "2026-04-19"
---

# Features

## Core Capabilities

### Holy Docs Generation
Translates a raw prompt or seed document into 8 sequential product specification documents (Vision, Features, Pages, Database, Flows, Design, Technical, Content).

### Design System Extraction
Automatically generates CSS tokens, layout classes, and UI components based on the project requirements. Outputs a standalone HTML design reference.

### Interactive HTML Prototypes
Generates standalone, browser-viewable HTML files that accurately represent the user interface and interactions before any backend code is written.

### Production Nuxt 4 Builds
Compiles the specs and prototypes into a complete, modular, production-ready Nuxt 4 repository with Vue components, composables, and server routes.

### Smart Dependency Tracking
When a change is requested (e.g., "Add an avatar to the user profile"), the system automatically traverses the dependency graph to update the database spec, the page spec, the mock data, and the prototype.

### Zero Lock-in Export
The final output is standard Nuxt code. There is no proprietary FlexOS runtime library required to host the finished application.