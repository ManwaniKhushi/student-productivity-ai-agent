# Student Productivity AI Agent

An AI-powered student productivity assistant built and deployed using IBM watsonx Orchestrate.

The agent helps college students organize academic work, prioritize tasks, create realistic study plans, and find relevant learning resources through web search.

## Project Overview

The Student Productivity Agent is designed to help students manage academic tasks based on their goals, deadlines, available study time, and current learning needs.

The agent can:
- Understand study goals and requirements
- Prioritize academic tasks
- Break large tasks into smaller actionable steps
- Create time-constrained study plans
- Search the web for relevant learning resources
- Adapt plans based on available study time
- Ask clarifying questions when important information is missing

## Technologies Used

- IBM watsonx Orchestrate
- Large Language Model (LLM)
- Exa Web Search
- MCP (Model Context Protocol)
- LLM-as-a-Judge evaluation

## Architecture

```text
Student
   ↓
Student Productivity Agent
   ↓
LLM
   ↓
 ┌───────────────────────┐
 │   Agent Instructions  │
 │   Task Prioritization │
 │   Study Planning      │
 └───────────────────────┘
   ↓
Exa Web Search
   ↓
Learning Resources
   ↓
Personalized Study Plan
