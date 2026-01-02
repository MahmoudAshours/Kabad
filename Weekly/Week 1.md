## QASR
- **Architecture finalization** (2 days)
    - Design document with sequence diagrams
    - Database schema finalization (PostgreSQL + Redis)
    - API specification (OpenAPI/Swagger)

- **Implement base features** (6 days)
    - URL shortening/unshortening endpoints
    - PostgreSQL integration with connection pooling
    - Redis caching layer (write-through pattern)
    - Basic rate limiting (token bucket algorithm)
    - Laravel admin dashboard

## RAG Prototype + Manim

- Choose use case (semantic book recommender or DB agent)
- Set up vector database (Chroma/Weaviate/Pinecone)
- Implement basic RAG pipeline
