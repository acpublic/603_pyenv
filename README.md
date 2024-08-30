# インストール
## https://blog.mori-soft.com/entry/2023/06/09/224950
## https://zenn.dev/tigrebiz/articles/2822fb4de256d8#ubuntu%E3%82%92%E5%8B%95%E3%81%8B%E3%81%99
### Github から clone します。
$ git clone https://github.com/pyenv/pyenv.git ~/.pyenv

### シェルの設定

$ echo 'export PYENV_ROOT="$HOME/.pyenv"' >> ~/.bashrc

$ echo 'command -v pyenv > /dev/null || export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bashrc

$ echo 'eval "$(pyenv init -)"' >> ~/.bashrc

$ pyenv -v

pyenv 2.3.18-9-ge0084304

### Pythonビルドの依存関係をインストール
$ sudo apt update
$ sudo apt install -y build-essential libssl-dev zlib1g-dev libbz2-dev libreadline-dev libsqlite3-dev curl libncursesw5-dev xz-utils tk-dev libxml2-dev libxmlsec1-dev libffi-dev liblzma-dev

### python インストール
$ pyenv install 3.**.*
