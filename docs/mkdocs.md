# mkdocs
```
# dnf info python
# dnf -y install pip

# alternatives --config python

3 プログラムがあり 'python' を提供します。

  選択       コマンド
-----------------------------------------------
*+ 1           /usr/libexec/no-python
   2           /usr/bin/python3
   3           /usr/bin/python3.11

Enter を押して現在の選択 [+] を保持するか、選択番号を入力します:3   

# python --version
Python 3.11.2

# update-alternatives --install /usr/bin/pip pip /usr/bin/pip-3.11 1
# pip --version
pip 22.3.1 from /usr/lib/python3.11/site-packages/pip (python 3.11)

# pip install mkdocs
# pip install mkdocs-material
# pip install mkdocs-material-extensions
# pip install pymdown-extensions

# mkdocs new mydoc
INFO    -  Creating project directory: mydoc
INFO    -  Writing config file: mydoc/mkdocs.yml
INFO    -  Writing initial docs: mydoc/docs/index.md

# mkdocs build
# mkdocs serve
```

## GitHubPageで公開する
https://squidfunk.github.io/mkdocs-material/publishing-your-site/