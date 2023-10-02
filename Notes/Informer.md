# Informer

The Informer model tackles the vanilla Transformer computational complexity challenges for long-horizon forecasting. 
The architecture has three distinctive features:
1) A ProbSparse self-attention mechanism with an O time and memory complexity Llog(L).
2) A self-attention distilling process that prioritizes attention and efficiently handles long input sequences.
3) An MLP multi-step decoder that predicts long time-series sequences in a single forward operation rather than step-by-step.

- We can only pass the input and target variables together to the informer model and it considers the last column as the target column.
