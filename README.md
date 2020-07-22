# Dutch_Renaissance_corpus

This corpus contains alexandrines and iambic pentameters written by a selection of Dutch Renaissance poets (end of 16th and 17th century). 
Its creation and annotation was part of a PhD project at the Meertens Institute (https://www.meertens.knaw.nl) which was funded by the Koninklijke Nederlandse Akademie van Wetenschappen (KNAW).

All texts have been taken from the Digitale Bibliotheek voor de Nederlandse Letteren (https://www.dbnl.org).

Most of the corpus has been automatically annotated and the lines marked with an asterisk have been manually annotated or checked. 

In the annotation folder, the poems are annotated according to the following annotation system:
0 for unstressed syllable
1 for stressed syllable (both primary and secondary stress)
3 for elided vowel
4 for synalepha (e.g. two vowels undergoing synalepha: me/4 een/0)

lines_augmentation.csv contains lines generated with data augmentation. The type of data augmentation used here exploits the orthographic variance attested in the corpus (since Dutch had not achieved standardisation in this period yet, several spelling diffences can be noticed among authors or even within works by the same poet). Sentences which contained words with different possible spellings were duplicated and both versions included in the training material. 

