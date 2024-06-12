# Lightweight Fine-Tuning to a Foundation Model using PEFT

Lightweight fine-tuning is one of the most important techniques for adapting foundation models, because it allows you to modify foundation models for your needs without needing substantial computational resources.
In this project, I am applying parameter-efficient fine-tuning using the Hugging Face peft library. Hugging Face PEFT allows you to fine-tune a model without having to fine-tune all of its parameters

* PEFT technique: [LoRA](https://huggingface.co/docs/peft/en/package_reference/lora)
* Model: [AutoModelForSequenceClassification](https://huggingface.co/transformers/v3.0.2/model_doc/auto.html#automodelforsequenceclassification)
* Evaluation approach: Accuracy
* Fine-tuning dataset: [ag_news](https://huggingface.co/datasets/fancyzhx/ag_news)

## Dataset Used:
AG is a collection of more than 1 million news articles. News articles have been gathered from more than 2000 news sources by ComeToMyHead in more than 1 year of activity. [https://huggingface.co/datasets/fancyzhx/ag_news](https://huggingface.co/datasets/fancyzhx/ag_news)

## Libraries Used:
* transformers==4.36.0
* torch==2.0.1
* datasets==2.18.0
* numpy==1.26.4
* pandas==2.2.1
* peft==0.5.0
* matplotlib==3.8.3


## Files in the Repo:
* LightweightFineTuning.ipynb: This file contains all the code and required documentation to understand the process.

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Udacity in providing the required resources to train and test the model. You can checkout their program: [Generative AI nanodegree](https://www.udacity.com/enrollment/nd608). Feel free to use the code here as you would like! 