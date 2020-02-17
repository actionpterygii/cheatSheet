# python

## pyenv

### pyenvアップデート
`pyenv update`

### インストール可能なpythonバージョン確認
`pyenv install -list`

### pythonインストール
`pyenv install {{ PYTHON_VERSION }}`

### インストールされているpythonバージョン確認
`pyenv versions`

### 全体で使われるpythonバージョン確認
`pyenv global`

### 全体で使われるpythonバージョン指定
`pyenv global {{ PYTHON_VERSION }}`

### いるディレクトリ以下で使われるpythonバージョン確認
`pyenv local`

### いるディレクトリ以下で使われるpythonバージョン指定
`pyenv local {{ PYTHON_VERSION }}`

### いるディレクトリ以下で使われるpythonバージョン指定削除
`pyenv local --unset`

### バージョンに別名を付ける(それは独立した別の環境になる)(PYTHON_VERSIONの代わりに使える)
`pyenv virtualenv {{ PYTHON_VERSION }} {{ NAMAE }}`

### pythonアンインストール
`pyenv uninstall {{ PYTHON_VERSION }}`