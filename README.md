# RIT CSCI-539 Large Language Models
* This is the Spring 2025 Seminar in Artificial Intelligence special topics class.

# Syllabus

[__week01__](./Week01_embeddings/) __Word Embeddings__
- Word tokenization and embeddings with PCA, Word2Vec, and GloVe. 2D projection
with t-SNE.

[__week02__](./Week02_classification/) __Text Classification__
- Translation with linear regression. Sampling strategies for language models:
temperature, top-k, beam-search, nuclear-k.

[__week03__](./Week03_lm/) __Language Modelling__
- Seq2seq model and attention mechanism for translation. Evaluation of language
models by perplexity. Subword segmentation: BPE tokenization. BLUE score.

[__week04__](./Week04_transformers/) __Transformers__
- Transformers.

[__week05__](./Week05_transfer/) __Transfer Learning__
- Masked Language Modelling and Next Sentence Prediction objectives for BERT. GPT-2
with fixed positioning encoder.

[__week06__](./Week06_bert/) __BERT Models__
- BERT-like models. Architecture details: layer norm, pretrained positional encodings,
rotary and ALiBi embeddings, gated FFN. Training tips for transformers: learning
rate “warm-up”, large batch size, layer norm vs. batch norm. Special tokens [CLS], [SEP],
[MASK]. Finetuning BERT.

[__week07__](./Week07_gpt/) __GPT Models__
- GPT-like models. System tokens. Creating and training GPT-2 model with PyTorch
transformer layers. Few-shot prompt engineering. Efficiency problems, large-scale training and
parallelization.

[__week08__](./Week08_peft/) __Fine-Tuning__
- Parameter Efficient Fine-Tuning (PEFT): prompt tuning and low-rank adaptors (LoRA).

[__week09__](./Week09_rlhf/) __Reinforcement Learning from Human Feedback__
- LLMs alignment with reinforcement learning from human feedback (RLHF).
Conversation systems. Instruction fine-tuning.

[__week10__](./Week10_efficiency/) __Quantization__
- Model compression and acceleration. Quantization of LLMs.

[__week11__](./Week11_retrieval/) __Retrieval Augmented LMs__
- Retrieval-Augmented Generation (RAG).

[__week12__](./Week12_doman/) __Domain Adaptation__
- Transfer learning and domain adaptation.

[__week13__](./Week13_api/) __API__
- Using API for LLMs. Decentralized LLMs on the example of together.ai and petals.

[__week14__](./Week14_multimodal/) __Multimodal LLMs__
- Image captioning and interpretation.
