# Scholars of Djenne and Timbuktu

The key files in this folder are:

## TS 9 DEEPL fr_en cleaned
This is an English translation of O. Houdas’ 1898 French translation of the ninth chapter of ‘Abd al-Rahman ibn ‘Abd Allah Sadi’s Tarikh As-Sudan. This chapter is the first of two that provide names and brief accounts of important scholars from Timbuktu. The translation was generated automatically by DeepL’s French-to-English model from a mark-down version of the full text found here (https://raw.githubusercontent.com/gregorycrane/TimbuktuChronicles/master/data/tarikh-as-soudan-fra.txt). Slight corrections have been made to the automated translation, but the majority of the text remains unchanged. In particular, the automated translation retains, for the most part, the French transliterations of proper names.  

## TS 9 Ara-MT Eng
This document contains an alignment of the English translation found in the above file with the original Arabic. The machine readable version of the Arabic is sourced from the OCR provided by Hathi Trust alongside scans of O. Houdas’ original text (https://babel.hathitrust.org/cgi/pt?id=hvd.32044035034420&view=1up&seq=1). Manual corrections were than made to the OCR through reference to the scanned pages.

## TS_Scholars_Edgelist
The edgelist for a graph linking scholars by unique ID numbers to unique lemmas, with edge weights corresponding to the number of times each lemma was used to describe that scholar.

## as_sudan_analysis_working_doc
A python notebook used for exploring the scholarly description graph and from which many of the other files were generated.

## Scholarly Description csvs
The four csv files are series of lists containing the transliterated version of a scholar’s name followed by the Arabic descriptors applied to them in the text. Each three files corresponds to a single chapter while the fourth is a combined version that also includes lemmas of the descriptors and unique IDs for each scholar. Chapter 6 consists of scholars from Jenne, while chapters nine and ten contain scholars from Timbuktu. Attempts were made to connect descriptors back to unique individuals from any place in which they were referenced, but in some cases it was not clear if two identical mentions referred to the same individual. In those cases, each ambiguous mention was given its own line followed by a number.
