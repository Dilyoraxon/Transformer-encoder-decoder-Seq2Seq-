# Transformer-encoder-decoder-Seq2Seq-
A small Transformer encoder-decoder (Seq2Seq) in PyTorch that translates short English sentences into Uzbek. 2 encoder + 2 decoder layers, 2 heads, C=64. Trained on 2,000 synthetic, template-based sentence pairs with AdamW and teacher forcing; greedy decoding. 100% accuracy on the test set, but only within its trained sentence patterns.
