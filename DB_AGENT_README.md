Create a db agent which will perform below functions

- Summarize host, storage, if OS needs update
- Summarize Mongo based on standalone/cluster
- Check slow logs in mongo logs and provide recommendation
- Agent will have data regarding current schema and index details
- This json data will be converted to SQL format so that model can query this data and provide recommendation. It will maintain this data and refer historical data while recommending
- Based ob DB version, notify if any critical vulnerability is present
- Also, provide duplicate and unused index details
- 
