# Windows Base Setup

* Pre-requistes
  * Windows Pro
* Install
  * Chrome
  * VS Code - https://code.visualstudio.com/
  * Git, Git Bash - https://gitforwindows.org/
  * Choco - https://chocolatey.org/install
  * WSL
    * WSL first - https://docs.microsoft.com/en-us/windows/wsl/install-win10#install-your-linux-distribution-of-choice
    * Install Ubuntu
    * WS2- https://docs.microsoft.com/en-us/windows/wsl/wsl2-install
    * Setup ssh keys for git 
* Choco Install
  * Sudo - `choco install sudo` 
    * Give windows sudo like capability
  * Miniconda - `sudo choco install miniconda3`
    * Add to Path 
    * `conda init`
* Ubuntu Install
  * Miniconda - `./scripts/miniconda.sh`
* Setup
  * Add SSH keys to Github - https://help.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent