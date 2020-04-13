---
layout: page
title: Datasets
---

### Download

Parallel Dataset: (Coming Soon)

CSV Dataset (with Metadata): (Coming Soon)

### About
This resource contains two different datasets with three levels of error generation for each. The two datasets are Amazon Fine Food Review and Large Movie Review datasets. The original datasets are cleaned for typographical errors before introducing artificial errors.

Here is the structure of the proposed resource

Each directory contains following contents
  1. clean.txt contains the clean text without errors
  2. Three subdirectories for 3 level of error generation. This levels low, medium and high corresponds to 3.75%, 7.5% and 15% error rate by character
  3. Each error level contains subdirectories for train and test sets
  Each subdirectory contains
    a. corrupt.txt contains text with error induced by our algorithm
    b. spell_check_v1.txt contains variant 1 of text corrected with Enchant spell check. Variant 1 is correction by top suggestion.
    c. spell_check_v1.txt contains variant 2 of text corrected with Enchant spell check. Variant 2 is correction by top suggestion which is not equal to actual word.

All the files are in parallel format.
The same dataset is also available in CSV format.

*Links to original datasets*: 
[Amazon Fine Food Review](https://www.kaggle.com/snap/amazon-fine-food-reviews), 
[Large Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)

