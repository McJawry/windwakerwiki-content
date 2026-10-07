---
title: Getting started
icon: 🚀
tags: [setup, github]
order: 2
---

# Getting started

This wiki is made of two GitHub repositories, so editors can change pages without ever touching the site's code.

| Repository | Holds | Who can write |
| --- | --- | --- |
| The site (app) repo | The editor and page layout | Maintainers only |
| The content repo | The pages and images | Maintainers and editors |

## Becoming an editor

1. Ask a maintainer to add you as a collaborator on the **content repository** (Write access).
2. On GitHub, create a **fine-grained token** limited to that repository with *Contents* and *Pull requests* set to read & write.
3. Open the wiki, press **Edit**, then **Save**, and paste the token when asked. It stays in your browser.

> [!TIP]
> Not an editor yet? Anyone with a GitHub account can still suggest a change. Create a classic token with the `public_repo` scope and your edit is sent as a pull request for a maintainer to review.

## Good to know

- Pages usually appear to everyone within a few minutes of saving. You see your own change immediately.
- Every change is kept in the content repository's history, so mistakes can always be undone.
- Maintainers can set `"directCommit": false` in `config.json` so that **all** edits go through pull requests.

Back to [[Welcome]].
