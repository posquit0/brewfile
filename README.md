<div align="center">
  <a href="https://github.com/posquit0/brewfile" title="Brewfile">
    <img alt="posquit0's brewfile" src="https://raw.githubusercontent.com/posquit0/i/main/brewfile/icon.png" width="128px" />
  </a>
  <br />
  <h1>Brewfile</h1>
</div>

<p align="center">
  :apple: Brewfile to install softwares in macOS for engineers
</p>

<div align="center">
  <a href="https://opensource.org/licenses/mit-license.php">
    <img alt="MIT License" src="https://badges.frapsoft.com/os/mit/mit.svg?v=103" />
  </a>
  <a href="https://github.com/ellerbrock/open-source-badge/">
    <img alt="Open Source Love" src="https://badges.frapsoft.com/os/v1/open-source.svg?v=103" />
  </a>
</div>

<br />

[**This brewfile**](https://github.com/posquit0/brewfile) is written by [posquit0](https://github.com/posquit0/) to easily set up the development environment to macOS.

- If you want to override my configuration or add more configuration, just edit `Brewfile`.


## Usage

```bash
$ git clone https://github.com/posquit0/brewfile
$ cd brewfile

# Install base packages in `base.Brewfile`
$ brew bundle --file base.Brewfile

# Install filesystem related packages in `filesystem.Brewfile`
$ brew bundle --file filesystem.Brewfile

# Install fonts in `font.Brewfile`
$ brew bundle --file font.Brewfile

# Install media related packages in `media.Brewfile`
$ brew bundle --file media.Brewfile

# Install messaging related packages in `messaging.Brewfile`
$ brew bundle --file messaging.Brewfile

# Install office related packages in `office.Brewfile`
$ brew bundle --file office.Brewfile

# Install secret related packages in `secret.Brewfile`
$ brew bundle --file secret.Brewfile

# Install web related packages in `web.Brewfile`
$ brew bundle --file web.Brewfile

# Install development packages
$ brew bundle --file dev-base.Brewfile
$ brew bundle --file dev-android.Brewfile
$ brew bundle --file dev-container.Brewfile
$ brew bundle --file dev-db.Brewfile
$ brew bundle --file dev-ide.Brewfile
$ brew bundle --file dev-jvm.Brewfile
$ brew bundle --file dev-network.Brewfile
$ brew bundle --file dev-terminal.Brewfile
$ brew bundle --file dev-vcs.Brewfile
$ brew bundle --file dev-web.Brewfile

# Install devops packages in `devops.Brewfile`
$ brew bundle --file devops.Brewfile
```


## Self Promotion

Like brewfile? Follow the repository on [GitHub](https://github.com/posquit0/brewfile). And if you're feeling especially charitable, follow [posquit0](https://posquit0.com) on [GitHub](https://github.com/posquit0).


## See Also

- [dotfiles](https://github.com/posquit0/dotfiles) - Awesome configurations for the development environments.
- [gitconfig](https://github.com/posquit0/gitconfig) - Git configurations.
- [tmux-conf](https://github.com/posquit0/tmux-conf) - TMUX Configuration for nerds with tpm.
- [vimrc](https://github.com/posquit0/vimrc) - Vim Configuration for nerds with vim-plug.
- [zsh](https://github.com/posquit0/zshrc) - Zsh Configuration for nerds with zplug.


## License

Provided under the terms of the [MIT License](https://github.com/posquit0/brewfile/blob/main/LICENSE).

Copyright © 2018-2023, [Byungjin Park](https://www.posquit0.com).
