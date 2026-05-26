# My Notes Site

A Jekyll-based notes site hosted on GitHub Pages.

## Adding a new note

Create a file in `_posts/` named `YYYY-MM-DD-your-title.md` with this front matter:

```markdown
---
layout: post
title: "Your Note Title"
date: 2026-05-26
tags: [tag1, tag2]
---

Your content here.
```

Then push:

```bash
git add .
git commit -m "add note: your title"
git push
```
