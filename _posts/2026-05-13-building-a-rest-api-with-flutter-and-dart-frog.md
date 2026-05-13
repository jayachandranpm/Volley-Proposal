---
layout: post
title: "Building a REST API with Flutter and Dart Frog"
date: 2026-05-13T20:59:08.066257
tags: [flutter, backend, dart]
description: ""
---

Dart Frog is a minimalist backend framework built for Dart, and it pairs beautifully with Flutter apps.

## Getting Started

First, install the Dart Frog CLI:

```
dart pub global activate dart_frog_cli
```

Then scaffold a new project:

```
dart_frog create my_api
cd my_api && dart_frog dev
```

> Dart Frog brings the simplicity of Express.js to the Dart ecosystem.

## Creating Routes

Every file in the `routes/` directory becomes an endpoint. For example:

- `routes/index.dart` → GET /
- `routes/posts.dart` → GET /posts
- `routes/posts/[id].dart` → GET /posts/:id
