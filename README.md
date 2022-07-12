# Oleacă profesor

This is the repository for [my website](babinion.xyz), on which I talk about random computer-science related stuff as well as I can, while trying to be funny. I also have some college notes (which you can complete, if you wish).

## How can I help?

You can contribute in multiple ways: simply sharing the site with people that might be interested, checking the text and code for errors, fixing dead links, adding new stuff, or checking the [todo](todos.md) file.

If you see any errors -- grammar or code, have any suggestions or want to contribute, please open a issue.

### Adding new stuff

If you think you've got something people using this website would benefit using -- open a pull request, but first make sure you follow the following requirements.

Your file:

1. has to be in [org](orgmode.org/)
2. has to be in the `pages/<filename>/` folder
3. has to have the following lines at the beginning

```org
#+TITLE: Post_title
#+AUTHOR: Post_author
#+LANGUAGE: ro
#+LATEX_HEADER: \usepackage[AUTO]{babel}
#+HTML_HEAD: <link rel="stylesheet" type="text/css" href="../../imagine.css" />
#+OPTIONS: num:nil html-style:nil
```

If you don't need a table of contents, also add `toc:nil` after `html-style:nil`

4. has to have `[[file:../../index.html][Înapoi]]` as the last line of your org file
5. has to have `[[file:pages/<filename>/<filename>.html][Post_title]]` in `index.org`, where `filename` has the same name as your `.org` file (even if you didn't export it to HTML)
6. if you can -- export it to HTML using `org-export`. If not, I'll export it myself.
