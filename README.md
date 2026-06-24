# Welcome to the AI App Builders Program!

## Day 1: AI Application Foundations (Using AI)

### Tasks

- Explore the following basic DIY AI Application Workflow

  <img src="basic-ai-app-workflow.png">

  using the following AI Stack:

  * Open WebUI
  * Ollama
  * LLMs (Qwen, Gemma, Phi, LLama)

### Activities

  * Chat
  * _Visual Question Answering (VQA)_
  * Document _Retrieval Augmented-Generation (RAG)_
  * Model switching for performance comparison and multimodality

### Outcome

- _"I understand the components and structure of an AI application."_
	
## Day 2: Building a Custom AI App (Connecting AI to Software)

### Task

- Combine AI stack with Streamlit frontend**
	
  <img src="connect-ai-to-software.png">

### Activities
	
* Text-to-SQL
* Data analysis and Visualization of AI output (Charts, Graphs)
	
### Outcome

- _"I can build my own interface."_

## Day 3: RAG Pipelines (Connecting AI to Knowledge)

### Tasks
- Understand and construct RAG pipelines for documents and images using Dify workflows
  
- **Document RAG**

  <img src="document-rag.png">

- **Image RAG**

  <img src="image-rag.png">

### Activities
- Summarize PDFs, Markdown, etc docs
- Perform semantic search and querying on private image collection
  
### Outcome
- _"I understand how AI remembers and retrieves information."_

## Day 4: Tool Calling and AI Agents (Connecting AI to Systems)

### Task

- Implement Dify workflows for tool use and simple AI agents
  
  <img src="tool-calling.png">

### Activities
- Implement tools
  * Calculator tool
  * Weather tool
  * Database tool
  * Web search tool

- Tool calling and agent loops

  ```text
  Question
    ↓
  Agent
    ↓
  Choose Tool
    ↓
  Answer
  ```

### Outcome
- _"I understand how AI takes actions."_

<!--
Notice this is not yet CrewAI territory.

No need for:

```text
Planner Agent
Research Agent
Writer Agent
Critic Agent
```
-->

## Day 5: Capstone Projects

### Activity Planner

- Assumptions
  - Weather Forecast for the month
  - School academic and sports calender with major events
  - Open/Close times for fields, swimming pool, gym
  - Maintanance schedules (e.g. swimming pool, fields, gym)
- Based on total activity time required (for the month), and the factors above, the agent should be able to provide schedule for the activity and even suggest alternatives
  
### AI-Powered Photo Ablum Manager
- Auto update of knowledge base upon add/remove of images
- Visual and image description search modes
- structured retriveal modes e.g. based on dates/period, size, type (jpg, png), etc
- Cool UI

