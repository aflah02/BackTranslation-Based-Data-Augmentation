# BackTranslation-Based-Data-Augmentation

The demo notebook uses the **Stanford Sentiment Treebank v2 (SST2)** present [here](https://github.com/clairett/pytorch-sentiment-classification/tree/master/data/SST2)

The methodology is simply to translate the sentence into a pivot language and the use that translated sentence to come back to the original language. This ensure the content is preserved while the framing and words used might differ essentially giving us a new data point with the same label

To learn more about Backtranslation you can check out this [blog post](https://towardsdatascience.com/data-augmentation-in-nlp-2801a34dfc28)

**Q- How can I run this?**

A - Just open the .ipynb file, click on the "open in colab" button located at the start of the notebook and run all cells (everything else is already handled)

References - 

- [How to use "translators" for comments translation by Welf Crozzo](https://www.kaggle.com/miklgr500/how-to-use-translators-for-comments-translation)
