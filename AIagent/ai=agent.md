What is AI agent is the system using LLM to achieve the define goal. 
AI agent is not response , it reasoning , plan and execute plan in real word 

Core AI Agent components

1. LLM - brain 
2. Tools -> like the hand to connect the external system , API , database...
3. Orchestration layer



LLM: 

is not agent , it only become agent when you connect it to the tool and wrap it in orchestration layer 

SLM : small language model 


Tools  : There are 3 type of tools
1. Extention 
2. Functions : custom chunk of coode 
3. Datastore (RAG)

Memory : Learn from  the past 
- previous conversation 
- user preferences 
- past decision
- historical context 

short term memory (task in hand)
long term memory 




orchestration layer 

manage angent memory 
maintain state
control how to plan , schedule and eaction , 


Some of term 

Chain of thought (COT) -> think step by step , breaking complex to liner sumple step by step 

Tree of though TOT : advanced , explore multiple steps to provude primisioning one 

Reason and Act -> ReACt  the agent reason what too need to do , choose the action like which tool colling ,get context, observed data from that tool , reason again base on new information  , until the goal achieve 



- When Agent  become common , we need standardize them to communicate that where agentic protocol coming 

There are 2 common protocol we need to know 

1. MCP : Model context protocol 
2. A2A Agent to Agent 


MCP connect Agnets to Tools and data resources , A2A connect agent to agent to make an powerful agent system 


Agentic framework : langgraph , crewai, llamaindex