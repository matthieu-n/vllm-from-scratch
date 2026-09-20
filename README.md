# vllm-from-scratch

Learning project: re-implement vLLM from scratch — paged KV cache, continuous
batching, attention kernels, speculative decoding — on a single GPU.

## Environment
- RayLab `matthieu-neau-vllm-from-scratch` (us1.staging.dog / venomoth, project `aip-practice`)
- 1× NVIDIA RTX PRO 6000 Blackwell (96 GB) worker (autoscaled, on demand)
- Staging pods have github.com + pypi.org egress

## Layout (planned)
- `notes/` — learning notes per milestone
- `src/` — the implementation
- `bench/` — micro-benchmarks
