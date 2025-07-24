# TIPS for Intermediate Workflow

- Import the workflow into n8n
- Connect your OpenAI API key
  - https://platform.openai.com/
- Connect Airtable with n8n through the Builder Hub
  - Create a Personal Access Token (PAT) with the following "scopes":
    - data.records:read
    - data.records:write
    - schema.bases:read
    - and give the Personal Access Token (PAT) the ability to interact the your base too
- Connect the nodes together and run!