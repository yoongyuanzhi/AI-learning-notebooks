# AI Learning Notebooks

Working through a weekly study plan of AI cookbook notebooks — tool/function calling, RAG, agents, and MCP. Each week's notebook lives in its own `Week_N/` folder.

Weeks 1–25 are the ranked core path (fundamentals → RAG → tool calling → agents → MCP → agentic RAG capstone). Everything marked **Extra** is optional / overlapping / deeper-dive — do any of them in any order once the core is done.

> Tip: the [Hugging Face MCP Course](https://github.com/huggingface/mcp-course) is the best end-to-end MCP walkthrough, but it's a course rather than a single `.ipynb`.

## Core path

| Week | Source | Topic | Notebook | Concept | Link |
|---|---|---|---|---|---|
| 1 | OpenAI Cookbook | Tool / function calling basics | `How_to_call_functions_with_chat_models.ipynb` | Tool calling | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_call_functions_with_chat_models.ipynb) |
| 2 | Anthropic Claude Cookbooks | Tool use fundamentals (calculator) | `tool_use/calculator_tool.ipynb` | Tool calling | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/tool_use/calculator_tool.ipynb) |
| 3 | Mistral Cookbook | Function calling on another API | `mistral/function_calling/function_calling.ipynb` | Tool calling | [Open notebook](https://github.com/mistralai/cookbook/blob/main/mistral/function_calling/function_calling.ipynb) |
| 4 | OpenAI Cookbook | Embeddings + Q&A (RAG foundation) | `Question_answering_using_embeddings.ipynb` | RAG | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/Question_answering_using_embeddings.ipynb) |
| 5 | Mistral Cookbook | Basic RAG end-to-end | `mistral/rag/basic_RAG.ipynb` | RAG | [Open notebook](https://github.com/mistralai/cookbook/blob/main/mistral/rag/basic_RAG.ipynb) |
| 6 | OpenAI Cookbook | RAG with a vector DB (Pinecone) | `vector_databases/pinecone/Gen_QA.ipynb` | RAG | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/vector_databases/pinecone/Gen_QA.ipynb) |
| 7 | Hugging Face Cookbook | Advanced RAG with LangChain | `advanced_rag` | RAG | [Open notebook](https://huggingface.co/learn/cookbook/en/advanced_rag) |
| 8 | Hugging Face Cookbook | RAG evaluation | `rag_evaluation` | RAG | [Open notebook](https://huggingface.co/learn/cookbook/en/rag_evaluation) |
| 9 | Advanced RAG (athina-ai) | Hybrid search RAG (vector + BM25) | `advanced_rag_techniques/hybrid_rag.ipynb` | RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/advanced_rag_techniques/hybrid_rag.ipynb) |
| 10 | Advanced RAG (athina-ai) | HyDE RAG (hypothetical doc embeddings) | `advanced_rag_techniques/hyde_rag.ipynb` | RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/advanced_rag_techniques/hyde_rag.ipynb) |
| 11 | Advanced RAG (athina-ai) | Contextual RAG (compression/rerank) | `advanced_rag_techniques/contextual_rag.ipynb` | RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/advanced_rag_techniques/contextual_rag.ipynb) |
| 12 | Hugging Face Cookbook | Graph RAG with knowledge graphs (Neo4j) | `rag_with_knowledge_graphs_neo4j` | RAG | [Open notebook](https://huggingface.co/learn/cookbook/en/rag_with_knowledge_graphs_neo4j) |
| 13 | Anthropic Claude Cookbooks | Tool-calling agent (customer service) | `tool_use/customer_service_agent.ipynb` | Agents + Tool calling | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/tool_use/customer_service_agent.ipynb) |
| 14 | Hugging Face Cookbook | Build a tool-calling agent (smolagents) | `agents` | Agents | [Open notebook](https://huggingface.co/learn/cookbook/en/agents) |
| 15 | Mistral Cookbook | Agents & tools (LlamaIndex) | `third_party/LlamaIndex/Agents_Tools.ipynb` | Agents | [Open notebook](https://github.com/mistralai/cookbook/blob/main/third_party/LlamaIndex/Agents_Tools.ipynb) |
| 16 | OpenAI Cookbook | Agent memory / context engineering | `agents_sdk/session_memory.ipynb` | Agents | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/agents_sdk/session_memory.ipynb) |
| 17 | OpenAI Cookbook | Multi-agent collaboration (Agents SDK) | `agents_sdk/multi-agent-portfolio-collaboration/multi_agent_portfolio_collaboration.ipynb` | Agents | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/agents_sdk/multi-agent-portfolio-collaboration/multi_agent_portfolio_collaboration.ipynb) |
| 18 | Hugging Face Cookbook | Multi-agent RAG system | `multiagent_rag_system` | Agents + RAG | [Open notebook](https://huggingface.co/learn/cookbook/en/multiagent_rag_system) |
| 19 | Google Gemini Cookbook | Managed agents (Antigravity) | `quickstarts/Get_started_managed_agents.ipynb` | Agents | [Open notebook](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Get_started_managed_agents.ipynb) |
| 20 | OpenAI Cookbook | MCP tool basics (Responses API) | `mcp/mcp_tool_guide.ipynb` | MCP | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/mcp/mcp_tool_guide.ipynb) |
| 21 | OpenAI Cookbook | MCP servers + Agents SDK (Databricks) | `mcp/databricks_mcp_cookbook.ipynb` | MCP + Agents | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/mcp/databricks_mcp_cookbook.ipynb) |
| 22 | OpenAI Cookbook | MCP + Codex CLI + Agents SDK | `codex/codex_mcp_agents_sdk/building_consistent_workflows_codex_cli_agents_sdk.ipynb` | MCP + Agents | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/codex/codex_mcp_agents_sdk/building_consistent_workflows_codex_cli_agents_sdk.ipynb) |
| 23 | Advanced RAG (athina-ai) | Agentic RAG basics | `agentic_rag_techniques/basic_agentic_rag.ipynb` | Agents + RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/agentic_rag_techniques/basic_agentic_rag.ipynb) |
| 24 | Advanced RAG (athina-ai) | Corrective RAG (CRAG) | `agentic_rag_techniques/corrective_rag.ipynb` | Agents + RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/agentic_rag_techniques/corrective_rag.ipynb) |
| 25 | OpenAI Cookbook | Capstone: multi-tool orchestration + RAG | `responses_api/responses_api_tool_orchestration.ipynb` | Agents + Tool + RAG | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/responses_api/responses_api_tool_orchestration.ipynb) |

