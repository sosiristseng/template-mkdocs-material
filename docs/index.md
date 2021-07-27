# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org) and [Material](https://squidfunk.github.io/mkdocs-material/) theme.

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

```
.gitlab-ci.yml  # GitLab CI/CD configurations
.github/        # Github actions 
    ...  

mkdocs.yml      # The configuration file.
docs/
    index.md    # The documentation homepage.
    ...         #  Other markdown pages, images and other files.
overrides/
    ...         # Override default templates if needed
includes/  
     examples.md # The files to be included in other files in `docs/`
     ...
```
