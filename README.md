# crewai_meeting_research
Build CrewAI Agents to perform research tasks using analytical tools prior to a meeting, based on the prepare for a meeting example by CrewAI.

CrewAI is a framework for orchestrating autonomous AI agents to tackle complex tasks. Agents within CrewAI operate in a loop, continuously processing information and executing actions until they reach an output that satisfies the agent. 

## Setup

1. **Define the Goal**
    - Specify the objective for your agents, e.g., creating a meeting brief.

2. **Plan Your Crew**
    - **Tasks:** Add description, agent, context, and async execution properties.
    - **Agents:** Assign tasks to specialized agents.
    - **Tools:** Equip agents with necessary tools (e.g., search engines).
    - **Process:** Decide on a workflow (sequential, hierarchical).

3. **Detailed Steps**
    - **Tasks:** Create detailed task descriptions.
    - **Agents:** Develop agents with specific roles and goals.
    - **Processes:** Choose a collaborative process for agents.

4. **Run Your Crew**
    - Initiate the `kickoff` method to start the agents on their tasks, leading to the final output.

## Cost Considerations
**The use of language models and external tools incurs expenses, particularly with frequent API calls. Effective monitoring, such as employing LangSmith, helps track resource usage and optimize costs.**
