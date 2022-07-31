

## Objective

This Hugo Theme Component allows to easily **insert audio players from local and remote files**


## Usage

```
{{<audio src="https://archive.org/download/test/aufiofile.mp3" >}}
```

## Installation

Requires **Hugo > 0.42**

    git submodule add https://gitlab.com/Roneo/hugo-shortcode-roneo-audio-player.git themes/hugo-shortcode-roneo-audio-player

Edit `config.toml`

    theme = ["hugo-shortcode-roneo-audio-player", "YourCurrentTheme"]
    enableInlineShortcodes = true

To learn more about "Theme components", see [the Hugo documentation](https://gohugo.io/hugo-modules/theme-components/)


### Call from a Markdown file

with the following Shortcode

```go
{{< audio  src="/audiofilename.mp3" >}}
```

with a custom CSS class

```go
{{< audio src="/audiofilename.mp3" class="custom-class" caption="A custom comment" >}}
```



## Contribute

Please star this repo to help this project gain some visibility and reach new contributors.

Code contributions are welcome, and the main place for development is [this Gitlab repo](https://gitlab.com/Roneo/hugo-shortcode-roneo-audio-player).

## References

- https://www.johnarroyo.com/2021/02/adding-audio-to-hugo/
- [Hugo documentation about Theme Components](https://gohugo.io/hugo-modules/theme-components/)
- Hugo documentation about [Shortcodes](https://gohugo.io/content-management/shortcodes/)
- Hugo documentation about [Partial Templates](https://gohugo.io/templates/partials/).