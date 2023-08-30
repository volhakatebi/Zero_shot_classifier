# Using Zero-Shot Model for Text Classification

* This code shows how to use zero-shot classifier as a quick-and-easy way to assign labels of intest to the data
* This classifier treats text classification task as a text entailment problem. More information on zero-shot classfier can be found in [Yin et al., 2019.](https://arxiv.org/abs/1909.00161)
* [facebook/bart-large-mnli model](https://huggingface.co/facebook/bart-large-mnli) is used on 200 tweets about disaster from [Kaggle](https://www.kaggle.com/competitions/nlp-getting-started/data)
* These tweets have been already labeled and thus can serve as a comparison point for us to evaluate zero-shot model performance on unseen data
* The model is used to assign 2 labels simultaneously: whether the document is about disaster and whether it is about forrest
