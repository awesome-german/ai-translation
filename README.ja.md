# ドイツ語のためのAI翻訳 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> ドイツ語処理のためのニューラル翻訳ツールと多言語コーパスアライメント技術の厳選リスト。

[科学的に効率的な現代学習のためのドイツ語-英語辞書アプリ](https://german-english-dictionary.devtheworld.jp/) をチェック 💡

*他の言語: [English](README.md) | [Deutsch](README.de.md)*

## 目次

- [ニューラル翻訳ツール](#ニューラル翻訳ツール)
  - [機械翻訳システム](#機械翻訳システム)
  - [翻訳API](#翻訳api)
  - [オープンソース翻訳モデル](#オープンソース翻訳モデル)
  - [翻訳品質評価](#翻訳品質評価)
- [多言語コーパスアライメント](#多言語コーパスアライメント)
  - [文アライメントツール](#文アライメントツール)
  - [単語アライメントツール](#単語アライメントツール)
  - [文書アライメント](#文書アライメント)
- [パラレルコーパス](#パラレルコーパス)
  - [ドイツ語-英語コーパス](#ドイツ語-英語コーパス)
  - [多言語コーパス](#多言語コーパス)
- [前処理ツール](#前処理ツール)
  - [トークン化](#トークン化)
  - [テキスト正規化](#テキスト正規化)
- [ドイツ語のための言語モデル](#ドイツ語のための言語モデル)
  - [Transformerモデル](#transformerモデル)
  - [事前学習済みモデル](#事前学習済みモデル)
- [データセット](#データセット)
  - [翻訳データセット](#翻訳データセット)
  - [評価ベンチマーク](#評価ベンチマーク)
- [研究論文](#研究論文)
- [学習リソース](#学習リソース)
  - [チュートリアル](#チュートリアル)
  - [コース](#コース)
  - [書籍](#書籍)
- [コミュニティ](#コミュニティ)

## ニューラル翻訳ツール

### 機械翻訳システム

- [DeepL](https://www.deepl.com/) - ドイツ語サポートに優れた高品質ニューラル機械翻訳サービス。
- [Google翻訳](https://translate.google.com/) - ドイツ語と100以上の言語をサポートする広く使用されている翻訳サービス。
- [Microsoft Translator](https://www.microsoft.com/translator/) - ドイツ語サポートを備えたクラウドベースの機械翻訳サービス。
- [SYSTRAN](https://www.systran.net/) - ニューラルMT機能を備えた専門的な翻訳ソフトウェア。
- [ModernMT](https://www.modernmt.com/) - ドメイン適応機能を備えたオープンソースのニューラル機械翻訳プラットフォーム。
- [Apertium](https://www.apertium.org/) - ドイツ語をサポートする無料/オープンソースのルールベース機械翻訳プラットフォーム。

### 翻訳API

- [DeepL API](https://www.deepl.com/pro-api) - DeepLのニューラル翻訳エンジン用REST API。
- [Google Cloud Translation API](https://cloud.google.com/translate) - AutoML機能を備えたスケーラブルな翻訳API。
- [Amazon Translate](https://aws.amazon.com/translate/) - AWSによるニューラル機械翻訳サービス。
- [Microsoft Translator Text API](https://azure.microsoft.com/en-us/services/cognitive-services/translator/) - カスタマイズオプションを備えたクラウド翻訳API。
- [LibreTranslate](https://libretranslate.com/) - 無料でオープンソースの機械翻訳API。

### オープンソース翻訳モデル

- [MarianMT](https://github.com/Helsinki-NLP/Opus-MT) - ヘルシンキ大学のニューラル機械翻訳モデル、ドイツ語ペアを含む。
- [OPUS-MT-train](https://github.com/Helsinki-NLP/OPUS-MT-train) - Marian NMTモデルのトレーニングパイプライン。
- [fairseq](https://github.com/facebookresearch/fairseq) - Facebookの翻訳モデル付きシーケンスモデリングツールキット。
- [OpenNMT](https://opennmt.net/) - オープンソースのニューラル機械翻訳フレームワーク。
- [Sockeye](https://github.com/awslabs/sockeye) - Apache MXNetベースのシーケンス間フレームワーク。
- [JoeyNMT](https://github.com/joeynmt/joeynmt) - ミニマリストなニューラル機械翻訳ツールキット。

### 翻訳品質評価

- [SacreBLEU](https://github.com/mjpost/sacrebleu) - MTシステムを比較するための標準BLEU実装。
- [COMET](https://github.com/Unbabel/COMET) - 多言語機械翻訳評価モデルをトレーニングするためのニューラルフレームワーク。
- [BERTScore](https://github.com/Tiiiger/bert_score) - BERT埋め込みを使用した自動評価メトリック。
- [BLEURT](https://github.com/google-research/bleurt) - 自然言語生成のための学習済み評価メトリック。
- [Prism](https://github.com/thompsonb/prism) - シーケンス間パラフレージングに基づく自動MTメトリック。

## 多言語コーパスアライメント

### 文アライメントツール

- [Bleualign](https://github.com/rsennrich/Bleualign) - MTとBLEUスコアを使用した文アライメント。
- [Hunalign](https://github.com/danielvarga/hunalign) - 自動辞書作成に基づく文レベルのアライメント。
- [vecalign](https://github.com/thompsonb/vecalign) - 多言語埋め込みを使用した正確な文アライメント。
- [Gargantua](https://github.com/cidles/gargantua) - パラレルテキストをアライメントするためのツール。
- [LF Aligner](https://sourceforge.net/projects/aligner/) - 文書および文のアライメントツール。

### 単語アライメントツール

- [fast_align](https://github.com/clab/fast_align) - 高速で教師なし単語アライメント実装。
- [eflomal](https://github.com/robertostling/eflomal) - 単語アライメントのための効率的な低メモリアライナー。
- [awesome-align](https://github.com/neulab/awesome-align) - 多言語BERTベースのニューラル単語アライメント。
- [SimAlign](https://github.com/cisnlp/simalign) - 静的および文脈化された埋め込みに基づく単語アライメント。

### 文書アライメント

- [bitextor](https://github.com/bitextor/bitextor) - ウェブからパラレル文書を収集するツール。
- [WMT Document Alignment](https://github.com/christianbuck/cld2) - ウェブクローリングにおける文書レベルのアライメントツール。

## パラレルコーパス

### ドイツ語-英語コーパス

- [OPUS](https://opus.nlpl.eu/) - ドイツ語-英語ペアを含む大規模なパラレルコーパスのコレクション。
- [Europarl](https://www.statmt.org/europarl/) - 欧州議会議事録から抽出されたパラレルコーパス。
- [News Commentary](https://opus.nlpl.eu/News-Commentary.php) - 政治経済コメンタリーコーパス。
- [Tatoeba](https://tatoeba.org/) - 多言語の文と翻訳のコレクション。
- [OpenSubtitles](https://www.opensubtitles.org/) - 映画字幕に基づく大規模パラレルコーパス。
- [WMT Datasets](https://www.statmt.org/wmt21/translation-task.html) - 機械翻訳の年次共有タスクデータセット。

### 多言語コーパス

- [OPUS-100](https://github.com/EdinburghNLP/opus-100-corpus) - 100言語をカバーする英語中心の多言語コーパス。
- [CCAligned](https://github.com/facebookresearch/LASER/tree/main/tasks/CCAligned) - Common Crawlからマイニングされた多言語パラレルコーパス。
- [WikiMatrix](https://github.com/facebookresearch/LASER/tree/main/tasks/WikiMatrix) - Wikipediaからマイニングされたパラレル文。
- [JW300](https://opus.nlpl.eu/JW300.php) - jw.orgからの300以上の言語のパラレルコーパス。
- [TED Talks](https://opus.nlpl.eu/TED2020.php) - TEDトーク文字起こしのパラレルコーパス。

## 前処理ツール

### トークン化

- [SentencePiece](https://github.com/google/sentencepiece) - 教師なしテキストトークナイザーとデトークナイザー。
- [subword-nmt](https://github.com/rsennrich/subword-nmt) - ニューラル機械翻訳のためのバイトペアエンコーディング。
- [SoMaJo](https://github.com/tsproisl/SoMaJo) - ドイツ語用のトークナイザーと文分割器。
- [spaCy](https://spacy.io/) - ドイツ語サポート付きの産業強度NLP。
- [NLTK](https://www.nltk.org/) - ドイツ語トークン化機能付き自然言語ツールキット。

### テキスト正規化

- [Moses](https://github.com/moses-smt/mosesdecoder) - 正規化スクリプト付き統計的機械翻訳ツールキット。
- [clean-text](https://github.com/jfilter/clean-text) - テキストクリーニングと正規化のためのPythonライブラリ。
- [ftfy](https://github.com/rspeer/python-ftfy) - テキストを修正 - エンコーディング問題と文字化けを処理。

## ドイツ語のための言語モデル

### Transformerモデル

- [BERT German](https://www.deepset.ai/german-bert) - deepsetによるドイツ語BERTモデル。
- [German GPT-2](https://huggingface.co/dbmdz/german-gpt2) - dbmdzによるGPT-2のドイツ語版。
- [GermanBERT](https://huggingface.co/bert-base-german-cased) - ドイツ語WikipediaでトレーニングされたBERTモデル。
- [GBERT](https://github.com/deepset-ai/FARM) - 下流タスク用のドイツ語BERTバリアント。
- [mBERT](https://github.com/google-research/bert/blob/master/multilingual.md) - ドイツ語をサポートする多言語BERT。
- [XLM-RoBERTa](https://huggingface.co/xlm-roberta-base) - 多言語RoBERTaモデル。

### 事前学習済みモデル

- [German ELMo](https://github.com/t-systems-on-site-services-gmbh/german-elmo-model) - ドイツ語ELMo埋め込み。
- [fastText German](https://fasttext.cc/docs/en/crawl-vectors.html) - ドイツ語用の事前学習済み単語ベクトル。
- [GloVe German](https://github.com/RUCAIBox/GermanGLOVE) - ドイツ語GloVe単語埋め込み。

## データセット

### 翻訳データセット

- [WMT Shared Tasks](https://www.statmt.org/wmt21/) - 年次機械翻訳コンペティションデータセット。
- [IWSLT](https://iwslt.org/) - 音声言語翻訳に関する国際会議データセット。
- [Multi30k](https://github.com/multi30k/dataset) - 多言語画像説明データセット（英語-ドイツ語-フランス語）。
- [Medical Translation](https://ufal.mff.cuni.cz/ufal_medical_corpus) - 医療ドメインパラレルコーパス。

### 評価ベンチマーク

- [WMT Test Sets](https://www.statmt.org/wmt21/translation-task.html) - 翻訳評価のための標準テストセット。
- [FLORES-101](https://github.com/facebookresearch/flores) - 多対多の多言語翻訳ベンチマーク。
- [TICO-19](https://tico-19.github.io/) - COVID-19データセットのための翻訳イニシアチブ。

## 研究論文

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Transformer アーキテクチャの基礎論文。
- [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473) - NMTのためのアテンションメカニズム。
- [Google's Neural Machine Translation System](https://arxiv.org/abs/1609.08144) - GNMTアーキテクチャ。
- [The Best of Both Worlds: Combining Recent Advances in Neural Machine Translation](https://arxiv.org/abs/1804.09849) - ハイブリッドNMTアプローチ。
- [Unsupervised Cross-lingual Representation Learning at Scale](https://arxiv.org/abs/1911.02116) - XLM-R論文。
- [Massively Multilingual Neural Machine Translation in the Wild](https://arxiv.org/abs/1907.05019) - 多言語NMTの知見。

## 学習リソース

### チュートリアル

- [Neural Machine Translation Tutorial](https://github.com/pytorch/tutorials/blob/master/beginner_source/torchtext_translation_tutorial.py) - PyTorch NMTチュートリアル。
- [OpenNMT Tutorial](https://opennmt.net/OpenNMT-py/quickstart.html) - OpenNMT入門。
- [Hugging Face Translation](https://huggingface.co/docs/transformers/tasks/translation) - transformersライブラリによる翻訳。
- [fairseq Tutorial](https://github.com/facebookresearch/fairseq/tree/main/examples/translation) - fairseqによる翻訳例。

### コース

- [Neural Machine Translation - Stanford CS224N](http://web.stanford.edu/class/cs224n/) - NMTを含むスタンフォードNLPコース。
- [Deep Learning for NLP](http://www.phontron.com/class/nn4nlp2021/) - カーネギーメロン大学のニューラルNLPコース。
- [Machine Translation - Edinburgh](https://www.inf.ed.ac.uk/teaching/courses/mt/) - エディンバラ大学のMTコース。

### 書籍

- [Neural Machine Translation](https://www.cambridge.org/core/books/neural-machine-translation/7AAA628F88ADD64124EA008C425C0197) - Philipp Koehnによる包括的な教科書。
- [Statistical Machine Translation](https://www.statmt.org/book/) - Philipp Koehnによる古典的なMT教科書。
- [Foundations of Statistical Natural Language Processing](https://nlp.stanford.edu/fsnlp/) - 必須のNLPリファレンス。

## コミュニティ

- [r/LanguageTechnology](https://www.reddit.com/r/LanguageTechnology/) - NLPとMTのためのRedditコミュニティ。
- [ACL Special Interest Group on Machine Translation](https://sigmt.org/) - MT研究のための専門組織。
- [WMT Mailing List](https://groups.google.com/g/wmt-tasks) - MT共有タスクのディスカッショングループ。
- [German NLP Community](https://german-nlp.github.io/) - ドイツ語処理のためのリソース。

## 貢献

貢献を歓迎します！まず[貢献ガイドライン](https://github.com/awesome-german/ai-translation/blob/main/CONTRIBUTING.md)をお読みください。

---

*awesome-germanコミュニティによってメンテナンスされています*