# Inference vs. Training
 
Training is the process of learning model weights from data. Inference is serving those weights in production to generate outputs. Training runs are compute-intensive batch jobs; inference is a continuous, latency-sensitive service. Where training success is measured in loss curves, inference success is measured in time to first token, tokens per second, and uptime.