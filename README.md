svelte-logoipsum
================

Svelte components for the beautiful [Logoipsum placeholders](https://logoipsum.com/).

## Installation

With npm
`npm install --save-dev svelte-logoipsum`

or yarn
`yarn add --dev svelte-logoipsum`

## Usage

```html
<script>
  import { Logo1, Logo16 } from 'svelte-logoipsum';
</script>

<Logo1 />
<Logo1 color="red" />
<Logo16 color1="#2a9d8f" color2="#ffd200" />
```

All components expose properties to change each color. Most logos are just one color so they just have a `color` property. If a logo has more than one color then the colors are numbered (i.e. `color1="#2a9d8f" color2="#ffd200"`). There's no real rhyme or reason to which color is assigned to which number, so just play around until you find what you want. :)

## Acknowledgements

All logo designs are from [logoipsum by SignalSupply](https://logoipsum.com/).

### TODO

- Github page for showing component usage.
