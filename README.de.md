# KI-Übersetzung für Deutsch [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Eine kuratierte Liste neuronaler Übersetzungstools und mehrsprachiger Korpus-Alignment-Techniken für die deutsche Sprachverarbeitung.

Schauen Sie sich die [Deutsch-Englisch-Wörterbuch-App für wissenschaftlich effizientes modernes Lernen](https://german-english-dictionary.devtheworld.jp/) an 💡

*In anderen Sprachen: [English](README.md) | [日本語](README.ja.md)*

## Inhaltsverzeichnis

- [Neuronale Übersetzungstools](#neuronale-übersetzungstools)
  - [Maschinelle Übersetzungssysteme](#maschinelle-übersetzungssysteme)
  - [Übersetzungs-APIs](#übersetzungs-apis)
  - [Open-Source-Übersetzungsmodelle](#open-source-übersetzungsmodelle)
  - [Bewertung der Übersetzungsqualität](#bewertung-der-übersetzungsqualität)
- [Mehrsprachiges Korpus-Alignment](#mehrsprachiges-korpus-alignment)
  - [Satz-Alignment-Tools](#satz-alignment-tools)
  - [Wort-Alignment-Tools](#wort-alignment-tools)
  - [Dokument-Alignment](#dokument-alignment)
- [Parallelkorpora](#parallelkorpora)
  - [Deutsch-Englisch-Korpora](#deutsch-englisch-korpora)
  - [Mehrsprachige Korpora](#mehrsprachige-korpora)
- [Vorverarbeitungstools](#vorverarbeitungstools)
  - [Tokenisierung](#tokenisierung)
  - [Textnormalisierung](#textnormalisierung)
- [Sprachmodelle für Deutsch](#sprachmodelle-für-deutsch)
  - [Transformer-Modelle](#transformer-modelle)
  - [Vortrainierte Modelle](#vortrainierte-modelle)
- [Datensätze](#datensätze)
  - [Übersetzungsdatensätze](#übersetzungsdatensätze)
  - [Bewertungs-Benchmarks](#bewertungs-benchmarks)
- [Forschungsarbeiten](#forschungsarbeiten)
- [Lernressourcen](#lernressourcen)
  - [Tutorials](#tutorials)
  - [Kurse](#kurse)
  - [Bücher](#bücher)
- [Community](#community)

## Neuronale Übersetzungstools

### Maschinelle Übersetzungssysteme

- [DeepL](https://www.deepl.com/) - Hochwertige neuronale maschinelle Übersetzung mit exzellenter Deutsch-Unterstützung.
- [Google Translate](https://translate.google.com/) - Weit verbreiteter Übersetzungsdienst mit Unterstützung für Deutsch und über 100 Sprachen.
- [Microsoft Translator](https://www.microsoft.com/translator/) - Cloud-basierter maschineller Übersetzungsdienst mit Deutsch-Unterstützung.
- [SYSTRAN](https://www.systran.net/) - Professionelle Übersetzungssoftware mit neuronalen MT-Funktionen.
- [ModernMT](https://www.modernmt.com/) - Open-Source-Plattform für neuronale maschinelle Übersetzung mit Domänenanpassung.
- [Apertium](https://www.apertium.org/) - Kostenlose/Open-Source-Plattform für regelbasierte maschinelle Übersetzung mit Deutsch-Unterstützung.

### Übersetzungs-APIs

- [DeepL API](https://www.deepl.com/pro-api) - REST-API für DeepLs neuronale Übersetzungs-Engine.
- [Google Cloud Translation API](https://cloud.google.com/translate) - Skalierbare Übersetzungs-API mit AutoML-Funktionen.
- [Amazon Translate](https://aws.amazon.com/translate/) - Neuronaler maschineller Übersetzungsdienst von AWS.
- [Microsoft Translator Text API](https://azure.microsoft.com/en-us/services/cognitive-services/translator/) - Cloud-Übersetzungs-API mit Anpassungsoptionen.
- [LibreTranslate](https://libretranslate.com/) - Kostenlose und Open-Source-API für maschinelle Übersetzung.

### Open-Source-Übersetzungsmodelle

- [MarianMT](https://github.com/Helsinki-NLP/Opus-MT) - Neuronale maschinelle Übersetzungsmodelle der Universität Helsinki, einschließlich deutscher Paare.
- [OPUS-MT-train](https://github.com/Helsinki-NLP/OPUS-MT-train) - Trainingspipeline für Marian-NMT-Modelle.
- [fairseq](https://github.com/facebookresearch/fairseq) - Facebooks Sequenzmodellierungs-Toolkit mit Übersetzungsmodellen.
- [OpenNMT](https://opennmt.net/) - Open-Source-Framework für neuronale maschinelle Übersetzung.
- [Sockeye](https://github.com/awslabs/sockeye) - Sequenz-zu-Sequenz-Framework auf Basis von Apache MXNet.
- [JoeyNMT](https://github.com/joeynmt/joeynmt) - Minimalistisches Toolkit für neuronale maschinelle Übersetzung.

### Bewertung der Übersetzungsqualität

- [SacreBLEU](https://github.com/mjpost/sacrebleu) - Standard-BLEU-Implementierung zum Vergleich von MT-Systemen.
- [COMET](https://github.com/Unbabel/COMET) - Neuronales Framework zum Training mehrsprachiger Bewertungsmodelle für maschinelle Übersetzung.
- [BERTScore](https://github.com/Tiiiger/bert_score) - Automatische Bewertungsmetrik mit BERT-Embeddings.
- [BLEURT](https://github.com/google-research/bleurt) - Gelernte Bewertungsmetrik für natürliche Sprachgenerierung.
- [Prism](https://github.com/thompsonb/prism) - Automatische MT-Metrik basierend auf Sequenz-zu-Sequenz-Paraphrasierung.

## Mehrsprachiges Korpus-Alignment

### Satz-Alignment-Tools

- [Bleualign](https://github.com/rsennrich/Bleualign) - Satz-Alignment unter Verwendung von MT und BLEU-Scores.
- [Hunalign](https://github.com/danielvarga/hunalign) - Satzebenen-Alignment basierend auf automatischer Wörterbucherstellung.
- [vecalign](https://github.com/thompsonb/vecalign) - Präzises Satz-Alignment mit mehrsprachigen Embeddings.
- [Gargantua](https://github.com/cidles/gargantua) - Werkzeug zum Ausrichten paralleler Texte.
- [LF Aligner](https://sourceforge.net/projects/aligner/) - Dokument- und Satz-Alignment-Tool.

### Wort-Alignment-Tools

- [fast_align](https://github.com/clab/fast_align) - Schnelle, unüberwachte Wort-Alignment-Implementierung.
- [eflomal](https://github.com/robertostling/eflomal) - Effizienter, speicherarmer Aligner für Wort-Alignment.
- [awesome-align](https://github.com/neulab/awesome-align) - Neuronales Wort-Alignment basierend auf mehrsprachigem BERT.
- [SimAlign](https://github.com/cisnlp/simalign) - Wort-Alignment basierend auf statischen und kontextualisierten Embeddings.

### Dokument-Alignment

- [bitextor](https://github.com/bitextor/bitextor) - Werkzeug zum Sammeln paralleler Dokumente aus dem Web.
- [WMT Document Alignment](https://github.com/christianbuck/cld2) - Tools für Dokument-Level-Alignment beim Web-Crawling.

## Parallelkorpora

### Deutsch-Englisch-Korpora

- [OPUS](https://opus.nlpl.eu/) - Große Sammlung von Parallelkorpora einschließlich Deutsch-Englisch-Paaren.
- [Europarl](https://www.statmt.org/europarl/) - Parallelkorpus extrahiert aus Protokollen des Europäischen Parlaments.
- [News Commentary](https://opus.nlpl.eu/News-Commentary.php) - Korpus politischer und wirtschaftlicher Kommentare.
- [Tatoeba](https://tatoeba.org/) - Sammlung von Sätzen und Übersetzungen in vielen Sprachen.
- [OpenSubtitles](https://www.opensubtitles.org/) - Großes Parallelkorpus basierend auf Filmuntertiteln.
- [WMT Datasets](https://www.statmt.org/wmt21/translation-task.html) - Jährliche Shared-Task-Datensätze für maschinelle Übersetzung.

### Mehrsprachige Korpora

- [OPUS-100](https://github.com/EdinburghNLP/opus-100-corpus) - Englisch-zentriertes mehrsprachiges Korpus mit 100 Sprachen.
- [CCAligned](https://github.com/facebookresearch/LASER/tree/main/tasks/CCAligned) - Mehrsprachiges Parallelkorpus aus Common Crawl.
- [WikiMatrix](https://github.com/facebookresearch/LASER/tree/main/tasks/WikiMatrix) - Parallele Sätze aus Wikipedia.
- [JW300](https://opus.nlpl.eu/JW300.php) - Parallelkorpus von jw.org in über 300 Sprachen.
- [TED Talks](https://opus.nlpl.eu/TED2020.php) - Parallelkorpus von TED-Talk-Transkripten.

## Vorverarbeitungstools

### Tokenisierung

- [SentencePiece](https://github.com/google/sentencepiece) - Unüberwachter Text-Tokenizer und Detokenizer.
- [subword-nmt](https://github.com/rsennrich/subword-nmt) - Byte-Pair-Encoding für neuronale maschinelle Übersetzung.
- [SoMaJo](https://github.com/tsproisl/SoMaJo) - Tokenizer und Satzsplitter für Deutsch.
- [spaCy](https://spacy.io/) - Industriestarkes NLP mit Deutsch-Unterstützung.
- [NLTK](https://www.nltk.org/) - Natural Language Toolkit mit deutscher Tokenisierung.

### Textnormalisierung

- [Moses](https://github.com/moses-smt/mosesdecoder) - Statistisches maschinelles Übersetzungs-Toolkit mit Normalisierungsskripten.
- [clean-text](https://github.com/jfilter/clean-text) - Python-Bibliothek für Textbereinigung und -normalisierung.
- [ftfy](https://github.com/rspeer/python-ftfy) - Behebt Text - behandelt Kodierungsprobleme und Mojibake.

## Sprachmodelle für Deutsch

### Transformer-Modelle

- [BERT German](https://www.deepset.ai/german-bert) - Deutsche BERT-Modelle von deepset.
- [German GPT-2](https://huggingface.co/dbmdz/german-gpt2) - Deutsche Version von GPT-2 von dbmdz.
- [GermanBERT](https://huggingface.co/bert-base-german-cased) - BERT-Modell trainiert auf deutscher Wikipedia.
- [GBERT](https://github.com/deepset-ai/FARM) - Deutsche BERT-Varianten für nachgelagerte Aufgaben.
- [mBERT](https://github.com/google-research/bert/blob/master/multilingual.md) - Mehrsprachiges BERT mit Deutsch-Unterstützung.
- [XLM-RoBERTa](https://huggingface.co/xlm-roberta-base) - Mehrsprachiges RoBERTa-Modell.

### Vortrainierte Modelle

- [German ELMo](https://github.com/t-systems-on-site-services-gmbh/german-elmo-model) - Deutsche ELMo-Embeddings.
- [fastText German](https://fasttext.cc/docs/en/crawl-vectors.html) - Vortrainierte Wortvektoren für Deutsch.
- [GloVe German](https://github.com/RUCAIBox/GermanGLOVE) - Deutsche GloVe-Wort-Embeddings.

## Datensätze

### Übersetzungsdatensätze

- [WMT Shared Tasks](https://www.statmt.org/wmt21/) - Jährliche Datensätze für maschinelle Übersetzungswettbewerbe.
- [IWSLT](https://iwslt.org/) - Datensätze der International Conference on Spoken Language Translation.
- [Multi30k](https://github.com/multi30k/dataset) - Mehrsprachiger Bildbeschreibungsdatensatz (Englisch-Deutsch-Französisch).
- [Medical Translation](https://ufal.mff.cuni.cz/ufal_medical_corpus) - Parallelkorpus im medizinischen Bereich.

### Bewertungs-Benchmarks

- [WMT Test Sets](https://www.statmt.org/wmt21/translation-task.html) - Standard-Testsets für die Übersetzungsbewertung.
- [FLORES-101](https://github.com/facebookresearch/flores) - Viele-zu-viele mehrsprachiger Übersetzungs-Benchmark.
- [TICO-19](https://tico-19.github.io/) - Übersetzungsinitiative für COVID-19-Datensatz.

## Forschungsarbeiten

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Grundlegendes Paper zur Transformer-Architektur.
- [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473) - Attention-Mechanismus für NMT.
- [Google's Neural Machine Translation System](https://arxiv.org/abs/1609.08144) - GNMT-Architektur.
- [The Best of Both Worlds: Combining Recent Advances in Neural Machine Translation](https://arxiv.org/abs/1804.09849) - Hybride NMT-Ansätze.
- [Unsupervised Cross-lingual Representation Learning at Scale](https://arxiv.org/abs/1911.02116) - XLM-R-Paper.
- [Massively Multilingual Neural Machine Translation in the Wild](https://arxiv.org/abs/1907.05019) - Erkenntnisse zu mehrsprachigem NMT.

## Lernressourcen

### Tutorials

- [Neural Machine Translation Tutorial](https://github.com/pytorch/tutorials/blob/master/beginner_source/torchtext_translation_tutorial.py) - PyTorch-NMT-Tutorial.
- [OpenNMT Tutorial](https://opennmt.net/OpenNMT-py/quickstart.html) - Einstieg in OpenNMT.
- [Hugging Face Translation](https://huggingface.co/docs/transformers/tasks/translation) - Übersetzung mit der transformers-Bibliothek.
- [fairseq Tutorial](https://github.com/facebookresearch/fairseq/tree/main/examples/translation) - Übersetzungsbeispiele mit fairseq.

### Kurse

- [Neural Machine Translation - Stanford CS224N](http://web.stanford.edu/class/cs224n/) - Stanford-NLP-Kurs einschließlich NMT.
- [Deep Learning for NLP](http://www.phontron.com/class/nn4nlp2021/) - Carnegie-Mellon-Kurs zu neuronalem NLP.
- [Machine Translation - Edinburgh](https://www.inf.ed.ac.uk/teaching/courses/mt/) - MT-Kurs der Universität Edinburgh.

### Bücher

- [Neural Machine Translation](https://www.cambridge.org/core/books/neural-machine-translation/7AAA628F88ADD64124EA008C425C0197) - Umfassendes Lehrbuch von Philipp Koehn.
- [Statistical Machine Translation](https://www.statmt.org/book/) - Klassisches MT-Lehrbuch von Philipp Koehn.
- [Foundations of Statistical Natural Language Processing](https://nlp.stanford.edu/fsnlp/) - Wesentliche NLP-Referenz.

## Community

- [r/LanguageTechnology](https://www.reddit.com/r/LanguageTechnology/) - Reddit-Community für NLP und MT.
- [ACL Special Interest Group on Machine Translation](https://sigmt.org/) - Fachorganisation für MT-Forschung.
- [WMT Mailing List](https://groups.google.com/g/wmt-tasks) - Diskussionsgruppe für MT-Shared-Tasks.
- [German NLP Community](https://german-nlp.github.io/) - Ressourcen für deutsche Sprachverarbeitung.

## Beitragen

Beiträge sind willkommen! Bitte lesen Sie zuerst die [Beitragsrichtlinien](https://github.com/awesome-german/ai-translation/blob/main/CONTRIBUTING.md).

---

*Gepflegt von der awesome-german-Community*