# Multi-AIAgents crewAI Projects

This repository contains a collection of hands-on projects developed while learning from the courses:
- **Multi AI Agent Systems with crewAI**
- **Practical Multi AI Agents and Advanced Use Cases with crewAI**

These short, project-based courses focus on practical implementations of **multi-agent AI systems** using the **crewAI framework**. The repository highlights different approaches, architectures, and use cases of multi-agent systems, showcasing how multiple AI agents can collaborate to solve complex tasks.

---

## Repository Structure

Each project folder contains:
- **`<Project_Name>.ipynb`** – Main Jupyter Notebook with project implementation.
- **`helper.py`** – Python helper functions used within the project.
- **`requirements.txt`** – Python dependencies for the project.
- **`config/`** – Configuration files:
  - `agents.yaml` – Defines the agents, roles, and capabilities.
  - `tasks.yaml` – Defines the tasks assigned to agents.

---

## Projects Overview

### 1. **Automated Project Planner**
- Demonstrates **multi-agent collaboration** for automated project planning.
- Includes a **cost calculation mechanism** for estimating the expense of running multiple agents.
- Focuses on breaking down a high-level task into subtasks and delegating them across agents.

### 2. **Agentic Sales Pipeline**
- Showcases how **different crews work together in a sales pipeline** using the **Flow architecture**.
- Simulates real-world sales processes with autonomous decision-making by agents.

### 3. **Support Data Insight Analysis**
- Covers **training and testing of AI crews** for data analysis.
- Implements **human-feedback-based fine-tuning** of AI agents to improve decision quality and insights.

### 4. **Content Creation at Scale**
- Demonstrates how to **optimize task performance** by using **different LLMs for different agents**.
- Shows the efficiency of role-specific LLM assignments for generating scalable content.

### 5. **Building Crew for Production**
- Focuses on **creating production-ready environments** with crewAI.
- Teaches how to deploy AI crews in a real-world production scenario.

---

## Key Learnings
- Building and configuring **multi-agent systems** with crewAI.
- Using **agents.yaml** and **tasks.yaml** to define roles, workflows, and task breakdowns.
- Applying **Flow architectures** for coordinated decision-making between agents.
- Optimizing performance by **selecting specialized LLMs for different agent roles**.
- Leveraging **human feedback loops** for fine-tuning agent performance.
- Understanding **cost estimation and monitoring** in multi-agent deployments.
- Deploying AI crews in **production-ready environments**.

---

## Installation and Setup

To set up the environment for any project:
```bash
git clone https://github.com/nishxnt/Multi-AIAgents_crewAI_Projects.git
cd <Project_Folder>
pip install -r requirements.txt

## Framework Used

All projects are built using **crewAI**, a framework for designing, training, evaluating, and orchestrating multi‑agent AI systems with clear role/task separation through YAML configs (`agents.yaml`, `tasks.yaml`) and support for flows, cost tracing, and production deployment patterns.

---

## Future Scope

- Add more **real-world case studies** (e.g., analytics, BI copilots, agentic RAG, fintech ops).
- Experiment with **advanced multi-agent coordination strategies** (flows, routers, supervisors, tool-using agents).
- Explore **LLM routing / model specialization** (open-weight vs API LLMs, cost–latency–quality trade-offs).
- Integrate **human-feedback loops (RLAIF/RLHF)** and reward models for continuous improvement.
- Build a stronger **evaluation & observability harness** (cost, latency, success rate, calibration).
- Hardening for **production**: Dockerization, CI/CD, feature flags, secrets management, and deployment on Ray Serve/FastAPI.

---

## Author

**Nishant Gupta**  
Exploring multi-agent systems with crewAI to design efficient, collaborative AI solutions that are production-ready and cost-aware.

(GitHub: [@nishxnt](https://github.com/nishxnt))
