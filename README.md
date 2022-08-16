

## Objective

This Hugo Theme Component allows to easily **insert audio players from local and remote files**


## Usage

```
{{<audio src="https://archive.org/download/test/aufiofile.mp3" >}}
```

## Screenshot

<div align="center">

![Screenshot of the Shortcode in action](https://raw.githubusercontent.com/RoneoOrg/hugo-shortcode-roneo-audio-player/main/img/screenshot.jpg)

</div>

This shortcode is based on [Plyr.io](https://plyr.io/), see [the documentation](https://github.com/sampotts/plyr#features) to learn about the features

## Installation

Requires **Hugo > 0.42**

Install as a Git submodule  

    git submodule add https://gitlab.com/Roneo/hugo-shortcode-roneo-audio-player.git themes/hugo-shortcode-roneo-audio-player

Then edit `config.toml`

    theme = ["hugo-shortcode-roneo-audio-player", "YourCurrentTheme"]
    enableInlineShortcodes = true

To learn more about "Theme components", see [the Hugo documentation](https://gohugo.io/hugo-modules/theme-components/)


### Insert in a Markdown file

With the following Shortcode

```go
{{< audio  src="/audiofilename.mp3" >}}
```

Options are available. Here we define a custom CSS class and a caption:

```go
{{< audio src="/audiofilename.mp3" class="custom-class" caption="A custom comment" >}}
```



## Contribute

Please [star this repo](https://github.com/RoneoOrg/hugo-shortcode-roneo-audio-player) to help this project reach new contributors.

Code contributions are welcome, and the main place for development is [this Gitlab repo](https://gitlab.com/Roneo/hugo-shortcode-roneo-audio-player).

## References

- https://www.johnarroyo.com/2021/02/adding-audio-to-hugo/
- [Hugo documentation about Theme Components](https://gohugo.io/hugo-modules/theme-components/)
- Hugo documentation about [Shortcodes](https://gohugo.io/content-management/shortcodes/)
- Hugo documentation about [Partial Templates](https://gohugo.io/templates/partials/).