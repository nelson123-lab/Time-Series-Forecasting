- Transformers were created as upgrades to RNN to handle sequential data. RNN tends to forget the first few tokens when we have a long sequence of data.(vanishing Gradients). The self-attention mechanism in Transformers enables each token to attend to all other tokens in the sequence, including the early tokens. This attention mechanism allows the model to assign different weights to different tokens based on their relevance to each other. As a result, Transformers can effectively capture long-range dependencies and retain information from the beginning of the sequence.