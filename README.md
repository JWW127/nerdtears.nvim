# NerdTears

Simple High Contrast Neovim Theme

<div align="center">
    <img src="https://res.cloudinary.com/dpc3zrcvs/image/upload/t_700 nerdtears/v1747933214/nerdtears-demo_d6c3hu.png">
</div>

## Install

> [!CAUTION]
> No LIGHT VERSION

### LazyVim

- just add to your colorscheme.lua file

```lua
return {
  { "JWW127/nerdtears.nvim" },

  {
    "LazyVim/LazyVim",
    opts = {
      colorscheme = "nerdtears",
    },
  },
}
```

### Packer

```lua
use { "JWW127/nerdtears.nvim" }
```

## Inspiration

I essentially used @ellisonleao's gruvbox as a template then adjusted colors to my taste.
[https://github.com/ellisonleao](ellisonleao)
