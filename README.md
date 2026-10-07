## Hi, I'm Israt Zaman Srity

CSE undergraduate at North South University, Dhaka. I work on machine learning and NLP, and I care most about honest evaluation: checking whether a model is as good as its numbers say.

### Featured work

**[Bank Marketing: one column that fakes the results](https://github.com/Israt24hub/bank-marketing-leakage)** · CSE445 group project, team of 4

Predicting term-deposit subscriptions on the UCI Bank Marketing dataset with four approaches: classical ML, tabular foundation models (iLTM, TabPFN v2), fine-tuned transformers (DistilBERT, RoBERTa) and LLM prompting (Phi-3-mini). Main finding: the `duration` column leaks the outcome and inflates ROC-AUC by about 0.14 in every pipeline that keeps it. With a time-based split (train 2008–2009, test 2010), ROC-AUC falls to 0.65. Written up as an IEEE-format paper.
*My role:* one of the two main contributors. I built the classical ML baselines, fine-tuned DistilBERT and RoBERTa, ran the iLTM, TabPFN v2 and Phi-3-mini experiments, and wrote the paper.

**[LeakGuard](https://github.com/Israt24hub/leakguard)** · Python library

Finds data leakage in tabular datasets: columns that predict the target suspiciously well, columns the whole model depends on (drop-column test), identifiers, duplicates, train/test overlap, and scores that collapse on a past-to-future split. Command-line tool with CI-friendly exit codes, tested on Python 3.10–3.13.

**[The Column That Fooled Every Model](https://israt24hub.github.io/data-leakage-explained/)** · interactive explainer · [code](https://github.com/Israt24hub/data-leakage-explained)

A web page where you switch columns on and off and a model trained in your browser shows how one leaky column inflates its score. Logistic regression, ROC curves and the synthetic data are all written from scratch in JavaScript.

**[Chime Gate](https://israt24hub.github.io/chime-gate/)** · creative coding · [code](https://github.com/Israt24hub/chime-gate)

A curtain of verses hanging in a temple doorway that parts under your cursor and rings like wind chimes. Rope physics (Verlet integration with follow-the-leader constraints) drawn on canvas, sounds synthesised with the Web Audio API, no libraries.

### Tools

**ML:** Python · pandas · scikit-learn · PyTorch · Hugging Face Transformers · Google Colab
**Programming:** C / C++ · Java · JavaScript · Git
**Writing:** LaTeX / Overleaf

### Contact

[LinkedIn](https://www.linkedin.com/in/israt-zaman-srity-286975370)
