# Sequence Classification with Transformers
Sample code and data to fine-tune commonly used transformer-based NLP models for sequence classification tasks. The code and data constitute essential elements of the approach I adopt for detecting self-attribution bias among mutual fund managers as described in Wang (2023). My paper can be found at https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4553526.

1. "sample_data.xlsx":
   this file contains a sample of well-labeled sentences indicating whether the sentence is about a performance contributor or a performance detractor.
2. "sequence_classification.ipynb":
   this Jupyter notebook illustrates the steps of training transformers. I use three models as examples: BERT, RoBERTa, GPT-2, and GPT-3. BERT, RoBERTa, and GPT-2 are open-sourced and provided by Hugging Face. You need an OpenAI API to access GPT-3. Note: The code is written on Google Colab

   
