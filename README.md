# Automation Portfolio

Practical business automations built with Make.com, n8n, and AI services.

## Projects

| Project | What it does | Tools |
| --- | --- | --- |
| [AI Email Draft Assistant](projects/ai-email-draft-assistant/) | Watches Gmail, generates a professional reply with Gemini, and saves it as a draft for human review. | Make.com, Gmail, Gemini 2.5 Flash |
| [Smart UPF Multi-Agent Assistant](projects/smart-upf-multi-agent-assistant/) | Handles university questions with specialist agents, Redis caching, PostgreSQL logging, supervisor validation, and Grafana dashboards. | n8n, Ollama, Redis, PostgreSQL, Grafana |
| [Smart UPF Multi-Agent System](projects/smart-upf-multi-agent-system/) | Routes university questions to five specialist AI agents for academic, planning, reception, PFE, and website information. | n8n, Groq, MCP |
| [RAG Customer Support Chatbot](projects/chatbot-rag/) | Answers support questions from indexed documentation with retrieval, memory, authentication checks, and rate limiting. | n8n, Groq, Pinecone, Ollama |
| [Documentation Indexing Pipeline](projects/documentation-indexing/) | Extracts, chunks, embeds, and indexes documents for semantic retrieval. | n8n, Pinecone, Ollama |
| [Customer Support Chatbot](projects/customer-support-chatbot/) | Provides scoped ecommerce support with conversation memory and clear escalation boundaries. | n8n, Groq |

## Portfolio Principles

- Human approval remains in the loop for external communication.
- Published blueprints are sanitized and contain no credentials.
- Documentation focuses on the business problem, workflow, and practical value.
- Results are described honestly without invented performance metrics.

## Repository Structure

```text
automation-portfolio/
|-- README.md
|-- LICENSE
`-- projects/
    |-- ai-email-draft-assistant/
    |-- smart-upf-multi-agent-assistant/
    |-- smart-upf-multi-agent-system/
    |-- chatbot-rag/
    |-- documentation-indexing/
    `-- customer-support-chatbot/
```

## Security

Connection identifiers, credentials, local paths, private contact details, and instance-specific workflow IDs are removed from published exports. Configure your own services after import.
