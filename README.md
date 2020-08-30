# PHP code2seq extractor

Extracts code2seq compatible datasets from PHP source files.

> The ability to generate natural language sequences from source code snippets has
a variety of applications such as code summarization, documentation, and retrieval. Sequence-to-sequence (seq2seq) models, adopted from neural machine
translation (NMT), have achieved state-of-the-art performance on these tasks by
treating source code as a sequence of tokens. We present CODE 2 SEQ : an alternative approach that leverages the syntactic structure of programming lan-
guages to better encode source code. Our model represents a code snippet as
the set of compositional paths in its abstract syntax tree (AST) and uses attention to select the relevant paths while decoding. We demonstrate the effec-
tiveness of our approach for two tasks, two programming languages, and four
datasets of up to 16M examples. Our model significantly outperforms previous models that were specifically designed for programming languages, as well
as state-of-the-art NMT models. An online demo of our model is available at
http://code2seq.org. Our code, data and trained models are available at http://github.com/tech-srl/code2seq.
