<!-- SURVEY:START -->

# Thesis Bibliography

A living survey grown from my thesis bibliography

**155** in Core · **25** Recs · updated 2026-09-12

> **How to read this page.**
> **Core** is what this survey contains; **Recs** is what to read next, found automatically by following citations. Only the top 10 of each is shown here, linked to the full lists.
> **Score** is 0 to 100 and says how tied into this survey a paper is, relative to the most connected one in its own list. It drives the default order.
> In Recs, **Why** says how a paper turned up: *cites N here*, newer work building on N of these; *cited by N here*, older work N of these rest on; *from ...*, the bibliography of a survey used as a seed.
> Column headings are links: click one to open the same list sorted that way.

## Core

The papers in this survey.

| # | [Paper](views/core-by-title.md) | Venue | [Year](views/core-by-year.md) | [Cited by](views/core-by-citations.md) | Score &#9660; |
| ---: | --- | --- | ---: | ---: | ---: |
| 1 | [Representing Numbers in NLP: a Survey and a Vision](https://www.semanticscholar.org/paper/28a5a53dafacebad8a7c47773079caeffb9a5baa)<br><sub>Avijit Thawani et al.</sub><br><sub>This work synthesizes best practices for representing numbers in text and articulate a vision for holistic numeracy in NLP, comprised of design trade-offs and a unified evaluation.</sub> | North American Chapter of the Association for Computational Linguistics | 2021 | 151 | 100 |
| 2 | [Learn Your Tokens: Word-Pooled Tokenization for Language Modeling](https://www.semanticscholar.org/paper/a401510c434b2274b299e9444085df0b18808aaa)<br><sub>Avijit Thawani et al.</sub><br><sub>This paper considers an alternative 'learn your tokens' scheme which utilizes the word boundary to pool bytes/characters into word representations, which are fed to the primary language model, before again decoding individual characters/bytes per word in parallel.</sub> | Conference on Empirical Methods in Natural Language Processing | 2023 | 13 | 44 |
| 3 | [Canine: Pre-training an Efficient Tokenization-Free Encoder for Language Representation](https://www.semanticscholar.org/paper/969287b8a96e242793b11f0dbb99ec341228106f)<br><sub>J. Clark et al.</sub><br><sub>Canine is presented, a neural encoder that operates directly on character sequences—without explicit tokenization or vocabulary—and a pre-training strategy that operates either directly on characters or optionally uses subwords as a soft inductive bias.</sub> | Transactions of the Association for Computational Linguistics | 2021 | 333 | 41 |
| 4 | [Subword Regularization: Improving Neural Network Translation Models with Multiple Subword Candidates](https://www.semanticscholar.org/paper/e73bd7f9bdc262b9b7fb60ca0d5230d3ab0fad5e)<br><sub>Taku Kudo</sub><br><sub>A simple regularization method is presented, subword regularization, which trains the model with multiple subword segmentations probabilistically sampled during training, and a new sub word segmentation algorithm based on a unigram language model is proposed.</sub> | Annual Meeting of the Association for Computational Linguistics | 2018 | 1412 | 38 |
| 5 | [Between words and characters: A Brief History of Open-Vocabulary Modeling and Tokenization in NLP](https://www.semanticscholar.org/paper/d617f51833860dc50d202af7f80be71304b2e994)<br><sub>Sabrina J. Mielke et al.</sub><br><sub>It is concluded that there is and likely will never be a silver bullet singular solution for all applications and that thinking seriously about tokenization remains important for many applications.</sub> | arXiv.org | 2021 | 234 | 38 |
| 6 | [Do NLP Models Know Numbers? Probing Numeracy in Embeddings](https://www.semanticscholar.org/paper/0427110f0e79f41e69a8eb00a3ec8868bac26a4f)<br><sub>Eric Wallace et al.</sub><br><sub>This work investigates the numerical reasoning capabilities of a state-of-the-art question answering model on the DROP dataset and finds this model excels on questions that require numerical reasoning, i.e., it already captures numeracy.</sub> | Conference on Empirical Methods in Natural Language Processing | 2019 | 319 | 36 |
| 7 | [Charformer: Fast Character Transformers via Gradient-based Subword Tokenization](https://www.semanticscholar.org/paper/e79d1206292bc5e67ba19737d87d4b2ea4a37105)<br><sub>Yi Tay et al.</sub><br><sub>A soft gradient-based subword tokenization module (GBST) that automatically learns latent subword representations from characters in a data-driven fashion is introduced that paves the way for highly performant token-free models that are trained completely end-to-end.</sub> | International Conference on Learning Representations | 2021 | 221 | 36 |
| 8 | [Injecting Numerical Reasoning Skills into Language Models](https://www.semanticscholar.org/paper/3dd61d97827e3f380bf9304101149a3f865051fc)<br><sub>Mor Geva, Ankit Gupta, Jonathan Berant</sub><br><sub>This work shows that numerical reasoning is amenable to automatic data generation, and thus one can inject this skill into pre-trained LMs, by generating large amounts of data, and training in a multi-task setup.</sub> | Annual Meeting of the Association for Computational Linguistics | 2020 | 249 | 36 |
| 9 | [ByT5: Towards a Token-Free Future with Pre-trained Byte-to-Byte Models](https://www.semanticscholar.org/paper/44ef6cf919250001836ed73c0d58b20ea1e2d308)<br><sub>Linting Xue et al.</sub><br><sub>This paper shows that a standard Transformer architecture can be used with minimal modifications to process byte sequences, characterize the trade-offs in terms of parameter count, training FLOPs, and inference speed, and shows that byte-level models are competitive with their token-level counterparts.</sub> | Transactions of the Association for Computational Linguistics | 2021 | 765 | 33 |
| 10 | [BPE beyond Word Boundary: How NOT to use Multi Word Expressions in Neural Machine Translation](https://www.semanticscholar.org/paper/674265c672777b6d10d5455adc58a6cacb0d0cfe)<br><sub>Dipesh Kumar, Avijit Thawani</sub><br><sub>This work observes that naively extending BPE beyond word boundaries results in incoherent tokens which are themselves better represented as individual words, and finds that Pointwise Mutual Information (PMI) instead of frequency finds better MWEs (e.g., New\_York, Statue of Liberty, neither .</sub> | First Workshop on Insights from Negative Results in NLP | 2022 | 6 | 33 |

[... and 145 more, sorted by score](views/core-by-score.md)

## ✨ Recs

<sub>Found by following the citation graph, not picked by hand. Refreshed daily. To accept one, paste its link into [`import/papers.txt`](import/papers.txt) and commit.</sub>

| # | [Paper](views/recs-by-title.md) | Venue | [Year](views/recs-by-year.md) | [Cited by](views/recs-by-citations.md) | Score &#9660; | Why |
| ---: | --- | --- | ---: | ---: | ---: | --- |
| 1 | [Learning to Automatically Solve Algebra Word Problems](https://www.semanticscholar.org/paper/3a395daf6c97c084cf9c3827384c53caf6502921)<br><sub>Nate Kushman et al.</sub><br><sub>An approach for automatically learning to solve algebra word problems by reasons across sentence boundaries to construct and solve a system of linear equations, while simultaneously recovering an alignment of the variables and numbers to the problem text.</sub> | Annual Meeting of the Association for Computational Linguistics | 2014 | 399 | 100  cited by 10 here |
| 2 | [Mining Numbers in Text: A Survey](https://www.semanticscholar.org/paper/40a1f266bb5ca853837355bfff272a55f0049c81)<br><sub>Minoru Yoshida, K. Kita</sub><br><sub>A quick overview of the history and recent advances of the research of mining such relations between numerals and words found in text data is provided.</sub> | Information Systems | 2021 | 4 | 100  cites 18 here |
| 3 | [Revisiting Character-Based Neural Machine Translation with Capacity and Compression](https://www.semanticscholar.org/paper/87639a90e0ab573236efeb79cf24efafc2463dcf)<br><sub>Colin Cherry et al.</sub><br><sub>The modeling problem can be solved by standard sequence-to-sequence architectures of sufficient depth, and that deep models operating at the character level outperform identical models operating over word fragments, implying that alternative architectures for handling character input are better viewed as methods for reducing computation time than as improved ways of modeling longer sequences.</sub> | Conference on Empirical Methods in Natural Language Processing | 2018 | 101 | 92  cited by 7 here |
| 4 | [Character-Aware Neural Language Models](https://www.semanticscholar.org/paper/891ce1687e2befddd19f54e4eef1d3f39c8dbaf7)<br><sub>Yoon Kim et al.</sub><br><sub>A simple neural language model that relies only on character-level inputs that is able to encode, from characters only, both semantic and orthographic information and suggests that on many languages, character inputs are sufficient for language modeling.</sub> | AAAI Conference on Artificial Intelligence | 2015 | 1733 | 89  cited by 12 here |
| 5 | [Injecting the score of the first-stage retriever as text improves BERT-based re-rankers](https://www.semanticscholar.org/paper/1c1b9f56f904a4fc8e980c3ccb5aa92b342d856b)<br><sub>Arian Askari et al.</sub><br><sub>A novel approach for combining first-stage lexical retrieval models and Transformer-based re-rankers is proposed, which injects the relevance score of the lexical model as a token into the input of the cross-encoder re-ranker.</sub> | Discover Computing | 2024 | 9 | 89  cites 16 here |
| 6 | [Neural Machine Translation by Jointly Learning to Align and Translate](https://www.semanticscholar.org/paper/fa72afa9b2cbc8f0d7b05d52548906610ffbb9c5)<br><sub>Dzmitry Bahdanau, Kyunghyun Cho, Yoshua Bengio</sub><br><sub>It is conjecture that the use of a fixed-length vector is a bottleneck in improving the performance of this basic encoder-decoder architecture, and it is proposed to extend this by allowing a model to automatically (soft-)search for parts of a source sentence that are relevant to predicting a target word, without having to form these parts as a hard segment explicitly.</sub> | International Conference on Learning Representations | 2014 | 29982 | 89  cited by 21 here |
| 7 | [Exploring the Limits of Language Modeling](https://www.semanticscholar.org/paper/2f2d8f8072e5cc9b296fad551f65f183bdbff7aa)<br><sub>R. Józefowicz et al.</sub><br><sub>This work explores recent advances in Recurrent Neural Networks for large scale Language Modeling, and extends current models to deal with two key challenges present in this task: corpora and vocabulary sizes, and complex, long term structure of language.</sub> | arXiv.org | 2016 | 1191 | 88  cited by 11 here |
| 8 | [Learning to Solve Arithmetic Word Problems with Verb Categorization](https://www.semanticscholar.org/paper/a7862e14b4c20cefd6dc4f611f8aa866fabf130b)<br><sub>Mohammad Javad Hosseini et al.</sub><br><sub>The paper analyzes the arithmetic-word problems “genre”, identifying seven categories of verbs used in such problems, and reports the first learning results on this task without reliance on predefined templates and makes the data publicly available.</sub> | Conference on Empirical Methods in Natural Language Processing | 2014 | 487 | 86  cited by 9 here |
| 9 | [Improving Multilingual Models with Language-Clustered Vocabularies](https://www.semanticscholar.org/paper/4d3f6673009589971973a81a097441e7c78a265e)<br><sub>Hyung Won Chung et al.</sub><br><sub>This work introduces a novel procedure for multilingual vocabulary generation that combines the separately trained vocabularies of several automatically derived language clusters, thus balancing the trade-off between cross-lingual subword sharing and language-specific vocABularies.</sub> | Conference on Empirical Methods in Natural Language Processing | 2020 | 76 | 84  cited by 6 here |
| 10 | [Byte Pair Encoding is Suboptimal for Language Model Pretraining](https://www.semanticscholar.org/paper/b0b0dddb8310e01b9407a21674c2d33a23a6e967)<br><sub>Kaj Bostrom, Greg Durrett</sub><br><sub>Differences between BPE and unigram LM tokenization are analyzed, finding that the latter method recovers subword units that align more closely with morphology and avoids problems stemming from BPE’s greedy construction procedure.</sub> | Findings | 2020 | 333 | 83  cited by 8 here |

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

Click **Use this template**, name your repo, and overwrite [`import/papers.txt`](import/papers.txt) with your papers, and you get the table above plus ✨ daily reading suggestions mined from the citation graph, with no site to host and no API keys. Details in [SETUP.md](SETUP.md).

<!-- TEMPLATE-FOOTER:END -->
