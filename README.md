# jhboouk.github.io

GitHub Pages blog repository for <https://jhboouk.github.io/>.

## Local management

```bash
cd /home/ubuntu/work/jhboouk.github.io

git status
# edit files

git add .
git commit -m "Update blog"
git push
```

## Add a post

Create a Markdown file under `_posts/` with this naming convention:

```text
YYYY-MM-DD-title.md
```

Example front matter:

```markdown
---
layout: post
title: "첫 글"
date: 2026-06-29 09:00:00 +0900
categories: blog
---

본문을 여기에 작성합니다.
```
