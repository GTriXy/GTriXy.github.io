# GTriXy.github.io

Terminal-style personal blog built with Astro and deployed with GitHub Pages.

## Development

```sh
npm install
npm run dev
```

## Add A Post

Create a Markdown file in `src/pages/posts/`:

```md
---
layout: ../../layouts/PostLayout.astro
title: "Post title"
description: "Short description."
date: "2026-07-19"
tags: ["notes"]
---

Write here.
```
