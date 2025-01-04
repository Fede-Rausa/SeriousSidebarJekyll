---
id: getting-started
title: Getting Started
auto_title: false
---

## Initialize Config

Add a `_config.yml` file to your docs directory. That can either be the repository root, or `/docs`.
Specify this theme as the `remote_theme`.

```yaml
remote_theme: Fede-Rausa/SeriousSidebarJekyll@main
```

Note, the `@main` version pin is required because GitHub pages currently only looks for the latest
`remote_theme` on the remote repositories master branch.

That's it! This will setup the minimal theme to be active once you enable GitHub pages in your
repo settings.


## Additional Features

[Sidebar Navigation](./customization/sidebar.md) and [Search](./customization/search.md) can be
enabled through additional site configuration.


## complete example content for config.yml
The content of thise file and the structure of the sidebar, explained in [Sidebar Navigation](./customization/sidebar.md), is everything you have to know
to build a markdown static website!
All the parameters, except sidebar, are explained in [this table](https://fede-rausa.github.io/SeriousSidebarJekyll/customization/additional.html)

```yaml
remote_theme: Fede-Rausa/SeriousSidebarJekyll@main

title: Serious Sidebar Jekyll Theme
version: v2.4.5
custom_footnotes: written by Z.R.

show_global_footnotes:  false
show_icons_navbar: false
link_to_github_repo: false
search_enabled: true
auto_page_title: true
show_title: true
show_last_update_datetime: true
show_version: true
show_custom_footnotes: true

sidebar:
  - getting-started
  - label: Customization
    children:
      - sidebar
      - search
      - relative-nav
      - additional-config
  - development
```
