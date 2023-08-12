# Zola Bear+ Blog Theme

## Installation

If you already have a Zola site on your machine, you can simply add this theme via

```
git submodule add https://codeberg.org/alanpearce/zola-bearblog themes/zola-bearblog
```

Then, adjust the `config.toml` as detailed below.

For more information, read the official [setup guide][zola-setup-guide] of Zola.

## Adjust configuration / config.toml

Please check out the included [config.toml](https://codeberg.org/alanpearce/zola-bearblog/src/branch/main/config.toml)

## Content & structure

### Menu

Create an array in `extra` with a key of `main_menu`. `url` is passed to [`get_url`](https://www.getzola.org/documentation/templates/overview/#get-url)

```toml
[[extra.main_menu]]
name = "Bear"
url = "@/bear.md"

[[extra.main_menu]]
name = "Zola"
url = "@/zola.md"

[[extra.main_menu]]
name = "Blog"
url = "@/blog/_index.md"
```

### Adding / editing content

#### Index-Page

The contents of the `index`-page may be changed by editing your `content/_index.md`-file.


### Adding your branding / colors / css

Add a `custom_head.html`-file to your `templates/`-directory. In there you may add a `<style>`-tag, *or* you may add a `<link>`-tag referencing your own `custom.css` (in case you prefer to have a separate `.css`-file). Check out the [`style.html`](https://codeberg.org/alanpearce/zola-bearblog/src/branch/main/templates/style.html)-file to find out which CSS-styles are applied by default.


## Acknowledgements

A special thank you goes out to [Herman](https://herman.bearblog.dev), for creating the original [ʕ•ᴥ•ʔ Bear Blog](https://bearblog.dev/), [Jan Raasch](https://www.janraasch.com) for creating the Hugo port of the Bear Blog theme, and [Alan Pearce](https://alanpearce.eu) for creating the Zola port of the Bear Blog theme.
