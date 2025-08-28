## 10_layer_nlp_model_3

num_layers = 10 layer

▶️ __layers :__ 

Transformer , Conv1D(kernel_sizes=3,5) , Linear_Layers(MLP)

▶️ __Model_Architecture :__ 

Conv1D(×2) -> TransformerLayer(×5) -> MLPBlock(×2) -> TransformerLayer(×1)

▶️ __tokenizer :__ 

GPT2TokenizerFast.from_pretrained("gpt2")

▶️ __requirements :__

pytorch_lightning , torch.utils.data(Dataset, DataLoader) , transformers(GPT2TokenizerFast) , datasets(load_dataset)

▶️ __dataset :__ "ag_news"

__توجه داشته باشید که این دیتاست برای طبقه بندی متن است ولی ما از text های این دیتاست برای تولید متن استفاده کردیم، یعنی کاری به دسته ها و label ها نداشتیم.__
