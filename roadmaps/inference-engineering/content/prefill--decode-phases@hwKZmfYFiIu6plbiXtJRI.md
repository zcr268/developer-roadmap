# Prefill and Decode Phases
 
LLM inference has two distinct phases. Prefill processes the entire input sequence in parallel to build the KV cache and is compute-bound. Decode generates output tokens one at a time by reading model weights from memory and is memory-bound. Each phase has different bottlenecks and responds to different optimization techniques.