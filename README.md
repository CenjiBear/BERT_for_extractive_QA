# BERT_for_extractive_QA
Depository for Math Winter 2023 group project


Team Members:
Sean Tran - 101449600
Mohammed Mujtaba Rabbani - 101387404


The Hugging Face models are powerful tools for extractive Q&A tasks and can handle straightforward questions and lengthy texts with ease. However, they can still produce incorrect answers with high confidence, which suggests that they may require further fine-tuning or modifications to improve their accuracy.

The customized BERT model that we fine-tuned using a semi-custom dataset was able to outperform the Hugging Face models in terms of accuracy, especially when dealing with questions that required information from longer texts. This suggests that fine-tuning a pre-trained model using a customized dataset can significantly improve its performance.

However, our customized BERT model received low probability scores, which could be due to the limited size of our dataset or the short training time. Therefore, to improve the performance of the customized model, we may need to increase the size of our dataset or increase the training time.

Overall, our evaluation highlights the importance of carefully selecting and fine-tuning models for specific Q&A tasks. While pre-trained models can be effective, they may not always be suitable for every scenario, and customized models may be necessary to achieve optimal performance.
