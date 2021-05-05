# dev-blog

# This codebase is no longer maintained.

Blog of the Raha software development team. Rendered using Github Pages' Jekyll
integration.

## Adding articles

1.  Create a file in `_posts/` with the following title format:
    `yyyy-mm-dd-title.md`
1.  Add the [Jekyll front matter](https://jekyllrb.com/docs/frontmatter/) to the
    beginning of the file, following the pattern of other posts. If you'd like
    to add a new author, add the metadata to `_config.yml`.
1.  Write your article in Markdown. Author info will be added automatically to
    the article, so don't worry about that.
1.  Publish it by opening an PR and having it merged into `master`.

## Serving it locally

If you'd like to see what it'll look like when it's published, do the following:

1.  Install [Ruby Version Manager](https://rvm.io/).
1.  Install a Ruby version: `rvm install 2.4`
1.  Install package dependencies: `bundle install`
1.  Run the server, defaults to http://localhost:4000. `bundle exec jekyll serve`
