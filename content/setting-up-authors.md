+++
author = "Seth MacLeod"
date = "2016-09-01T12:11:11-04:00"
tags = [
  "Getting Started",
]
title = "Setting up authors"

+++

Setting up authors is straightforward. Each author needs their own profile page. Using Hugo from the command line, type `hugo new authors/author-name.md` (e.g. `hugo new authors/seth-macleod.md`). Open your newly created author page. The front matter for the author archetype is:

```
+++
title = ""
date = ""

+++

```

The date will be filled in by Hugo, but you must fill in the `title` with the author's name, spelled exactly how it will be used for the rest of the site. Any differences in spellings throughout the site, whether by adding a middle name, different capitalizations, etc., will result in pages not linking together.

After filling in the author's name, you can write an optional about section. If written, it will be displayed above a list of the author's posts.
