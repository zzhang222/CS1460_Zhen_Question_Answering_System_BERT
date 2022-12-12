# CS1460_Zhen_Question_Answering_System_BERT
A simple Pytorch implementation of [Bert for QA system](https://arxiv.org/pdf/1901.08634.pdf).
I finetuned the pretrained model [distilbert-base-uncased-distilled-squad](https://huggingface.co/distilbert-base-uncased-distilled-squad) on the provided training dataset (train.json) and evaluate its performance on the validation dataset (dev.json). The result are reported as follows:

PRECISION:  0.5619464065478192
RECALL:  0.6379025073183149
F1-SCORE:  0.5975202670481641
