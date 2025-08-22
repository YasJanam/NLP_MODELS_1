## 10_layer_nlp_model_3

project : Text_Classification

num_layers = 10 layer

layers : Transformer , Conv1D(kernel_sizes=3,5) , Linear_Layers(MLP)

Model_Architecture : Conv1D(#2) -> TransformerLayer(#5) -> MLPBlock(#2) -> TransformerLayer(#1)

tokenizer : GPT2TokenizerFast.from_pretrained("gpt2")

requirements : pytorch_lightning , torch.utils.data(Dataset, DataLoader) , transformers(GPT2TokenizerFast) , datasets(load_dataset)

dataset : "ag_news"
