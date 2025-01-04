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
