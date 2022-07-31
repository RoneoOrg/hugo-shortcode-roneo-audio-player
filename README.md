

## Objective

This Hugo Theme Component allows to easily **insert audio players**

Both a [Shortcode](https://gohugo.io/content-management/shortcodes/) and a [Partial Template](https://gohugo.io/templates/partials/) are provided.

## Usage

```
{{< audio src="/audiofilename.mp3" class="custom-class" >}}
```

## Installation

Requires **Hugo > 0.42**

    git submodule add https://gitlab.com/Roneo/hugo-shortcode-roneo-audio-player.git themes/hugo-shortcode-roneo-audio-player

Edit `config.toml`

    theme = ["hugo-shortcode-roneo-audio-player", "YourCurrentTheme"]

To learn more about "Theme components", see [the Hugo documentation](https://gohugo.io/hugo-modules/theme-components/)


### Call from a Markdown file

with the following Shortcode

```go
{{< audio  src="/audiofilename.mp3" >}}
```

with a custom CSS class

```go
{{< audio src="/audiofilename.mp3" class="custom-class" >}}
```

### Call from a template

```go
{{ partial "audio.html" (dict "context" . "pages" $.Site.Pages "/audiofilename.mp3" "custom-class" ) }}
```


## Contribute

Please star this repo [on Github](https://github.com/RoneoOrg/hugo-shortcode-roneo-button-icon-badge) or [Gitlab](https://gitlab.com/Roneo/hugo-shortcode-roneo-button-icon-badge), to help this project gain some visibility and reach new contributors.

Code contributions are welcome, and the main place for development is [this Gitlab repo](https://gitlab.com/Roneo/hugo-shortcode-roneo-button-icon-badge). Feel free to use [this Github repo](https://github.com/RoneoOrg/hugo-shortcode-roneo-button-icon-badge).

## References

- Inspired by the [Button Shortcode](https://github.com/marketempower/axiom/blob/master/layouts/shortcodes/button.html) from the [Axiom Theme](https://www.axiomtheme.com/docs/shortcodes/#button)
- [Hugo documentation about Theme Components](https://gohugo.io/hugo-modules/theme-components/)
- Hugo documentation about [Shortcodes](https://gohugo.io/content-management/shortcodes/)
- Hugo documentation about [Partial Templates](https://gohugo.io/templates/partials/).