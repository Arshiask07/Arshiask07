# Shaik Arshia

BTech Computer Science and Engineering (AI/ML), VIT-AP University.

I work on real-world problems using data. I build a solution, then measure how well it holds up and where it falls short.

## Research

**A Unified Transformer-Based Pipeline for Multi-Domain Threat Detection: Hate Speech and Phishing**
Accepted and presented at IEEE InC4 2026, with Dr. Beebi Naseeba. Hate speech and phishing are usually handled by separate systems. This work asks whether one shared pipeline, built on XLM-RoBERTa-base, can cover both. Each task is fine-tuned separately from the same starting model, with only small task-specific changes. Tested on a Hinglish (Hindi-English code-mixed) hate speech dataset and the SMS Spam Collection, used as a proxy for phishing. Macro F1: hate speech 0.7381, phishing 0.9674.

## Projects

The speech emotion and multi-agent search projects were group work; each repository lists individual contributions.

- [Speech Emotion Recognition](https://github.com/Arshiask07/Speech-Emotion-Detection): will a model trained on one set of recordings still work on recordings from a different source? 57.0% accuracy across six emotions on unseen speakers. Trained on RAVDESS alone, it fell to about 17% on CREMA-D, close to chance.
- [Cost-Aware Multi-Agent Search](https://github.com/Arshiask07/Cost-Aware-MARL-Search-Rescue): how much should a search team spend on sharing information when every message drains a battery? A simulation study. The first version showed no learning because its policies were reset every episode; after the rebuild, reward rose from about -190 to about -60/-70 over 150 episodes.
- [Temporal Gap Detection](https://github.com/Arshiask07/temporal-gap-detection): can research areas that are about to grow be spotted early? Ranks topics by how concepts connect and what the papers say, then checks the predictions against later publications. Genuine citation-based ranking is a planned next step, pending API access. In progress.

Also: [Chronic Kidney Disease Early Prediction](https://github.com/Arshiask07/Early-Prediction-for-Chronic-Kidney-Disease-Detection), a group project (forked from a teammate's repository) comparing classifiers on routine lab values.

## Tools used in my repositories

Python, PyTorch, scikit-learn.

## Now

Temporal-gap-detection's graph, ranking, and a mention-based re-ranking step are built. Citation-based velocity, a more precise version of that signal, is a future step, pending institutional API access we don't currently have.

