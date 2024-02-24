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
     - AI Agent -> OpenAI   API 
     - AI Agent -> VSCode   HTTPS
     - AI Agent -> QuestDB  PostgreSQL/REST HTTP API
     - AI Agent -> Grafana  API
     - Grafana  -> QuestDB  Native
 
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
