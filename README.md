# agnews_slm_classification
Use a Small Language Model (SLM) for a classification task

## Conclusion
We can notice that fine-tuning is neccessary for a good classification:

- F1-score = 0.91 when the model is fine-tune vs 0.15 when not
- With a prompt, the F1-score at the first epoch is higher (0.86 vs 0.84) but the result still close so it's difficult to conclude if a good prompting could lead to a better classification
- Looking at the training loss, we can notice a better convergence with a prompt
