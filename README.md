Behind the scenes
===============================

- Based this on the [SinglePaged theme](https://github.com/t413/SinglePaged),  see it live at [t413.com/SinglePaged](http://t413.com/SinglePaged)
- Combined with ideas on [multiblog sites](https://www.garron.me/en/blog/multi-blog-site-jekyll.html)

-------------------------

## plan for categories

switch to csv of categories w/ script to generate *.md



## Usage

Alright, you've got a clean copy and are ready to push some schmancy pages for the world to ogle at.

- Edit `_config.yml` to change your title, keywords, and description.
- Create a new file in `_posts/` called `2014-01-01-intro.md`
  Edit it, and add:

~~~
  ---
  title: "home"
  bg: white     #defined in _config.yml, can use html color like '#010101'
  color: black  #text color
  style: center
  ---

  # Example headline!
  and so on..
~~~

- Create a second post called `2014-01-02-art.md` with an divider image this time:

~~~
  ---
  title: "Art"
  bg: turquoise  #defined in _config.yml, can use html color like '#0fbfcf'
  color: white   #text color
  fa-icon: paint-brush
  ---

  #### A new section- oh the humanity!
~~~
