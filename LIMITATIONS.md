# Limitations

- This is an educational learning artifact, not medical research or clinical software.
- The original preprocessing fitted transformations before the train/test split, creating data-leakage risk.
- Category encoding was also fitted before the split.
- One experiment treated encoded severity labels as regression values and rounded predictions; that is not a reliable default classification design.
- The original ROC visualisation used hard predictions rather than class probabilities.
- Original results have not been reproduced from a controlled, documented environment.
