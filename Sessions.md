### &emsp;&emsp; [ABOUT](./index.md) &emsp; Sessions &emsp; [Learning Resources](./Resources) &emsp;

Join us in Room 100C on 21st October 2024, 9:00 am :)

# Presentation
Session Presentation: [Frontiers of Langue Language Model-Based Agentic Systems - Construction, Efficacy and Safety (PPTX)](https://github.com/Frontiers-of-AI-Agents-Tutorial/Frontiers-of-AI-Agents-Tutorial.github.io/raw/main/Files/Frontiers%20of%20Langue%20Language%20Model-Based%20Agentic%20Systems%20-%20Construction%2C%20Efficacy%20and%20Safety.pptx)

## Session notes
The presentation "Frontiers of Language Model-Based Agentic Systems: Construction, Efficacy, and Safety" offers a comprehensive exploration of the development, effectiveness, and safety considerations of agentic systems powered by large language models (LLMs). Below are summarized notes for each section, tailored for the CIKM ACM conference.

### 1. Introduction to Language Model-Based Agentic Systems 
Presented by: Jia He

This section introduces the concept of agentic systems that leverage LLMs to perform tasks autonomously. It highlights the evolution of LLMs from simple language processors to sophisticated agents capable of decision-making and task execution. The discussion emphasizes the significance of integrating LLMs into agentic frameworks to enhance their capabilities and adaptability across various domains. [Additional Reading](https://github.com/zjunlp/LLMAgentPapers).
Essentially Agents can be thought of as LLM (or GenAI) model calls + expandable capabilities in the form of Tools, Memory, and Planning/Orchestration 


### 2. Construction of LLM-Based Agents
Presented by: Jia He & Kabir Walia

Here, the focus is on the methodologies employed in building agents powered by LLMs. Key components include data collection, model training, and the integration of reinforcement learning techniques to fine-tune agent behaviors. The section also addresses architectural considerations, such as modular design and scalability, to ensure that agents can handle complex tasks efficiently. We go over three key components:
1. Profiling
2. Perception
3. Model Routing
4. Memory
5. Memory Types
6. Reflection
7. Planning (Reaosning in Static and Dynamic)
8. Actions
9. Embodied Actions (actions in a physical world)
Additional Readings:
1. ["If LLM Is the Wizard, Then Code Is the Wand: A Survey on How Code Empowers Large Language Models to Serve as Intelligent Agents"](https://arxiv.org/abs/2401.00812#:~:text=As%20a%20medium%20between%20humans%20and%20computers%2C%20code,benefits%20of%20integrating%20code%20into%20LLMs%27%20training%20data.)

### 3. Multi-Agent Systems and differentials from a Single-Agent System
In this section, we go over differentiators that makes multi-agent systems different from single-agent systems. We cover topics such as collaboration patterns, notable multi-agent system frameworks such as AutoGen and present a hands on demo for configuring a multi-agent system 


### 4. Evaluations and Efficient Agent frameworks
Evaluation choices for Agents are a non-trivial task. The session will go over how to make decisions, understand tradeoffs related to **single-trajectory**, **end-to-end** evaluations, automated evaluations using LLM Judge vs. grounded, deterministic metrics, and examples of how to think about and standardize evaluations procedure. 

Efficient frameworks 


### 5. Safety Considerations in LLM-Based Agentic Systems



Additionally, safety is a critical aspect addressed in this section, focusing on the potential risks associated with autonomous LLM agents. Topics include the prevention of harmful outputs, ensuring fairness and bias mitigation, and safeguarding user privacy. The section references recent studies on AI safety, such as the work on TrustLLM, which establishes benchmarks across dimensions like truthfulness, safety, and fairness citeturn0search6. Additionally, it discusses frameworks like TrustAgent, designed to enhance the safety of LLM-based agents through strategic planning and adherence to predefined constitutions 

### 6. Efficacy of LLM-Based Agents

This part evaluates the performance metrics of LLM-based agents, including accuracy, adaptability, and user satisfaction. It presents case studies where these agents have been deployed, demonstrating their ability to understand context, generate human-like responses, and learn from interactions to improve over time. The discussion also covers the challenges faced in measuring efficacy, such as handling ambiguous inputs and maintaining coherence in extended interactions.
[Additional Readings:]


### 6. Future Directions and Research Opportunities**

The final section outlines prospective avenues for advancing LLM-based agentic systems. It emphasizes the need for interdisciplinary research combining machine learning, ethics, and human-computer interaction to develop agents that are not only effective but also trustworthy. The section also highlights the importance of creating robust benchmarks, such as SafeAgentBench, to evaluate the safety and task planning capabilities of embodied LLM agents citeturn0academia11. Emerging trends like the incorporation of human-centered design principles in AutoML paradigms are also discussed, promoting collaborative design of ML systems that integrate human expertise and values citeturn0search7.

In summary, the presentation provides a thorough examination of the current landscape and future prospects of LLM-based agentic systems, with a strong emphasis on their construction, efficacy, and safety. 
