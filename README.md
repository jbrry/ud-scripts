# ud-scripts
Scripts for compatibilitising between VISL-CG3, Apertium, CoNLL-X and Universal Dependency

*vislcg3-flatten.sh:*

Flatten VISL-CG3 output, replaces subreadings with null surface tokens (well, actually '*').

*vislcg3-to-conllx-input.py:*

Convert VISL-CG3 output to ConLL-X format. 

*conllu-to-tikzdep.py:*

Convert CoNLL-U to TiKZdependency graphs. One file per input sentence.
