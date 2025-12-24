Last year (Albab 2025) was somehow successful year and a gate to successful career inshallah, Started sharp at the beginning of the year, had multiple interviews with Microsoft, CambioML (YC incubator 2025) also had some messages from recruiters from Siemens.
Not gonna lie had some difficulties (this year's theme) like marriage preparations which took a-lot of time and effort.

This year's theme is kabad كبد which really represents how life goes. There're many downs in life & that what forms experience.

![Kabad](Kabad.png)


أجمل ما قيل في قوله تعالى "لَقَدْ خَلَقْنَا الْإِنْسَانَ فِي كَبَدٍ" هو أن ==الحياة الدنيا لا تخلو من المشقة والتعب==، وأن الإنسان مُعَدٌّ لمكابدة صعوبات الحياة، لكن هذه المشقة ليست عقابًا بل اختبار لمدى صبره وقوة إيمانه، وأن هذه الآية تحمل معنيين: الأول هو التعب والمشقة الدنيوية، والثاني هو الاستقامة والتمام في الخلقة، وأنها دعوة للتفكر في الحكمة من الخلق وأن الله يُعِدّ الإنسان للآخرة، وأن يتقرب إلى الله ليجد الرحمة والتخفيف

قال ابن القيم: فإن الإنسان مخلوق في شدة بكونه في الرحم، ثم في القماط والرباط، ثم هو على خطر عظيم عند بلوغه حال التكليف ومكابدة المعيشة والأمر والنهي، ثم مكابدة الموت وما بعده في البرزخ وموقف القيامة، ثم مكابدة العذاب في النار، ولا راحة له إلا في الجنة. انتهى.

- **الرازي**:  
    لم يُخلق للراحة المطلقة، بل للسعي والابتلاء
> أي: الإنسان خُلق في طريق فيه تعب → لكن فيه **معنى وقيمة ونتيجة**

إن كل بلاء يقدره الله على العبد فهو من تمام مصلحته، والله لا يقدر ما يقدر إلا لحكمة. وحسبك ما يساق للمؤمن من الأجور، ويرفع به من الدرجات بسبب تلك المكابدات والمشاق، ولو لم يكن في تلك المكابدات والمشاق إلا تشويق الإنسان إلى الجنة وإعلامه أن الراحة إنما تكون فيها، لكفى.

---

This year will be different somehow, it will be divided into quarters and the quarters will be divided into weeks, each week will have 2 days of revision of what's made (Monday and Thursday)

**So a quick diagram could be :**
Q1 -> weeks (1-12) January **1st** to March **31st** (total of 13 weeks) -> Each week (Monday , Thursday)

-----------------------------------
There's a yearly plan (**as always**) but this time I will focus more in writing the details of Quarters, rather than writing the yearly plan.

-----
# **Q1 2026: COMPREHENSIVE EXECUTION PLAN**

## **(January 1 - March 31)**

## **QUARTER THEME: "CONSOLIDATION & LEADERSHIP FOUNDATION"**

**Q1 Mantra:** "Finish what you start, lead from the front, measure everything."

## **PROJECT 1: QASR URL SHORTENER PRODUCTIONIZATION**

### **(Pillar 1: Systems Mastery)**

**January Goal:** Complete MVP with core features  
**February Goal:** Add analytics and monitoring  
**March Goal:** Production deployment and load testing

**Weekly Breakdown:**

**Week 1-2 (Jan 1-12): Core System Completion**

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
- **Testing setup** (2 days)
    - Unit tests (80% coverage target)
    - Integration tests with test containers
    - Load testing baseline with k6

**Week 3-4 (Jan 13-26): Advanced Features**

- **Enhanced rate limiting** (3 days)
    - Implement sliding window algorithm
    - Add IP-based and user-based limiting
    - Create admin override capability
- **Analytics foundation** (4 days)
    - Click tracking system (event sourcing pattern)
    - Geographic analytics (IP to location)
    - Device/browser detection
- **NGINX configuration** (3 days)
    - Reverse proxy setup
    - SSL/TLS configuration
    - Security headers implementation
    - Gzip compression setup

**Week 5-6 (Jan 27-Feb 9): Monitoring & DevOps**

- **Observability stack** (4 days)
    - OpenTelemetry instrumentation
    - Prometheus metrics (custom exporters)
    - Grafana dashboards (5 key dashboards)
- **CI/CD Pipeline** (3 days)
    - GitHub Actions workflow
    - Docker containerization
    - Multi-stage builds
    - Automated testing in pipeline
- **Deployment setup** (3 days)
    - Terraform/IaC for infrastructure
    - Staging environment setup
    - Blue-green deployment configuration

**Week 7-8 (Feb 10-23): Polish & Security**

- **Security enhancements** (4 days)    
    - API key authentication
    - Request validation & sanitization
    - SQL injection prevention
    - XSS protection headers
- **Performance optimization** (3 days)
    - Database indexing analysis
    - Query optimization
    - Connection pooling tuning
    - Cache invalidation strategy

**Week 9-10 (Feb 24-Mar 9): Production Readiness**

- **Load testing** (3 days)
    - 10k RPS target testing
    - Database performance under load
    - Cache performance analysis
    - Identify bottlenecks
- **Disaster recovery** (3 days)
    - Backup/restore procedures
    - Failover testing
    - Monitoring alert thresholds
    - Incident response playbook
- **User acceptance** (4 days)
    - Internal team testing
    - Bug bounty style testing
    - Performance SLA definition
    - Go/no-go checklist

**Week 11-13 (Mar 10-31): Launch & Iteration**

- **Production deployment** (2 days)
    - Gradual traffic rollout
    - Monitoring setup verification
    - Post-launch checklist
- **Post-launch monitoring** (Ongoing)
    - Daily performance review
    - Error rate tracking
    - User feedback collection
- **First iteration planning** (3 days)
    - Feature prioritization
    - Technical debt assessment
    

---

## **PROJECT 4: AI/LLM PRODUCTION READINESS**

### **(Pillar 2: AI Productionization)**

**January Goal:** RAG system prototype  
**February Goal:** Observability implementation  
**March Goal:** Cost optimization framework

**Sprint Breakdown (2-week sprints):**

**Sprint 1 (Jan 1-14): RAG Prototype**

- Choose use case (semantic book recommender or DB agent)
- Set up vector database (Chroma/Weaviate/Pinecone)
- Implement basic RAG pipeline
- Create simple frontend interface
- **Deliverable:** Working prototype with basic functionality

**Sprint 2 (Jan 15-28): Performance Optimization**

- Implement chunking strategies
- Add re-ranking capabilities
- Optimize embedding generation
- Add caching layer for embeddings
- **Deliverable:** Optimized pipeline with metrics

**Sprint 3 (Jan 29-Feb 11): Observability**

- Add LLM call tracing
- Implement token usage tracking
- Create quality metrics (relevance scoring)
- Build monitoring dashboard
- **Deliverable:** Complete observability stack

**Sprint 4 (Feb 12-25): Production Patterns**

- Implement circuit breakers for LLM calls
- Add retry logic with exponential backoff
- Create fallback mechanisms
- Implement A/B testing framework
- **Deliverable:** Production-ready patterns

**Sprint 5 (Feb 26-Mar 11): Cost Optimization**

- Implement cost tracking per query
- Create model selection logic (cost/performance)
- Add usage quotas and limits
- Implement result caching
- **Deliverable:** Cost optimization framework

**Sprint 6 (Mar 12-25): Documentation & Handoff**

- Create deployment guide
- Write operational runbook
- Document architecture decisions
- Prepare knowledge transfer
- **Deliverable:** Complete project documentation

---

## **Project 5**
### Go Project — Goal-edge (CLI v1)

- Scrape football matches (30-day window)
- Normalize data
- CLI flags:
    - date range
    - league filter
- Output: JSON + basic table
-----
## **LEARNING & DEVELOPMENT SCHEDULE**

### **(Wednesdays + 30min daily)**

**January Focus: Distributed Systems Deep Dive**

- Week 1: Raft consensus algorithm (paper reading + implementation)
- Week 2: PostgreSQL internals (indexing, query planning)
- Week 3: Redis advanced patterns (streams, pub/sub, Lua scripting)
- Week 4: NGINX mastery (load balancing algorithms, TLS optimization)

**February Focus: AI/ML Production Patterns**

- Week 5: LLM observability best practices
- Week 6: Vector database optimization
- Week 7: Model quantization techniques
- Week 8: Cost optimization strategies

**March Focus: Leadership & Communication**

- Week 9: Technical writing for architecture docs
- Week 10: Stakeholder management
- Week 11: Effective feedback delivery
- Week 12: Conflict resolution techniques
- Week 13: Quarterly review and planning

**Daily Learning (30min):**

- 15min: LeetCode/System Design problem
- 10min: Reading (newsletter, paper, article)
- 5min: Notes and synthesis

---

## **CONTENT CREATION PLAN**

### **(20% of learning time)**

**Target:** 12 quality pieces in Q1 (1 per week)

**January Themes:**

1. "Building a Production URL Shortener: Architecture Decisions"
2. "Rate Limiting Algorithms: Token Bucket vs Sliding Window"
3. "PostgreSQL Indexing Strategies for High Traffic"
4. "Implementing Raft Consensus: Lessons Learned"

**February Themes:**  
5. "RAG Systems: Beyond the Basic Tutorial"  
6. "LLM Observability: What to Measure and Why"

**March Themes:**  
9. "Production Readiness Checklist for AI Systems"  
10. "Technical Leadership: From IC to Manager of One"  
11. "Cost Optimization in AI/ML Systems"  
12. "Q1 Retrospective: Shipping vs Learning Balance"

**Content Creation Process:**

- Monday: Outline and research
- Wednesday: Draft creation (during learning time)
- Friday: Review and polish
- Saturday/Sunday: Publish and share

---
## Open Source Deep Dive (Light)

**Goal:** Learn to read code, not contribute yet.

- Read code from:
    - Tech Interview Handbook
    - System Design Primer
    - Green-mask (Go)
- Practice:
    - Trace execution
    - Draw architecture diagrams

## Q1 Outcomes (Must-Have by End of Quarter)

- Solid grasp of **how large systems work end-to-end**
- Completed **Cognitive Chatbot course** + chatbot prototype
- Go fundamentals refreshed with **performance-first thinking**
- One shipped project: **Goal-edge (CLI v1)**
- Read 2–3 foundational SWE books
