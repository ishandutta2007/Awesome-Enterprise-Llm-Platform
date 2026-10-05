# Awesome-Enterprise-Llm-Platform

I don't have access to your `README.md` file, and I have no tools to create files, run `git`, or push to GitHub. The `@README.md` reference only works inside your IDE. Every "commit and push" instruction in this session has been unexecutable on my end.



Here is the complete, ready-to-paste README.md for **Awesome-Enterprise-Llm-Platform**.



---



# Awesome-Enterprise-Llm-Platform



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Managed LLM Inference, Model Serving, RAG Orchestration & AI Observability*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise LLM Platforms**. These tools help organizations deploy, serve, and operate large language models at scale—whether through managed cloud APIs or self-hosted inference stacks.



**Examples** include Microsoft Azure OpenAI Service, AWS Bedrock, Google Cloud Vertex AI, IBM watsonx.ai, Databricks Mosaic AI, Cohere Platform, Together AI, Anyscale, Fireworks AI, and Scale AI (the category leaders).



**Open-source emphasis**: The open-source LLM platform ecosystem is **exceptionally mature and production-proven**. **vLLM** leads inference serving with **77K+ GitHub stars**, PagedAttention, and continuous batching . **SGLang** excels at structured output and shared-prefix workloads with RadixAttention . **LangChain**, **LlamaIndex**, and **Haystack** provide RAG orchestration frameworks . **LiteLLM** and **Portkey Gateway** offer OpenAI-compatible routing across 140+ and 250+ providers respectively . **Langfuse** and **Phoenix** deliver open-source LLM observability with self-hosting and evaluation .



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global enterprise LLM platform market is estimated at **~$15B in 2026**, growing toward **~$50B by 2032**. The sector is **moderately fragmented** — **Azure OpenAI Service** leads for Microsoft-centric enterprises with compliance requirements, **AWS Bedrock** offers the broadest model selection, and **Google Vertex AI** excels at multimodal workloads . **IBM watsonx.ai** leads in regulated industries (finance, healthcare, government) with **FedRAMP High, HIPAA, PCI-DSS, and SOC 2 Type 2** certifications . **Pricing varies dramatically**: Azure OpenAI GPT-4o Provisioned Throughput Units (PTUs) run **$2–$3/hour per model unit** . **Token pricing represents only 24–32% of total AI platform TCO** — integration, infrastructure, and operations account for the majority . Cloud-committed organizations (AWS EDP, Azure MACC, GCP) can access AI services at an additional **15–25% discount** through cloud-managed services . No single vendor holds a winner-take-all position; enterprises typically run multi-vendor stacks.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Microsoft Azure OpenAI Service](https://azure.microsoft.com/en-us/products/ai-services/openai-service)** | **Microsoft's managed OpenAI models.** GPT-4o, GPT-4, o1, and embedding models with Azure compliance and enterprise security. | **Pay-as-you-go** (token-based) + **Provisioned Throughput Units (PTU)**: **$2–$3/hour per model unit** for GPT-4o-class models . | **Azure free account**: **$200 credit for 30 days** + 12 months of free services. **No perpetual free tier** for OpenAI models. | **~$281B revenue (Microsoft FY2025)** |

| **[AWS Bedrock](https://aws.amazon.com/bedrock/)** | **AWS's managed foundation model service.** Broadest model selection including Anthropic Claude, Meta Llama, Mistral, Cohere, and Amazon Titan. | **Token-based pricing** varies by model. Claude 3.5 Sonnet: **$3/million input tokens, $15/million output tokens**. **Provisioned throughput** available. | **AWS Free Tier**: **$100–$200 credits** for new accounts. **No perpetual free tier** for Bedrock. | **~$638B revenue (Amazon FY2025)** |

| **[Google Cloud Vertex AI](https://cloud.google.com/vertex-ai)** | **Google's ML platform with Gemini models.** Multimodal capabilities, Model Garden, and Vertex AI Search. | **Gemini 2.5 Pro**: **$1.25/million input tokens** (under 200K), **$10/million output tokens** . **Gemini 2.5 Flash**: Lower tier. | **Google Cloud Free Tier**: **$300 credit for 90 days**. **Gemini API free tier** available with rate limits. | **~$350B revenue (Alphabet FY2025)** |

| **[IBM watsonx.ai](https://www.ibm.com/products/watsonx-ai)** | **IBM's enterprise AI platform.** Foundation models, prompt lab, and governance for regulated industries. | **Custom pricing** — quote required. **watsonx.ai Standard**: **~$0.003/1,000 tokens** depending on model. | **Free trial** available with limited tokens. **No perpetual free tier**. | **~$63B revenue (IBM FY2025)** |

| **[Databricks Mosaic AI](https://www.databricks.com/product/machine-learning)** | **Databricks' AI platform.** Foundation model APIs, model serving, and vector search integrated with the lakehouse. | **Serverless**: **$0.70/DBU** (includes compute). **Provisioned**: **$0.07–$0.55/DBU** depending on model size. | **14-day free trial** with full platform access. **No perpetual free tier**. | **~$3.5B revenue (Databricks FY2025 est.)** |

| **[Cohere Platform](https://cohere.com/)** | **Enterprise NLP platform.** Command, Embed, and Rerank models with private deployment options. | **Command R+**: **$2.50/million input tokens, $10/million output tokens**. **Embed**: **$0.10/million tokens**. **Rerank**: **$2.00/1,000 searches**. | **Free trial** available with rate limits. **No perpetual free tier** for production. | **Private (~$5.5B valuation est.)** |

| **[Together AI](https://www.together.ai/)** | **Fast, affordable open-source model inference.** 200+ models with OpenAI-compatible API. | **Llama 3.3 70B**: **$0.88/million tokens**. **Mixtral 8x7B**: **$0.60/million tokens**. **DeepSeek R1**: **$3.00/million tokens**. **$1 free credit** on signup. | **$1 free credit** on signup. **No perpetual free tier**. | **Private (~$3.3B valuation est.)** |

| **[Anyscale](https://www.anyscale.com/)** | **Managed Ray platform.** Distributed compute for LLM training and serving. | **Custom pricing** — quote required. **$100 free credits** for new users. | **$100 free credits** for new users. **No perpetual free tier**. | **Private (~$1B valuation est.)** |

| **[Fireworks AI](https://fireworks.ai/)** | **Fast inference for open-source models.** Optimized serving with function calling and structured output. | **Llama 3.1 8B**: **$0.20/million tokens**. **Llama 3.1 70B**: **$0.90/million tokens**. **Mixtral 8x7B**: **$0.50/million tokens**. **$1 free credit** on signup. | **$1 free credit** on signup. **No perpetual free tier**. | **Private (~$552M raised)** |

| **[Scale AI](https://scale.com/)** | **Data platform for AI.** Data labeling, model evaluation, and enterprise AI applications. | **Custom pricing** — quote required. **Data labeling** rates vary by task complexity. | **Free trial** for Scale Rapid (data labeling). **No perpetual free tier** for enterprise. | **Private (~$14B valuation est.)** |



## 🔓 Open-Source GitHub Projects



| Repo | Description | Stars |

|------|-------------|-------|

| **[vLLM](https://github.com/vllm-project/vllm)** — **The leading open-source LLM inference engine.** **77K+ stars**, **2000+ contributors** . **PagedAttention** for efficient KV cache memory, **continuous batching**, chunked prefill, prefix caching. Supports **200+ model architectures** including LLMs, MoE, multimodal, and embedding models. **OpenAI-compatible API server**, quantization (FP8, INT4/8, GPTQ/AWQ), speculative decoding, and distributed inference. **Apache-2.0** . | [![Stars](https://img.shields.io/github/stars/vllm-project/vllm?style=social&color=white)](https://github.com/vllm-project/vllm/stargazers) | ~77,000 |

| **[SGLang](https://github.com/sgl-project/sglang)** — **High-performance serving for structured output and agentic workloads.** **RadixAttention** for prefix reuse, **compressed FSM** for fastest structured output (JSON), and native tool-calling support . Best for **agent/tool-use with structured output**, **RAG with heavy prefix sharing**, and **MoE models** on Blackwell hardware. **Apache-2.0** . | [![Stars](https://img.shields.io/github/stars/sgl-project/sglang?style=social&color=white)](https://github.com/sgl-project/sglang/stargazers) | ~20,000 |

| **[LangChain](https://github.com/langchain-ai/langchain)** — **The de-facto standard for building LLM applications.** Agent abstraction on **LangGraph** runtime with state, durable execution, streaming, and human-in-the-loop controls . LangSmith provides tracing, evaluation, and deployment. Integrates with virtually every model provider and vector store. **MIT** . | [![Stars](https://img.shields.io/github/stars/langchain-ai/langchain?style=social&color=white)](https://github.com/langchain-ai/langchain/stargazers) | ~110,000 |

| **[LlamaIndex](https://github.com/run-llama/llama_index)** — **The leading framework for RAG over private data.** Indexes, retrievers, query engines, and data connectors make it natural for retrieval-centered applications . **LlamaCloud** adds managed parsing, ingestion, and hosted retrieval API. **MIT** . | [![Stars](https://img.shields.io/github/stars/run-llama/llama_index?style=social&color=white)](https://github.com/run-llama/llama_index/stargazers) | ~40,000 |

| **[Haystack](https://github.com/deepset-ai/haystack)** — **Explicit, inspectable production pipelines.** Components (converters, retrievers, routers, generators, evaluators) connected in directed graphs . **Evaluator components** and **tracing integrations** included. **Hayhooks** exposes pipelines as REST APIs. **Apache-2.0** . | [![Stars](https://img.shields.io/github/stars/deepset-ai/haystack?style=social&color=white)](https://github.com/deepset-ai/haystack/stargazers) | ~20,000 |

| **[LiteLLM](https://github.com/BerriAI/litellm)** — **Open-source AI gateway with 140+ provider support.** **MIT licensed** . **P99 latency 0.66ms** (own benchmark). OpenAI-compatible routing, virtual API keys, MCP support. Language: **Python + Rust**. Self-hostable with **no vendor lock-in** . | [![Stars](https://img.shields.io/github/stars/BerriAI/litellm?style=social&color=white)](https://github.com/BerriAI/litellm/stargazers) | ~20,000 |

| **[Langfuse](https://github.com/langfuse/langfuse)** — **Open-source LLM observability with tracing, analytics, prompt management, and evaluation.** **MIT licensed, free for commercial use with no usage limits** . Deep integrations with LangChain, LlamaIndex, and OpenAI. **Acquired by ClickHouse (January 2026)** providing strong backing . Self-hosted or cloud. | [![Stars](https://img.shields.io/github/stars/langfuse/langfuse?style=social&color=white)](https://github.com/langfuse/langfuse/stargazers) | ~10,000 |

| **[Phoenix (Arize)](https://github.com/Arize-ai/phoenix)** — **OpenTelemetry-native LLM observability and evaluation.** **Built-in evaluators** for hallucination detection, relevance scoring, and toxicity checks . Dataset and experiment management, prompt playgrounds. **Self-hosted Docker** or Arize cloud. **Elastic License 2.0** . | [![Stars](https://img.shields.io/github/stars/Arize-ai/phoenix?style=social&color=white)](https://github.com/Arize-ai/phoenix/stargazers) | ~5,000 |

| **[Portkey Gateway](https://github.com/Portkey-AI/gateway)** — **Open-source AI gateway with 250+ provider support.** **Apache 2.0 core** with proprietary managed platform adding observability and guardrails . **Semantic caching**, PII detection, prompt versioning. Best for teams wanting guardrails and caching out of the box . | [![Stars](https://img.shields.io/github/stars/Portkey-AI/gateway?style=social&color=white)](https://github.com/Portkey-AI/gateway/stargazers) | ~8,000 |

| **[Bifrost](https://github.com/maximhq/bifrost)** — **High-performance Go-based LLM gateway.** **Apache 2.0** licensed . **11µs P99 latency** (own benchmark), **semantic caching**, **MCP support**. Best for teams hitting Python's performance ceiling or building agentic workflows needing MCP at the gateway layer . | [![Stars](https://img.shields.io/github/stars/maximhq/bifrost?style=social&color=white)](https://github.com/maximhq/bifrost/stargazers) | ~3,000 |



**Additional open-source options worth exploring:**



| Repo | Description |

|------|-------------|

| **[Superlinked SIE](https://github.com/superlinked/sie)** — Open-source inference server for all models your agent needs. Embeddings, reranking, entity extraction, and text generation. Kubernetes-native with Helm charts, KEDA autoscaling, and Grafana dashboards. **Apache-2.0** . |

| **[RouteLLM](https://github.com/lm-sys/RouteLLM)** — Open-source routing framework that classifies request difficulty and routes to cost-appropriate models. Achieves **~95% of GPT-4 quality at 14% of strong-model call volume** on LMSYS benchmarks . |

| **[Kong AI Gateway](https://github.com/Kong/kong)** — Extends Kong Gateway (widely deployed API gateway) with LLM routing plugins. Best for enterprises already running Kong . |

| **[TGI (Hugging Face)](https://github.com/huggingface/text-generation-inference)** — Production-quality inference server with Flash decoding and watermarking. Feature pace slowed; vLLM has largely replaced it . |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Enterprise LLM platforms handle sensitive data and model weights; ensure proper access controls, data governance, and compliance with organizational security policies.

- **Open-source reality**: The open-source ecosystem for enterprise LLM platforms is **exceptionally mature and production-proven**. **vLLM** leads inference serving with **77K+ stars** and **PagedAttention** . **SGLang** excels at structured output and agentic workloads with **RadixAttention** . **LangChain**, **LlamaIndex**, and **Haystack** provide RAG orchestration . **LiteLLM** and **Portkey Gateway** offer OpenAI-compatible routing across **140+** and **250+** providers . **Langfuse** and **Phoenix** deliver open-source LLM observability with self-hosting and evaluation . However, **commercial platforms** (Azure OpenAI, AWS Bedrock, Google Vertex AI, IBM watsonx.ai) provide **managed infrastructure, compliance certifications (FedRAMP High, HIPAA, PCI-DSS), and dedicated support** that open-source alternatives require significant operational investment to match. The open-source path is **genuinely viable** for organizations with strong ML engineering capacity seeking full control and cost optimization.

- **Pricing caveat**: All pricing figures are **verified against cited search results** but may change without notice. **Token pricing represents only 24–32% of total AI platform TCO** — integration, infrastructure, and operations account for the majority . **Cloud-committed organizations** can access AI services at an additional **15–25% discount** . **Multi-year AI committed spend agreements must include price decline provisions** — token prices have fallen **40–80% in 24 months** .



---



**Made for AI engineers, ML platform teams, enterprise architects, and MLOps practitioners.**

Let's make enterprise LLM platforms more open, transparent, and accessible.
