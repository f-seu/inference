 
1. install

```bash
pip install "xinference[transformers]"
pip install sentence-transformers
```

2. start

```bash
xinference-local --host 0.0.0.0 --port 9997
```

3. download model
```bash
xinference launch --model-engine  Transformers  --model-name qwen1.5-moe-chat --size-in-billions 2_7 --model-format pytorch --quantization 8-bit
```
