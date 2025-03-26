# Copiste d'un jour
# Description
The Copiste d'un jour project aims at creating a dataset of ground truth of contemporary Québécois handwriting to train HTR models.

This project draws inspiration from CREMMA Wikipedia : https://github.com/HTR-United/cremma-wikipedia

The Copiste d'un jour dataset is based on a collection of randomly selected Wikipedia summaries. Each text comprises between 125 and 175 words and was copied by hand by volunteers. 
The texts were ordered in a way to prioritize texts that presented rare character 1- and 2-grams. Non-French characters were replaced with "-".
In general, the copy of one text took between 1 and 2 pages. In total, 267 volunteers copied 265 texts (2 texts were unfortunately copied twice by two different volunteers). 
We took care of the alignment between the handwritten portion and the original text.

# Transcription guidelines
The transcription guidelines follow CREMMA's convention for modern documents. In short:

Sequences that are readable but crossed out have been transcribed \>word sequence<.  
Sequences that are unreadable have been transcribed \><.

# License
This work is licensed under a Creative Commons Attribution 4.0 International License.
