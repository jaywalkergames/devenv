# devenv
My development environment setup.


### WSL
Install: https://learn.microsoft.com/en-us/windows/wsl/install

Setup:

- java: `curl -s "https://get.sdkman.io" | bash` && open new shell
- javascript: `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash` && open new shell
- python: `curl -LsSf https://astral.sh/uv/install.sh | sh`
- rust:  `curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh`


### Docker
Install: https://docs.docker.com/desktop/wsl/


### Neovim
1. Install [neovim](https://neovim.io/doc/install/)
2. Install [config](https://github.com/jaywalkergames/kickstart.nvim)



## Language Environments


### Java
Install: `sdk install java 25-tem` && `sdk install gradle`

Remove: `sdk uninstall java 25-tem`

Check Version: `sdk current java`

Change Version: `sdk use java 25-tem`

Default Version: `sdk default java 25-tem`


### JavaScript
Install: `nvm install node` or `nvm install 14.7.0`

Check Version: `node --version` and `npm --version`

Change Version: `nvm use node`


### Python
Install: `uv python install 3.12`

Activate: `uv sync`

Update uv: `uv self update`


### Rust
Check Version: `rustc --version` && `cargo --version`

Update Version: `rustup update`
