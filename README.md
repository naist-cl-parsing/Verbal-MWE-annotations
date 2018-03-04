# Verbal-MWE-annotations

We provide users with annotations of verbal multiword expressions (VMWEs) on English Ontonotes. Regarding methods we exploit for annotations, please refer to [1].

## Files

### VMWE annotations (vmwe_indices.txt)
Indices of components of VMWEs in sentences.

2 tab-separated columns:

1.  MWE (e.g., "break silence")
2.  Instance_id (e.g., wsj_1279_1:12_17)

 - A format of instance id is [filename]_[sentence_id]:[token_indices].
     - Filename (e.g., wsj_1279)
     - Sentence_id (0-origin)
     - Token_indices
     - Indices of components of a VMWE (1-origin)

### Dependency (ontonotes_wsj_00_24_masked.conll)
- Stanford dependencies [2] of the Wall Street Journal portion of Ontonotes Release 5.0 (LDC2013T19).

#### Conll Format
1 token per line, with blank lines separating sentences.

9 tab-separated columns (columns 1-8 are based on CoNLL-X Format [3]):

1.  ID
2.  FORM (masked)
3.  LEMMA (masked)
4.  CPOSTAG
5.  POSTAG
6.  FEATS
7.  HEAD
8.  DEPREL
9.  Filename

## References
- [1] Akihiko Kato, Hiroyuki Shindo and Yuji Matsumoto. 2018. Construction of Large-scale English Verbal Multiword Expression Annotated Corpus. LREC 2018 (to appear)

- [2] Marie-Catherine de Marneffe, Christopher D. Manning. 2008. The Stanford Typed Dependencies Representation. Coling 2008: Proceedings of the workshop on Cross-Framework and Cross-Domain Parser Evaluation, pages 1–8, Manchester, UK. Coling 2008 Organizing Committee.
(http://www.aclweb.org/anthology/W08-1301)

- [3] CoNLL-X Shared Task: Multi-lingual Dependency Parsing (http://ilk.uvt.nl/conll/)

## History
  - Ver 1.0: 2018-03-04.

## Contact
- Please e-mail kato.akihiko.ju6 /at/ is.naist.jp with questions.

## Contributors
- Akihiko Kato
- Hiroyuki Shindo
- Yuji Matsumoto
