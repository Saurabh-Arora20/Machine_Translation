# Machine_Translation (using seq2seq model)
Machine translation using Encoder-Decoder seq2seq Deep Learning model to convert English text to French text.
In seq2seq models, both the input and output are sentences. In other words, these sentences are a sequence of words going in and out of a model.
Sequence-to-Sequence (seq2seq) models are used for a variety of NLP tasks, such as text summarization, speech recognition, DNA sequence modeling, among others. Our aim is to translate given sentences from one language to another.
# Available Data
we will use a dataset of pairs of English sentences and their French translation, which you can download from manythings.org/anki. The file to download is called fra-eng.zip.
We will implement a character-level sequence-to-sequence model, processing the input character-by-character and generating the output character-by-character. Another option would be a word-level model, which tends to be more common for machine translation.
