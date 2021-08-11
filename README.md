## License/Citation

This code is licensed under a **CC BY 4.0** license. If you use it, you should cite the following paper in your work:

> Franziska Pannach and Tillmann Dönicke (2021). "Cracking a Walnut with a Sledgehammer:  XLM-RoBERTa for German Verbal Idiom Disambiguation Tasks". In Proceedings of the Shared Task on the Disambiguation of German Verbal Idioms at KONVENS 2021.

The data in `train_extra` was collected from different sources, which fall under the following licenses:

- `train_extra_filtered_20_tokens.tsv`: These examples were extracted from the German Wiktionary ([hier Link zum Dump einfügen](hier Link zum Dump einfügen)) and are published under a **CC-BY-SA-3.0** license. Some of the examples originate from external sources such as newspapers. You can find the original source of an example in the corresponding Wiktionary entry.
- `train_extra_literally.tsv`: These examples were collected manually from publically accessible websites on the world wide web. The first column of the file contains the link to each website. We assume that the examples fall under **fair use** restrictions.
- `train_extra_literally_news_edited.tsv`: These examples were collected from the News-wrt corpus of the Leipzig Corpora Collection / Deutscher Wortschatz ([https://wortschatz.uni-leipzig.de/en/download/German](https://wortschatz.uni-leipzig.de/en/download/German)) © 2021 Abteilung Automatische Sprachverarbeitung, Universität Leipzig. The corpus is published under a **CC BY 4.0** license. The corpus consists of sentences that were collected from the world wide web. The first column of the file contains the link to each website. We added context to the examples from the original websites and assume that the extended examples fall under **fair use** restrictions.
