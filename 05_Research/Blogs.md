# Generative AI and Machine Learning Blogs

Table of contents:

- [Generative AI and Machine Learning Blogs](#generative-ai-and-machine-learning-blogs)
  - [Blog Posts by Leoni Monigatti \& Related/Referenced](#blog-posts-by-leoni-monigatti--relatedreferenced)
  - [Blog Posts by Sebastian Raschka](#blog-posts-by-sebastian-raschka)
  - [Blog Posts by Elastic](#blog-posts-by-elastic)

## Blog Posts by Leoni Monigatti & Related/Referenced

- [Building Retrieval-Augmented Generation Systems, by Leonie Monigatti (2024-04-24)](https://medium.com/@iamleonie/building-retrieval-augmented-generation-systems-be587f42aedb)

    - Guide for RAG topics
      - RAG Paradigms
        - Naive RAG (see below)
        - Advanced RAG
        - Modular RAG
      - Orchestration Frameworks
      - RAG Evaluation
    - [Paper: Retrieval-Augmented Generation for Large Language Models: A Survey (Gao et al., 2024)](http://arxiv.org/pdf/2312.10997)
    - [Paper: Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks (Lewis et al., 2020)](https://arxiv.org/abs/2005.11401)

- [Retrieval-Augmented Generation (RAG): From Theory to LangChain Implementation, by Leonie Monigatti (2023-11-14)](https://towardsdatascience.com/retrieval-augmented-generation-rag-from-theory-to-langchain-implementation-4e9bd5f6a4f2): **Naive RAG**.

    ![Naive RAG, by Leoni Monigatti](./assets/rag_naive_monigatti.jpeg)
    - ...

- [RAG vs Finetuning — Which Is the Best Tool to Boost Your LLM Application? By Heiko Hotz (2023-08-24)](https://towardsdatascience.com/rag-vs-finetuning-which-is-the-best-tool-to-boost-your-llm-application-94654b1eaba7)

    - In a nutshell:
      - RAG is optimal for external and changing data sources; additionally, it minimizes hallucinations.
      - Fine-tuning is optimal when the behavior and style (vocabulary) need to be captured (e.g., poetic/literary contexts, medicine, etc.).
      - In some cases, both external data and style are very important, then, we need to do both: fine-tune and use a RAG.
    - Other criteria:
      - Are hallucinations to be avoided at all costs? Then, RAG is better.
      - Training data (labeled, structured) available? If so, fine-tuning is possible.
      - Is data mostly changing? If so, RAG is better.
      - Is interpretability required? If so, then RAG is better.
    - We should consider each use case and ask those questions carefully
    - Typical use-cases:
      - Summarization (usually fine-tuning recommended)
      - QA system for organizational knowledge (usually RAG recommended)
      - Customer Support Automation (usually fine-tuning + RAG recommended)
    - Other aspects to consider
      - Scalability
      - Latency
      - Maintenance
      - Robustness and reliability
      - Integration with existing systems
      - User Experience
      - Cost
      - Complexity

- [Advanced Retrieval-Augmented Generation: From Theory to LlamaIndex Implementation, by Leoni Monigatti (2024-02-19)](https://towardsdatascience.com/advanced-retrieval-augmented-generation-from-theory-to-llamaindex-implementation-4de1464a9930): **Advanced RAG**

- [A Guide on 12 Tuning Strategies for Production-Ready RAG Applications, by Leonie Monigatti (2023-12-06)](https://towardsdatascience.com/a-guide-on-12-tuning-strategies-for-production-ready-rag-applications-7ca646833439)

- [Evaluating RAG Applications with RAGAs, by Leonie Monigatti (2023-12-13)](https://towardsdatascience.com/evaluating-rag-applications-with-ragas-81d67b0ee31a)

- [The Challenges of Retrieving and Evaluating Relevant Context for RAG, by Leonie Monigatti (2024-06-10)](https://towardsdatascience.com/the-challenges-of-retrieving-and-evaluating-relevant-context-for-rag-e362f6eaed34)

- [Retrieval-Augmented Generation Reading List, by Leonie Monigatti](https://medium.com/@iamleonie/list/retrievalaugmented-generation-652a960f44ff)

    - All posts related to RAG are compiled here.

<!--
## Blog Posts by Leoni Monigatti

- [The Challenges of Retrieving and Evaluating Relevant Context for RAG (2024-06-10, Leoni Monigatti)](https://towardsdatascience.com/the-challenges-of-retrieving-and-evaluating-relevant-context-for-rag-e362f6eaed34)
- [Shifting Tides: The Competitive Edge of Open Source LLMs over Closed Source LLMs (2023-04-29 Leoni Monigatti)](https://towardsdatascience.com/shifting-tides-the-competitive-edge-of-open-source-llms-over-closed-source-llms-aee76018b5c7)
- [Building Retrieval-Augmented Generation Systems (2024-04-02, Leonie Monigatti)]()
- [Advanced Retrieval-Augmented Generation: From Theory to LlamaIndex Implementation (2024-02-19, Leonie Monigatti)]()
- [Evaluating RAG Applications with RAGAs (2023-12-13, Leonie Monigatti)]()
- [A Guide on 12 Tuning Strategies for Production-Ready RAG Applications (2023-12-06, Leonie Monigatti)]()
- [Improving Retrieval Performance in RAG Pipelines with Hybrid Search (2023-11-28, Leonie Monigatti)]()
- [Retrieval-Augmented Generation (RAG): From Theory to LangChain Implementation (2023-11-14, Leonie Monigatti)]()
- [Getting Started with Weaviate: A Beginner’s Guide to Search with Vector Databases (2023-07-18, Leonie Monigatti)]()
- [Understanding LLMOps: Large Language Model Operations (2023-05-02, Leonie Monigatti)]()
- [Explaining Vector Databases in 3 Levels of Difficulty (2023-07-04, Leonie Monigatti)]()
- [Everything You Need to Know About the Binary Search Algorithm (2022-09-27, Leonie Monigatti)](https://medium.com/towards-data-science/everything-you-need-to-know-about-the-binary-search-algorithm-6bc4f9a3127d)

-->

<!--
- [The Kaggle Blueprints: Unlocking Winning Approaches to Data Science Competitions (2023-03-01, Leonie Monigatti)]()
- [The Challenges of Retrieving and Evaluating Relevant Context for RAG (2023-06-10, Leonie Monigatti)]()
- [Shifting Tides: The Competitive Edge of Open Source LLMs over Closed Source LLMs (2023-04-29, Leonie Monigatti)]()
- [Intro to DSPy: Goodbye Prompting, Hello Programming! (2023-02-27, Leonie Monigatti)]()
- [2023 in Review: Recapping the Post-ChatGPT Era and What to Expect for 2024 (2023-12-18, Leonie Monigatti)]()
- [Recreating Amazon’s New Generative AI Feature: Product Review Summaries (2023-11-21, Leonie Monigatti)]()
- [Recreating Andrej Karpathy’s Weekend Project — a Movie Search Engine (2023-11-07, Leonie Monigatti)]()
- [Why OpenAI’s API Is More Expensive for Non-English Languages (2023-08-16, Leonie Monigatti)]()
- [Towards Green AI: How to Make Deep Learning Models More Efficient in Production (2023-08-08, Leonie Monigatti)]()
- [Easily Estimate Your OpenAI API Costs with Tiktoken (2023-08-01, Leonie Monigatti)]()
- [Boosting PyTorch Inference on CPU: From Post-Training Quantization to Multithreading (2023-06-13, Leonie Monigatti)]()
- [10 Exciting Project Ideas Using Large Language Models (LLMs) for Your Portfolio (2023-05-15, Leonie Monigatti)]()
- [Getting Started with LangChain: A Beginner’s Guide to Building LLM-Powered Applications (2023-04-25, Leonie Monigatti)]()
- [Cutout, Mixup, and Cutmix: Implementing Modern Image Augmentations in PyTorch (2023-04-14, Leonie Monigatti)]()
- [How to Save and Load Your Neural Networks in Python (2023-04-05, Leonie Monigatti)]()
- [2 Simple Steps To Reduce the Memory Usage of Your Pandas Dataframe (2023-03-21, Leonie Monigatti)]()
- [How to Handle Large Datasets in Python (2022-06-26, Leonie Monigatti)](https://medium.com/towards-data-science/how-to-handle-large-datasets-in-python-1f077a7e7ecf)
-->

## Blog Posts by Sebastian Raschka

- [Instruction Pretraining LLMs (2024-06, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/instruction-pretraining-llms)
- [Developing an LLM: Building, Training, Finetuning (2024-06-08, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/llms-building-training-finetuning)
- [LLM Research Insights: Instruction Masking and New LoRA Finetuning Experiments (2024-06-02, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/llm-research-insights-instruction)
- [Improving LoRA: Implementing Weight-Decomposed Low-Rank Adaptation (DoRA) from Scratch (2024-02-18, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/lora-and-dora-from-scratch)
- [Tackling Hallucinations, Boosting Reasoning Abilities, and New Insights into the Transformer Architecture (2023-12-09, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/research-papers-in-november-2023)
- [Practical Tips for Finetuning LLMs Using LoRA (Low-Rank Adaptation) (2023-11-19, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/practical-tips-for-finetuning-llms)
- [A Potential Successor to RLHF for Efficient LLM Alignment and the Resurgence of CNNs (2023-11-04, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/research-papers-october-2023)
- [Ten Noteworthy AI Research Papers of 2023 (2023-12-30, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/10-ai-research-papers-2023)

<!--
- [How Good Are the Latest Open LLMs? And Is DPO Better Than PPO? (2024-05-12, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/how-good-are-the-latest-open-llms)
- [Using and Finetuning Pretrained Transformers (2024-04-20, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/using-and-finetuning-pretrained-transformers)
- [Tips for LLM Pretraining and Evaluating Reward Models (2024-03-31, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/tips-for-llm-pretraining-and-evaluating-rms)
- [Research Papers in February 2024: A LoRA Successor, Small Finetuned LLMs Vs Generalist LLMs, and Transparent LLM Research (2024-03-03, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/research-papers-in-february-2024)
- [Model Merging, Mixtures of Experts, and Towards Smaller LLMs (2024-02-03, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/research-papers-in-january-2024)
- [Understanding and Coding Self-Attention, Multi-Head Attention, Cross-Attention, and Causal-Attention in LLMs (2024-01-14, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/understanding-and-coding-self-attention)
- [AI and Open Source in 2023 (2023-10-23, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ai-and-open-source-in-2023)
- [LLM Business and Busyness: Recent Company Investments and AI Adoption, New Small Openly Available LLMs, and LoRA Research (2023-10-08, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-12-llm-businesses)
- [From Self-Alignment to LongLoRA (2023-09-23, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/research-highlights-in-three-sentences-3d5)
- [LLM Training: RLHF and Its Alternatives (2023-09-10, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/llm-training-rlhf-and-its-alternatives)
- [The Missing Bits: Llama 2 Weights Have Changed (2023-08-27, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/the-missing-bits-llama-2-weights)
- [New Foundation Models: CodeLlama and other highlights in Open-Source AI (2023-08-26, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-11-new-foundation-models)
- [Llama 2, Flash-Attention 2, and More (2023-08-12, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/research-highlights-in-three-sentences)
- [Large Language Models and Nearest Neighbors (2023-07-30, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/large-language-models-and-nearest)
- [Long Contexts and Scaling Transformers to 1,000,000,000 Tokens (2023-07-15, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ai-research-highlights-in-3-sentences-738)
- [State of Computer Vision 2023: From Vision Transformers to Neural Radiance Fields (2023-07-06, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-10-state-of-computer)
- [Accelerating PyTorch Model Training Using Mixed-Precision and Fully Sharded Data Parallelism (2023-06-26, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/accelerating-pytorch-model-training)
- [Understanding Encoder And Decoder LLMs (2023-06-17, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/understanding-encoder-and-decoder)
- [Direct-Preference Optimization for Human Feedback and More (2023-06-10, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ai-research-highlights-in-3-sentences-2a1)
- [LLM Tuning & Dataset Perspectives (2023-06-03, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-9-llm-tuning-and-dataset)
- [About LayerNorm Variants in the Original Transformer Paper, and Some Other Interesting Historical Tidbits About LLMs (2023-05-24, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/why-the-original-transformer-figure)
- [Finetuning LLMs Efficiently with Adapters (2023-05-20, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/finetuning-llms-with-adapters)
- [Transformers for Long Inputs and Less Training Data (2023-05-13, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ai-research-highlights-in-3-sentences)
- [Insights from Large-Scale LLM Training Runs And the Latest Open Source LLMs and Datasets (2023-05-06, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-8-the-latest-open-source)
- [Understanding Parameter-Efficient LLM Finetuning: Prompt Tuning And Prefix Tuning (2023-04-30, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/understanding-parameter-efficient)
- [Finetuning Large Language Models (2023-04-22, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/finetuning-large-language-models)
- [Understanding Large Language Models (2023-04-16, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/understanding-large-language-models)
- [Large Language Models 3.0 (2023-04-04, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-7-large-language-models)
- [TrAIn Differently: Do We Need Reinforcement Learning with Human Feedback (RLHF)? (2023-03-07, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-6-train-differently)
- [RevAIval of Ideas: From Next-Generation Convolutional Neural Networks to LLMs (2023-02-06, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-5-revaival-of-ideas)
- [Looking Back at 2022: A Big Year For AI (2023-01-02, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-4-a-big-year-for-ai)
- [Launching Large Language Models and Open Source Software (2022-12-07, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-3-ainnouncements)
- [Transformers, Fast and Slow: New Developments in Language Processing (2022-11-10, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-2-transformers-fast-and)
- [A Diffusion of Innovations: Recent Developments in Generative Learning (2022-11-04, Sebastian Raschka)](https://magazine.sebastianraschka.com/p/ahead-of-ai-1-a-diffusion-of-innovations)
-->

## Blog Posts by Elastic

[ElasticSearch - SearchLabs - Blog](https://www.elastic.co/search-labs/blog)

- [How to choose a vector database, by Elastic Platform Team](https://www.elastic.co/blog/how-to-choose-a-vector-database)
- [How Orca leverages Search AI to help users gain visibility, achieve compliance, and prioritize risks, by Shai Alon](https://www.elastic.co/blog/orca-search-ai)
- [Deep learning vs. machine learning: Understanding the differences, by Elastic Platform Team (08 July 2024)](https://www.elastic.co/blog/deep-learning-vs-machine-learning)
- [15 generative AI use cases for the enterprise, by Elastic Platform Team (27 June 2024)](https://www.elastic.co/blog/portfolio/15-generative-AI-use-cases-enterprise)
- [GenAI for customer support — Part 1: Building our proof of concept, by Elastic Platform Team (27 June 2024)](https://www.elastic.co/blog/genai-customer-support-building-proof-of-concept)
- [How does combining search with AI solve enterprise data problems?, by Elastic Platform Team (25 June 2024)](https://www.elastic.co/blog/how-does-search-solve-data-problems)
- [Unpacking the US Senate’s new AI Roadmap, by Elastic Platform Team (16 May 2024)](https://www.elastic.co/blog/united-states-senate-ai-roadmap)
- [Elastic's RAG-based AI Assistant: Analyze application issues with LLMs and private GitHub issues, by Elastic Platform Team (08 May 2024)](https://www.elastic.co/blog/elastic-rag-ai-assistant-application-issues-llm-github)
- [Elastic integrates Anthropic's Claude 3 models to enhance AI-driven security analytics, by Elastic Platform Team (08 May 2024)](https://www.elastic.co/blog/ai-security-analytics-integrating-anthropic-claude)
- [Built-in protections for Elastic AI Assistant, by Elastic Platform Team (06 May 2024)](https://www.elastic.co/blog/combating-llm-threat-techniques-with-elastic-ai-assistant)
- [The benefits of utilizing locally hosted models with Elastic AI Assistant, by Elastic Platform Team (03 May 2024)](https://www.elastic.co/blog/ai-assistant-locally-hosted-models)
- [Getting started with the Elastic AI Assistant for Observability and Amazon Bedrock, by Elastic Platform Team (03 May 2024)](https://www.elastic.co/blog/elastic-ai-assistant-observability-amazon-bedrock)
- [Understanding the approximate nearest neighbor (ANN) algorithm, by Elastic Platform Team (26 April 2024)](https://www.elastic.co/blog/understanding-ann)
- [NLP vs. LLMs: Understanding the differences, by Elastic Platform Team (15 April 2024)](https://www.elastic.co/blog/nlp-vs-llms)
- [Vector database vs. graph database: Understanding the differences, by Elastic Platform Team (11 April 2024)](https://www.elastic.co/blog/vector-database-vs-graph-database)
- [Getting started with the Elastic AI Assistant for Observability and Microsoft Azure OpenAI, by Elastic Platform Team (04 April 2024)](https://www.elastic.co/blog/elastic-ai-assistant-observability-microsoft-azure-openai)
- [Machine learning vs. AI: Understanding the differences, by Elastic Platform Team (07 March 2024)](https://www.elastic.co/blog/ml-vs-ai)
- [Emerging trends in observability: GAI, AIOps, tools consolidation, and OpenTelemetry, by Elastic Platform Team (06 March 2024)](https://www.elastic.co/blog/observability-gai-aiops-tools-consolidation-opentelemetry)
- [Elastic part of a select group with AWS Generative AI Competency, by Elastic Platform Team (06 March 2024)](https://www.elastic.co/blog/elastic-aws-generative-ai-competency)
- [How to make a chatbot: Dos and don'ts for developers in an AI-driven world, by Elastic Platform Team (05 March 2024)](https://www.elastic.co/blog/how-to-make-a-chatbot)
- [How to create a search engine, by Elastic Platform Team (29 February 2024)](https://www.elastic.co/blog/how-to-create-a-search-engine)
- [Fraud in financial services: Leaning on generative AI to protect a rapidly expanding attack surface, by Elastic Platform Team (28 February 2024)](https://www.elastic.co/blog/financial-services-fraud-generative-ai-attack-surface)
- [LangChain tutorial: A guide to building LLM-powered applications, by Elastic Platform Team (21 February 2024)](https://www.elastic.co/blog/langchain-tutorial)
- [5 AI search trends impacting developers in 2024, by Elastic Platform Team (21 February 2024)](https://www.elastic.co/blog/ai-search-trends-developers)
- [Understanding AI search algorithms, by Elastic Platform Team (21 February 2024)](https://www.elastic.co/blog/understanding-ai-search-algorithms)
- [Choosing an LLM: The 2024 getting started guide to open-source LLMs, by Elastic Platform Team (12 February 2024)](https://www.elastic.co/blog/open-source-llms-guide)

<!--
- [UK government: Reduce cyber risk by modernising legacy IT, by Syed Rafice](https://www.elastic.co/blog/uk-government-reduce-legacy-it-streamline-budget)
- [Elastic and Google Cloud: Enhancing security analytics from data ingestion to incident response, by Valerio Arvizzigno](https://www.elastic.co/blog/elastic-google-cloud-security-data-ingestion-incident-response)
- [Elastic wins 2024 Microsoft US Partner of the Year, by Elastic Platform Team (26 June 2024)](https://www.elastic.co/blog/elastic-wins-2024-microsoft-us-partner-of-the-year)
- [Expedient innovates with Elastic Observability to deliver better management, monitoring, and more to customers, by Elastic Platform Team (26 June 2024)](https://www.elastic.co/blog/expedient-elastic-observability)
- [How can unifying observability and security strengthen your business?, by Elastic Platform Team (25 June 2024)](https://www.elastic.co/blog/observability-security-strengthen-business)
- [Elastic Observability 8.14: New feature for SLO, AI Assistant, and .NET for Universal Profiling, by Elastic Platform Team (26 June 2024)](https://www.elastic.co/blog/whats-new-elastic-observability-8-14-0)
- [Elastic Search 8.14: Faster and more cost-effective vector search, improved relevance with retrievers and reranking, by Elastic Platform Team](https://www.elastic.co/blog/whats-new-elastic-search-8-14-0)
- [Elastic Platform 8.14: ES|QL GA, encryption at rest, and vector search optimizations, by Elastic Platform Team (05 June 2024)](https://www.elastic.co/blog/whats-new-elasticsearch-platform-8-14-0)
- [Elastic Observability 8.14: New feature for SLO, AI Assistant, and .NET for Universal Profiling, by Elastic Platform Team (05 June 2024)](https://www.elastic.co/blog/whats-new-elastic-observability-8-14-0)
- [NEW in Elastic 8.14: Attack Discovery, GA of ES|QL, and AI Assistant features, by Elastic Platform Team (05 June 2024)](https://www.elastic.co/blog/whats-new-elastic-8-14-0)
- [Elastic 8.14: GA of Elasticsearch Query Language (ES|QL) for simplified analysis, by Elastic Platform Team (05 June 2024)](https://www.elastic.co/blog/whats-new-elasticsearch-query-language-8-14-0)
- [Why customer service matters for government — and how AI will help, by Elastic Platform Team (16 May 2024)](https://www.elastic.co/blog/customer-service-government-ai)
- [Announcing Search AI Lake and Elastic Cloud Serverless to scale low latency search, by Elastic Platform Team (15 May 2024)](https://www.elastic.co/blog/search-ai-lake-elastic-cloud-serverless)
- [Elasticsearch accelerates building AI search apps on serverless, by Elastic Platform Team (15 May 2024)](https://www.elastic.co/blog/elasticsearch-serverless-preview)
- [Elastic changes the SIEM game with AI-driven security analytics, by Elastic Platform Team (06 May 2024)](https://www.elastic.co/blog/ai-driven-security-analytics)
- [Elastic and AWS deliver on AI-driven security analytics, by Elastic Platform Team (06 May 2024)](https://www.elastic.co/blog/elastic-aws-deliver-ai-driven-security-analytics)
- [Elastic Security Labs releases guidance to avoid LLM risks and abuses, by Elastic Platform Team (06 May 2024)](https://www.elastic.co/blog/address-llm-adoption-security-risks)
- [Elastic Security evolves into the first and only AI-driven security analytics solution, by Elastic Platform Team (03 May 2024)](https://www.elastic.co/blog/elastic-security-ai-security-analytics-solution)
- [Navigating the web of Scattered Spider: Defending financial institutions from cybercriminal networks, by Elastic Platform Team (03 May 2024)](https://www.elastic.co/blog/scattered-spider-cybercriminal-networks)
- [Tracing history: The generative AI revolution in SIEM, by Elastic Platform Team (09 April 2024)](https://www.elastic.co/blog/generative-ai-revolution-in-siem)
- [Elastic wins Google Cloud Partner of the Year for the fourth time, by Elastic Platform Team (08 April 2024)](https://www.elastic.co/blog/elastic-wins-google-cloud-partner-of-the-year)
- [The Elastic AI Assistant for Observability escapes Kibana!, by Elastic Platform Team (08 April 2024)](https://www.elastic.co/blog/elastic-ai-assistant-observability-escapes-kibana)
- [Accelerating generative AI experiences, by Elastic Platform Team (02 April 2024)](https://www.elastic.co/blog/elastic-generative-ai-experiences)
- [Elastic 8.13: GA of Amazon Bedrock in the Elastic AI Assistant for Observability, by Elastic Platform Team (02 April 2024)](https://www.elastic.co/blog/whats-new-elastic-8-13-0)
- [The state of generative AI: Our global survey of over 3,000 tech leaders, by Elastic Platform Team (26 March 2024)](https://www.elastic.co/blog/generative-ai-adoption-survey)
- [Elasticsearch and Kibana 8.13: Simplified kNN and improved query parallelization, by Elastic Platform Team (26 March 2024)](https://www.elastic.co/blog/whats-new-elasticsearch-kibana-8-13)
- [Elastic Search 8.13: Simplifying embedding and ranking for developers, by Elastic Platform Team (26 March 2024)](https://www.elastic.co/blog/whats-new-elastic-8-13-0)
- [Maximize IT efficiency leveraging alert management with Elastic AI Assistant for Observability, by Elastic Platform Team (26 March 2024)](https://www.elastic.co/blog/it-efficiency-alert-management-elastic-ai-assistant-observability)
- [Simplify stream processing for generative AI applications with Confluent Cloud for Apache Flink® and Elasticsearch®, by Elastic Platform Team (26 March 2024)](https://www.elastic.co/blog/generative-ai-applications-confluent-cloud-apache-flink-elasticsearch)
- [Analyzing OpenTelemetry apps with Elastic AI Assistant and APM, by Elastic Platform Team (21 March 2024)](https://www.elastic.co/blog/analyzing-opentelemetry-apps-elastic-ai-assistant-apm)
- [Elastic Observability 8.13: GA of AI Assistant support for AWS Bedrock and enhancements for AI Assistant and SLO, by Elastic Platform Team (04 March 2024)](https://www.elastic.co/blog/whats-new-elastic-observability-8-13-0)
- [Build better Service Level Objectives (SLOs) from logs and metrics, by Elastic Platform Team (21 February 2024)](https://www.elastic.co/blog/service-level-objectives-slos-logs-metrics)
- [Bridging IT intelligence and business KPIs with AI: The elephant in the room, by Elastic Platform Team (21 February 2024)](https://www.elastic.co/blog/it-intelligence-business-kpis-elephant-in-the-room)
- [Migrating from self-managed Elastic Stack to Elastic Cloud using snapshot and restore with Azure Blob Storage, by Elastic Platform Team (21 February 2024)](https://www.elastic.co/blog/elastic-stack-elastic-cloud-migration-snapshot-restore-azure-blob-storage)
- [How Elastic AI Assistant for Security and Amazon Bedrock can empower security analysts for enhanced performance, by Elastic Platform Team (08 February 2024)](https://www.elastic.co/blog/elastic-ai-assistant-amazon-bedrock-security-analysts)
- [Multilingual search using language identification in Elasticsearch, by Elastic Platform Team (12 February 2020)](https://www.elastic.co/blog/multilingual-search-using-language-identification-in-elasticsearch)

-->