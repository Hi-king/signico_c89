# signico_c89



ビルド
-------------

#### 依存インストール

```
pip install sphinx
```

#### pdf

```
# latex関係のコマンドが入ってる環境で
make latexpdf
open build/latex/signico_c89.pdf
```

#### html

```
make html
python -m SimpleHTTPServer
open http://localhost:8000/build/html/
```

