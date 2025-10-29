---
title: "AlphaDIA published in Nature Biotechnology"
date: 2025-07-01T10:00:00Z
description: "AlphaDIA our free, open, and performant DIA search engine is now peer-reviewed and published in Nature Biotechnology"
tags: ["announcement", "publication", "alphadia"]
---

We’re excited to share the publication of [alphaDIA](https://alphadia.readthedocs.io/en/latest/) in [Nature Biotechnology](https://doi.org/10.1038/s41587-025-02791-w). alphaDIA is a modern, open-source search engine that brings deep learning directly to raw mass spectrometry data for data-independent acquisition (DIA) proteomics.

## A search engine for modern DIA proteomics
Mass spectrometry-based proteomics continues to generate increasingly complex datasets, especially with new, high-speed time-of-flight (TOF) detectors and advanced acquisition modes. alphaDIA addresses this complexity head-on through a feature-free processing approach, applying machine learning directly on the raw signal instead of relying on peak detection or data reduction. This enables robust analysis even for highly noisy TOF data, ensuring that all information contributes to peptide identification.

A major innovation introduced with alphaDIA is DIA transfer learning, built on the deep learning framework [**alphapeptdeep**](https://github.com/MannLabs/alphapeptdeep.git). By continuously fine-tuning neural networks to reflect the specific instrument and experimental setup, alphaDIA adapts to new conditions, e.g. different post-translational modifications (PTMs), without requiring specialized retraining. This flexibility allows the analysis of previously inaccessible peptide classes and significantly improves both identification depth and FDR control.

In benchmarking studies, alphaDIA matches or exceeds the performance of established tools, identifying over 120,000 precursors and nearly 10,000 protein groups in 21-minute gradients on the Orbitrap Astral. The framework supports both empirical and fully predicted libraries and integrates seamlessly with the broader alphapept ecosystem, including [alphaRaw](https://github.com/MannLabs/alpharaw.git), [alphaTims](https://github.com/MannLabs/alphatims.git), [directLFQ](https://github.com/MannLabs/directlfq.git), and [**alphapeptdeep**](https://github.com/MannLabs/alphapeptdeep.git).

alphaDIA is fully open, FAIR, and extensible, designed to run locally or in high-performance computing environments, with graphical, command-line, and API access. It follows modern best practices in software engineering — including modular design, continuous integration, automated testing, and rich documentation - to ensure reliability, transparency, and ease of contribution.

## Try it yourself!
We warmly invite the community to explore, test, and [contribute](https://alphadia.readthedocs.io/en/latest/developer_guide.html) to [alphaDIA on GitHub](https://github.com/MannLabs/alphadia.git). Together, we can continue to advance the open, modular, and intelligent future of computational proteomics.


> **AlphaDIA enables DIA transfer learning for feature-free proteomics**
Georg Wallmann, Patricia Skowronek, Vincenth Brennsteiner, Mikhail Lebedev, Marvin Thielert, Sophia Steigerwald, Mohamed Kotb, Oscar Despard, Tim Heymann, Xie-Xuan Zhou, Maximilian T. Strauss, Constantin Ammar, Sander Willems, Magnus Schwörer, Wen-Feng Zeng & Matthias Mann, _Nature Biotechnology_ (2025). [https://doi.org/10.1038/s41587-025-02791-w](https://doi.org/10.1038/s41587-025-02791-w)