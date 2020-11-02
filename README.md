# rucor_to_conllu: RuCor corpus to CoNLL-U format conversion

This notebook provides a pipeline to convert
[*RuCor*](http://rucoref.maimbava.net/) corpus to
[*CoNLL-U*](https://universaldependencies.org/format.html) format.

## Prerequisites

1. [***Toxine***](https://github.com/fostroll/toxine) preprocessor.
1. **Opional:** Morphological parser
[***MorDL***](https://github.com/fostroll/mordl) with UPOS and FEATS models
already trained.

## Usage

All pipeline is contained rucor_to_conllu.ipynb notebook file. Just set the
paths to the *RuCor* and *MorDL* models and run. Maybe, you'll want also to
change some variables in cells `2` or/and `4`.

## License

***rucor_to_conllu*** is released under the Creative Commons License. See the
[LICENSE](https://github.com/fostroll/srv_zero/blob/master/LICENSE) file for
more details.
