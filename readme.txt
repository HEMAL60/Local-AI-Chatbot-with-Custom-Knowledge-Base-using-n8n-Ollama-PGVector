steps for installation

1. install ollama and run a suitable model and text embedding (for vector database).
2. for our knowledge base I am using postgres vector database and using docker for installation
3. install n8n instance using node js (run "npx n8n start")
4. I am using llama 3.2 3b model and nomic-embed-text:v1.5 embedding for vector database.
5. I am also using a second n8n workflow to upload any documents to our custom knowledge base.
6. for other tools, I am using calculator, postgres vector databse( for custom knowledge base) and serpapi to give llm access to internet.

7. basically this n8n workflows mimics the functionality provided by chatgpt but here everthing used is local, opensource and free.