# AI Agent Development

## Project Title
Self-Correcting SQL Agent

## Objective
Build an AI agent that converts natural language questions into SQL, executes the query, detects errors, and corrects them automatically.

## Agent Loop
Perceive → Plan → Act → Observe → Repeat

## Technology
- Python
- OpenAI API
- SQLite
- Python-dotenv

## Features
- Real LLM call
- SQL generation
- SQL execution
- Error detection
- Self-correction
- Maximum iteration limit
- Iteration logging

## Workflow
User Question  
→ Generate SQL  
→ Execute SQL  
→ Observe Result  
→ Correct Error  
→ Retry  
→ Final Result
