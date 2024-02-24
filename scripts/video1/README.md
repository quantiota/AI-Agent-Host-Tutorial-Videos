# Overview 

 ## Time duration T

 - AI Agent Host  **2T/5** Flexible
   - Containers
     - VSCode
     - QuestDB
     - Grafana
     - Nginx 
  
   - Remote connection for Computational Offloading
     - JupyterHub : Python, Julia, R.   API Token
     - Dedicated GPU  Tesla K80 16 nodes, P100 8 nodes, V100  8 nodes
  
   - Docker Host Monitoring
     - NodeExporter 

 - AI Agent Lab   **1T/5** Flexible
   - Containers
     - VSCode
     - QuestDB
     - Grafana
     - Nginx
     - AI Agent 

   - Connection
     - AI Agent -> OpenAI API: This connection likely involves the AI agent making API calls to OpenAI services, possibly  for generating responses, processing natural language, or other AI-related tasks. The communication would use HTTPS for secure, encrypted data exchange.

     - AI Agent -> VSCode (code-server): The AI agent accesses the code-server (a web-based version of VSCode) over HTTPS. This secure connection could be for automating coding tasks, managing projects, or executing scripts within the development environment provided by code-server.

     - AI Agent -> QuestDB PostgreSQL/REST HTTP API: Here, the AI agent interacts with QuestDB, a high-performance time-series database, using either the PostgreSQL interface or the REST HTTP API. The PostgreSQL interface would allow for complex SQL queries and database operations, while the REST API might be used for more straightforward data insertion, querying, and management tasks. The choice between PostgreSQL and REST depends on the specific needs and capabilities of the AI agent.

     - AI Agent -> Grafana API: The AI agent uses the Grafana API for interactions with Grafana, a platform for monitoring and visual analytics. This could involve creating or modifying dashboards, querying data visualizations, or managing Grafana configurations. The API facilitates automated control over Grafana's features, enhancing the ability to dynamically present and analyze data.

     - Grafana -> QuestDB Native: Grafana directly connects to QuestDB using QuestDB's native interface, likely for real-time data visualization and analytics. This connection enables Grafana to query QuestDB for time-series data, which can then be used to create dashboards and graphs within Grafana, offering insights into the stored data.
 
   - Remote connection for Computational Offloading
     - JupyterHub : Python, Julia, R.   API Token
     - Dedicated GPU   Tesla K80 16 nodes, P100 8 nodes, V100 8 nodes
    
    - Docker Host Monitoring
      - NodeExporter 

 - AI Agent Farm  **2T/5**  Flexible

   - Distributed AI Computing

     - Microservers
     - GPU Serveur  AI Applications, JupytherHub: Python, Julia, R

   - Monitoring Server
     - Prometheus

   - Administration
     - RMS Remote Managment System


## Images

- ai-agent-host-diagram.png
- ai-agent-lab-diagram.png
- ai-agent-farm-diagram.png
  
## Logo

- logo.png
- inlinelogo.png

## Link

github/quantiota
