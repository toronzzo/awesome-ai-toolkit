<div align="center">

# 🧠 Build-Your-Own-AI Toolkit

**A curated list of open-source tools for building, training, and running your own AI, offline.**

![Repos](https://img.shields.io/badge/repos-29-blueviolet?style=flat) ![Offline first](https://img.shields.io/badge/offline-first-2ea44f?style=flat) ![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-M1%20Pro-black?style=flat&logo=apple) ![License: CC0-1.0](https://img.shields.io/badge/license-CC0--1.0-lightgrey?style=flat) ![Awesome](https://awesome.re/badge.svg)

</div>

I am building **Bakugan Buddy**, a talking AI companion that runs fully offline. These are the repos I use and learn from along the way. Star counts below update live.

## 📑 Contents

- [Fine-tuning and training](#fine-tuning-and-training)
- [Core model libraries](#core-model-libraries)
- [Running models locally](#running-models-locally)
- [Retrieval (RAG) and app building](#retrieval-rag-and-app-building)
- [Vector databases](#vector-databases)
- [Embeddings](#embeddings)
- [Data labeling and dataset tools](#data-labeling-and-dataset-tools)
- [Evaluation and monitoring](#evaluation-and-monitoring)
- [Chat interfaces and gateways](#chat-interfaces-and-gateways)
- [Curated lists](#curated-lists)
- [🍎 Where to start on a Mac](#-where-to-start-on-a-mac)

## 🎯 Fine-tuning and training

| Repo | What it does | Stars |
| --- | --- | --- |
| [**Unsloth**](https://github.com/unslothai/unsloth) | Fast, low-memory fine-tuning of open models. | ![Stars](https://img.shields.io/github/stars/unslothai/unsloth?style=flat) |
| [**Axolotl**](https://github.com/axolotl-ai-cloud/axolotl) | Configurable fine-tuning pipelines. | ![Stars](https://img.shields.io/github/stars/axolotl-ai-cloud/axolotl?style=flat) |
| [**LLaMA-Factory**](https://github.com/hiyouga/LlamaFactory) | A fine-tuning framework with a web UI. | ![Stars](https://img.shields.io/github/stars/hiyouga/LlamaFactory?style=flat) |
| [**TRL**](https://github.com/huggingface/trl) | Reinforcement learning and preference tuning from Hugging Face. | ![Stars](https://img.shields.io/github/stars/huggingface/trl?style=flat) |
| [**PEFT**](https://github.com/huggingface/peft) | Parameter-efficient methods like LoRA. | ![Stars](https://img.shields.io/github/stars/huggingface/peft?style=flat) |

## 🧩 Core model libraries

| Repo | What it does | Stars |
| --- | --- | --- |
| [**Transformers**](https://github.com/huggingface/transformers) | The standard library for loading and running open models. | ![Stars](https://img.shields.io/github/stars/huggingface/transformers?style=flat) |

## 💻 Running models locally

| Repo | What it does | Stars |
| --- | --- | --- |
| [**llama.cpp**](https://github.com/ggml-org/llama.cpp) | Runs models efficiently on ordinary hardware. | ![Stars](https://img.shields.io/github/stars/ggml-org/llama.cpp?style=flat) |
| [**Ollama**](https://github.com/ollama/ollama) | The easiest way to run open models locally. | ![Stars](https://img.shields.io/github/stars/ollama/ollama?style=flat) |
| [**vLLM**](https://github.com/vllm-project/vllm) | High-throughput serving for production. | ![Stars](https://img.shields.io/github/stars/vllm-project/vllm?style=flat) |

## 🔎 Retrieval (RAG) and app building

| Repo | What it does | Stars |
| --- | --- | --- |
| [**LlamaIndex**](https://github.com/run-llama/llama_index) | Data connectors and retrieval pipelines. | ![Stars](https://img.shields.io/github/stars/run-llama/llama_index?style=flat) |
| [**LangChain**](https://github.com/langchain-ai/langchain) | Chaining models, tools, and data sources. | ![Stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=flat) |
| [**Haystack**](https://github.com/deepset-ai/haystack) | Production-oriented search and RAG pipelines. | ![Stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=flat) |
| [**DSPy**](https://github.com/stanfordnlp/dspy) | Programmatically optimizes prompts and pipelines. | ![Stars](https://img.shields.io/github/stars/stanfordnlp/dspy?style=flat) |

## 🗄️ Vector databases

| Repo | What it does | Stars |
| --- | --- | --- |
| [**Chroma**](https://github.com/chroma-core/chroma) | Simple, embeddable vector store. | ![Stars](https://img.shields.io/github/stars/chroma-core/chroma?style=flat) |
| [**Qdrant**](https://github.com/qdrant/qdrant) | Fast vector search with filtering. | ![Stars](https://img.shields.io/github/stars/qdrant/qdrant?style=flat) |

## 🔢 Embeddings

| Repo | What it does | Stars |
| --- | --- | --- |
| [**Sentence-Transformers**](https://github.com/huggingface/sentence-transformers) | Text embeddings for search and retrieval. | ![Stars](https://img.shields.io/github/stars/huggingface/sentence-transformers?style=flat) |

## 🏷️ Data labeling and dataset tools

| Repo | What it does | Stars |
| --- | --- | --- |
| [**Argilla**](https://github.com/argilla-io/argilla) | Human feedback and dataset curation. | ![Stars](https://img.shields.io/github/stars/argilla-io/argilla?style=flat) |
| [**Label Studio**](https://github.com/HumanSignal/label-studio) | Labeling for text, images, and audio. | ![Stars](https://img.shields.io/github/stars/HumanSignal/label-studio?style=flat) |
| [**Datasets**](https://github.com/huggingface/datasets) | Loading and processing datasets at scale. | ![Stars](https://img.shields.io/github/stars/huggingface/datasets?style=flat) |

## 📊 Evaluation and monitoring

| Repo | What it does | Stars |
| --- | --- | --- |
| [**Ragas**](https://github.com/vibrantlabsai/ragas) | Evaluates RAG quality. | ![Stars](https://img.shields.io/github/stars/vibrantlabsai/ragas?style=flat) |
| [**Promptfoo**](https://github.com/promptfoo/promptfoo) | Tests prompts and models against your own cases. | ![Stars](https://img.shields.io/github/stars/promptfoo/promptfoo?style=flat) |
| [**MLflow**](https://github.com/mlflow/mlflow) | Tracks experiments and model versions. | ![Stars](https://img.shields.io/github/stars/mlflow/mlflow?style=flat) |

## 💬 Chat interfaces and gateways

| Repo | What it does | Stars |
| --- | --- | --- |
| [**Open WebUI**](https://github.com/open-webui/open-webui) | A self-hosted chat interface for local and API models. | ![Stars](https://img.shields.io/github/stars/open-webui/open-webui?style=flat) |
| [**LiteLLM**](https://github.com/BerriAI/litellm) | One API that works across many model providers. | ![Stars](https://img.shields.io/github/stars/BerriAI/litellm?style=flat) |

## 📚 Curated lists

| Repo | What it does | Stars |
| --- | --- | --- |
| [**Awesome-LLM**](https://github.com/Hannibal046/Awesome-LLM) | Papers, models, and tools across the LLM world. | ![Stars](https://img.shields.io/github/stars/Hannibal046/Awesome-LLM?style=flat) |
| [**Awesome Machine Learning**](https://github.com/josephmisiti/awesome-machine-learning) | ML frameworks and libraries, sorted by language. | ![Stars](https://img.shields.io/github/stars/josephmisiti/awesome-machine-learning?style=flat) |
| [**Awesome LLM Apps**](https://github.com/Shubhamsaboo/awesome-llm-apps) | Runnable LLM apps with RAG, agents, and local models. | ![Stars](https://img.shields.io/github/stars/Shubhamsaboo/awesome-llm-apps?style=flat) |
| [**Awesome AI Agents**](https://github.com/e2b-dev/awesome-ai-agents) | A big directory of AI agent projects. | ![Stars](https://img.shields.io/github/stars/e2b-dev/awesome-ai-agents?style=flat) |
| [**LLM Course**](https://github.com/mlabonne/llm-course) | A free roadmap and notebooks for learning LLMs. | ![Stars](https://img.shields.io/github/stars/mlabonne/llm-course?style=flat) |

## 🍎 Where to start on a Mac

Path for an Apple Silicon Mac like the M1 Pro:

1. **Run a model locally.** Install [Ollama](https://github.com/ollama/ollama) for a one-command start, or build [llama.cpp](https://github.com/ggml-org/llama.cpp) (Metal GPU support is built in) for full control over GGUF models.
2. **Fine-tune a small model.** Use [mlx-lm](https://github.com/ml-explore/mlx-lm) for LoRA fine-tuning directly on the Mac, or run [Unsloth](https://github.com/unslothai/unsloth) notebooks in Google Colab.
3. **Add memory and knowledge.** Pair [Chroma](https://github.com/chroma-core/chroma) with [Sentence-Transformers](https://github.com/huggingface/sentence-transformers) for simple local RAG.

> [!NOTE]
> Unsloth and vLLM mainly target NVIDIA GPUs. On a Mac, use mlx-lm and llama.cpp locally, and rent a cloud GPU (Colab or RunPod) when you need them.

---

<div align="center">

Made with 💙 by [toronzzo](https://github.com/toronzzo) · Found this useful? Leave a ⭐

Released under [CC0-1.0](LICENSE). Each listed project has its own license.

</div>
