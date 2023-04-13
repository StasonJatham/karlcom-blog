# Hugo FixIt Blog Template (Git)

This is a quick start template for Hugo theme [FixIt](https://github.com/hugo-fixit/FixIt). It uses [Git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) feature to load the theme.

It comes with a basic theme structure and configuration. GitHub action has been set up to deploy the theme to a public GitHub page automatically. Also, there's a cron job to update the theme automatically everyday.

1. Click *Use this template*, and create your repository on GitHub.
2. Once the repository is created, just clone and enjoy it!

## Directory structure

```bash
▸ .github/       # GitHub configuration
▸ archetypes/    # page archetypes (like scaffolds of archetypes)
▸ assets/        # css, js, third-party libraries etc.
▸ config/        # configuration files
▸ content/       # markdown files for hugo project
▸ data/          # blog data (allow: yaml, json, toml), e.g. friends.yml
▸ public/        # build directory
▸ static/        # static files, e.g. favicon.ico
▸ themes/        # theme submodules
```

## Quick Start

### Prerequisites

Just install latest version of [Hugo(>= 0.109.0)](https://gohugo.io/installation/) for your OS (Windows, Linux, macOS).

### Clone Template

Clone with your own repository url

```bash
git clone --recursive git@github.com:hugo-fixit/hugo-fixit-blog-git.git
```

### Launching the Site

```bash
# Development environment
hugo server --disableFastRender --navigateToChanged --bind 0.0.0.0
# Production environment
hugo server --disableFastRender --navigateToChanged --environment production --bind 0.0.0.0
```

<details>
  <summary>Start via NPM script</summary>

  ```bash
  npm install
  # build the blog
  npm run build
  # run a local debugging server with watch
  npm run server
  # run a local debugging server in production environment
  npm run server:production
  # update theme submodules
  npm run update:theme
  ```

</details>


### Build the Site

When your site is ready to deploy, run the following command:

```bash
hugo
```

For a complete quick start, see this [page](https://fixit.lruihao.cn/documentation/getting-started/).

<!-- This project was generated with [hugo-fixit-blog-git](https://github.com/hugo-fixit/hugo-fixit-blog-git). Documentation about the original structure can be found [here](https://github.com/hugo-fixit/hugo-fixit-blog-git#directory-structure). -->
