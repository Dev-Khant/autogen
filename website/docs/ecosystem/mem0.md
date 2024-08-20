# Mem0 Platform: AI Memory Management and Personalization

<img src="https://github.com/mem0ai/mem0/blob/main/docs/images/mem0-bg.png?raw=true" alt="Mem0 logo" style="width: 40%;" />

[Mem0 Platform](https://www.mem0.ai/) provides a smart, self-improving memory layer for Large Language Models (LLMs), enabling developers to create personalized AI experiences that evolve with each user interaction.

At a high level, Mem0 Platform offers comprehensive memory management, self-improving memory capabilities, cross-platform consistency, and centralized memory control for AI applications. For more info, check out the [Mem0 Platform Documentation](https://docs.mem0.ai).

|                                          |                                                                   |
| ---------------------------------------- | ----------------------------------------------------------------- |
| 🧠 **Comprehensive Memory Management**   | Manage long-term, short-term, semantic, and episodic memories     |
| 🔄 **Self-Improving Memory**             | Adaptive system that learns from user interactions                |
| 🌐 **Cross-Platform Consistency**        | Unified user experience across various AI platforms               |
| 🎛️ **Centralized Memory Control**        | Effortless storage, updating, and deletion of memories            |
| 🚀 **Simplified Development**            | API-first approach for streamlined integration                    |

<details open>
  <summary><b><u>Activity Dashboard</u></b></summary>
  <a href="https://app.mem0.ai/">
   <img src="https://github.com/mem0ai/mem0/blob/main/docs/images/platform/activity.png?raw=true" style="width: 70%;" alt="Activity Dashboard"/>
  </a>
</details>

## Installation

Mem0 Platform works seamlessly with various AI applications.

1. **Sign Up:**
Create an account at [Mem0 Platform](https://app.mem0.ai/)

2. **Generate API Key:**
Create an API key in your Mem0 dashboard

3. **Install Mem0 SDK:**
```bash
pip install mem0ai
```

4. **Configure Your Environment:**
Add your API key to your environment variables

```
MEM0_API_KEY=<YOUR_MEM0_API_KEY>
```

5. **Initialize Mem0:**

```python
from mem0ai import MemoryClient
memory = MemoryClient(api_key=os.getenv("MEM0_API_KEY"))
```

After initializing Mem0, you can start using its memory management features in your AI application.

## Features

- **Long-term Memory**: Store and retrieve information persistently across sessions
- **Short-term Memory**: Manage temporary information within a single interaction
- **Semantic Memory**: Organize and retrieve conceptual knowledge
- **Episodic Memory**: Store and recall specific events or experiences
- **Self-Improving System**: Continuously refine understanding based on user interactions

## Common Use Cases

- Personalized Learning Assistants
- Customer Support AI Agents
- Healthcare Assistants
- Virtual Companions

## Mem0 Platform Examples
* [Quickstart Guide](https://docs.mem0.ai/platform/quickstart)
