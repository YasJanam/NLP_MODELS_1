## 10_layer_nlp_model_3

num_layers = 10 layer

layers : Transformer , Conv1D(kernel_sizes=3,5) , Linear_Layers(MLP)

Model_Architecture : Conv1D(#2) -> TransformerLayer(#5) -> MLPBlock(#2) -> TransformerLayer(#1)

tokenizer : GPT2TokenizerFast.from_pretrained("gpt2")

requirements : pytorch_lightning , torch.utils.data(Dataset, DataLoader) , transformers(GPT2TokenizerFast) , datasets(load_dataset)

dataset : "ag_news"

__توجه داشته باشید که این دیتاست برای طبقه بندی متن است ولی ما از text های این دیتاست برای تولید متن استفاده کردیم، یعنی کاری به دسته ها و label ها نداشتیم.__
