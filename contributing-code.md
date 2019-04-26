# Contributing code
### Getting started
1) Fork this repository, then clone your fork to make changes on your local machine. See [here](https://help.github.com/en/articles/fork-a-repo) for help on forking and keeping your fork synced.

2) Install bundler and jekyll gems.

        gem install bundler jekyll

    If this command fails because you do not have ruby on your machine, follow the [instructions to install ruby](https://www.ruby-lang.org/en/documentation/installation/).

3) Install dependencies for this project.

        bundle install

4) Start jekyll to build the site and make it available on a local server. You should be able to see it running at http://localhost:4000

        bundle exec jekyll serve

5) Once your changes are ready, you'll make a pull request (PR) to have your changes reviewed by one of the maintainers who can merge the changes to the production website.

6) Check out the [issues tab](https://github.com/humanetech-community/community-hub/issues) for open tickets you might be able to help with, especially if there are any with the ![](https://img.shields.io/badge/-good%20first%20issue-blueviolet.svg) tag!


### Docs / Resources
- The community hub is a static site built with [jekyll](https://jekyllrb.com/). If you're new to jekyll, we recommend checking out the [docs](https://jekyllrb.com/docs), in particular the [tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/).

- On top of jekyll, we also use a theme called [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) which provides a lot of useful functionality.


### Tips / Tricks
- remember that any changes to `_config.yml` will require you to restart jekyll in order to take effect!

