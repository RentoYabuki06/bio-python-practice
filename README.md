# 🧬 Bio-Python Practice

バイオインフォマティクスの基本的なDNA解析をPythonで実践するリポジトリです。BiopythonライブラリとJupyter Notebookを使って、配列解析の基本を学ぶことができます。

## 📚 内容

### 🧪 dna_translate.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RentoYabuki06/bio-python-practice/blob/main/dna_translate.ipynb)

DNA配列の解析と翻訳に関する基本操作を学べるノートブックです：

- **DNA→タンパク質翻訳**: 開始コドン・終止コドンを考慮した翻訳
- **配列解析**: 塩基頻度カウント、GC含量計算
- **FASTA形式ファイル操作**: 実際の遺伝子配列の読み込みと処理
- **カスタム翻訳テーブル**: 独自のコドン翻訳辞書の作成
- **データ可視化**: Matplotlibを用いた塩基頻度グラフ作成

高度な解析機能：
- **ORF検出**: オープンリーディングフレームの検索アルゴリズム
- **コドン使用頻度分析**: 生物種特有のコドンバイアスの可視化
- **GCスキュー解析**: 複製起点予測に役立つGC塩基の偏りを調査

### 🧬 codon_table.ipynb
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/RentoYabuki06/bio-python-practice/blob/main/codon_table.ipynb)

標準およびカスタムコドン表の操作と利用方法を学ぶノートブック（開発中）。

## 📁 データファイル

### sequence.fasta
ヒトの[BRCA1遺伝子](https://www.ncbi.nlm.nih.gov/gene/672)（乳がん1型感受性タンパク質）のDNA配列を含むFASTAファイル。
- NCBI RefSeqID: NG_005905.2
- 配列長: 約193kb
- このファイルは実践的なDNA配列解析の演習用データとして使用

## 🛠️ 使用方法

1. Google Colabで各ノートブックを開く（上記のボタンをクリック）
2. または、ローカル環境で実行する場合:
   ```
   git clone https://github.com/RentoYabuki06/bio-python-practice.git
   cd bio-python-practice
   pip install biopython matplotlib numpy
   jupyter notebook
   ```

## 📌 必要ライブラリ

- [Biopython](https://biopython.org/): 配列解析、FASTA操作
- [Matplotlib](https://matplotlib.org/): データ可視化
- [NumPy](https://numpy.org/): 数値計算

## 🔍 学習のポイント

このリポジトリでは以下のバイオインフォマティクスの基本概念について学ぶことができます：

- DNAとタンパク質の関係性
- コドン表とタンパク質翻訳の仕組み
- FASTA形式のデータ構造と操作方法
- GC含量やコドン使用頻度などの配列特性の解析
- 遺伝子予測に関する基本アルゴリズム（ORF検出など）

## ✉️ 連絡先

質問やフィードバックがあればIssueを作成してください。
