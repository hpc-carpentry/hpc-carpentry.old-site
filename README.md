# Website of HPC Carpentry

## Building it

This webiste uses jekyll to generate html5 webpages. To build it, do:

```
$ make site
```

To build and serve it to the browser on your `localhost`, do 

```
$ make serve
```

## Adding a blog post

To **write a blog post**,
create a file called `_posts/YYYY/MM/YYYY-MM-DD-some-title.html` or  `_posts/YYYY/MM/YYYY-MM-DD-some-title.md`
(for HTML and Markdown respectively).
YYYY is the 4-digit year of the post, MM the 2-digit month, and DD the 2-digit day;
`some-title` can be any hyphenated string of words that do not include special characters such as quotes.
Please do *not* use underscores or periods in the names.
When published,
your blog post will appear as `https://hpc-carpentry.github.io/blog/YYYY/MM/some-title.html`.

The YAML header of a blog post must look like this:

~~~
---
layout: page
authors: ["Your Name"]
title: "A Title-Cased Title for the Post"
date: YYYY-MM-DD
time: "hh:mm:ss"
teaser: "A short teaser on the content of the blog post"
---
~~~

where `YYYY-MM-DD` is replaced by the post's date and `hh:mm:ss` by the post's time.
Note that the time *must* be quoted so that the colons it contains do not confuse Jekyll's YAML parser.
Note also that `authors` is a list---if the post has more than one author,
please format the list like this:

~~~
...
authors: ["First Author", "Second Author", "Third Author"]
...
~~~

rather than running all the authors' names together in one long string.
