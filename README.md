# dl_seminar_2017

#### お知らせ
- 第６回資料を更新しています
   - RNNの学習まわりの記述をブラッシュアップ (10/9、21:20)
   - 研究動向のスライドを追加 (10/9、21:20)
   - さらに Appendix、前回のご質問についての回答などを追加（10/10、00:00）

#### セミナー資料
- 10/10 第６回 資料
   - https://www.dropbox.com/s/xvbkgoc967n2dje/deep_learning_6.pdf?dl=0
- 9/26 第５回 資料
   - https://www.dropbox.com/s/pkxkd8wjkc589rk/deep_learning_5.pdf?dl=0
   - mnist data: https://www.dropbox.com/s/iruiklt5ted91sc/mnist_comp.npz?dl=1
- 9/15 第４回 資料
   - https://www.dropbox.com/s/aso3tu0illfghun/deep_learning_4.pdf?dl=0
- 8/29 第３回 資料
   - https://www.dropbox.com/s/0no8zlw07vjm7dd/deep_learning_3.pdf?dl=0
- 8/15 第２回 資料
   - https://www.dropbox.com/s/2aiow0undfx2z3t/deep_learning_2.pdf?dl=0
- 8/1 第１回 資料
   - https://www.dropbox.com/s/2lmwx3ww3kv9491/deep_learning_1.pdf?dl=0

#### memo
- TensorFlow インストールについて
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
- jupyter notebookをダウンロードする際、github.com上で表示されているファイルのリンクを辿る形だと、htmlとしてダウンロードされてしまう等 上手く取得できないことが予想されます。この画面右上の緑色の「Clone or download」ボタンを押して、「Download ZIP」を選ぶことで必要なファイルをまるごと確実に取得できます。 
   - あるいは（githubに慣れてる方でしたら）clone機能を使って取得していただく選択肢もあります。
   
#### license
- 資料については CC-BY-4.0、演習用コードについては public domainとします。

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
