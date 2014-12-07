# All-your-base -- Sane Sass scaffolds for you

All-your-base is a Sass scaffolding tool created to bring sense into colorscheme management, neat typography and media-queries. It consists of three components that work in unison, but are designed to be as decoupled as possible(e.g. typera's responsive text doesn't make much sense without semantic-query media-queries). Thus, one may use the sub-projects separately or combined.

## Example usage

```
@import 'all-your-base';

$fonts: (
  serif: 'Lora',
  sans-serif: 'Questrial',
  monospace: 'VT323',
  cursive: 'Lobster'
);

$colors: (
  primary: #9955ff,
  scheme: accented-analogic
);

$palette: palette($colors);
@include typography($fonts, $palette);
```
