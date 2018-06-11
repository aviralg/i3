# i3

This is my configuration for [i3](https://i3wm.org/ "i3 Window Manager").

## Key bindings

### Default Mode

| Key binding                  | Action                                           |
| ---------------------------- | ------------------------------------------------ |
| Mod+Enter                    | Open terminal                                    |
| Mod+Shift+C                  | Close focused window                             |
| Mod+Shift+F                  | Reload configuration file                        |
| Mod+Shift+R                  | Restart i3 in place (preserves layout/session)   |
| Mod+Shift+Q                  | Log out from Xsession                            |
| Mod+Shift+T                  | Reboot                                           |
| Mod+Shift+S                  | Suspend                                          |
| Mod+Shift+W                  | Hibernate                                        |
| Mod+Shift+x                  | Lock                                             |
| Mod+Shift+e                  | Shutdown                                         |
| Mod+o                        | Program Launcher                                 |
| Mod+h  Mod+Left              | Focus Left                                       |
| Mod+l  Mod+Right             | Focus Right                                      |
| Mod+k  Mod+Up                | Focus Up                                         |
| Mod+j  Mod+Down              | Focus Down                                       |
| Mod+Shift+h  Mod+Shift+Left  | Move Left                                        |
| Mod+Shift+l  Mod+Shift+Right | Move Right                                       |
| Mod+Shift+k  Mod+Shift+Up    | Move Up                                          |
| Mod+Shift+j  Mod+Shift+Down  | Move Down                                        |
| Mod+x                        | Split Horizontal                                 |
| Mod+y                        | Split Vertical                                   |
| Mod+e                        | Toggle Split                                     |
| Mod+f                        | Fullscreen Toggle                                |
| Mod+d                        | Default Layout                                   |
| Mod+s                        | Stacked Layout                                   |
| Mod+t                        | Tabbed Layout                                    |
| Mod+a                        | Focus on parent                                  |
| Mod+g                        | Focus on child                                   |
| Mod+Space                    | Switch focus between tiling and floating windows |
| Mod+Shift+Space              | Toggle between tiling/floating                   |
| Mod+n n ∈ {0 .. 9}           | Switch to Workspace n                            |
| Mod+r                        | Switch to Resize mode                            |
| Mod+m                        | Switch to Move mode                              |


### Move Mode

In move mode, the arrow keys and home row keys can be used to move the focused window.

| Key binding | Action                   |
| ----------- | ------------------------ |
| h  Left     | Move Left                |
| l  Right    | Move Right               |
| k  Up       | Move Up                  |
| j  Down     | Move Down                |
| Return      | Switch to Default mode   |
| Escape      | Switch to Default mode   |
| Mod+m       | Switch to Default mode   |

### Resize Mode

In resize mode, the arrow keys and home row keys can be used to resize the focused window.

| Key binding | Action                  |
| ----------- | ----------------------- |
| h  Left     | Shrink width            |
| l  Right    | Grow width              |
| k  Up       | Shrink height           |
| j  Down     | Grow height             |
| Return      | Switch to Default mode  |
| Escape      | Switch to Default mode  |
| Mod+r       | Switch to Default mode  |


## Todo
- Font setup from [Nerd Fonts](https://nerdfonts.com/ "Nerd Fonts: Iconic font aggregator, collection, and patcher").
- Devise `$mod+Shift+<keysym>` key-bindings for reload, restart, close, halt, logout and lock operations.
- Configure better border and indicator colors from [i3-configurator](https://thomashunter.name/i3-configurator/ "i3-configurator: Online Colorscheme Configurator for i3, i3status, dmenu"). Take inspiration from [i3wm-themer](https://github.com/unix121/i3wm-themer "i3wm-themer: A collection of themes and scripts for i3-wm").
- Create key bindings for standard program keys
- Document special keys and program keys
