## Installation guide

```bash
python3 -m venv .venv
souce .venv/bin/activate
pip install ".[sglang,gpu]"
pip install megatron-core==0.11
pip install wheel
pip install --no-build-isolation "transformer-engine[torch]==2.2.0"
```

## e2e 测试

```
bash examples/grpo_trainer/run_qwen2-7b_sgl_megatron.sh
```
