# nvim_config

## 安装方法

1. 安装neovim最新版本

   sudo apt-add-repository ppa:neovim-ppa/unstable

   sudo apt-get update

   sudo apt-get install neovim

2. 拷贝本配置文件目录存为~/.config/nvim目录

3. 安装包管理软件Packer

   git clone --depth 1 https://github.com/wbthomason/packer.nvim\

   ~/.local/share/nvim/site/pack/packer/start/packer.nvim

4. 启动neovim后输入:PackerSync自动安装已配置的插件

5. 安装或更新node.js版本

  - 安装node.js
    sudo apt update

    curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash

    source ~/.bashrc

    nvm --version

    nvm ls

    nvm ls-remote

    nvm install [version.number]

  - 更新node.js版本，参考网址：https://phoenixnap.com/kb/update-node-js-version

6. 启动neovim输入:Copilot enable激活copilot(需要使用已经拥有copilot使用权的github账号进行认证)

7. 激活调试功能，为使用调试功能需要安装相关包：

   pip install debugpy

   pip install pyperclip
