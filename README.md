# Twitch Chat CLI
[Twitch.tv](https://twitch.tv) chat client in your terminal

## Demo

## Features


Goal is to be simmiler to [Chatterino](https://chatterino.com/), but for CLI use

Built With
- Go
- bubbletea

## Inspiration
- https://github.com/chatterino/chatterino2 - Chatterino
- https://github.com/atye/ttchat, similar principle, 1 channel only and need dev account
- https://github.com/dlvhdr/gh-dash - beautiful TUI

## Docs
- https://dev.twitch.tv/docs/cli
- https://dev.twitch.tv/docs/irc
- https://github.com/gempir/go-twitch-irc
- https://github.com/nicklaw5/helix


## TODO
- [ ] Open streamlink for current channel
- [ ] Add multiuser support
- [x] Tab for each chat/channel
- [x] Scrolling chat window
- [ ] Remove older messages
- [ ] OIDC Authorization code grant flow Authentication (https://dev.twitch.tv/docs/authentication/getting-tokens-oidc). Doing this currently via OIDC Implicit grant flow which requires copy/pasting. Not ideal
  - Consider via oauth2 pkg https://pkg.go.dev/golang.org/x/oauth2#AuthStyle, https://dev.twitch.tv/docs/authentication/getting-tokens-oauth/#implicit-grant-flow
- [x] Enter chat msg
- [ ] Vim-modes for navigation
- [x] Idea: Start in lurker mode. No chat input, just focus on seeing
- [x] Goreleaser https://goreleaser.com/intro/
- [ ] Animated emotes (image/gif?)
- [ ] Add to lists
  - https://github.com/charmbracelet/bubbletea#bubble-tea-in-the-wild
  - https://github.com/rothgar/awesome-tuis
- [x] Add viper for config files https://github.com/spf13/viper
- [ ] BTTW emote support via https://github.com/pajlada/gobttv (see usage https://github.com/pajbot/pajbot2/search?q=gobttv)
- [ ] Add emote cache https://github.com/charmbracelet/charm/tree/main/kv
- [ ] User profile pages + mentions
- [ ] Nicer text wrapping (indentet length of user name)
- [ ] Add info about terminal emote support (kitty / iterm2 / sixel)
  - https://github.com/alacritty/alacritty (soon)
    - soon https://github.com/alacritty/alacritty/pull/4763, https://github.com/alacritty/alacritty/issues/910
  - Windows Terminal does not support emotes
- [ ] `PM` and `WhisperMessage` support. See https://pkg.go.dev/github.com/gempir/go-twitch-irc/v3@v3.0.0#readme-available-data


## License

This application is released under the MIT license. See [`LICENSE`](LICENSE)
