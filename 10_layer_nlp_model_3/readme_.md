## 10_layer_nlp_model_3
__num_layers = 10 layer__
__layers : Transformer , Conv1D(kernel_sizes=3,5) , Linear_Layers(MLP)__
__Model_Architecture : Conv1D(#2) -> TransformerLayer(#5) -> MLPBlock(#2) -> TransformerLayer(#1)__
__tokenizer : GPT2TokenizerFast.from_pretrained("gpt2")__
__requirements : pytorch_lightning , torch.utils.data(Dataset, DataLoader) , transformers(GPT2TokenizerFast) , datasets(load_dataset)__
__dataset : "ag_news"__
