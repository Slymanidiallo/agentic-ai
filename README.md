# Agentic AI, MCP & Workflow Automation

> **EN:** Experiments, notebooks and learning resources focused on AI agents, Model Context Protocol (MCP), retrieval-augmented generation and workflow automation.  
> **FR :** Expérimentations, notebooks et ressources autour des agents IA, du Model Context Protocol (MCP), du RAG et de l'automatisation des workflows.

## 🇬🇧 English

### Overview
This repository is a collection of agentic-AI experiments and supporting learning material. The code includes examples built with the OpenAI Agents SDK and MCP servers, along with Streamlit demonstrations and JSON configuration files.

### Main components observed
- `agent_mcp.py`: connects an agent to a local filesystem MCP server using `MCPServerStdio`.
- `server.py`, `streamin-ui-agent-mcp.py`, `streamin-ui-demo.py`: MCP/server and Streamlit-related experiments.
- `Digital_Marketer_Agent.json`: agent configuration/data.
- `digital_mcp_client.json`, `digital_mcp_server.json`: MCP-related configuration files.
- Jupyter notebook and PDF resources on agentic AI, multi-model RAG and AI for education.

### Requirements
The project metadata specifies Python 3.11+ and dependencies including:
- `openai-agents[viz]`
- `python-dotenv`
- `streamlit`
- `pydantic`
- `ipykernel`

### Setup
```bash
git clone https://github.com/Slymanidiallo/agentic-ai.git
cd agentic-ai
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
pip install -e .
```

The MCP filesystem example also requires Node.js/npm and `npx`. It creates and exposes a local `sample_files/` directory to the MCP server. Configure any required API credentials through environment variables; never commit secrets.

### Demo
[Watch the Agentic AI & Workflow Automation demo](https://www.youtube.com/watch?v=wc7AjaMsE50)

## 🇫🇷 Français

### Présentation
Ce dépôt regroupe des expérimentations autour de l'IA agentique et des ressources pédagogiques. Le code comprend des exemples utilisant l'OpenAI Agents SDK, des serveurs MCP, des démonstrations Streamlit et des fichiers de configuration JSON.

### Principaux éléments
- `agent_mcp.py` : connecte un agent à un serveur MCP local de système de fichiers avec `MCPServerStdio`.
- `server.py`, `streamin-ui-agent-mcp.py`, `streamin-ui-demo.py` : expérimentations autour des serveurs MCP et de Streamlit.
- `Digital_Marketer_Agent.json` : configuration/données d'agent.
- `digital_mcp_client.json`, `digital_mcp_server.json` : fichiers de configuration liés à MCP.
- Notebook et documents PDF sur l'IA agentique, le RAG multimodèle et l'IA pour l'éducation.

### Dépendances
Le fichier `pyproject.toml` indique Python 3.11+ et notamment :
- `openai-agents[viz]`
- `python-dotenv`
- `streamlit`
- `pydantic`
- `ipykernel`

### Installation
```bash
git clone https://github.com/Slymanidiallo/agentic-ai.git
cd agentic-ai
python -m venv .venv
# Windows : .venv\Scripts\activate
# macOS/Linux : source .venv/bin/activate
pip install -e .
```

L'exemple MCP avec le système de fichiers nécessite également Node.js/npm et `npx`. Il expose un dossier local `sample_files/`. Placez les clés API dans des variables d'environnement et ne publiez jamais de secrets.

### Démonstration
[Voir la démonstration Agentic AI & Workflow Automation](https://www.youtube.com/watch?v=wc7AjaMsE50)

### Organisation du dépôt
Ce dépôt contient aussi des supports de formation et de conférence. Les PDF et notebooks sont des ressources complémentaires ; tous ne correspondent pas nécessairement à un module exécutable de l'application.
