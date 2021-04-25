# Summary

The UD Kazakh treebank is a combination of text from various sources including Wikipedia, some folk tales,
sentences from the UDHR, news and phrasebook sentences. Sentences IDs include partial document identifiers.

# Introduction


The tokenisation in the Kazakh UD treebank follows the principles of [Turkic lexica in Apertium](http://wiki.apertium.org/wiki/Turkic_lexicon).
Morphological processing in the Kazakh UD treebank follows the principles of [Turkic lexica in Apertium](http://wiki.apertium.org/wiki/Turkic_lexicon).
The treebank was randomly split into training (80%), testing (10%), and development (10%) sets.

# Acknowledgements

Please, cite the following papers if you use Kazakh UD treebank:

@inproceedings{tyers_tl2015,
  author = {Tyers, Francis M. and Washington, Jonathan N.},
  title = {Towards a Free/Open-source Universal-dependency Treebank for Kazakh},
  booktitle = {3rd International Conference on Turkic Languages Processing,
  (TurkLang 2015)},
  pages = {276--289},
  year = {2015},
}

@inproceedings{makazhan_tl2015,
  author = {Makazhanov, Aibek and
  Sultangazina, Aitolkyn and
  Makhambetov, Olzhas and
  Yessenbayev, Zhandos},
  title = {Syntactic Annotation of Kazakh: Following the Universal Dependencies Guidelines. A report},
  booktitle = {3rd International Conference on Turkic Languages Processing,
  (TurkLang 2015)},
  pages = {338--350},
  year = {2015},
}

# Changelog

2021-05-15 v2.8
  * Tense=Aor is undocumented and controversial (see https://github.com/UniversalDependencies/docs/issues/773);
    tentatively replaced with Aspect=Hab|Tense=Pres.
  * Undocumented Cov(erb) is probably better represented as Inf, see https://github.com/UniversalDependencies/docs/issues/747
  * Voice=Coop actually should be Voice=Rcp, which is already defined in UD.
  * Undocumented PronType=Qnt changed to PronType=Tot.
2018-04-15 v2.2
  * Repository renamed from UD_Kazakh to UD_Kazakh-KTB.
2016-11-15 v1.4
  * A first feature set has been developped.
  * Added 150 more trees annotated for morpho-lexical features (in addition to POS, lemmata, and syntax).
  * Several annotation errors have been fixed.

=== Machine-readable metadata (DO NOT REMOVE!) ================================
Data available since: UD v1.3
License: CC BY-SA 4.0
Includes text: yes
Genre: wiki fiction news
Lemmas: manual native
UPOS: converted from manual
XPOS: manual native
Features: converted from manual
Relations: manual native
Contributors: Makazhanov, Aibek; Washington, Jonathan North; Tyers, Francis
Contributing: elsewhere
Contact: aibek.makazhanov@nu.edu.kz, jonathan.north.washington@gmail.com, ftyers@prompsit.com
===============================================================================
