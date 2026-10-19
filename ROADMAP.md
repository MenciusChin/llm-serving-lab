# Roadmap

- [ ] Minimal autoregressive inference server
- [ ] Streaming responses
- [ ] Async request queue
- [ ] KV-cache instrumentation
- [ ] Static batching
- [ ] Continuous batching
- [ ] Scheduling and cancellation
- [ ] Prefix caching
- [ ] Overload protection / load shedding
- [ ] Multi-GPU serving
- [ ] Compare against vLLM
- [ ] Ray Serve deployment
- [ ] Benchmark TTFT, TPOT, throughput, p50/p95 latency, and GPU utilization

## Questions

- Why does continuous batching improve throughput?
- How does sequence length change KV-cache pressure?
- Which scheduling policy gives the best latency/throughput tradeoff?
- When does prefix caching materially help?
- Where does the bottleneck move as concurrency increases?
