# When to compress retrieved context for small language models

Retrieved documents can make small language models (about 1–4B parameters) less accurate when the documents contain many sentences that are not evidence. Compressing the context helps in some settings and hurts in others. This project asks:

- **When to compress:** from which input length does a compressed context beat the full context for a given answering model?
- **How much to keep:** should the budget be a fraction of the input or a fixed number of tokens?

It follows [HOPPER](https://github.com/sungchul02/hopper-context-compression), a training-free sentence-extraction compressor, and [HOPPER-G](https://github.com/sungchul02/HOPPER-G), which selects evidence along document-graph paths.

**Status:** pilot experiments in progress. Code and results will be released with the paper.

Author: Sungchul Choi, Baekseok University (advisor: Prof. Jin-Keun Hong).
