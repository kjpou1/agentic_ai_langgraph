# AGENTIC_AI_LANGRAPH

Learning LANGGRAPH repo

https://github.com/sunnysavita10/youtubelive



## Intro Notebook

[Live Session-Building Agentic AI Using LangGraph](https://www.youtube.com/watch?v=R4-P79KgSMg)

LangGraph Introduction
This notebook explores LangGraph basics.  

### Setup environment
```
            GROQ_API_KEY="gxxxxxxxx"
```

## Papers

### 1. **"Measuring and Narrowing the Compositionality Gap in Language Models"**
- **Summary**: This paper examines the limitations of large language models (LLMs) in handling compositional tasks, where understanding and generating new combinations of learned concepts is critical. The authors propose metrics to measure this gap and methods to narrow it, improving LLMs’ capabilities in reasoning and generalization.
- **Key Contributions**:
  - Introduces the compositionality gap as a measure of model performance.
  - Proposes techniques to mitigate this gap through fine-tuning and prompt engineering.
- **URL**: [arXiv](https://arxiv.org/abs/2210.03350)

---

### 2. **"Seal-Tools: Self-Instruct Tool Learning Dataset for Agent Tuning and Detailed Benchmark"**
- **Summary**: This paper presents Seal-Tools, a dataset designed to improve the learning of API-like tools through self-instruct methodologies. The work aims to fine-tune language models to perform better on tool-based tasks and provides a comprehensive benchmark for evaluation.
- **Key Contributions**:
  - Introduces a novel dataset for tool-based task learning.
  - Highlights the benefits of self-instruct data for language model tuning.
  - Benchmarks performance across a variety of agent-based tasks.
- **URL**: [arXiv PDF](https://arxiv.org/pdf/2405.08355)

---

### 3. **"ReAct: Synergizing Reasoning and Acting in Language Models"**
- **Summary**: This paper introduces ReAct, a framework that integrates reasoning (e.g., chain-of-thought) and action generation into a single process for language models. The approach enables LLMs to dynamically generate reasoning traces alongside task-specific actions, improving both interpretability and task success rates.
- **Key Contributions**:
  - Proposes an interleaved reasoning and acting method for LLMs.
  - Mitigates hallucination and error propagation in tasks like question answering and fact verification.
  - Demonstrates superior performance on decision-making tasks in interactive environments.
- **URL**: [arXiv](https://arxiv.org/abs/2210.03629)

## Agentic RAG









## LLM-Powered SQL Database Agents

This project demonstrates the creation and deployment of an LLM-powered SQL database agent using LangGraph. It integrates advanced language models with SQL to interpret natural language queries and execute database commands.

#### **Objective**
The notebook demonstrates the use of LangGraph to create an intelligent SQL database agent capable of interpreting user queries in natural language, translating them into SQL commands, and returning results. It integrates LLMs with SQL databases for querying and data management.

**Key Features**:
- Interactive SQL querying with natural language inputs.
- Support for basic, intermediate, and advanced SQL queries including joins, aggregations, and window functions.
- Error handling for edge cases like unmatched records and malformed queries.
- Visualization of query-processing workflows using LangGraph's `MermaidDrawMethod`.

**Applications**:
- Querying structured data in databases with ease.
- Building intelligent customer-facing or internal query agents.
- Demonstrating advanced use cases of LLMs in data management.

**Future Enhancements**:
- Integration with larger datasets and real-world database schemas.
- Extending support for complex analytical queries.
- Incorporating additional natural language understanding capabilities.


