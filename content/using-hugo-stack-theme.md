---
title: "Using the Hugo Stack Theme"
date: 2025-08-27T00:00:00Z
categories:
  - tutorial
---

In this tutorial post we'll walk through the basics of working with the **Hugo Stack** theme.

## Creating new posts

To create a new blog post, run the following command in your Hugo project directory:

```bash
hugo new posts/my-first-post.md
```

Hugo will create a new Markdown file under `content/posts/` with front matter already filled in.  Edit the file to add your content, then run `hugo serve` to preview the changes locally.

## Customizing the site

The Stack theme is highly configurable via the files in `config/_default`.  You can:

- Change the site title and base URL in `config.toml`.
- Adjust sidebar settings, colors, and widgets in `params.toml`.
- Define your navigation and social links in `menu.toml`.

Refer to the [official documentation](https://stack.jimmycai.com/config/site) for a comprehensive guide.
