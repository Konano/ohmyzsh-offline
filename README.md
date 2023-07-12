# oh-my-zsh offline install

This patch is for Oh My Zsh to be installed offline.

### Usage

1. Prepare the [Oh My Zsh source code](https://github.com/ohmyzsh/ohmyzsh/archive/refs/heads/master.zip) on GitHub and extract it to `~/oh-my-zsh-source`.
2. `cd ~/oh-my-zsh-source` and put the [patch](https://raw.githubusercontent.com/Konano/ohmyzsh-offline/main/offline-patch.diff) into the folder.
3. Run `git apply offline_patch.diff`.
4. Now you can install by runing `sh ./tool/install.sh`.
