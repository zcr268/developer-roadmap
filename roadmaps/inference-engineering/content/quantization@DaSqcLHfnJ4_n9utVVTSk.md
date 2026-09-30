# Quantization
 
Quantization converts model weights and other values from their native precision to a lower-precision format. Cutting precision in half doubles memory bandwidth for decode and enables twice the FLOPS for prefill on compatible Tensor Cores. The tradeoff is potential quality loss from reduced numerical precision, which can compound across the many calculations in a forward pass.