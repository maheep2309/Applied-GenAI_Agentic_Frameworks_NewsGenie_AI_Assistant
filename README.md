# Applied-GenAI_Agentic-Frameworks_NewsGenieAI-Assistant_using-LangGrraph
An AI-powered news assistant built using LangGraph, ReAct Agents, NewsAPI and Tavily Search. It intelligently classifies queries, routes requests through specialized workflows and leverages conversational memory to deliver real-time, context-aware and trustworthy responses.

# Project Summary
The NewsGenie project is a conversational AI assistant developed to simplify news discovery and information retrieval by enabling users to interact with news and general knowledge topics using natural language. Built using a LangGraph-based Agentic AI architecture, the solution combines intelligent query classification, dynamic workflow orchestration, real-time news retrieval, web search enrichment and conversational response generation.

The system first classifies user requests based on query type (News or General) and query intent (New Topic or Follow-Up), before dynamically routing them through specialized workflows. News-related queries leverage NewsAPI to retrieve real-time news content and Tavily Search to enrich articles with additional context, while General Queries are handled through a dedicated ReAct Agent capable of reasoning and selectively invoking external search tools. Contextual News Follow-Up queries are managed through a specialized ReAct Agent with access to both NewsAPI and Tavily Search, enabling deeper exploration of previously discussed topics.

To support multi-turn conversations, the solution incorporates Gradio Session Management, LangGraph State Management and SQLite Checkpointing; ensuring conversational continuity and persistent workflow state across interactions. Dedicated error handling, fallback mechanisms, API validation and LLM failure recovery strategies improve solution resilience and user experience. The application is exposed through an intuitive Gradio-based user interface, allowing users to seamlessly interact with the underlying multi-agent system.

Overall, the project demonstrates how Agentic AI, workflow orchestration, external tool integration and conversational memory can be combined to create an intelligent, context-aware news and information assistant capable of transforming raw information into actionable insights.

Agentic AI Concepts / Topics Covered
- Agentic AI Workflow Orchestration using LangGraph
- Multi-Agent Architecture
- Intelligent Query Classification
- Dynamic Workflow Routing
- ReAct Agents
- Tool Calling & External API Integration
- Real-Time News Retrieval using NewsAPI
- Web Search & Information Enrichment using Tavily
- Context-Aware Follow-Up Conversations
- Conversational Memory Management
- Graph State Management
- SQLite Checkpointing & Persistence
- Session Management
- Prompt Engineering
- Structured Output Enforcement using Pydantic
- LLM-Powered Reasoning & Decision Making
- Error Handling & Recovery Workflows
- Technical & Semantic Fallback Strategies
- Hallucination Prevention Techniques
- Source Validation & Trustworthy Response Generation
- Human-AI Interaction using Gradio UI
