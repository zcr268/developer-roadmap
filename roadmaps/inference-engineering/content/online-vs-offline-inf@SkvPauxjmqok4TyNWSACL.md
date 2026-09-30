# Online vs. Offline Inference
 
Online inference serves real-time user-facing requests where latency matters. Offline inference processes large batches of data asynchronously where throughput and cost matter more than per-request speed. The same model, like Whisper for transcription, may need separate deployments for each use case because the optimal configurations differ significantly.