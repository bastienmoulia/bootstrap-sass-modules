# Bootstrap with SASS Modules

Bootstrap equivalent but with [SASS modules](https://sass-lang.com/blog/the-module-system-is-launched/) because `@import` is now deprecated.

## Differences

Between the original Bootstrap and this version:
- https://raw.githubusercontent.com/twbs/bootstrap/refs/heads/main/dist/css/bootstrap.css
- https://raw.githubusercontent.com/bastienmoulia/bootstrap-sass-modules/refs/heads/main/dist/css/bootstrap.css

You will see that SASS now generate RGB colors with decimal values instead of hex colors.
Also the inline SVG with `d=` path lost the last `z` character.
