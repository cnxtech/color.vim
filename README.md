# color.vim
my colorscheme

## [Neovim](https://github.com/neovim/neovim)
```
export NVIM_TUI_ENABLE_TRUE_COLOR=1
```

## [FZF](https://github.com/junegunn/fzf)
```
export FZF_DEFAULT_OPTS='
  --color=bg+:#282c34,bg:#21252a,spinner:#98c373,hl:#98c373
  --color=fg:#abb2c0,header:#abb2c0,info:#526270,pointer:#d19966
  --color=marker:#d19966,fg+:#abb2c0,prompt:#abb2c0,hl+:#d19966
'
```

## [Sway](https://github.com/SirCmpwn/sway)
```
bar {
  colors {
    separator #282c34
    background #21252a
    statusline #abb2c0
    focused_workspace #abb2c0 #21252a #abb2c0
    active_workspace #21252a #21252a #abb2c0
    inactive_workspace #21252a #21252a #abb2c0 
    urgent_workspace #abb2c0 #21252a #abb2c0
  }
}
client.focused          #282c34 #abb2c0 #282c34 #abb2c0 
client.focused_inactive #282c34 #282c34 #282c34 #282c34 
client.unfocused        #282c34 #282c34 #282c34 #282c34 
client.urgent           #282c34 #282c34 #282c34 #282c34 
```

## [Highlight](http://www.andre-simon.de/doku/highlight/en/highlight.php)
`~/.highlight/hinshun.theme`
```
Description = "hinshun"

Default	= { Colour="#abb2c0" }
Canvas	= { Colour="#282c34" }
Number	= { Colour="#d19966" }
Escape	= Default
String	= { Colour="#98c373" }
BlockComment	= { Colour="#526270" }
StringPreProc = String
LineComment   = BlockComment
Operator      = Default
LineNum      = BlockComment
PreProcessor      = { Colour="#defa25" }
Interpolation  = Escape

Keywords = {
  { Colour="#4096dd" },
  { Colour="#4096dd" },
  { Colour="#4096dd" },
  { Colour="#4096dd" },
}
```
