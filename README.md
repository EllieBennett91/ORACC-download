# ORACC-download
This code allows you to download data from the [Open Richly Annotated Cuneiform Corpus (ORACC)](http://oracc.museum.upenn.edu/index.html).

This project is code that I have remixed from Niek Veldhuis' [Computational Assyriology (Compass) project](https://github.com/niekveldhuis/compass). I have not written the original code, but I did put two part of his code together and add filters in order to produce a dataset from ORACC I required for my project.

In the same folder you download this file, you need a folder called "output". This folder will be where your saved data will be saved to.

The result of the code is a table where every line represents a text, and every word is represented as a _lemma_. The lemmas are represented as lemma[guideword]POS. Data for this is taken from ORACC, where you can find more information regarding [these terms](http://oracc.museum.upenn.edu/doc/help/lemmatising/primer/index.html). The texts included are filtered according to their metadata, which is also provided by ORACC.

The code is full of comments, but if you have any issues please contact me [eleanor.bennett@helsinki.fi](eleanor.bennett@helsinki.fi).

You are free to use, reuse, and remix this code, but please credit myself (Ellie Bennett) and Niek Veldhuis.

[(CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)
