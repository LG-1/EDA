# EDA
These are the Easiest Data Augmentation Techniques.

## how to use
```python
from EDA import EDA
test_sentence = 'GitHub is home to over 31 million developers working together to host ' \
                    'and review code, manage projects, and build software together.'
augment_sentence = EDA(test_sentence, 1).eda(num_aug=3)
print(augment_sentence)
    
    [['github is home to over million developers software manage to host and review code together projects and build working together', 1], 
    ['software system github is home to over million developers working together to host and review inspection code manage projects and build software together', 1], 
    ['github is over million developers workingtogether host and review code manage projects and build together', 1]]

```
 

# reference
[These are the Easiest Data Augmentation Techniques in Natural Language Processing you can think of — and they work.](https://towardsdatascience.com/these-are-the-easiest-data-augmentation-techniques-in-natural-language-processing-you-can-think-of-88e393fd610)
