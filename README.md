# apollo

Modern and minimalistic blog theme powered by [Zola](https://getzola.org). See a live preview [here](https://not-matthias.github.io/apollo).

<sub><sup>Named after the greek god of knowledge, wisdom and intellect</sup></sub>

## Features

- [X] Pagination
- [X] Themes (light, dark, auto)
- [X] Projects page
- [x] Social Links
- [x] MathJax Rendering
- [x] Taxonomies
- [x] Meta Tags For Individual Pages
- [x] Custom homepage
- [x] Comments
- [ ] Search
- [ ] Categories

## Installation

1. Download the theme

```bash
git submodule add git@github.com:headlessvoyager/apollo.git  themes/apollo
```

2. Add the following to the top of your `config.toml`

```toml
theme = "apollo"
taxonomies = [{ name = "tags" }]

[extra]
theme = "auto"
socials = [
  # Configure socials here
]
menu = [
  # Configure menu bar here
]

# See this for more options: https://github.com/not-matthias/apollo/blob/main/config.toml#L14
```

3. Copy the example content

```
cp -r themes/apollo/content/* content/
```

## Configuration

You can find all the configuration options [here](./content/posts/configuration.md)

## References

This theme is based on [archie-zola](https://github.com/XXXMrG/archie-zola/).
