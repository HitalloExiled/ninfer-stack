# ninfer-stack

Simplified `ninfer-serve` launcher for RTX 4090 (sm_89) via Docker.

- `serve.sh` — profiles c1/c8/vision/balanced/max/ultra, VRAM pre-flight gate, v1/v2 magic check
- `switch.sh` — stop the running server, start another profile
- `download-qwen38.sh`, `download-qwen36-35b-vision.sh` — resumable HF fetches with SHA gate
- `models/` — local `.ninfer` artifacts (git-ignored)

Run `./check.sh` to validate.
