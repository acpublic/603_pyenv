# インストール
## https://blog.mori-soft.com/entry/2023/06/09/224950
### Github から clone します。
$ git clone https://github.com/pyenv/pyenv.git ~/.pyenv

### .bashrc を設定します。

$ echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc

$ echo 'command -v pyenv > /dev/null || export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc

$ echo 'eval "$(pyenv init -)"' >> ~/.bashrc
