# Overview

Exploring various types of AI agents built using Google ADK (Agent Development Kit).
It covers how different agents behave, how they use tools, manage state, produce structured outputs, and execute callbacks.

---

# Agent Types Explored 🤖

1. Basic Agent
![setup](https://github.com/Reshmagvs/Google_adk_agents/blob/main/ag_3.png)
A simple conversational agent that responds purely based on prompts without external tools.
Ideal for understanding core LLM behavior and basic message handling.

2. Basic Agent with Tool
![setup](https://github.com/Reshmagvs/Google_adk_agents/blob/main/ag_4.png)
Enhances a basic agent by allowing it to call external tools for extra functionality.
Useful for fetching information, performing tasks, or integrating APIs.

3. Agent with State
![setup](https://github.com/Reshmagvs/Google_adk_agents/blob/main/ag_5.png)
Maintains memory within a session, allowing the agent to remember previous interactions.
Perfect for tasks requiring context retention, personalization, or step-by-step reasoning.

4. Multi-Tool Agent
![setup](https://github.com/Reshmagvs/Google_adk_agents/blob/main/ag_6.png)
An advanced agent capable of accessing and selecting from multiple tools dynamically.
Enables richer workflows where the agent decides the correct tool depending on the query.

5. Structured Output Agent
![setup](https://github.com/Reshmagvs/Google_adk_agents/blob/main/ag_7.png)
Produces responses in predefined formats such as JSON, tables, or schemas.
Ensures consistent, predictable outputs for integrations and automation pipelines.

6. Callback Agent
![setup](https://github.com/Reshmagvs/Google_adk_agents/blob/main/ag_8.png)
Executes custom callback functions during the reasoning process.
Allows monitoring intermediate steps, logging, or dynamically influencing the agent’s decisions.

---

# Technologies Used

Google ADK (Agent Development Kit)
Python
LLM-based agent frameworks
Tooling architecture & state management concepts
