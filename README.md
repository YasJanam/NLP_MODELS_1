# NLP_MODELS_1
## FOLDERS


| num_Folder |dependent on the code| name | Model-Type | توضیحات | 
|:-----:|:--:|:------------------------:|:-----:|:---------------------------------------------------------:|
| 14 | 9 | Labratory_14 | BART |  generate ارزیابی مدل حاصل از لابراتوری 13 و تعریف متد  |
| 13 | 9 | Labratory_13 | BART | بررسی عملکرد مدل کد 9 با پیش آموزش و اموزش دوباره مدل لابراتوری 12 |
| 12 | 9 | Labratory_12 | BART | بررسی عملکرد مدل کد 9 با پیش آموزش با متدهای فایل 11 |
| 11 | 9 | Pretrain_Methods_11 | - | معرفی متدهای پیش آموزش و استفاده از آنها در کد 12 |
| 10 | 9 | Labratory_10 | BART | بررسی عملکرد مدل کد 9 با یک سری تغییرات |
| 9 | - | miniBART_sumarization_9 | BART | پیاده سازی یک مدل مینی بارت 3×3 برای خلاصه سازی |
| 8 | - | Conv1D_vs_Transformer_8 | - | مقایسه داده های خروجی ترنسفورمر با کانولوشن یک بعدی و بدون کانولوشن یک بعدی |
| 7 | 3 | Labratory_7  | - | بررسی عملکرد مدل کد 3 |
| 6 | 3 | Labratory_6  | - | بررسی عملکرد مدل کد 3 |
| 5 | 3 | Labratory_5           | - | بررسی عملکرد مدل کد 3 |
| 4 | 3 | Labratory_4           | - | بررسی عملکرد مدل کد 3 |
| 3 | - | 10_layer_nlp_model_3           | - | مدل زبانی 10 لایه |
| 2 | - | 6_layer_nlp_model_2           | - | مدل زبانی 6 لایه |
| 1 | - | 6_Layer_nlp_model_1 | - | مدل زبانی 6 لایه  |

---
### Folder 9 : miniBART_sumarization_9
پیاده سازی یک مدل مینی بارت 3×3 برای خلاصه سازی 

---
### Folder 8 : Conv1D_vs_Transformer_8
بررسی عملکرد کانولوشن روی داده های خروجی ترنسفورمر

---
### Folder 7 : Labratory_7

تغییر بلاک های استفاده شده در معماری مدل فولدر 3 و بررسی نتایج حاصل از تغییر بلاک ها در train های مختلف با epoch = 2

---
### Folder 6 : Labratory_6
بررسی عملکر مدل کد 3 با تغییر لایه ها و تغییر دیتاست ( wikitext-2 )


مدل اصلی این کد همان مدل کد 3 است

main-model : 10_layer_nlp_model_3  

---
### Folder 5 : Labratory_5
بررسی عملکرد مدل کد 3 با تغییر لایه ها و افزایش train_size به 30000 


مدل اصلی این کد همان مدل کد 3 است

main-model : 10_layer_nlp_model_3   

---
### Folder 4 : Labratory_4
بررسی عملکر مدل کد 3 با تغییر لایه ها و تغییر اندازه دیتای آموزش 

مدل پایه این آزمایش ,همان مدل کد 3 است

main-model : 10_layer_nlp_model_3

---
### Folder 3 : 10_layer_nlp_model_3

__requirements :__
pytorch_lightning, Dataset, DataLoader, GPT2TokenizerFast, load_dataset

__10 Layers :__ 
Transformer-Layers , Conv1D(kernel_sizes=3,5) , MLP (Linear-Layers)

__Dataset :__ "ag_news"

__Tokenizer :__ GPT2TokenizerFast

---
### Folder 2 : 6_layer_nlp_model_2

requirements : Dataset, DataLoader, torch, dataclass, argparse

6 Layers : Transformer-Layers

Dataset : a small text

Tokenizer : char-level tokenizer

---
### Folder 1 : 6_Layer_nlp_model_1  

requirements : torch

6 Layers : Transformer-Layers

Dataset : a small text ( 3 lines )

Tokenizer : char-level tokenizer
