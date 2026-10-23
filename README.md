# ViLegalREB: Vietnamese Legal Retrieval Embedding Benchmark

**Quang Huy Nguyen, Tri Hieu Phan, Dong Duong Le, Anh-Cuong Le and Trong-Chi Duong**

[![arXiv](https://img.shields.io/badge/arXiv-TBA-b31b1b.svg)](https://arxiv.org/) [![HuggingFace](https://img.shields.io/badge/HuggingFace-TBA-e28743.svg)](https://huggingface.co/datasets/NLP-KD-Lab-TDTU/ViLegalREB) 

## Abstract

Retrieving statutory grounds for citizen inquiries requires distinguishing provisions that directly govern an issue from supporting legal context and merely topical matches. We introduce ViLegalREB, a Vietnamese statute retrieval benchmark comprising 1,574 reformulated citizen inquiries across 32 legal domains and 26,317 graded query--provision judgments over 3,284,399 chunks from 96,215 normative documents. Construction combines citation extraction, query auditing, BM25-based candidate mining with dense reranking, multi-model relevance assessment, and blind review by three legal specialists. We evaluate BM25 and ten dense bi-encoders using full-corpus retrieval and dense reranking of 5,000 BM25 candidates per query. BM25 achieves the highest reported nDCG@10 (26.02), while BGE-M3 achieves the highest Recall@100 (55.86) in full-corpus retrieval (scores scaled by 100). Two-stage retrieval improves nDCG@10 for all evaluated dense models but slightly reduces BGE-M3's Recall@100. Incomplete judgments and selective human review limit the interpretation of these results.

## Citation

> TBA

## Contact

- Quang Huy Nguyen: nguyenquanghuy.st@tdtu.edu.vn