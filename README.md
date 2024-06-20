<img src="https://cdn.rawgit.com/oh-my-fish/oh-my-fish/e4f1c2e0219a17e2c748b824004c8d0b38055c16/docs/logo.svg" align="left" width="144px" height="144px"/>

#### material_fish
> A theme for [Oh My Fish][omf-link].

[![Fish Shell Version](https://img.shields.io/badge/fish-≥v2.2.0-007EC7.svg?style=flat-square)](https://fishshell.com)
[![Oh My Fish Framework](https://img.shields.io/badge/Oh%20My%20Fish-Framework-007EC7.svg?style=flat-square)](https://www.github.com/oh-my-fish/oh-my-fish)

<br/>

### Install Fish

`brew install fish`

### Make Fish the default

1. check the fish path with `which fish`. In the examples below it was located at: `/opt/homebrew/bin/fish`. On older Macs the path might differ.
2. **Add fish to the know shells**
  run the command: `sudo sh -c 'echo /opt/homebrew/bin/fish >> /etc/shells'`
3. Restart your terminal
4. **Set fish as the default shell**
   run the command: `chsh -s /opt/homebrew/bin/fish`
5. Restart your terminal and check if it launched with `fish` or not
6. **Add brew binaries in fish path**
   run the command: `fish_add_path /opt/homebrew/bin`

### Install OMF

```fish
$ git clone https://github.com/oh-my-fish/oh-my-fish
$ cd oh-my-fish
$ bin/install --offline
```

### Install Theme

```fish
$ omf install https://github.com/JCTec/material_fish
$ omf theme material_fish
```

[omf-link]: https://www.github.com/oh-my-fish/oh-my-fish
