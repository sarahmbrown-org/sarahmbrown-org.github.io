

# How this works

regular jekyll setup stuff

# Content Organization

This site uses jekyll collections to organize most of the content

## academic
This collection is the sections on the front page /index. There should be any header sections for the main page here as well as markdown files for the content collections as described in the next section.

Minimal yml example:
```yml
---
title: "home"
display: "About"
news: news
---
```

if the `news` key is used, then this section will have a News list on the front page, taking the 3 most recent posts with this category and listing the `headline` if available or title with a link to the post main page.  The keyword News will link to the category page for that type of news

## content collections

These are the sections `research`, `teaching`, `service`
each of these (and any additional similar sections) should have a directory named accordingly and be added to the `_config.yml`

To generate the `/collection/ ` page there needs to be an index.md with the following yaml

For each of these collections, there needs to be a markdown in `/_academic`. This markdown will also be displayed at the top of the `/collection/ ` page.
 - `itemdata` must match the collection name exactly this will add the more info bar at the bottom of the section on the front page and fill this markdown content to the collection page
 -

minimal yaml front matter like:

```yml
---
display: Teaching
itemdata: teaching
layout: academic
---
```

## category

This is a processing collection to generate pages of blog content these are just yaml header matter to make the `_layout/category.html` page works

`type:blog` is required on all pages that need to use the blognav

```yml
---
layout: category
title: As it should display
category: "Grad School"
type: blog
---
```

# Notes
