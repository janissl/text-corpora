# text-corpora

Each corpus is stored in a separate ZIP file.

Documents of each corpus in the 'bilingual' folder are aligned by domain. i.e. they belong to the same topic. However, they may or may not be aligned at document level.

Documents of each corpus in the 'parallel' folder are aligned at sentence level. Parallel files have identical identificators (titles). Filenames of documents in the 'parallel' folder have the following pattern:<br>
`${title}.${language_1}-${language_2}.${language_1_or_2}`<br>
e.g. `economics.en-lv.lv`

The top level in each ZIP file contain plaintext documents that have the same text structure (division into paragraphs) as in original source documents. Filenames of plaintext documents have the following pattern:<br>
`${title}.${language}`<br>
e.g. `article_1.lv`

Documents in 'snt' folders contain segmented plaintext, i.e. one sentence per line. Those filenames correspond the filenames of documents at the top level. Filenames of segmented documents have the following pattern:<br>
`${title}\_${language}.snt`<br>
e.g. `publication_99_lv.snt`

Language codes used in filenames must comply with ISO 639-1 language codes.
