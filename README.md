# Awesome Machine Translation [![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
A list of awesome Machine Translation frameworks, libraries, software and papers. Inspired by [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning).

If you want to contribute to this list (please do), send me a pull request or contact me [@anilozbek](https://twitter.com/anilozbek). Also, a listed repository should be deprecated if:

- Repository's owner explicitly say that "this library is not maintained".
- Not committed for long time (2~3 years).

You can also find an updated list of machine translation frameworks, libraries, software and papers at [machinetranslate.org](http://machinetranslate.org).

## Contents
- [Aligners 🌌](#aligners-)
- [Applications 💻](#applications-)
- [Books 📚](#books-)
- [Companies and Paid Services 💰](#companies-and-paid-services-)
- [Frameworks 🖼](#frameworks-)
- [Hardware 🎧](#hardware-)
- [Online MT Services 🌐](#online-mt-services-)
- [Organizations and Events 🎉](#organizations-and-events-)
- [Other MT Lists 📝](#other-mt-lists-)
- [Papers 📄](#papers-)
- [Parallel Texts ⏸️](#parallel-texts-️)
- [Tools 🛠](#tools-)
- [Tutorials and Blogs 🎒](#tutorials-)

## Aligners 🌌
- [Bleualign](https://github.com/rsennrich/Bleualign) - A machine translation based sentence alignment tool for parallel text.
- [Bleualign-cpp](https://github.com/bitextor/bleualign-cpp) - A C++ sentence alignment tool based on Bleualign. Bleualign-cpp is expected to be used together with document-aligner.
- [hunalign](http://mokk.bme.hu/resources/hunalign/) - A tool that aligns bilingual text on the sentence level. 
- [Getting started with Sentence Alignment](https://textprocessing.org/getting-started-with-sentence-alignment) - A list of sentence alignment tools.
- [LF Aligner](https://sourceforge.net/projects/aligner/) - A tool to create translation memories from texts and their translations. It relies on Hunalign for automatic sentence pairing.
- [Vecalign](https://github.com/thompsonb/vecalign) - An accurate sentence alignment algorithm that works in about 100 languages, without the need for a machine translation system or lexicon.
- [Web Align Toolkit](http://phraseotext.univ-grenoble-alpes.fr/webAlignToolkit/) - Online parallel texts aligner and format converter.
- [yalign](https://github.com/machinalis/yalign) - A sentence aligner for comparable corpora.
- [yasa](http://rali.iro.umontreal.ca/rali/?q=en/yasa) - Yet Another Sentence Aligner.

## Applications 💻
- [Argos Translate](https://github.com/argosopentech/argos-translate) - An open-source offline translation library written in Python. Uses OpenNMT for translations, SentencePiece for tokenization, Stanza for sentence boundary detection, and PyQt for GUI.
- [Canopy Speak](https://www.withcanopy.com/canopy-speak/) - A freemium smart medical phrase mobile app.
- [CTranslate-NMT-Web-Interface](https://github.com/ymoslem/CTranslate-NMT-Web-Interface) - A Machine Translation web interface for OpenNMT and FairSeq models using CTranslate and Streamlit.
- [DesktopTranslator](https://github.com/ymoslem/DesktopTranslator) - A local cross-platform machine translation GUI, based on CTranslate2.
- [Intento](https://inten.to/api-platform/ai/text/translate) - A simple API to third-party machine translation services from many vendors.
- [iTranslate](https://itranslate.com/) - A translation and dictionary app.
- [LibreOffice Translate](https://github.com/lernapparat/lotranslate) - An extension providing neural machine translation for LibreOffice with a single click.
- [LibreTranslate](https://github.com/LibreTranslate/LibreTranslate) - A free and open source machine translation API.
- [Local-NMT](https://github.com/fantinuoli/Local-NMT) - A pre-trained Huggingface Machine Translation engine with UI on local computer.
- [Mantra](https://mntr.jp/) - A highly accurate automatic translation of manga.
- [Skype Translator](https://www.skype.com/en/features/skype-translator/) - A real-time voice and text translator.
- [Slatona Translator](https://slatona.com) - A translation app for macOS that annotates word senses.
- [translateLocally](https://github.com/XapaJIaMnu/translateLocally) - A fast and secure translation on your local machine, powered by marian and Bergamot.

## Books 📚
- [Learning Machine Translation](https://www.amazon.com/Learning-Machine-Translation-Information-Processing/dp/0262072971) - [Cyril Goutte](https://sites.google.com/site/cyrilgoutte/), [Nicola Cancedda](https://dblp.uni-trier.de/pers/hd/c/Cancedda:Nicola), [Marc Dymetman](http://www.europe.naverlabs.com/NAVER-LABS-Europe/People/Marc-Dymetman), [George Foster](http://www-labs.iro.umontreal.ca/~foster/) - 2008 - The book looks first at enabling technologies that solve problems that are not Machine Translation proper but are linked closely to the development of a Machine Translation system, and then presents some Machine Translation techniques.
- [Machine Translation](https://www.amazon.com/Machine-Translation-Press-Essential-Knowledge/dp/B07B697ZZF/) - [Thierry Poibeau](http://lattice.cnrs.fr/Thierry-Poibeau) - 2018 - A concise, nontechnical overview of the development of machine translation, including the different approaches, evaluation issues, and market potential.
- [Machine Translation](https://www.amazon.com/Machine-Translation-Pushpak-Bhattacharyya/dp/1439897182/) - [Pushpak Bhattacharyya](https://www.cse.iitb.ac.in/~pb/) - 2015 - A book that compares and contrasts the salient principles and practices of rule-based machine translation, statistical machine translation, and and example-based machine translation.
- [Statistical Machine Translation](https://www.amazon.com/Statistical-Machine-Translation-Philipp-Koehn/dp/0521874157) - [Philipp Koehn](https://github.com/phikoehn) - An introductory text to statistical machine translation (SMT) provides all of the theories and methods needed to build a statistical machine translator.
- [Syntax-based Statistical Machine Translation](https://www.amazon.com/Syntax-based-Statistical-Translation-Synthesis-Technologies/dp/1627059008) - [Philip Williams](http://homepages.inf.ed.ac.uk/s0898777/), [Rico Sennrich](http://homepages.inf.ed.ac.uk/rsennric/), [Matt Post](https://mjpost.github.io/), [Philipp Koehn](http://www.cs.jhu.edu/~phi/) - 2016 - A comprehensive introduction to the syntax-based statistical machine translation models.
- [Makine Çevirisi](https://www.amazon.com.tr/Makine-%C3%87evirisi-Erdin%C3%A7-Aslan/dp/6052814187) - [Erdinç Aslan](https://avesis.marmara.edu.tr/erdinc.aslan) - 2019 - Turkish - A book that will provide a good introduction to students taking courses such as Translation Technologies and those starting to work in the field of machine translation.
- [Neural Machine Translation](https://www.amazon.com/Neural-Machine-Translation-Philipp-Koehn/dp/1108497322) - [Philipp Koehn](https://github.com/phikoehn) - 2020 - A book that introduces the challenge of machine translation and evaluation, including historical, linguistic, and applied context, then develops the core deep learning methods used for natural language applications.
- [Machine Translation: Foundations and Models](https://github.com/NiuTrans/MTBook) - Tong Xiao, Jingbo Zhu - 2020... - Chinese - A book that gives a systematic introduction to the basic knowledge and modeling methods of machine translation, and on this basis, discuss some cutting-edge technologies of machine translation. It can be used for the study of senior undergraduates and graduate students in computer and artificial intelligence related majors, and can also be used as a reference material for researchers related to natural language processing, especially machine translation.

## Companies and Paid Services 💰
- [Alexa Translations A.I.](https://alexatranslations.com/alexa-translations-ai/) - Alexa Translations provides A.I.-powered translations for the largest and most prestigious legal, financial, and government institutions. 
- [KantanAI](https://www.kantanai.io/) - A SaaS-based Machine Translation platform.
- [Lingua Custodia](https://www.linguacustodia.finance/) - A machine translation company specializes in finance.
- [SYSTRAN](http://www.systransoft.com/) - One of the oldest machine translation companies.
- [SDL Machine Translation](https://www.sdl.com/software-and-services/translation-software/machine-translation/) - Neural and statistical based machine translation services.
- [Unbabel](https://unbabel.com/) - A company that provides AI-powered, human-refined translation for customer support.
- [Waverly Labs](https://www.waverlylabs.com/) - A tech startup in NYC at the convergence of wearable technology and machine translation.

## Frameworks 🖼
- [Apertium](https://www.apertium.org) - An open source rule-based machine translation platform.
- [Bergamot](https://github.com/browsermt/bergamot-translator) - Cross platform C++ library focusing on optimized machine translation on the consumer-grade device.
- [EnglishTurkishTranslation-CPP](https://github.com/olcaytaner/EnglishTurkishTranslation-CPP) - An English-Turkish phrase-based translation library.
- [fairseq](https://github.com/pytorch/fairseq) - A sequence modeling toolkit to train custom models for translation, summarization, language modeling and other text generation tasks.
- [Joey NMT](https://github.com/joeynmt/joeynmt) - A minimalist NMT for educational purposes.
- [Marian](https://marian-nmt.github.io/) - A neural machine translation framework written in pure C++ with minimal dependencies.
- [ModernMT](https://github.com/ModernMT/MMT) - A neural adaptive machine translation that adapts to context and learns from corrections.
- [Moses](http://www.statmt.org/moses/) - A statistical machine translation system that allows to automatically train translation models for any language pair.
- [Nematus](https://github.com/EdinburghNLP/nematus) - Attention-based encoder-decoder model for neural machine translation built in Tensorflow.
- [NiuTrans.NMT](https://github.com/NiuTrans/NiuTrans.NMT) - A fast Neural Machine Translation system that developed in C++ and resorts to NiuTensor for fast tensor APIs.
- [NiuTrans.SMT](https://github.com/NiuTrans/NiuTrans.SMT) - An open source statistical machine translation system that fully developed in C++ language.
- [OpenNMT](http://opennmt.net/) - An open source initiative for neural machine translation and neural sequence modeling.
- [Sockeye](https://github.com/awslabs/sockeye) - A sequence-to-sequence framework with a focus on Neural Machine Translation based on PyTorch.
- [THUMT](http://thumt.thunlp.org/) - An open source toolkit for neural machine translation.

## Hardware 🎧
- [ili](https://iamili.com) - An instant offline translation device for travelers.

## Online MT Services 🌐
- [Bing Microsoft Translator](https://www.bing.com/translator) - A service to translate texts or entire web pages into different languages.
- [DeepL Translator](https://www.deepl.com/translator) - A translation service that currently supports translations between seven major European languages, powered by neural network technology.
- [Google Translate](https://translate.google.com/) - A free service instantly translates words, phrases, and web pages between English and over 100 other languages.
- [Masakhane](http://translate.masakhane.io/) - A machine translation service for African languages.
- [ModernMT](https://www.modernmt.eu/translate) - ModernMT online demo.
- [MyDutchPal's Neural MT Gateway](http://www.nmtgateway.com/) - A free online neural machine translation system to translate short pieces of text.
- [NiuTrans](https://niutrans.vip/) - A neural machine translation engine for 115 languages.
- [SYSTRAN Translate](https://translate.systran.net/translationTools/) - A demonstrator of SYSTRAN's MT engines.
- [THUMT](http://101.6.5.207:3892/) - THUMT online demo.
- [Ubiqus Online Text Translation](https://www.ubiqus.io/translator) - Free online translation for information purposes only in English, French, German, Spanish, Italian, Dutch. Up to 2,500 characters i.e. about 350 words.
- [Yandex.Translate](https://translate.yandex.com/) - A web service provided by Yandex, intended for the translation of text or web pages into another language.

## Organizations and Events 🎉
- [AAMT](http://www.aamt.info/) - Asia-Pacific Association for Machine Translation.
- [AMTA](https://amtaweb.org/) - Association for Machine Translation in the Americas.
- [EAMT (European Association for Machine Translation)](http://www.eamt.org/) - An organization that serves the growing community of people interested in MT and translation tools, including users, developers, and researchers.
- [WMT18](http://www.statmt.org/wmt18/) - A conference builds on a series of annual workshops and conferences on statistical machine translation, going back to 2006.

## Other MT Lists 📝
- [14 Current Machine Translation Applications and Services](https://emerj.com/ai-sector-overviews/machine-translation-14-current-applications-and-services/) - A list of B2B and B2C machine translation applications.
- [Awesome-Multimodal-Machine-Translation](https://github.com/ZihengZZH/awesome-multimodal-machine-translation) - A curated list of awesome papers, datasets and tutorials within Multimodal Machine Learning.
- [awesome-nmt](https://github.com/sanjibnarzary/awesome-nmt) - A curated list of useful paper, tools, tutorials, data, conferences, journals for neural machine translation.
- [Awosome Simultaneous Translation](https://github.com/js-lee-AI/Awesome_SimultaneousTranslation) - Awesome papers and codes for Simultaneous Machine Translation.
- [Awesome Simultaneous Translation](https://github.com/Vily1998/Awesome-Simultaneous-Translation) - Paper list of Simultaneous Translation Research, including both text-to-text machine translation and speech-to-text translation.
- [Comparison of machine translation applications](https://en.wikipedia.org/wiki/Comparison_of_machine_translation_applications) - General information for popular Machine translation applications.
- [inspiring_papers](https://github.com/alphadl/inspiring_papers) - Papers related to machine translation.
- [MT-Reading-List](https://github.com/THUNLP-MT/MT-Reading-List) - A machine translation reading list maintained by the Tsinghua Natural Language Processing Group.
- [Neural Machine Translation Implementations](https://github.com/jonsafari/nmt-list) - A list of Neural MT implementations.
- [NMT Papers](https://github.com/yokusama/NMT_Papers) - Some papers about NMT.

## Papers 📄

## Parallel Texts ⏸️
- [Avrupa Birliği İlerleme Raporları](https://github.com/ogun/ab-ilerleme-raporlari) - Regular Turkish and English progress reports prepared for Turkey by the European Commission.
- [Corpora Cleaning Tools](https://github.com/M4t1ss/parallel-corpora-tools) - Tools for filtering and cleaning parallel and monolingual corpora in order to train better (neural) machine translation systems.
- [OmegaWiki](http://www.omegawiki.org/) - A collaborative project to produce a free, multilingual dictionary for every language with lexicological, terminological and thesaurus information.
- [OPUS](http://opus.nlpl.eu/) - A growing collection of translated texts from the web.
- [Publicly accessible translation memories](http://wiki.proz.com/wiki/index.php/Publicly_accessible_translation_memories_(TMs)) - Several online services allowing access to aggregated translation memories.
- [turkish-parallel-corpora](https://github.com/maidis/turkish-parallel-corpora) - Some English-Turkish parallel texts for use in machine translation systems.

## Tools 🛠
- [Corpora Cleaning Tools](https://github.com/M4t1ss/parallel-corpora-tools) - Tools for filtering and cleaning parallel and monolingual corpora in order to train better (neural) machine translation systems.
- [MT-Tools](https://github.com/ymoslem/MT-Tools) - A collection of common machine translation tools.
- [MTData](https://github.com/thammegowda/mtdata) - A tool that locates, downloads, and extracts machine translation corpora.
- [Multiword Expression Tools](https://github.com/M4t1ss/MWE-Tools) - Tools for use with multiword expression extraction from parallel corpora for Moses statistical machine translation system.
- [OpusFilter](https://github.com/Helsinki-NLP/OpusFilter) - A tool for filtering and combining parallel corpora.
- [SMT Corpus Tools](https://smt-corpus-tools.readthedocs.io) - A tool set to process corpus files for machine translation.

## Tutorials and Blogs 🎒
- [Build Your Own ‘Google Translate’-Quality Machine Translation System](https://medium.com/@ageitgey/build-your-own-google-translate-quality-machine-translation-system-d7dc274bd476) - A blog post that explains how to built a NMT.
- [ChatGPT-translation.py](https://gist.github.com/ymoslem/cc46564d23857883aeeec136436fac23) - Minimal working code for translation with GPT-4.
- [Jindřich’s Blog](https://jlibovicky.github.io/) - Remarks and comments on natural language processing, artificial intelligence, and their potential social impact.
- [MachineTranslation.io](https://blog.machinetranslation.io/category/nmt) - Machine translation researcher Yasmin Moslem's blog.
- [nmt](https://github.com/tensorflow/nmt) - TensorFlow neural machine translation tutorial.
- [Tips on Building Neural Machine Translation Systems](https://github.com/neubig/nmt-tips) - A tutorial that explains some practical tips about how to train a neural machine translation system. It's partly based around examples using the lamtram toolkit.
