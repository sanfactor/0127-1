# Elena Framework

Elena is a multi-agent AI framework built on top of DeepSeek's advanced language model capabilities. It provides a robust infrastructure for creating and managing autonomous AI agents that can collaborate effectively on complex tasks.

## Features

- Built on DeepSeek's MoE architecture
- Efficient token activation system
- Multi-agent collaboration
- Task orchestration and management
- Flexible communication protocols
- Tool integration capabilities

## Installation

```bash
pip install -r requirements.txt
```

## Usage

```python
from elena import AgentGroup, DeepSeekAgent

# Create agents
agent1 = DeepSeekAgent(role="assistant")
agent2 = DeepSeekAgent(role="researcher")

# Create agent group
group = AgentGroup([agent1, agent2])

# Execute task
result = group.execute_task("Research and summarize recent AI developments")
```

## License

MIT License
