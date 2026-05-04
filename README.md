# Madison QLM Website

## Setup
1. Clone this repo
1. Install [Zola](https://www.getzola.org/)

### Writing a post
1. Create a new markdown file (e.g. `your-post-title.md`) in `content/`. The part of the filename before `.md` will be the page's URL slug (e.g. `https://madisonqlm.org/your-post-title`).
1. Add the following content to the file, filling in the post title and date
```md
+++
title = "Your Post Title"
date = "yyyy-mm-dd"
+++
```
3. Write the post content using [markdown](https://commonmark.org/help/).
4. Run `zola serve` to run a local dev server to preview your changes, then `zola build` to build the site for publication.
5. Commit and push to publish your changes.