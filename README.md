# Contents for template of themes

There are 2 directories you have to put into the home directory of the theme.

`content` folder includes markdown files of contents.

`static` folder includes pics needed for contents.

For `.toml` config file, please change the **menu** section with the following:

```

[[menu.main]]
identifier = "education"
name = "Education"
url = "/education/"
weight = 1
[[menu.main]]
identifier = "honors"
name = "Honors"
url = "/honors/"
weight = 2
[[menu.main]]
identifier = "projects"
name = "Projects"
url = "/projects/"
weight = 3
[[menu.main]]
identifier = "activities"
name = "Activities"
url = "/activities/"
weight = 4

```

Note that there might be slight differences between different themes, but the procedure should be the same.
