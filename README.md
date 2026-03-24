# Awesome Local AI

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/Turbo31150/awesome-local-ai/issues)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> A curated list of tools, frameworks, and resources for running AI locally — no cloud needed.

Running AI on your own hardware gives you **privacy**, **speed**, **zero API costs**, and **full control**. This list covers everything from LLM inference engines to GPU management, voice processing, and orchestration.

---

## Contents

- [LLM Inference Engines](#llm-inference-engines)
- [Model Context Protocol (MCP)](#model-context-protocol-mcp)
- [Agent Frameworks](#agent-frameworks)
- [Voice & Speech](#voice--speech)
- [GPU Management](#gpu-management)
- [Orchestration](#orchestration)
- [Models (Open Source)](#models-open-source)
- [Contributing](#contributing)

---

## LLM Inference Engines

| Tool | Description |
|------|-------------|
| [Ollama](https://github.com/ollama/ollama) | Run LLMs locally with a single command. Supports GGUF, pulls models like Docker images. |
| [LM Studio](https://lmstudio.ai/) | Desktop GUI for discovering, downloading, and running local LLMs. OpenAI-compatible API. |
| [llama.cpp](https://github.com/ggerganov/llama.cpp) | High-performance C/C++ inference for LLMs. CPU & GPU support, quantization, GGUF format. |
| [vLLM](https://github.com/vllm-project/vllm) | High-throughput LLM serving engine with PagedAttention for efficient memory management. |
| [LocalAI](https://github.com/mudler/LocalAI) | Drop-in OpenAI-compatible REST API that runs locally. Supports LLMs, image gen, audio. |
| [koboldcpp](https://github.com/LostRuins/koboldcpp) | Easy-to-use llama.cpp wrapper with built-in web UI and API. |
| [MLC LLM](https://github.com/mlc-ai/mlc-llm) | Universal deployment of LLMs on any hardware — phone, laptop, server. |
| [GPT4All](https://github.com/nomic-ai/gpt4all) | Run open-source LLMs on consumer hardware. Desktop app + Python bindings. |

## Model Context Protocol (MCP)

| Tool | Description |
|------|-------------|
| [MCP Specification](https://github.com/modelcontextprotocol/specification) | The open protocol standard for connecting AI assistants to external data and tools. |
| [MCP Python SDK](https://github.com/modelcontextprotocol/python-sdk) | Official Python SDK for building MCP servers and clients. |
| [MCP TypeScript SDK](https://github.com/modelcontextprotocol/typescript-sdk) | Official TypeScript SDK for building MCP servers and clients. |
| [MCP Servers](https://github.com/modelcontextprotocol/servers) | Collection of reference MCP server implementations (filesystem, GitHub, Slack, etc.). |

## Agent Frameworks

| Tool | Description |
|------|-------------|
| [Claude Agent SDK](https://github.com/anthropics/claude-code) | Anthropic's official SDK for building AI agents with Claude. |
| [LangChain](https://github.com/langchain-ai/langchain) | Framework for building applications powered by LLMs — chains, agents, RAG. |
| [LangGraph](https://github.com/langchain-ai/langgraph) | Framework for building stateful, multi-actor LLM applications as graphs. |
| [CrewAI](https://github.com/crewAIInc/crewAI) | Framework for orchestrating autonomous AI agents working together. |
| [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) | Autonomous AI agent that chains LLM calls to accomplish complex tasks. |
| [OpenDevin](https://github.com/OpenDevin/OpenDevin) | Open-source autonomous AI software engineer. |
| [Aider](https://github.com/paul-gauthier/aider) | AI pair programming in your terminal — edits code in your local git repo. |

## Voice & Speech

| Tool | Description |
|------|-------------|
| [Whisper](https://github.com/openai/whisper) | OpenAI's robust speech-to-text model. Runs fully offline, multi-language support. |
| [Faster Whisper](https://github.com/SYSTRAN/faster-whisper) | CTranslate2-based reimplementation of Whisper — up to 4x faster with lower memory. |
| [Edge TTS](https://github.com/rhasspy/edge-tts) | Python module using Microsoft Edge's online TTS service. |
| [Piper TTS](https://github.com/rhasspy/piper) | Fast, local neural text-to-speech. Optimized for Raspberry Pi and edge devices. |
| [Coqui TTS](https://github.com/coqui-ai/TTS) | Deep learning toolkit for text-to-speech. Voice cloning, multi-language. |
| [Vosk](https://github.com/alphacep/vosk-api) | Offline speech recognition API supporting 20+ languages. Lightweight and fast. |

## GPU Management

| Tool | Description |
|------|-------------|
| [nvidia-smi](https://developer.nvidia.com/nvidia-system-management-interface) | NVIDIA's CLI tool for monitoring and managing GPU devices. |
| [nvtop](https://github.com/Syllo/nvtop) | Interactive GPU process monitor — htop for GPUs (NVIDIA, AMD, Intel). |
| [gpustat](https://github.com/wookayin/gpustat) | Simple CLI utility for querying GPU status with minimal overhead. |
| [NVIDIA DCGM](https://developer.nvidia.com/dcgm) | Data Center GPU Manager for cluster-level GPU monitoring and diagnostics. |
| [ROCm](https://github.com/ROCm/ROCm) | AMD's open-source platform for GPU computing. |

## Orchestration

| Tool | Description |
|------|-------------|
| [n8n](https://github.com/n8n-io/n8n) | Fair-code workflow automation tool. 400+ integrations, self-hostable, AI-native workflows. |
| [Docker](https://github.com/docker/docker-ce) | Containerization platform — essential for packaging and deploying AI services. |
| [Docker Compose](https://github.com/docker/compose) | Define and run multi-container applications for local AI stacks. |
| [Dify](https://github.com/langgenius/dify) | Open-source LLM app development platform — RAG, agents, workflows. |
| [Open WebUI](https://github.com/open-webui/open-webui) | Self-hosted web UI for LLMs. Supports Ollama and OpenAI-compatible APIs. |

## Models (Open Source)

| Model Family | Description |
|-------------|-------------|
| [Qwen](https://github.com/QwenLM/Qwen) | Alibaba's series of large language models. Strong multilingual and coding performance. |
| [DeepSeek](https://github.com/deepseek-ai/DeepSeek-V3) | High-performance open models with strong reasoning capabilities. |
| [Mistral](https://github.com/mistralai/mistral-inference) | Efficient open models from Mistral AI. Excellent performance-to-size ratio. |
| [LLaMA](https://github.com/meta-llama/llama) | Meta's family of open-weight LLMs. Foundation for many fine-tuned variants. |
| [Gemma](https://github.com/google/gemma_pytorch) | Google's lightweight open models built from Gemini research. |
| [Phi](https://huggingface.co/microsoft/phi-3-mini-4k-instruct) | Microsoft's small language models with strong reasoning for their size. |
| [StarCoder](https://github.com/bigcode-project/starcoder) | Open-access code LLMs trained on permissively licensed data. |

---

## Contributing

Contributions are welcome! Please read the [contribution guidelines](CONTRIBUTING.md) before submitting a pull request.

If you know of a great local AI tool not listed here, [open an issue](https://github.com/Turbo31150/awesome-local-ai/issues/new) or submit a PR.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under [MIT License](LICENSE).
