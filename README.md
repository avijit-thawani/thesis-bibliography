<!-- SURVEY:START -->

# Thesis Bibliography

A living survey grown from my thesis bibliography

**177** in Core · **25** Recs · updated 2026-09-13

## Core

The papers in this survey.

| # | [Paper](views/core-by-title.md) | Venue | [Year](views/core-by-year.md) | [Cited by](views/core-by-citations.md) | Score &#9660; |
| ---: | --- | --- | ---: | ---: | ---: |
| 1 | [Representing Numbers in NLP: a Survey and a Vision](https://www.semanticscholar.org/paper/28a5a53dafacebad8a7c47773079caeffb9a5baa)<br><sub>Avijit Thawani et al.</sub><br><sub>This work synthesizes best practices for representing numbers in text and articulate a vision for holistic numeracy in NLP, comprised of design trade-offs and a unified evaluation.</sub> | North American Chapter of the Association for Computational Linguistics | 2021 | 151 | 100 |
| 2 | [Learn Your Tokens: Word-Pooled Tokenization for Language Modeling](https://www.semanticscholar.org/paper/a401510c434b2274b299e9444085df0b18808aaa)<br><sub>Avijit Thawani et al.</sub><br><sub>This paper considers an alternative 'learn your tokens' scheme which utilizes the word boundary to pool bytes/characters into word representations, which are fed to the primary language model, before again decoding individual characters/bytes per word in parallel.</sub> | Conference on Empirical Methods in Natural Language Processing | 2023 | 13 | 40 |
| 3 | [Subword Regularization: Improving Neural Network Translation Models with Multiple Subword Candidates](https://www.semanticscholar.org/paper/e73bd7f9bdc262b9b7fb60ca0d5230d3ab0fad5e)<br><sub>Taku Kudo</sub><br><sub>A simple regularization method is presented, subword regularization, which trains the model with multiple subword segmentations probabilistically sampled during training, and a new sub word segmentation algorithm based on a unigram language model is proposed.</sub> | Annual Meeting of the Association for Computational Linguistics | 2018 | 1412 | 36 |
| 4 | [Between words and characters: A Brief History of Open-Vocabulary Modeling and Tokenization in NLP](https://www.semanticscholar.org/paper/d617f51833860dc50d202af7f80be71304b2e994)<br><sub>Sabrina J. Mielke et al.</sub><br><sub>It is concluded that there is and likely will never be a silver bullet singular solution for all applications and that thinking seriously about tokenization remains important for many applications.</sub> | arXiv.org | 2021 | 234 | 36 |
| 5 | [Do NLP Models Know Numbers? Probing Numeracy in Embeddings](https://www.semanticscholar.org/paper/0427110f0e79f41e69a8eb00a3ec8868bac26a4f)<br><sub>Eric Wallace et al.</sub><br><sub>This work investigates the numerical reasoning capabilities of a state-of-the-art question answering model on the DROP dataset and finds this model excels on questions that require numerical reasoning, i.e., it already captures numeracy.</sub> | Conference on Empirical Methods in Natural Language Processing | 2019 | 319 | 34 |
| 6 | [Charformer: Fast Character Transformers via Gradient-based Subword Tokenization](https://www.semanticscholar.org/paper/e79d1206292bc5e67ba19737d87d4b2ea4a37105)<br><sub>Yi Tay et al.</sub><br><sub>A soft gradient-based subword tokenization module (GBST) that automatically learns latent subword representations from characters in a data-driven fashion is introduced that paves the way for highly performant token-free models that are trained completely end-to-end.</sub> | International Conference on Learning Representations | 2021 | 221 | 34 |
| 7 | [Injecting Numerical Reasoning Skills into Language Models](https://www.semanticscholar.org/paper/3dd61d97827e3f380bf9304101149a3f865051fc)<br><sub>Mor Geva, Ankit Gupta, Jonathan Berant</sub><br><sub>This work shows that numerical reasoning is amenable to automatic data generation, and thus one can inject this skill into pre-trained LMs, by generating large amounts of data, and training in a multi-task setup.</sub> | Annual Meeting of the Association for Computational Linguistics | 2020 | 249 | 34 |
| 8 | [ByT5: Towards a Token-Free Future with Pre-trained Byte-to-Byte Models](https://www.semanticscholar.org/paper/44ef6cf919250001836ed73c0d58b20ea1e2d308)<br><sub>Linting Xue et al.</sub><br><sub>This paper shows that a standard Transformer architecture can be used with minimal modifications to process byte sequences, characterize the trade-offs in terms of parameter count, training FLOPs, and inference speed, and shows that byte-level models are competitive with their token-level counterparts.</sub> | Transactions of the Association for Computational Linguistics | 2021 | 765 | 31 |
| 9 | [BPE beyond Word Boundary: How NOT to use Multi Word Expressions in Neural Machine Translation](https://www.semanticscholar.org/paper/674265c672777b6d10d5455adc58a6cacb0d0cfe)<br><sub>Dipesh Kumar, Avijit Thawani</sub><br><sub>This work observes that naively extending BPE beyond word boundaries results in incoherent tokens which are themselves better represented as individual words, and finds that Pointwise Mutual Information (PMI) instead of frequency finds better MWEs (e.g., New\_York, Statue of Liberty, neither .</sub> | First Workshop on Insights from Negative Results in NLP | 2022 | 6 | 31 |
| 10 | [Investigating the Limitations of Transformers with Simple Arithmetic Tasks](https://www.semanticscholar.org/paper/2cc3ab9fa41ba2804e301f7eae9598636e62422a)<br><sub>Rodrigo Nogueira, Zhiying Jiang, Jimmy J. Li</sub><br><sub>It is found that how a number is represented in its surface form has a strong influence on the model's accuracy, and this result bolsters evidence that subword tokenizers and positional encodings are components in current transformer designs that might need improvement.</sub> | - | 2021 | 165 | 30 |

[... and 167 more, sorted by score](views/core-by-score.md)

## ✨ Recs

<sub>Found by following the citation graph — a deterministic algorithm you can tune, not an LLM. Refreshed daily. Use the **Decide** column to accept or reject one.</sub>

| # | [Paper](views/recs-by-title.md) | Venue | [Year](views/recs-by-year.md) | [Cited by](views/recs-by-citations.md) | Score &#9660; | Why | Decide |
| ---: | --- | --- | ---: | ---: | ---: | --- | --- |
| 1 | [Revisiting Character-Based Neural Machine Translation with Capacity and Compression](https://www.semanticscholar.org/paper/87639a90e0ab573236efeb79cf24efafc2463dcf)<br><sub>Colin Cherry et al.</sub><br><sub>The modeling problem can be solved by standard sequence-to-sequence architectures of sufficient depth, and that deep models operating at the character level outperform identical models operating over word fragments, implying that alternative architectures for handling character input are better viewed as methods for reducing computation time than as improved ways of modeling longer sequences.</sub> | Conference on Empirical Methods in Natural Language Processing | 2018 | 101 | 100 | cited by 8 in Core | [review #1](https://github.com/avijit-thawani/thesis-bibliography/pull/1) |
| 2 | [Mining Numbers in Text: A Survey](https://www.semanticscholar.org/paper/40a1f266bb5ca853837355bfff272a55f0049c81)<br><sub>Minoru Yoshida, K. Kita</sub><br><sub>A quick overview of the history and recent advances of the research of mining such relations between numerals and words found in text data is provided.</sub> | Information Systems | 2021 | 4 | 100 | cites 17 in Core | [review #2](https://github.com/avijit-thawani/thesis-bibliography/pull/2) |
| 3 | [Learning to Automatically Solve Algebra Word Problems](https://www.semanticscholar.org/paper/3a395daf6c97c084cf9c3827384c53caf6502921)<br><sub>Nate Kushman et al.</sub><br><sub>An approach for automatically learning to solve algebra word problems by reasons across sentence boundaries to construct and solve a system of linear equations, while simultaneously recovering an alignment of the variables and numbers to the problem text.</sub> | Annual Meeting of the Association for Computational Linguistics | 2014 | 399 | 95 | cited by 10 in Core | [review #3](https://github.com/avijit-thawani/thesis-bibliography/pull/3) |
| 4 | [Character-Aware Neural Language Models](https://www.semanticscholar.org/paper/891ce1687e2befddd19f54e4eef1d3f39c8dbaf7)<br><sub>Yoon Kim et al.</sub><br><sub>A simple neural language model that relies only on character-level inputs that is able to encode, from characters only, both semantic and orthographic information and suggests that on many languages, character inputs are sufficient for language modeling.</sub> | AAAI Conference on Artificial Intelligence | 2015 | 1733 | 92 | cited by 13 in Core | [review #4](https://github.com/avijit-thawani/thesis-bibliography/pull/4) |
| 5 | [Exploring the Limits of Language Modeling](https://www.semanticscholar.org/paper/2f2d8f8072e5cc9b296fad551f65f183bdbff7aa)<br><sub>R. Józefowicz et al.</sub><br><sub>This work explores recent advances in Recurrent Neural Networks for large scale Language Modeling, and extends current models to deal with two key challenges present in this task: corpora and vocabulary sizes, and complex, long term structure of language.</sub> | arXiv.org | 2016 | 1191 | 92 | cited by 12 in Core | [review #5](https://github.com/avijit-thawani/thesis-bibliography/pull/5) |
| 6 | [Systematic review and comparative synthesis of cross lingual question answering systems for low resource Indic languages](https://www.semanticscholar.org/paper/234fea0bca0519286edc98b49e94337bac2e2719)<br><sub>Siddesh Savant, Uttam U. Deshpande, Jovi D'Silva</sub><br><sub>A systematic review of 137 shortlisted research articles reveals that the performance of a cross-lingual QA system is structurally influenced by the interaction between linguistic typology, model design, and not exclusively by model scale or architecture.</sub> | Discover Artificial Intelligence | 2026 | 0 | 82 | past month · cites 14 in Core | [review #10](https://github.com/avijit-thawani/thesis-bibliography/pull/10) |
| 7 | [Hierarchical aspect-based sentiment analysis Using FinRoBERTa](https://www.semanticscholar.org/paper/23bd8f0daba4db8a62d026ebf3a237ec9e1ff166)<br><sub>Stefan Straleger, Flavius Frasincar</sub> | Data & Knowledge Engineering | 2026 | 0 | 71 | past month · cites 12 in Core | [review #26](https://github.com/avijit-thawani/thesis-bibliography/pull/26) |
| 8 | [Scratchpad Patching: Decoupling Compute from Patch Size in Byte-Level Language Models](https://www.semanticscholar.org/paper/999cf59792831e0916e9fcc94d1a549b8dfeeb5f)<br><sub>Lin Zheng et al.</sub><br><sub>This work introduces Scratchpad Patching (SP), which inserts transient scratchpads inside each patch to aggregate the bytes seen so far and refresh patch-level context for subsequent predictions, and improves model quality at the same patch size.</sub> | arXiv.org | 2026 | 0 | 65 | past 6 months · cites 11 in Core | [review #35](https://github.com/avijit-thawani/thesis-bibliography/pull/35) |
| 9 | [TokAlign++: Advancing Vocabulary Adaptation via Better Token Alignment](https://www.semanticscholar.org/paper/f168e23ff65084d0df3445db554706387edca0b3)<br><sub>Chong Li et al.</sub><br><sub>This work introduces a method named TokAlign++ to improve vocabulary adaptation performance by learning better token alignment lexicon and shows that this method boosts the multilingual text compression rates and preserves most of the multilingual ability of vanilla models.</sub> | arXiv.org | 2026 | 1 | 59 | past 6 months · cites 10 in Core | [review #36](https://github.com/avijit-thawani/thesis-bibliography/pull/36) |
| 10 | [Self-Reflective Multi-modal Reasoning for Short-Video Fake News Detection](https://www.semanticscholar.org/paper/92cec07fb969215c35e0c3d657e50615450a5a31)<br><sub>Pin-Jie Xu et al.</sub><br><sub>SRM-FND is proposed, a self-reflective multimodal reasoning framework for short-video fake news detection that outperforms strong baselines, produces more reliable and interpretable predictions, and delivers noticeable improvements in cross-dataset performance.</sub> | - | 2026 | 0 | 53 | past month · cites 9 in Core | [review #27](https://github.com/avijit-thawani/thesis-bibliography/pull/27) |

[... and 15 more, sorted by score](views/recs-by-score.md)

<!-- SURVEY:END -->

<!--
  Anything you write between the SURVEY:END marker above and the footer below
  is yours and is never overwritten. Notes, scope, open questions, a call for
  contributions -- all safe here.
-->

---

<!-- TEMPLATE-FOOTER:START -->

### Want your own living survey?

Click **Use this template**, add your papers, and a daily GitHub Action keeps
the tables above up to date. Everything lives in your own repo — no website, no
backend, no database, no API keys — and the Recs come from a citation graph
algorithm you can tune, not from an LLM. See **[SETUP.md](https://github.com/avijit-thawani/living-survey/blob/main/SETUP.md)**.

<!-- TEMPLATE-FOOTER:END -->
