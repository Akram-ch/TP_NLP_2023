French Sentiment Analysis Dataset with Television Series Reviews
http://sentiment.nlproc.org/

This is a preprocessed version of the Allociné dataset from
https://www.irit.fr/~Tim.Van-De-Cruys/tal/tp/tp3/tp3.pdf
We are providing it for better reproducibility of the results in our papers cited below.

=== Data Format ===

There are three separate tab-separated value (TSV) files for the
training/development/test sets, respectively.

The first item in each file is the label (1: positive, 0: negative).
The second item is the text, with some basic preprocessing applied
(tokenization with space separated tokens, lower-casing).



=== References ===

Please see 
http://sentiment.nlproc.org/ 
for further datasets and information.

Please cite the following papers:

Xin Dong, Gerard de Melo. Cross-Lingual Propagation for Deep Sentiment Analysis.
In: Proceedings of AAAI 2018. AAAI Press, 2018.

Xin Dong, Gerard de Melo. A Helping Hand: Transfer Learning for Deep Sentiment Analysis.
In: Proceedings of ACL 2018. Association for Computational Linguistics, 2018.


BibTeX entries:

@inproceedings{DongDeMelo2018CLSentimentEmbedding,
  author = {Xin Dong and Gerard de Melo},
  title = {Cross-Lingual Propagation for Deep Sentiment Analysis},
  booktitle = {Proceedings of the 32nd {AAAI} Conference on Artificial Intelligence (AAAI 2018)},
  year = {2018},
  pages = {5771--5778},
  publisher = {{AAAI} Press},
  location = {New Orleans, LA, USA},
  url = {https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17382},
}

@inproceedings{DongDeMelo2018SentimentHelpingHand,
  author = {Dong, Xin and {de Melo}, Gerard},
  title = {A Helping Hand: Transfer Learning for Deep Sentiment Analysis},
  booktitle = {Proceedings of ACL 2018},
  year = {2018},
  pages = {2524--2534},
  location = {Melbourne},
  url = {https://www.aclweb.org/anthology/P18-1235.pdf},
  doi = {10.18653/v1/P18-1235},
}

