# my-blog (in3m0.github.io)

The source code and content repository for my personal technical blog, built using Jekyll and the Chirpy theme.

This site serves as an open-source logbook where I document my software engineering journey, computer vision pipelines, web performance experiments, and technical write-ups.

Live Site: [in3m0.github.io/my-blog/](https://in3m0.github.io/my-blog/)

---

## Tech Stack

* **Static Site Generator:** Jekyll
* **Theme:** [Chirpy](https://github.com/cotes2020/jekyll-theme-chirpy)
* **Math Rendering:** MathJax / KaTeX
* **Syntax Highlighting:** Rouge
* **Deployment:** GitHub Pages (via GitHub Actions)

---

## Core Topics & Domains

My writing focuses on the intersection of programmatic automation, performance engineering, and practical software design. Key areas include:

* **Computer Vision & Hardware Control:** Designing real-time spatial tracking pipelines, custom gesture controllers, and interactive software-to-hardware interfaces.
* **Web Engineering & Performance:** Structuring scalable, responsive front-ends and optimizing content delivery pipelines for speed and accessibility.
* **Technical SEO & Visibility:** Implementing structured data (JSON-LD), Schema architecture, and strategic optimization to drive discovery and search rankings.
* **Work Term Reflections:** Documenting engineering learnings, project management takeaways, and technical problem-solving from industry placements.

---

## Content Workflow

### 1. Creating a Post

All articles live in the `_posts/` directory and must follow the naming convention:
`YYYY-MM-DD-your-post-title.md`

### 2. Front Matter Template

Every markdown file requires the following YAML configuration at the top:

```yaml
---
title: "Your Post Title Here"
date: YYYY-MM-DD HH:MM:SS -0330 # Local timezone offset
categories: [Primary Category, Sub Category]
tags: [tag1, tag2]
math: true                  # Set to true to enable LaTeX rendering
image:
  path: /assets/img/posts/your-thumbnail.gif
  alt: "Descriptive alt text for SEO and accessibility"
---

```

---

## Local Development

To run the blog locally and preview drafts:

1. **Install dependencies:**
```bash

```



bundle install

```
2. **Run the local server:**
   ```bash
bundle exec jekyll serve

```

3. Open `[http://127.0.0.1:4000/my-blog/](http://127.0.0.1:4000/my-blog/)` in your browser.

## License

This work is published under [MIT][mit] License.