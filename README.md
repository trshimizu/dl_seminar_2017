# dl_seminar_2017

#### セミナー資料
- 8/1 第１回 資料
   - https://1drv.ms/b/s!AguvnfZwI81sgphmCz0ETLudVmI9Ag?e=4QYLUj
- 8/15 第２回 資料
   - https://1drv.ms/b/s!AguvnfZwI81sgphkVecmNt-K0HWmAg?e=LhIQbl
- 8/29 第３回 資料
   - https://1drv.ms/b/s!AguvnfZwI81sgphoGezdEOPGzZSX-w?e=6o08v0
- 9/15 第４回 資料
   - https://1drv.ms/b/s!AguvnfZwI81sgphu-WUjz56h9xqAdw?e=ITc59Q
- 9/26 第５回 資料
   - https://1drv.ms/b/s!AguvnfZwI81sgphrx6RZOkeLA153JA?e=CZUJTc
- 10/10 第６回 資料
   - https://1drv.ms/b/s!AguvnfZwI81sgphw2kgEKcQeXDGiFg?e=YubGFh

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
