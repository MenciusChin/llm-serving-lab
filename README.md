# LLM Serving Lab

Hands-on experiments for understanding the systems behind modern LLM inference.

Rather than treating serving frameworks as black boxes, this repo will progressively implement and benchmark the components that drive latency and throughput.

## Learning path

```text
Autoregressive inference
      ↓
KV cache
      ↓
Static batching
      ↓
Continuous batching
      ↓
Scheduling / cancellation
      ↓
Prefix caching
      ↓
Multi-GPU serving
      ↓
vLLM / Ray Serve comparisons
```

## Core metrics

- TTFT — time to first token
- TPOT — time per output token
- requests / second
- tokens / second
- p50 / p95 latency
- GPU memory and utilization

See [ROADMAP.md](ROADMAP.md).

## Status

**Planned.** Active implementation starts after the first milestones in `generative-recsys`.
