# Mkdocs Workshop

This repository serves as an mkdocs-material based template for creating #30DaysOf websites that can be hosted on GitHub Pages endpoints.

**Features:** The repository is instrumented with:

1. A [**devcontainer**](https://containers.dev). This means you can launch it with GitHub Codespaces (cloud) or Docker Desktop (local) to get a pre-build development environment for modifying and previewing the website.
1. A [GitHub Actions for MkDocs](https://squidfunk.github.io/mkdocs-material/publishing-your-site/?h=pages#with-github-actions) workflow. This means it will automatically rebuild and publish the website to GitHub Pages on very repo commit. You can also force a manual publish anytime with `mkdocs gh-deploy --force`.
1. A [Google Analytics](https://squidfunk.github.io/mkdocs-material/setup/setting-up-site-analytics/?h=google+an#google-analytics) tracker. This is useful for tracking user behaviors in your website and understanding where learners drop off most or have issues. It also demonstrates usage of [built-in cookie consent](https://squidfunk.github.io/mkdocs-material/setup/ensuring-data-privacy/?h=cookies#cookie-consent) support in mkdocs-material.

<br/>

**Content:** The repository contains:

1. An [Mkdocs Workshop](./01-Workshop/) tutorial that teaches you how this website was setup, and how you can customize or repurpose it for your new project.
1. A [Basic blog](https://squidfunk.github.io/mkdocs-material/tutorials/blogs/basic/?h=blog) example that shows you what a #30DaysOf series structure could look like, with tips for syndication and SEO.

---