# Agentic AI with Hybrid Planning

**Objective** is to outline the architecture as diagram, develop heuritstics, refine the decision prompt and test the code with several examples.

## High Level Plan
- [X] Setup the code base from existing architecture from class, python packages, run few examples
- [ ] Add pdb inspect steps to work through the steps to understand the execution flow
- [ ] Understand the folder structure and go over course materials
- [ ] Post a video in youtube, link :  




## Rough Notes
Start with the code shared. Your task is

Explain the Architecture in full detail, including a Chart/Graph (hand-drawn or using an app)
Fix an "error" in the framework, which will not allow you to run other queries shared in "agent.py"
Write 10 Heuristics that run on the query and results. Think of "removing banned words", etc.
Index your Past Historical Conversation and provide it to Your Agent. Do this very smartly, a lot of scores for this. 
decision_prompt_conservative.txt has 729 words. Reduce it to less than 300 without breaking performance. 
What are you submitting?

Architecture Diagram and report
Bug fix report.
Your GitHub Repo README file with details and 3 examples of full log (query>perception>decision>...>Result) for new queries NOT shared in agent.py file
Heuristic rule file link
historical_conversation_store.json (or similar)
New Decision prompt, direct Github link
Total Word count in your Decision Prompt
A YouTube Video showing:
Using the prompt above, and then 3 runs for the 3 new queries

## References
- OpenAI. "GPT-4o System Card." OpenAI Research, 2024. Accessed January 2025. https://cdn.openai.com/papers/GPT-4o-system-card.pdf
- Google DeepMind. "SIMA: A Scalable Instructable Multiworld Agent." DeepMind Blog, 2024. Accessed January 2025. https://www.deepmind.com/blog/sima-scalable-instructable-multiworld-agent
- LangChain. "Announcing LangGraph: Programmatic Agent Workflows." LangChain Blog, 2024. Accessed January 2025. https://blog.langchain.dev/announcing-langgraph/
- Anthropic. "Claude 3 Model and System Card." Anthropic Research, 2024. Accessed January 2025. https://www-files.anthropic.com/production/images/Claude-3-Model-Card.pdf
