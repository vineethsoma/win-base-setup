# Windows Base Setup

* Pre-requistes
  * Windows Pro
* Install
  * Chrome
  * VS Code - https://code.visualstudio.com/
  * Git, Git Bash - https://gitforwindows.org/
  * Choco - https://chocolatey.org/install
  * [WSL](./docs/wsl-setup.md)
* Choco Install
  * Sudo - `choco install sudo` 
    * Give windows sudo like capability
  * Miniconda - `sudo choco install miniconda3`
    * Add to Path 
    * `conda init`
    * PS - `Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser` for UnAuthorizedAccess error
  * AWS CLI - `pip install awscli`
    * `aws configure`
  * Docker
    * `choco install docker-desktop`
    * Restart after
* WSL Ubuntu Install
  * Miniconda - `./scripts/miniconda.sh`
  * AWS CLI = `pip install awscli`
  * [NVM](./docs/nvm-setup.md)
* Setup
  * Add SSH keys to Github - https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent