---
layout: page
title: Datasets
---

### Download

[Typo Dataset (Parallel Format)](https://1drv.ms/u/s!AAU3jG1nh6NXlgY)  
[Typo Dataset (CSV with Metadata)](https://1drv.ms/u/s!AAU3jG1nh6NXlgc)

### About
This resource contains two different datasets with three levels of error generation for each. The two datasets are Amazon Fine Food Review and Large Movie Review datasets. The original datasets are cleaned for typographical errors before introducing artificial errors.

Here is the structure of the resource

  1. Two datasets amazon and imdb. 
  2. For each dataset, three subdirectories for 3 level of error generation. This levels are low, medium and high which corresponds to 3.75%, 7.5% and 15% error rate by character. 
  3. Each error level contains subdirectories for train and test sets. Each subdirectory contains. 
    3.1. clean.txt contains the clean text without errors.  
    3.2. corrupt.txt contains text with error induced by our algorithm.  
    3.3. corrected_v1.txt contains variant 1 of text corrected with Enchant spell check. Variant 1 is correction by top suggestion.  
    3.4. corrected_v2.txt contains variant 2 of text corrected with Enchant spell check. Variant 2 is correction by top suggestion which is not equal to actual word.  
    

All the files are in parallel format.

The same dataset is also available in CSV format. The CSV dataset contains the similar structure, with parallel files being the columns with same name in a CSV file. It also contains metadata like word count and out-of-vocabulary words.

*Links to original datasets*: 
[Amazon Fine Food Review](https://www.kaggle.com/snap/amazon-fine-food-reviews), 
[Large Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)

