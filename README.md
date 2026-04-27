  <p align="center">                                                                                                                                                                                                       
    <img src="https://github.com/IceDev528/IceDev528/blob/main/Logo.gif" />                                                                                                                                              
  </p>                                                                                                                                                                                                                     

  <p align="center">                                                                                                                                                                                                       
    <a href="https://github.com/DenverCoder1/readme-typing-svg">                                                                                                                                                           
    </a>                                                                                                                                                                                                                   
  </p>                                                                                                                                                                                                                     

  ## Core Skills

  - 🤖 <b>AI & LLMs</b>: OpenAI (GPT-4, GPT-5), Claude, LangChain, LangGraph, LLMs, Local LLMs, RAG, Prompt Engineering, AI Agents, Agentic AI Development                                                                 
  - 🎙️   <b>Voice AI</b>: Vapi.ai, TTS, Whisper, AI Voice Agents
  - ⚡ <b>Automation</b>: n8n, Make.com, Zapier, AI Workflow Automation, custom webhooks                                                                                                                                   
  - 👨‍💻 <b>Backend</b>: Node.js, NestJS, FastAPI, TypeScript, Python, REST APIs, SSE                                                                                                                                    
  - 🔭 <b>Frontend</b>: Next.js, React, Tailwind CSS                                                                                                                                                                       
  - 🗄️   <b>Database</b>: Supabase (PostgreSQL), MongoDB, SQL Server, Chroma, Redis
  - ☁️   <b>Infra</b>: Vercel, Docker, Google Cloud, Azure API Management, Azure Key Vault, CI/CD                                                                                                                           
  - 🔧 <b>CRM & Tools</b>: GoHighLevel (GHL), HubSpot          

                     
  ## Featured Projects                                                                                                                                                                                                   
  ### [RAG Explorer v2](https://github.com/ivan-kyu/rag-poc-v2)
  A full-stack RAG (Retrieval-Augmented Generation) learning project built with the modern Python AI stack. Upload documents, ask questions, and watch the entire pipeline execute live - with technique toggles to compare
   retrieval strategies.                                                                                                                                                                                                   
  
  | Layer | Stack |                                                                                                                                                                                                        
  |---|---|                                                                                                                                                                                                              
  | Frontend | Next.js 16 + Tailwind + shadcn/ui - Vercel |                                                                                                                                                                
  | Backend | FastAPI + LangChain + LangGraph - Fly.io / Railway |                                                                                                                                                       
  | Storage | PostgreSQL + Chroma (vectors) + Redis |                                                                                                                                                                      
  
  **Pipeline:** `query -> [classify] -> [retrieve: naive | hybrid | multi-query | HyDE] -> [rerank] -> [generate + citations] -> SSE stream -> UI`   
