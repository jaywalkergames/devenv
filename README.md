# devenv
My development environment setup.


### WSL
Install: https://learn.microsoft.com/en-us/windows/wsl/install

### Docker
Install: https://docs.docker.com/desktop/wsl/

### VS Code
Install: https://code.visualstudio.com/

### VS Code Extensions
Black Formatter
Debugger for Java
Docker
ESLint
Flake8
GitHub Copilot
Gradle for Java
IntelliCode
Language Support for Java by Red Hat
Prettier
Project Manager for Java
Pylance
Python
Python Debugger
Tailwind CSS IntelliSense



## Python


### Install
Anaconda: https://docs.anaconda.com/anaconda/install/linux/


### Management
Create Environment: `conda create --name <env name> python=3.12`
Activate Environment: `conda init` and `conda activate <env name>`
Check Version: `python --version`



# Java


### Install
SDKMAN!: https://sdkman.io/install
JDK: https://sdkman.io/jdks
Gradle: `sdk install gradle`


### Management
Install: `sdk install java 22-open`
Remove: `sdk uninstall java 22-open`
Check Version: `sdk current java`
Change Version: `sdk user java 22-open`
Default Version: `sdk default java 22-open`



## JavaScript


### Install
NVM: https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating
Node/NPM: `nvm install node` or `nvm install 14.7.0`


### Management
Check Version: `node --version` and `npm --version`
Change Version: `nvm use node`
