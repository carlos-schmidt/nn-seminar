# Plan for Presentation and Paper: Multi-modal Speech Representation Learning

1. Read and understand papers.
2. Write down questions regarding papers and also highlight important stuff etc.
3. Ask said questions, also ask what exactly the paper and presentation should contain / not contain.

## Papers

[1] Mohamed, Abdelrahman, et al. "Self-supervised speech representation learning: A review." IEEE Journal of Selected Topics in Signal Processing (2022).
Intrinsic vs. Extrinsic Approaches
Questions:
- Are there supervised methods for multi-modal speech repr learning / should I cover them?
- Should I cover non multi-modal approaches such as Generative, Predictive, Contrastive?
- How deep into datasets for speech learning do I need to go into?

[2] Ao, Junyi, et al. "Speecht5: Unified-modal encoder-decoder pre-training for spoken language processing." ACL (2022).
- Speech/Text to Speech/Text
- text and speech input into same vector space
- Advantage: You can pre-train it on large amounts of unlabeled text/speech data
- Why does it work so good?

Questions:

[3] Zhu, Qiushi, et al. "Vatlm: Visual-audio-text pre-training with unified masked prediction for speech representation learning." IEEE Transactions on Multimedia (2023).
-

Questions:

[4] Shi, Bowen, et al. "Learning audio-visual speech representation by masked multimodal cluster prediction." ICLR (2022).

## What needs to be in the presentation

0. What is Speech Representation Learning, why do we need it? (Review Section VI), What is Self-Supervised Learning
1. Motivation: Current state (is single mode current sota?), then show that multi modal datas is easy to get (if it's true)
2. History of (Speech) Representation Learning?
3. Requirements of Speech Representations
4. SPEECH REPRESENTATION LEARNING PARADIGMS
5. Multi-modal approaches, challenges thereof
5. Gathering multi-modal data
6. Evaluation methods
7. Present approaches by papers
8. Advantages / Drawbacks of Multi-modal learning (e.g., domain-specific data)
4. Present their results? Possibly better scores / more use cases