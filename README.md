# Multi-dialect-Arabic-BERT
This is a repository of Multi-dialect Arabic BERT model.

### About our Multi-dialect-Arabic-BERT model
Instead of training the Multi-dialect Arabic BERT model from scratch, we initialized the weights of the model using [Arabic-BERT](https://github.com/alisafaya/Arabic-BERT) and trained it on 10M arabic tweets from the unlabled data of [The Nuanced Arabic Dialect Identification (NADI) shared task](https://sites.google.com/view/nadi-shared-task).

### Model Parameters
| Parameter | Value |
| ------------- | ------------- |
| architecture  | BertForMaskedLM  |
| hidden_size  | 768  |
| max_position_embeddings  | 512  |
| num_attention_heads  | 12  |
| num_hidden_layers  | 12  |
| vocab_size  | 32000  |
| hidden_size  | 768  |

##### Total number of parameters = 110M 


