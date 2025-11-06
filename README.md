# AI Translation for German [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of neural translation tools and multilingual corpus alignment techniques for German language processing.

Check out the [German-English Dictionary App for Scientifically-Efficient Modern Learning](https://german-english-dictionary.devtheworld.jp/) 💡

*Read this in [Deutsch](README.de.md) | [日本語](README.ja.md)*

## Contents

- [Neural Translation Tools](#neural-translation-tools)
  - [Machine Translation Systems](#machine-translation-systems)
  - [Translation APIs](#translation-apis)
  - [Open Source Translation Models](#open-source-translation-models)
  - [Translation Quality Evaluation](#translation-quality-evaluation)
- [Multilingual Corpus Alignment](#multilingual-corpus-alignment)
  - [Sentence Alignment Tools](#sentence-alignment-tools)
  - [Word Alignment Tools](#word-alignment-tools)
  - [Document Alignment](#document-alignment)
- [Parallel Corpora](#parallel-corpora)
  - [German-English Corpora](#german-english-corpora)
  - [Multilingual Corpora](#multilingual-corpora)
- [Preprocessing Tools](#preprocessing-tools)
  - [Tokenization](#tokenization)
  - [Text Normalization](#text-normalization)
- [Language Models for German](#language-models-for-german)
  - [Transformer Models](#transformer-models)
  - [Pre-trained Models](#pre-trained-models)
- [Datasets](#datasets)
  - [Translation Datasets](#translation-datasets)
  - [Evaluation Benchmarks](#evaluation-benchmarks)
- [Research Papers](#research-papers)
- [Learning Resources](#learning-resources)
  - [Tutorials](#tutorials)
  - [Courses](#courses)
  - [Books](#books)
- [Community](#community)

## Neural Translation Tools

### Machine Translation Systems

- [DeepL](https://www.deepl.com/) - High-quality neural machine translation service with excellent German support.
- [Google Translate](https://translate.google.com/) - Widely-used translation service supporting German and 100+ languages.
- [Microsoft Translator](https://www.microsoft.com/translator/) - Cloud-based machine translation service with German language support.
- [SYSTRAN](https://www.systran.net/) - Professional translation software with neural MT capabilities.
- [ModernMT](https://www.modernmt.com/) - Open-source neural machine translation platform with domain adaptation.
- [Apertium](https://www.apertium.org/) - Free/open-source rule-based machine translation platform supporting German.

### Translation APIs

- [DeepL API](https://www.deepl.com/pro-api) - REST API for DeepL's neural translation engine.
- [Google Cloud Translation API](https://cloud.google.com/translate) - Scalable translation API with AutoML capabilities.
- [Amazon Translate](https://aws.amazon.com/translate/) - Neural machine translation service by AWS.
- [Microsoft Translator Text API](https://azure.microsoft.com/en-us/services/cognitive-services/translator/) - Cloud translation API with customization options.
- [LibreTranslate](https://libretranslate.com/) - Free and open-source machine translation API.

### Open Source Translation Models

- [MarianMT](https://github.com/Helsinki-NLP/Opus-MT) - Neural machine translation models from the University of Helsinki, includes German pairs.
- [OPUS-MT-train](https://github.com/Helsinki-NLP/OPUS-MT-train) - Training pipeline for Marian NMT models.
- [fairseq](https://github.com/facebookresearch/fairseq) - Facebook's sequence modeling toolkit with translation models.
- [OpenNMT](https://opennmt.net/) - Open-source neural machine translation framework.
- [Sockeye](https://github.com/awslabs/sockeye) - Sequence-to-sequence framework built on Apache MXNet.
- [JoeyNMT](https://github.com/joeynmt/joeynmt) - Minimalist neural machine translation toolkit.

### Translation Quality Evaluation

- [SacreBLEU](https://github.com/mjpost/sacrebleu) - Standard BLEU implementation for comparing MT systems.
- [COMET](https://github.com/Unbabel/COMET) - Neural framework for training multilingual machine translation evaluation models.
- [BERTScore](https://github.com/Tiiiger/bert_score) - Automatic evaluation metric using BERT embeddings.
- [BLEURT](https://github.com/google-research/bleurt) - Learned evaluation metric for natural language generation.
- [Prism](https://github.com/thompsonb/prism) - Automatic MT metric based on sequence-to-sequence paraphrasing.

## Multilingual Corpus Alignment

### Sentence Alignment Tools

- [Bleualign](https://github.com/rsennrich/Bleualign) - Sentence alignment using MT and BLEU scores.
- [Hunalign](https://github.com/danielvarga/hunalign) - Sentence-level alignment based on automatic dictionary creation.
- [vecalign](https://github.com/thompsonb/vecalign) - Accurate sentence alignment using multilingual embeddings.
- [Gargantua](https://github.com/cidles/gargantua) - Tool for aligning parallel texts.
- [LF Aligner](https://sourceforge.net/projects/aligner/) - Document and sentence alignment tool.

### Word Alignment Tools

- [fast_align](https://github.com/clab/fast_align) - Fast, unsupervised word alignment implementation.
- [eflomal](https://github.com/robertostling/eflomal) - Efficient low-memory aligner for word alignment.
- [awesome-align](https://github.com/neulab/awesome-align) - Neural word alignment based on multilingual BERT.
- [SimAlign](https://github.com/cisnlp/simalign) - Word alignment based on static and contextualized embeddings.

### Document Alignment

- [bitextor](https://github.com/bitextor/bitextor) - Tool for harvesting parallel documents from the web.
- [WMT Document Alignment](https://github.com/christianbuck/cld2) - Tools for document-level alignment in web crawling.

## Parallel Corpora

### German-English Corpora

- [OPUS](https://opus.nlpl.eu/) - Large collection of parallel corpora including German-English pairs.
- [Europarl](https://www.statmt.org/europarl/) - Parallel corpus extracted from European Parliament proceedings.
- [News Commentary](https://opus.nlpl.eu/News-Commentary.php) - Political and economic commentary corpus.
- [Tatoeba](https://tatoeba.org/) - Collection of sentences and translations in many languages.
- [OpenSubtitles](https://www.opensubtitles.org/) - Large parallel corpus based on movie subtitles.
- [WMT Datasets](https://www.statmt.org/wmt21/translation-task.html) - Annual shared task datasets for machine translation.

### Multilingual Corpora

- [OPUS-100](https://github.com/EdinburghNLP/opus-100-corpus) - English-centric multilingual corpus covering 100 languages.
- [CCAligned](https://github.com/facebookresearch/LASER/tree/main/tasks/CCAligned) - Multilingual parallel corpus mined from Common Crawl.
- [WikiMatrix](https://github.com/facebookresearch/LASER/tree/main/tasks/WikiMatrix) - Parallel sentences mined from Wikipedia.
- [JW300](https://opus.nlpl.eu/JW300.php) - Parallel corpus from jw.org in 300+ languages.
- [TED Talks](https://opus.nlpl.eu/TED2020.php) - Parallel corpus of TED talk transcripts.

## Preprocessing Tools

### Tokenization

- [SentencePiece](https://github.com/google/sentencepiece) - Unsupervised text tokenizer and detokenizer.
- [subword-nmt](https://github.com/rsennrich/subword-nmt) - Byte Pair Encoding for neural machine translation.
- [SoMaJo](https://github.com/tsproisl/SoMaJo) - Tokenizer and sentence splitter for German.
- [spaCy](https://spacy.io/) - Industrial-strength NLP with German language support.
- [NLTK](https://www.nltk.org/) - Natural language toolkit with German tokenization.

### Text Normalization

- [Moses](https://github.com/moses-smt/mosesdecoder) - Statistical machine translation toolkit with normalization scripts.
- [clean-text](https://github.com/jfilter/clean-text) - Python library for text cleaning and normalization.
- [ftfy](https://github.com/rspeer/python-ftfy) - Fixes text for you - handles encoding issues and mojibake.

## Language Models for German

### Transformer Models

- [BERT German](https://www.deepset.ai/german-bert) - German BERT models by deepset.
- [German GPT-2](https://huggingface.co/dbmdz/german-gpt2) - German version of GPT-2 by dbmdz.
- [GermanBERT](https://huggingface.co/bert-base-german-cased) - BERT model trained on German Wikipedia.
- [GBERT](https://github.com/deepset-ai/FARM) - German BERT variants for downstream tasks.
- [mBERT](https://github.com/google-research/bert/blob/master/multilingual.md) - Multilingual BERT supporting German.
- [XLM-RoBERTa](https://huggingface.co/xlm-roberta-base) - Multilingual RoBERTa model.

### Pre-trained Models

- [German ELMo](https://github.com/t-systems-on-site-services-gmbh/german-elmo-model) - German language ELMo embeddings.
- [fastText German](https://fasttext.cc/docs/en/crawl-vectors.html) - Pre-trained word vectors for German.
- [GloVe German](https://github.com/RUCAIBox/GermanGLOVE) - German GloVe word embeddings.

## Datasets

### Translation Datasets

- [WMT Shared Tasks](https://www.statmt.org/wmt21/) - Annual machine translation competition datasets.
- [IWSLT](https://iwslt.org/) - International Conference on Spoken Language Translation datasets.
- [Multi30k](https://github.com/multi30k/dataset) - Multilingual image description dataset (English-German-French).
- [Medical Translation](https://ufal.mff.cuni.cz/ufal_medical_corpus) - Medical domain parallel corpus.

### Evaluation Benchmarks

- [WMT Test Sets](https://www.statmt.org/wmt21/translation-task.html) - Standard test sets for translation evaluation.
- [FLORES-101](https://github.com/facebookresearch/flores) - Many-to-many multilingual translation benchmark.
- [TICO-19](https://tico-19.github.io/) - Translation initiative for COVID-19 dataset.

## Research Papers

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Foundational transformer architecture paper.
- [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473) - Attention mechanism for NMT.
- [Google's Neural Machine Translation System](https://arxiv.org/abs/1609.08144) - GNMT architecture.
- [The Best of Both Worlds: Combining Recent Advances in Neural Machine Translation](https://arxiv.org/abs/1804.09849) - Hybrid NMT approaches.
- [Unsupervised Cross-lingual Representation Learning at Scale](https://arxiv.org/abs/1911.02116) - XLM-R paper.
- [Massively Multilingual Neural Machine Translation in the Wild](https://arxiv.org/abs/1907.05019) - Multilingual NMT findings.

## Learning Resources

### Tutorials

- [Neural Machine Translation Tutorial](https://github.com/pytorch/tutorials/blob/master/beginner_source/torchtext_translation_tutorial.py) - PyTorch NMT tutorial.
- [OpenNMT Tutorial](https://opennmt.net/OpenNMT-py/quickstart.html) - Getting started with OpenNMT.
- [Hugging Face Translation](https://huggingface.co/docs/transformers/tasks/translation) - Translation with transformers library.
- [fairseq Tutorial](https://github.com/facebookresearch/fairseq/tree/main/examples/translation) - Translation examples with fairseq.

### Courses

- [Neural Machine Translation - Stanford CS224N](http://web.stanford.edu/class/cs224n/) - Stanford NLP course including NMT.
- [Deep Learning for NLP](http://www.phontron.com/class/nn4nlp2021/) - Carnegie Mellon course on neural NLP.
- [Machine Translation - Edinburgh](https://www.inf.ed.ac.uk/teaching/courses/mt/) - University of Edinburgh MT course.

### Books

- [Neural Machine Translation](https://www.cambridge.org/core/books/neural-machine-translation/7AAA628F88ADD64124EA008C425C0197) - Comprehensive textbook by Philipp Koehn.
- [Statistical Machine Translation](https://www.statmt.org/book/) - Classical MT textbook by Philipp Koehn.
- [Foundations of Statistical Natural Language Processing](https://nlp.stanford.edu/fsnlp/) - Essential NLP reference.

## Community

- [r/LanguageTechnology](https://www.reddit.com/r/LanguageTechnology/) - Reddit community for NLP and MT.
- [ACL Special Interest Group on Machine Translation](https://sigmt.org/) - Professional organization for MT research.
- [WMT Mailing List](https://groups.google.com/g/wmt-tasks) - Discussion group for MT shared tasks.
- [German NLP Community](https://german-nlp.github.io/) - Resources for German language processing.

## Contributing

Contributions are welcome! Please read the [contribution guidelines](https://github.com/awesome-german/ai-translation/blob/main/CONTRIBUTING.md) first.

---

*Maintained by the awesome-german community*
