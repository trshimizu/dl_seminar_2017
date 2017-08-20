# dl_seminar_2017

#### TensorFlow インストールについて
- macOS
   - Launchpad -> その他 から ターミナルを起動
   - その中でコマンド実行：
      - ```conda install -c conda-forge tensorflow```
   - ※ もし command not found などと出てきてしまう場合は、以下のようにディレクトリを移動し、そこで再度 インストールコマンド実行
      - ```cd （Anacondaをインストールしたディレクトリ）/anaconda/bin```
      - ```./conda install -c conda-forge tensorflow```
- Windows
   - スタートメニューから Anaconda Promptを起動
   - その中でコマンド実行：
      - ```conda install -c conda-forge tensorflow```
- 確認方法（macOS、Windows共通）
   - jupyter notebookを立ち上げ、以下を実行して '1.2.1' など、1.0以上のバージョンが表示されればOK
      - ```import tensorflow as tf```
      - ```tf.__version__```    
- その他
   - ※ pipでパッケージを管理されている場合は、```pip install tensorflow``` でも大丈夫です

#### セミナー資料
- 8/29 第３回 資料（ドラフト版）
   - https://www.dropbox.com/s/0no8zlw07vjm7dd/deep_learning_3.pdf?dl=0
      - 8/20： 予習用 ドラフト版です。この後もスライドを追加する予定ですが、「用語整理」「ニューラルネットワークの微分計算、backpropagation」のセクションは概ね完成。
- 8/15 第２回 資料
   - https://www.dropbox.com/s/2aiow0undfx2z3t/deep_learning_2.pdf?dl=0
      - 8/19： 全体の構成を分かりやすくするため、セクションタイトル的なページを追加。
- 8/1 第１回 資料
   - https://www.dropbox.com/s/2lmwx3ww3kv9491/deep_learning_1.pdf?dl=0
      - 8/9： p.84 のWは実際は転置記号付きであり、そのように修正。
      - 8/14： p. 73 の図を微調整。

#### memo
- jupyter notebookをダウンロードする際、github.com上で表示されているファイルのリンクを辿る形だと、htmlとしてダウンロードされてしまう等 上手く取得できないことが予想されます。この画面右上の緑色の「Clone or download」ボタンを押して、「Download ZIP」を選ぶことで必要なファイルをまるごと確実に取得できます。 
   - あるいは（githubに慣れてる方でしたら）clone機能を使って取得していただく選択肢もあります。
