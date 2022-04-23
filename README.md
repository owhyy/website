# Oleacă profesor
This is the repository for [my website](babinion.xyz), on which I talk about random computer-science related stuff (but not limited to) as well as I can, while trying to be funny. If you see any errors - grammar or code, have any suggestions or want to contribute, please open a issue.

## How can I help?
You can contribute in multiple ways: simply sharing the site with people that might be interested, checking the text and code for errors, fixing dead links, adding new stuff, or checking the [todo](todos.md) file.

### Adding new stuff
If you want to add new stuff, it
1. has to be in org
2. has to have the following lines at the beginning
``` org
#+TITLE: Post_title
#+AUTHOR: Post_author
#+LANGUAGE: ro
#+LATEX_HEADER: \usepackage[AUTO]{babel}
#+HTML_HEAD: <link rel="stylesheet" type="text/css" href="imagine.css" />
#+OPTIONS: num:nil html-style:nil
```
3. has to have `[[file:index.html][Înapoi]]` at the end
4. has to have  to `[[file:filename.html][Post_title]]` in `index.html`, where `filename` is the name of your `.org` files (even if you didn't export it to html)
5. if you can - export it to html using `org-export`. If not, I'll export it myself.
