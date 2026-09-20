# Lab environment (verified 2026-09-20)

- RayLab `matthieu-neau-vllm-from-scratch` — us1.staging.dog (venomoth), project aip-practice
- GPU worker: 1x NVIDIA RTX PRO 6000 Blackwell 96GB (autoscaled, spins up on GPU work)
- Head node code checkout: `~/code` (branch main, remote origin = GitHub)
- Git on this pod is configured to bypass the pod egress proxy for github.com and uses a stored credential
- Verified: git fetch + git push to github.com from this pod
