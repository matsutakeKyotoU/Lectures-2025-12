# Lectures-2025-12 Sample Programs

授業中のデモはリアルタイムでプログラムを生成して実行しましたが、同様のシナリオで予め用意したJupyter Notebookのサンプルプログラムを配置しておきます。同じプロンプトでもChatGPTの出力はその時々で異なるため、デモ時のプログラムとは異なっています。


- JGBYieldCurvePCA.ipynb
  - 財務省の国債金利情報から国債利回りの履歴を取得、イールドカーブのグラフ化、さらにPCA分析を行い、カーブの動きを主成分3つで表現しグラフ化

- StockChart.ipynb
  - yfinanceからデータを取得、チャートで表示

- EfficientFrontier.ipynb 
  - 日経225から時価総額の上位20銘柄を選び、yfinanceから株価を取得、効率的フロンティアをグラフ化、また最小分散ポートフォリオ、並びにシャープ・レシオ最大（接点）ポートフォリオを求め、投資ウェイトをグラフ表示

---

# Pythonについて
Pythonはデータ分析、AIを含め幅広い分野で使われているプログラミング言語です。書いたプログラムをその場ですぐに実行できる「スクリプト言語」の一種で、いろいろな機能を持つ別モジュール（ライブラリ）が豊富に存在し、それらを組み合わせて使うことで、いろいろなタスクを柔軟にこなすことができます。ライブラリとしては次が代表的なものです。
- データ分析：pandas, numpy, scipy
- AI：TensorFlow, PyTorch, SciKitLearn
- グラフ表示：matplotlib, plotly
- Web作成：Django, Flask

---

# Jupyter Notebookの実行環境について
自分のコンピュータにPython がインストールされていることが前提です。
- Pythonが環境に入っていなければインストール: https://www.python.org
	- バージョンは現在3.xx.xx (Stable Releaseで最もバンジョンの高いものを選べば良い）
	- データサイエンスのパッケージ Anaconda https://www.anaconda.com でもインストール可
	- インストール後、コマンドプロンプト/ターミナルを立ち上げ、`python`(または`python3`)と入力してpythonが起動すればOK
- Pythonと組み合わせて使うモジュール（ライブラリ）パッケージをインストール
	- Pythonをインストールすると、パッケージのインストーラ`pip`が付属している
	- コマンドプロンプト/ターミナルから`pip install パッケージ名`と入力
		- デモで使用したJupyter Notebookは`pip install notebook`でインストールできる
- Jupyter Notebookの実行
	- コマンドプロンプト/ターミナルから`jupyter notebook`または`python -m notebook`と入力
		- ブラウザ内でJupyter Notebookの画面が開く
