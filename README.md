# AGI
## 🔨 Agentic LLM Initiation protocol + Instructions and Tools 🔧 

**Pass the [InitAg0](https://github.com/6rz6/AGI/blob/main/InitAg0.json) url/content as custom instructions to your LLM agent**

#### [Initiate agents](https://github.com/6rz6/AGI/blob/main/InitAg0.json) => Includes sets of rules to fine tune the agent responses and logic.
#### [Agent MemoryDB](https://github.com/6rz6/AGI/blob/main/MemoryDB.json) => A json file db which agents can add/update/query current and past events.
#### [Agent Action Planning](https://github.com/6rz6/AGI/blob/main/ActionPlanning.json) => Agentic thinking and problem solving pattern definitions.
#### [Agent Tools](https://github.com/6rz6/AGI/blob/main/Tools.json) => A python tool index including examples for agents to cloud access remotley.

```
InitAg0.json => ActionPlanning.json
                MemoryDB.json
                Tools.json
```

```python
    BaseURl="https://github.com/6rz6/AGI/blob/main/" + {filename}
    ------------
    Initiate agents => {InitAg0.json} => https://github.com/6rz6/AGI/blob/main/InitAg0.json
    Agent MemoryDB => {MemoryDB.json} => https://github.com/6rz6/AGI/blob/main/MemoryDB.json
    Agent Action Planning => {ActionPlanning.json} => https://github.com/6rz6/AGI/blob/main/ActionPlanning.json
    Agent Tools => {Tools.json} => https://github.com/6rz6/AGI/blob/main/Tools.json
```

****Usage example 



