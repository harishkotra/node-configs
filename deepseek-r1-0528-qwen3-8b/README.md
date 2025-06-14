# A DeepSeek-R1-0528-Qwen3-8B node

**Step 1:** Install Gaia node

```
curl -sSfL 'https://github.com/GaiaNet-AI/gaianet-node/releases/latest/download/install.sh' | bash
```

**Step 2:** Init with the DeepSeek-R1-0528-Qwen3-8B model

```
gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/deepseek-r1-0528-qwen3-8b/config.json
```


**Step 3:** Start the node

```
gaianet start
```

Now you can [use the node](https://docs.gaianet.ai/user-guide/mynode) as a web-based chatbot or as an OpenAI API drop-in replacement.

## References

* [Official PyTorch model](https://huggingface.co/deepseek-ai/DeepSeek-R1-0528-Qwen3-8B)
* [GGUF formatted model](https://huggingface.co/gaianet/DeepSeek-R1-0528-Qwen3-8B-GGUF)
* [GaiaNet node quick start guide](https://docs.gaianet.ai/node-guide/quick-start)
