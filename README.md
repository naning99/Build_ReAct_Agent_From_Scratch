# 1. Reference: 
https://www.youtube.com/watch?v=hKVhRA9kfeM


# 2. ReAct: 

Paper Reference: https://arxiv.org/abs/2210.03629

Concept Explanation: Combining Reasoning & Acting. Imagine when you use chatgpt to ask a question. You normally cannot obtain the final answer from the first generation. 
Everytime gpt gives you an answer, it will serve as context to another round of generation. Continue this loop until the final answer is generated. Now an ReAct Agent
is going to imitate this process in the loop of [Thought] - [Action] - [Observation] 

<img width="478" alt="image" src="https://github.com/user-attachments/assets/55604d26-6433-4ccf-a7ae-9a53e0adf122">

Multi-agent frameworks such as Langgraph, CrewAI, AutoGen often incorporate the ReAct paradigm in their design.

# 3. Code Design
  - Define Agent Class
    Key components: LLM client, system prompt, user input, assistant response, messages
  - System Prompt: Describe as ReAct paradigm
  - Define Tools: any functions / externel tools
  - Define Agent Loop to imitate the loop of [Thought] - [Action] - [Observation]
    

