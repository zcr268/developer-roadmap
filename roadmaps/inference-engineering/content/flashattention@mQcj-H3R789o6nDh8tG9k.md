# FlashAttention
 
FlashAttention is a series of hand-optimized CUDA kernels that compute attention with fewer reads and writes to GPU memory by fusing the attention algorithm into a single kernel. Standard attention stores intermediate matrices to memory between steps; FlashAttention eliminates those round-trips. FlashAttention 3 targets Hopper GPUs and FlashAttention 4 targets Blackwell GPUs.