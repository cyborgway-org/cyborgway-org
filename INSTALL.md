# Installation

Please read through our [Contributing Guidelines](CONTRIBUTING.md).

## General setup

#### Using Docker (easy way)

- Install [Docker](https://www.docker.com)
- Run `docker-compose up -d`

The website can be accessed at http://localhost:4000.

#### Without Docker (advanced way)

- Install [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
- Install [Bundler](https://bundler.io)
- Install [Jekyll](https://jekyllrb.com/docs/installation/)

Before you start, install dependencies:

```
bundle install
```

Start development server:

```
bundle exec jekyll serve
```

The website can be accessed at http://localhost:4000.

In case you need to rebuild the website:

```
bundle exec jekyll build
```

In case you need to update dependencies:

```
bundle update listen
```

## Additional information

- [Testing your GitHub Pages site locally with Jekyll](https://help.github.com/en/articles/testing-your-github-pages-site-locally-with-jekyll)
