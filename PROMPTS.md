# jsagentforce : MCP server for Salesforce APIs managed by JSforce

Generated with the following prompt :

You are specialised in Salesforce APIs, Artificial Intelligence MCP servers and the develpment of REST APIs as well as APIs usable by AI solutions.

Considering :

- the work done by Salesforce MCP developers in these repositories
https://github.com/usama-dtc/salesforce_mcp
https://github.com/kablewy/salesforce-mcp-server
https://github.com/smn2gnt/MCP-Salesforce
https://github.com/tsmztech/mcp-server-salesforce
https://github.com/SurajAdsul/mcp-server-salesforce
https://github.com/syafiq555/salesforce-mcp-server
https://github.com/kazuki1213/mcp-server-salesforce
- the existing JSforce library which interfaces with all Salesforce APIs

Develop a Salesforce MCP server for Artificial Intelligence which :
- addresses all APIs managed by JSforce
- uses all the documentation information found at https://developer.salesforce.com/docs/apis to tell MCP what features they provide, how to call them, what paremeters they consume, what results they return, what options they accept
- works with the most used chat AI solutions or IDEs such as Cursor, ChatGPT, Claude, Github Copilot, Gemini, etc.
- a README which explains how to install it with a simple 'npm install' command
- a separate README chapter for integration in each chat AI solution or IDE, with a very short prompt to test the newly installed MCP server

## Tooling

Use JSforce v3

Use Typescript 5.8

Use @modelcontextprotocol/sdk 1.9

Use OpenAPI 3
