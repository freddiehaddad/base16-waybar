# base16-waybar

This repo provides templates for using
[Base16](https://github.com/tinted-theming) color schemes with
[Waybar](https://github.com/Alexays/Waybar), a status bar for Wayland
compositors like [Sway](https://github.com/swaywm/sway).

The color schemes are built from the Tinted Theming source which extends the
number of colors to over 200.

It's still a work in progress, and right now only provides the Base16 colors as
CSS variables. You can download the generated color files and then include them
to use the CSS variables `@base{00-0F}` in a Waybar style config like this:

```css
@import "/path/to/color/scheme.css";

window#waybar {
  color: @base04;
}
```

This repo was originally forked from
[https://github.com/mnussbaum/base16-waybar](https://github.com/mnussbaum/base16-waybar).
Due to lack of updates and being built around an unmaintained set of sources, I
have taken over this project.
