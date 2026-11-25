### Hi, I’m Lio Einaudi 👋

I’m Jinbin Zhao, based in Beijing. I’m currently an **Inference Systems Research Intern at NIO** and contribute to [vLLM](https://github.com/vllm-project/vllm).

#### Open source

- **vLLM · Tensor parallelism ([PR #58495](https://github.com/vllm-project/vllm/pull/58495)):** Tuned batch-invariant matmul for per-GPU matrix shapes at TP=2, 4, and 8. In a decode-heavy Qwen3-8B benchmark on two RTX PRO 6000 Blackwell GPUs, this cut end-to-end latency by **55.7%** (3.00 s → 1.33 s).
- **vLLM · CUDA graphs ([PR #57586](https://github.com/vllm-project/vllm/pull/57586)):** Updated CUDA graph handling in batch-invariant mode so the engine selects a tuned matmul configuration for the actual token count at runtime.

#### Experience

- **NIO** — AI Infra / Inference Systems Research Intern *(Current)*
- **Dexmal** — AI Infra Intern

[Blog](https://lioeinaudi.github.io/) · [Email](mailto:Jinbin.Zhao.Dev@gmail.com)
