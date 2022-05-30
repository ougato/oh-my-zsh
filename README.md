# 安装流程

```shell
yum install -y git zsh
git clone --depth 1 http://gitlab.ougato.com:8880/ougato/oh-my-zsh.git ~/.oh-my-zsh
cp ~/.oh-my-zsh/templates/zshrc.zsh-template ~/.zshrc
zsh
chsh -s $(which zsh)
```