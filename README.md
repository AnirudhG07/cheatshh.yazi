# cheatshh.yazi
A Yazi plugin for searching commands and copying them to your clipbaord, using [cheatshh](https://github.com/AnirudhG07/cheatshh)

## Dependencies
Please follow the download instruction and dependencies in the below link.
- [cheatshh](https://github.com/AnirudhG07/cheatshh)

This is mainly for Unix(Linux and Macos). 

## Installation
Use the below command to install the plugin-
```bash
git clone https://github.com/AnirudhG07/cheatshh.yazi.git ~/.config/yazi/plugins/cheatshh.yazi
```
## Keymapping and Usage
You can copy the below commands to `keymap.toml` to use the plugin-
```toml
[[manager.prepend_keymap]]
on   = [ "c","h" ]
run  = "plugin cheatshh"
desc = "Find command in cheatshh"
```

## TODO
1. Add provision for more flags in cheatshh hopefully using popup in the middle of the screen.
2. Fill the yazi_cheatsheet with commands.