# varname1.github.io

Personal site built with [Jekyll](https://jekyllrb.com/).

## Local Setup

### Prerequisites

- [Ruby](https://www.ruby-lang.org/) (v2.5+)
- [Bundler](https://bundler.io/)

### 1. Install dependencies

```bash
sudo apt install libssl-dev
bundle config set --local path 'vendor/bundle'
bundle install
```

### 2. Run the development server

```bash
bundle exec jekyll serve
```

The site will be available at `http://localhost:4000`. Changes to `_config.yml` require a server restart; other edits are auto-regenerated.
