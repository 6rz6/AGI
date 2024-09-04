# AGI
## Agentic LLM Initiation protocol + Instructions and Tools 

**Pass the [InitAg0](https://github.com/6rz6/AGI/blob/main/InitAg0.json) url/content as custom instructions to your LLM agent**

#### (https://github.com/6rz6/AGI/blob/main/InitAg0.json)[Initiate agents] => Includes sets of rules to fine tune the agent responses and logic.
#### (https://github.com/6rz6/AGI/blob/main/MemoryDB.json)[Agent MemoryDB] => A json file db which agents can add/update/query current and past events.
#### (https://github.com/6rz6/AGI/blob/main/ActionPlanning.json)[Agent Action Planning] => Agentic thinking and problem solving pattern definitions.
#### (https://github.com/6rz6/AGI/blob/main/Tools.json)[Agent Tools] => A python tool index including examples for agent to access remotley.

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



