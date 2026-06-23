# Agentic Scientific Workflow Development for Galaxy

This project aims to develop an AI-assisted framework for creating scientific workflows in the Galaxy Scientific Workflow System. The framework will use natural language prompts, Galaxy tool metadata, and large language models to help users generate Galaxy-compatible workflows.

## Goal

The main goal of this project is to support automatic scientific workflow development in Galaxy. Given a user request, the system should understand the analysis goal, identify suitable Galaxy tools, create a workflow plan, and generate a valid Galaxy workflow.

## Motivation

Creating scientific workflows in Galaxy requires knowledge of available tools, input/output formats, parameter settings, and correct workflow connections. This project aims to reduce this complexity by assisting users in translating high-level analysis requirements into executable Galaxy workflows.

## Planned Features

- Understand user requests from natural language prompts
- Retrieve Galaxy tool information
- Select suitable tools for workflow steps
- Generate workflow plans
- Build Galaxy-compatible workflow files
- Validate generated workflows

## Initial Workflow

```text
User Prompt
   ↓
Prompt Understanding
   ↓
Tool Retrieval
   ↓
Workflow Planning
   ↓
Workflow Generation
   ↓
Workflow Validation
   ↓
Galaxy Workflow Export


### Session
**tmux new -s training_model

tmux attach -t training_model**

## Steps
1. preprocess_dataset.ipynb