## Extras

| Week | Source | Topic | Notebook | Concept | Link |
|---|---|---|---|---|---|
| Extra | OpenAI Cookbook | Functions with a knowledge base | `How_to_call_functions_for_knowledge_retrieval.ipynb` | Tool calling + RAG | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/How_to_call_functions_for_knowledge_retrieval.ipynb) |
| Extra | OpenAI Cookbook | Function calling: nearby places | `Function_calling_finding_nearby_places.ipynb` | Tool calling | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/Function_calling_finding_nearby_places.ipynb) |
| Extra | OpenAI Cookbook | Function calling with reasoning models | `o-series/o3o4-mini_prompting_guide.ipynb` | Tool calling | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/o-series/o3o4-mini_prompting_guide.ipynb) |
| Extra | OpenAI Cookbook | Embedding Wikipedia for search | `Embedding_Wikipedia_articles_for_search.ipynb` | RAG / embeddings | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/Embedding_Wikipedia_articles_for_search.ipynb) |
| Extra | OpenAI Cookbook | Semantic text search with embeddings | `Semantic_text_search_using_embeddings.ipynb` | RAG / embeddings | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/Semantic_text_search_using_embeddings.ipynb) |
| Extra | OpenAI Cookbook | HyDE with Chroma | `vector_databases/chroma/hyde-with-chroma-and-openai.ipynb` | RAG | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/vector_databases/chroma/hyde-with-chroma-and-openai.ipynb) |
| Extra | OpenAI Cookbook | Image understanding with RAG | `multimodal/image_understanding_with_rag.ipynb` | Multimodal RAG | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/multimodal/image_understanding_with_rag.ipynb) |
| Extra | OpenAI Cookbook | AgentKit walkthrough | `agentkit/agentkit_walkthrough.ipynb` | Agents | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/agentkit/agentkit_walkthrough.ipynb) |
| Extra | OpenAI Cookbook | Dispute agent (Agents SDK + Stripe) | `agents_sdk/dispute_agent.ipynb` | Agents | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/agents_sdk/dispute_agent.ipynb) |
| Extra | OpenAI Cookbook | MCP-powered voice agents | `partners/mcp_powered_voice_agents/mcp_powered_agents_cookbook.ipynb` | MCP + Agents | [Open notebook](https://github.com/openai/openai-cookbook/blob/main/examples/partners/mcp_powered_voice_agents/mcp_powered_agents_cookbook.ipynb) |
| Extra | Anthropic Claude Cookbooks | SQL queries via tools | `misc/how_to_make_sql_queries.ipynb` | Tool calling | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/misc/how_to_make_sql_queries.ipynb) |
| Extra | Anthropic Claude Cookbooks | RAG with Pinecone | `third_party/Pinecone/rag_using_pinecone.ipynb` | RAG | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/third_party/Pinecone/rag_using_pinecone.ipynb) |
| Extra | Anthropic Claude Cookbooks | RAG with MongoDB | `third_party/MongoDB/rag_using_mongodb.ipynb` | RAG | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/third_party/MongoDB/rag_using_mongodb.ipynb) |
| Extra | Anthropic Claude Cookbooks | Wikipedia search cookbook | `third_party/Wikipedia/wikipedia-search-cookbook.ipynb` | RAG / search | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/third_party/Wikipedia/wikipedia-search-cookbook.ipynb) |
| Extra | Anthropic Claude Cookbooks | Sub-agents (Haiku under Opus) | `multimodal/using_sub_agents.ipynb` | Agents | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/multimodal/using_sub_agents.ipynb) |
| Extra | Anthropic Claude Cookbooks | Getting started with vision | `multimodal/getting_started_with_vision.ipynb` | Multimodal | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/multimodal/getting_started_with_vision.ipynb) |
| Extra | Anthropic Claude Cookbooks | Prompt caching (cost optimization) | `misc/prompt_caching.ipynb` | Optimization | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/misc/prompt_caching.ipynb) |
| Extra | Anthropic Claude Cookbooks | Building evals | `misc/building_evals.ipynb` | Evaluation | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/misc/building_evals.ipynb) |
| Extra | Anthropic Claude Cookbooks | JSON mode | `misc/how_to_enable_json_mode.ipynb` | Structured output | [Open notebook](https://github.com/anthropics/claude-cookbooks/blob/main/misc/how_to_enable_json_mode.ipynb) |
| Extra | Google Gemini Cookbook | Get started (fundamentals) | `quickstarts/Get_started.ipynb` | Fundamentals | [Open notebook](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Get_started.ipynb) |
| Extra | Google Gemini Cookbook | Grounding (search grounding) | `quickstarts/Grounding.ipynb` | RAG / grounding | [Open notebook](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Grounding.ipynb) |
| Extra | Google Gemini Cookbook | File Search | `quickstarts/File_Search.ipynb` | RAG | [Open notebook](https://github.com/google-gemini/cookbook/blob/main/quickstarts/File_Search.ipynb) |
| Extra | Google Gemini Cookbook | Code execution | `quickstarts/Code_Execution.ipynb` | Tool calling | [Open notebook](https://github.com/google-gemini/cookbook/blob/main/quickstarts/Code_Execution.ipynb) |
| Extra | Hugging Face Cookbook | Simple RAG (Zephyr + LangChain) | `rag_zephyr_langchain` | RAG | [Open notebook](https://huggingface.co/learn/cookbook/en/rag_zephyr_langchain) |
| Extra | Hugging Face Cookbook | RAG with Milvus | `rag_with_hf_and_milvus` | RAG | [Open notebook](https://huggingface.co/learn/cookbook/en/rag_with_hf_and_milvus) |
| Extra | Hugging Face Cookbook | Text-to-SQL agent (auto error correction) | `agent_text_to_sql` | Agents | [Open notebook](https://huggingface.co/learn/cookbook/en/agent_text_to_sql) |
| Extra | Hugging Face Cookbook | Data analyst agent | `agent_data_analyst` | Agents | [Open notebook](https://huggingface.co/learn/cookbook/en/agent_data_analyst) |
| Extra | Hugging Face Cookbook | Multi-agent web assistant (hierarchy) | `multiagent_web_assistant` | Agents | [Open notebook](https://huggingface.co/learn/cookbook/en/multiagent_web_assistant) |
| Extra | Hugging Face Cookbook | Multimodal RAG (ColPali + VLMs) | `multimodal_rag_using_document_retrieval_and_vlms` | Multimodal RAG | [Open notebook](https://huggingface.co/learn/cookbook/en/multimodal_rag_using_document_retrieval_and_vlms) |
| Extra | Hugging Face Cookbook | RAG backed by SQL + Jina reranker | `rag_with_sql_reranker` | RAG | [Open notebook](https://huggingface.co/learn/cookbook/en/rag_with_sql_reranker) |
| Extra | Mistral Cookbook | Text-to-SQL via function calling | `mistral/function_calling/text_to_SQL.ipynb` | Tool calling | [Open notebook](https://github.com/mistralai/cookbook/blob/main/mistral/function_calling/text_to_SQL.ipynb) |
| Extra | Mistral Cookbook | RAG via function calling | `mistral/rag/RAG_via_function_calling.ipynb` | RAG | [Open notebook](https://github.com/mistralai/cookbook/blob/main/mistral/rag/RAG_via_function_calling.ipynb) |
| Extra | Mistral Cookbook | Agentic RAG (LlamaIndex) | `third_party/LlamaIndex/llamaindex_agentic_rag.ipynb` | Agents + RAG | [Open notebook](https://github.com/mistralai/cookbook/blob/main/third_party/LlamaIndex/llamaindex_agentic_rag.ipynb) |
| Extra | Mistral Cookbook | Bank support agent (Pydantic AI) | `third_party/PydanticAI/pydantic_bank_support_agent.ipynb` | Agents | [Open notebook](https://github.com/mistralai/cookbook/blob/main/third_party/PydanticAI/pydantic_bank_support_agent.ipynb) |
| Extra | Mistral Cookbook | Embeddings | `mistral/embeddings/embeddings.ipynb` | Embeddings | [Open notebook](https://github.com/mistralai/cookbook/blob/main/mistral/embeddings/embeddings.ipynb) |
| Extra | Mistral Cookbook | RAG with Pinecone | `third_party/Pinecone/pinecone_rag.ipynb` | RAG | [Open notebook](https://github.com/mistralai/cookbook/blob/main/third_party/Pinecone/pinecone_rag.ipynb) |
| Extra | Advanced RAG (athina-ai) | Naive RAG (baseline) | `advanced_rag_techniques/naive_rag.ipynb` | RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/advanced_rag_techniques/naive_rag.ipynb) |
| Extra | Advanced RAG (athina-ai) | Parent-document retriever | `advanced_rag_techniques/parent_document_retriever.ipynb` | RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/advanced_rag_techniques/parent_document_retriever.ipynb) |
| Extra | Advanced RAG (athina-ai) | Fusion RAG (RRF) | `advanced_rag_techniques/fusion_rag.ipynb` | RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/advanced_rag_techniques/fusion_rag.ipynb) |
| Extra | Advanced RAG (athina-ai) | Rewrite-retrieve-read | `advanced_rag_techniques/rewrite_retrieve_read.ipynb` | RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/advanced_rag_techniques/rewrite_retrieve_read.ipynb) |
| Extra | Advanced RAG (athina-ai) | Unstructured RAG (text+tables+images) | `advanced_rag_techniques/basic_unstructured_rag.ipynb` | RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/advanced_rag_techniques/basic_unstructured_rag.ipynb) |
| Extra | Advanced RAG (athina-ai) | Self-RAG | `agentic_rag_techniques/self_rag.ipynb` | Agents + RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/agentic_rag_techniques/self_rag.ipynb) |
| Extra | Advanced RAG (athina-ai) | Adaptive RAG | `agentic_rag_techniques/adaptive_rag.ipynb` | Agents + RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/agentic_rag_techniques/adaptive_rag.ipynb) |
| Extra | Advanced RAG (athina-ai) | ReAct RAG | `agentic_rag_techniques/react_rag.ipynb` | Agents + RAG | [Open notebook](https://github.com/athina-ai/rag-cookbooks/blob/main/agentic_rag_techniques/react_rag.ipynb) |

## Sources

| Source | Repo / site |
|---|---|
| OpenAI Cookbook | https://github.com/openai/openai-cookbook |
| Anthropic Claude Cookbooks | https://github.com/anthropics/claude-cookbooks |
| Google Gemini Cookbook | https://github.com/google-gemini/cookbook |
| Hugging Face Open-Source AI Cookbook | https://huggingface.co/learn/cookbook/index |
| Mistral Cookbook | https://github.com/mistralai/cookbook |
| Advanced RAG Cookbooks (athina-ai) | https://github.com/athina-ai/rag-cookbooks |
