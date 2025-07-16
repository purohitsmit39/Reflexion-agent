# Reflexion Agent System 🧠🤖

A modular reflexion agent built using LangGraph and LangChain.

## Features
- Reflection-based learning
- Modular LangGraph nodes
- Uses OpenAI LLM + Tools

## Project Structure
- `reflexion_graph.py`: Builds and runs the reflexion graph
- `chains.py`: Defines chain logic (task, critic, revisor)
- `prompts.py`: Prompt templates for each phase
- `utils.py`: Utility functions

## Setup

```bash
pip install -r requirements.txt
python reflexion_graph.py

