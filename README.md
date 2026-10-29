# Multi-Agent AI Research and Content Generation

## Project Overview

A Python-based AI agent workflow built with CrewAI, Google Gemini, and Serper web search. The project is designed to automate AI industry research and turn research findings into an accessible blog post.

## Architecture

The workflow consists of two specialized agents:

1. **Market Researcher** — researches AI industry trends using a configured web-search tool.
2. **Blog Writer** — transforms research findings into an informative blog post.

The agents are orchestrated using CrewAI's sequential task process.

## Technologies

- Python
- Google Colab
- CrewAI
- Google Gemini API
- SerperDevTool
- Python asynchronous execution

## Project Workflow

1. Configure API credentials using Colab Secrets.
2. Initialize the Gemini language model.
3. Configure the search tool.
4. Define the researcher and writer agents.
5. Assign research and writing tasks.
6. Run the crew and inspect the generated output.

## Setup

Install the required packages in Google Colab:

```python
%pip install crewai crewai-tools langchain-google-genai
```

Configure `GOOGLE_API_KEY` and `SERPER_API_KEY` in Colab Secrets and enable notebook access. Never commit API keys to the repository.

## Project Status

Prototype developed. Validate successful end-to-end execution and review the generated output before treating the workflow as production-ready.

## Learning Outcomes

- Multi-agent workflow design
- LLM integration
- Tool-enabled AI agents
- Task orchestration
- API credential management
- Troubleshooting model compatibility and asynchronous execution
# crewai-multi-agent-ai-research
Multi-agent AI research and content generation using CrewAI, Google Gemini, and Serper web search.
