# ABZ AGENT SDK

The Fastest Way To Build AI Agents In Minutes

# Installition

```bash
pip install abzagent
```
After Installing You Need to set you GEMINI_API_KEY in your code like this
```bash
GEMINI_API_KEY = your_gemini_api_key_here
```
# Code Example

```bash
from abzagent import Agent
agent = Agent(
  name = "Assistant",
  instructions = "You are a helpfull assistant",
)
result = agent.run("What is the Capital Of France")
print(result)
```
# Result

```bash
The Capital Of France is ***Paris***
```
