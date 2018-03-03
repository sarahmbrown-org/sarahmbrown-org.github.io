

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

These are the sections [`research`, `teaching`, `service`]
each of these (and any additional similar sections) should have a directory named accordingly and be added to the `_config.yml`

To generate the `/collection/ ` page there needs to be a file somewhere with the following yaml excerpt (mostly in `_academic`)

```yml
itemdata: <related collection name>
layout: collectionmain
```

For each of these collections, there needs to be a markdown in `/_academic`. This text from there will also be displayed at the top of the `/collection/ ` page.
 - `itemdata` must match the collection name exactly this will add the more info bar at the bottom of the section on the front page and fill this markdown content to the collection page
 -

### gallery

on these pages, add the following to yaml to add link/gallery content at the bottom.  The icon names are without the `fa` prefix, but include any font-awesome icon

```yml
gallery:
  - [<icon name>, link content]
```

## category

This is a processing collection to generate pages of blog content these are just yaml header matter to make the `_layout/category.html` page works

`type:blog` is required on all pages that need to use the blognav, this is flagged in `_layout/main` to change the width of the `<main>` section by setting the class

```yml
---
layout: category
title: As it should display
category: "Grad School"
type: blog
---
```


# Layouts

## default
shell ofthe page, outer content, mostly meta

## main

generally always used


# Notes

To do: add feature for pinned project/item to index.html, use collectionmain as reference to get it. Allow pinned collection item to be set by id in `_academic` post and then pulled into page, no requirement to edit actual item to pin/unpin a post.  Bonus, allow pinning on collection main for sort.
