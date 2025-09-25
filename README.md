# devenv
My development environment setup.


### WSL
Install: https://learn.microsoft.com/en-us/windows/wsl/install

Setup:
1. `sudo apt update`
2. `sudo apt install -y build-essential gcc g++ make gdb clang lldb clang-format clang-tidy cmake ninja-build pkg-config git curl unzip zip libpq-dev python3-dev`
3. `sudo add-apt-repository ppa:deadsnakes/ppa`
4. `sudo apt update`
5. `sudo apt install -y python3.13 python3.13-venv python3.13-dev python3-pip python3.13-distutils`
6. `mkdir ~/.venvs`
7. `curl -s "https://get.sdkman.io" | bash` && open new shell
8. `sdk install java 25-tem`
9. `sdk install gradle`
10. `curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash` && open new shell


### Docker
Install: https://docs.docker.com/desktop/wsl/


### Neovim
X



## Language Environments



### C++
Set in CMakeLists.txt


### Java
Install: `sdk install java 25-tem`
Remove: `sdk uninstall java 25-tem`
Check Version: `sdk current java`
Change Version: `sdk use java 25-tem`
Default Version: `sdk default java 25-tem`


### JavaScript
Install: `nvm install node` or `nvm install 14.7.0`
Check Version: `node --version` and `npm --version`
Change Version: `nvm use node`


### Python
Create: `python3.13 -m venv ~/.venvs/myenv`
Activate: `source ~/.venvs/myenv/bin/activate`
Deactivate: `deactivate`
Remove: `rm -rf ~/.venvs/myenv`
