# ByzantineGreekDatasets

This repository contains datasets developed by Colin Swaelens in the context of research on **Ancient and Byzantine Greek** within the [Database of Byzantine Book Epigrams (DBBE)](https://www.dbbe.ugent.be) project at Ghent University.  
The datasets are intended for use in Natural Language Processing (NLP) and Digital Humanities research.

---

## 📂 Contents

- **Dataset 1: [lingAnn_GS_medievalGreek]**  
  Example: a 10,000-token gold standard annotated for part-of-speech, morphology, and lemmatisation.

- **Dataset 2: [STS_benchmark_medievalGreek]**  
  Example: a benchmark of 300 verse pairs annotated for semantic textual similarity (STS) via comparative judgement.

---

## 🔍 Research Context

These datasets were created to support experiments in:
- Automatic linguistic annotation (POS tagging, morphology, lemmatisation)  
- Similarity detection in medieval Greek poems
- Development of specialised transformer models (e.g., **DBBErt**)  

More details can be found in the following publications:
- [Swaelens, C., De Vos, I., Lefever, E. (2024). *Lemmatisation & Morphological Analysis of Unedited Greek: Do Simple Tasks Need Complex Solutions?* ACL 2024.](#)  
- [Swaelens, C. (2024). *A Gold Standard and Benchmark for Semantic Similarity in Byzantine Greek Poetry.* LREC-COLING 2024.](#)  

*(replace `#` with links once you upload the papers/preprints)*

---

## 📑 Format

- Encoding: **UTF-8**  
- File formats: `.tsv`  (tab-separated plain text)  
- Sentence boundaries: inferred based on punctuation  
- Columns: documented in each dataset’s subfolder

---

## 📜 License

Unless stated otherwise, the datasets are released under the [CC BY 4.0 License](https://creativecommons.org/licenses/by/4.0/).  
You are free to share and adapt the data as long as appropriate credit is given.

---

## ✨ Citation

If you use these datasets, please cite:

```bibtex
@article{swaelens_lre,
	author = {Swaelens, Colin and De Vos, Ilse and Lefever, Els},
	date = {2025/03/01},
	date-added = {2025-03-23 21:03:33 +0100},
	date-modified = {2025-03-23 21:03:33 +0100},
	doi = {10.1007/s10579-023-09703-x},
	id = {Swaelens2025},
	isbn = {1574-0218},
	journal = {Language Resources and Evaluation},
	number = {1},
	pages = {109--134},
	title = {Linguistic annotation of Byzantine book epigrams},
	url = {https://doi.org/10.1007/s10579-023-09703-x},
	volume = {59},
	year = {2025},
	bdsk-url-1 = {https://doi.org/10.1007/s10579-023-09703-x}}
