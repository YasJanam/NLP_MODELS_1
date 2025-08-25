# NLP_MODELS
## PROJECTS
### code 4 : Labratory_4
بررسی عملکر مدل کد 3 با معماری های مختلف و تغییر اندازه دیتای آموزش 

مدل پایه این آزمایش ,همان مدل کد 3 است

main-model : 10_layer_nlp_model_3
### code 3 : 10_layer_nlp_model_3

requirements : pytorch_lightning, Dataset, DataLoader, GPT2TokenizerFast, load_dataset

10 Layers : Transformer-Layers , Conv1D(kernel_sizes=3,5) , MLP (Linear-Layers)

Dataset : "ag_news"

Tokenizer : GPT2TokenizerFast
### code 2 (text-generation) : 6_layer_nlp_model_2

requirements : Dataset, DataLoader, torch, dataclass, argparse

6 Layers : Transformer-Layers

Dataset : a small text

Tokenizer : char-level tokenizer
### code 1 (text-generation) : 6_Layer_nlp_model_1  

requirements : torch

6 Layers : Transformer-Layers

Dataset : a small text ( 3 lines )

Tokenizer : char-level tokenizer
