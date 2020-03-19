# README
## フォルダごとの説明
### Jupyter_notebook/CaboCha.ipynb
- 動作環境
    - Jupyter_notebook
- インストール系の準備
    - CaboCha自体の準備
        - `brew install crf++`
        - `brew install cabocha`
    - CaboChaをjupyterで呼び出す準備
        - `git clone https://github.com/taku910/cabocha.git`
        - `pip install cabocha/python/`

### Jupyter_notebook/parse_ontrogy.ipynb
- 動作環境
    - Jupyter_notebook
- インストール系の準備
    - MeCab自体の準備
        - `brew install mecab`
        - `brew install mecab-ipadic`
    - MeCabをjupyterで呼び出す準備
        - `pip install mecab-python3`

### ontrogy_datas/ryudai-ontrogy.xmls
- ダウンロード
    - http://www.hozo.jp より法蔵をダウンロード
- 動作環境
    - Java(TM) SE Runtime Environment (build 1.8.0以降を推奨）
- 実行方法
    - `java -jar oe57run.jar`
