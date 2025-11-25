# Lectures-2025-12 Sample Programs

授業中のデモはリアルタイムでプログラムを生成して実行しましたが、同様のシナリオで予め用意したJupyter Notebookのサンプルプログラムを配置しておきます。同じプロンプトでもChatGPTの出力はその時々で異なるため、デモ時のプログラムとは異なっています。

- StockChart.ipynb
  - yfinanceからデータを取得、チャートで表示

- JGBYieldCurvePCA.ipynb
  - 財務省の国債金利情報から国債利回りの履歴を取得、イールドカーブのグラフ化、さらにPCA分析を行い、カーブの動きを主成分3つで表現しグラフ化

- EfficientFrontier.ipynb 
  - yfinanceから株価を複数銘柄取得、最適投資ポートフォリオの効率的フロンティアをグラフ化、またリスク最小、並びにシャープ・レシオ最大の投資配分をグラフ化

# Pythonについて
Pythonはデータ分析、AIなどを含めた幅広い分野で使われているプログラミング言語です。書いたプログラムをその場ですぐに実行できる「スクリプト言語」の一種で、いろいろな機能を持つ別モジュール（ライブラリ）が豊富に存在し、それらを組み合わせて使うことで、いろいろなタスクを柔軟にこなすことができます。ライブラリとしては次が代表的なものです。
- データ分析：pandas, numpy, scipy
- AI：TensorFlow, PyTorch, SciKitLearn
- グラフ表示：matplotlib, plotly
- Web作成：Django, Flask

# Jupyter Notebookの実行環境について
自分のコンピュータにPython がインストールされていることが前提です。
