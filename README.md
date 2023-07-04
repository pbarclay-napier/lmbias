# lmbias
Code for project investigating bias in language models

Placeholder for now, files still to be added

List of files to be added:

* sentences.csv      - the 56 sentences used, describing software engineering tasks
* FI-output.txt      - translations returned via Finnish back-translation
* FIX-output.txt     - translations returned via Finnish back-translation, with phrase 'As a software engineer' removed from source sentence
* INDO-ouput.txt     - translations returned via Indonesian back-translation
* HU-ouptut.txt      - translations returned via Hungarian back-translation
* prepdata.py        - Python script to extract pronouns from the back-translated text
* lmbias.R           - R script for the data analysis
* ucoeff.R           - R implemnentation of the unalikeability coefficient
* charts.zip         - archive contains PNG versions of the charts generated

Note that we do not include the code and data kindly shared by Treude and Hata, from which the FI0 dataset is derived. 
This can be found in their repository at https://zenodo.org/record/7745437 
