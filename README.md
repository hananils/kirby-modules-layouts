# Kirby Modules Layouts

This is an experimental plugin adding additonal layout options to [Thomas Günther's Modules plugin](https://github.com/medienbaecker/kirby-modules).

## Layouts

Layouts can be enabled by defining the `layout` option on the module definition. Layouts can be combined in a whitespace-separated list, e. g. `layout: list info`.

- `layout: list`: Creates a dense layout similar to the default pages section list layout.
- `layout: info`: Adds styles for `<small>` elements in module labels which will be rendered smaller with dimmed colors. Small texts will create a new line and can either be used to start ("eyebrow") or end the label ("info text").
- `layout: shortened`: Makes sure long labels will not wrap to the next line, shortening texts with and ellipsis. This mimicks Kirby's default section behaviour.
