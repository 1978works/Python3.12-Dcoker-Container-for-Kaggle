# Python3.12-Dcoker-Container-for-Kaggle
Python3.12 Dcoker Container for Kaggle


## 使い方

### Docker Desktop起動
あらかじめDocker Desktopを起動させておく

### 必要なフォルダを作る
必ずVSCodeのために、.devcontainerというフォルダと、その上のフォルダ（この名前はテキトーで良い）を作っておく。
（構成例）

Python3.12_container  > .devcontainer

その.devcontainerフォルダの中に、以下のファイルを入れる
        * Dockerfile
        * devcontainer.json
        * requirements.txt

### VScodeでの作業
VSCodeで、上でつくったPython3.12_containerというフォルダを開く。
あとは自動的にVSCodeがうまいこと処理してくれる。
