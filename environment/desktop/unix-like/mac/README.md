# Mac Setup

## Settings

* System Preferences
  * Appearance
    * Show scroll bars: Always

## Software

* [Rectangle](https://rectangleapp.com/) _(previously [Spectacle](https://www.spectacleapp.com/))_
* [Homebrew](https://brew.sh/)
  * Brews _(`brew install <formulaName>`)_:
    * `cask`
    * `direnv`
    * `mysql`
    * `nvm`
    * `wget`
    * `powerlevel10k`
      * Add `source $(brew --prefix)/share/powerlevel10k/powerlevel10k.zsh-theme` to `.zshrc` post-install
  * Casks _(`brew install --cask <caskName>`)_:
    * `qlmarkdown`
    * `qlvideo` _(open app in Applications after installing)_
    * `syntax-highlight` _(install with `--no-quarantine` flag)_
    * `youtube-to-mp3`
      * Latest version requires downloading and installing straight from MediaHuman's website;
        brewing causes YouTube downloads to fail
* [1password](https://1password.com/downloads/mac/)
* [VLC Media Player](https://www.videolan.org/vlc/download-macosx.html)
* [Audacity](https://www.audacityteam.org/download/mac/)
* [Cron](https://cron.com/download/macos/)
* [SimpleComic](https://apps.apple.com/us/app/simple-comic/id1497435571)
* [GIPHY Capture](https://apps.apple.com/us/app/giphy-capture-the-gif-maker/id668208984)
* [Hermes](https://hermesapp.org/)
* [Microsoft Remote Desktop](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466)
* Visual Studio Code
    * [Run `code` from the command line to launch Visual Studio Code](https://code.visualstudio.com/docs/setup/mac)
* [iTerm2](https://iterm2.com/downloads.html)
  * Startup
    * Window restoration policy: "Use System Window Restoration Setting"
      * Turn off "General > Close windows when quitting an app" in macOS System Preferences (see [here](https://iterm2.com/documentation-restoration.html) for why)
  * Closing
    * Check "Quit when all windows are closed"
  * Profiles
    * Profiles > Keys > General
    * Left Option key: Esc+
    * Profiles > Keys > Key mappings
      | FOR | ACTION | SEND |
      | --- | ------ | ---- |
      | ⌘ ← |"SEND HEX CODE" | `0x01` |
      | ⌘ → |"SEND HEX CODE" | `0x05` |
      | ⌥ ← |"SEND ESC SEQ" | `b` |
      | ⌥ → |"SEND ESC SEQ" | `f` |
    * Pointer Settings
      * Bindings
        * Remove all bindings
        * Add action for "Paste from Clipboard" and set to "Right button single click"
