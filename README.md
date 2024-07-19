 
1. install

```bash
pip install "xinference[all]"
````

2. download model
```bash
xinference launch --model-engine  Transformers  --model-name qwen1.5-moe-chat --size-in-billions 2_7 --model-format pytorch --quantization 8-bit
```
