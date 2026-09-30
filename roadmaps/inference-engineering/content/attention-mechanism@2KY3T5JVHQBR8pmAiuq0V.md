# Attention Mechanism
 
Attention is the mechanism transformers use to relate each token to all previous tokens via query, key, and value projections. During decode, each new token attends to every prior token, and the KV cache stores precomputed keys and values to avoid recomputation. Attention is the most expensive and most heavily optimized operation in LLM inference.