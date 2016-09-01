+++
author = "Seth MacLeod"
date = "2016-09-01T12:42:20-04:00"
tags = [
  "Getting Started",
]
title = "Creating static pages"

+++

Creating static pages is similar to creating author pages. Using the Hugo command line, type `hugo new static/page-name.md` (e.g. `hugo new static/about.md`). Open your newly created static page. The front matter for the static archetype is:

```
+++
title = ""
date = ""
url = ""
+++

```

The date will be filled in automatically by Hugo. Fill in the page `title` and the `url`. The `url` can be a relative path, such as `/about/`, which makes it easy to have a URL of `hugo-multi-author.netlify.com/about/` rather than `hugo-multi-author.netlify.com/static/about/`.