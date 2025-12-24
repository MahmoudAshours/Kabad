ChatGPT

> **Executive summary**

This is a practical, measurable, and flexible 12‑month plan tailored to a senior software engineer who: loves systems, LLMs/AI, Golang, tooling, Neovim, and building production projects (Qasr, Ensat, robotics). It balances deep learning, high‑impact projects, leadership (team & company), public presence, and wellbeing so you grow technically and move toward Staff/Principal outcomes.

---

# Vision for 2026

By the end of 2026 you will have:

- Led and shipped 2+ productionworthy systems (one AI/LLM product and one infra/system product).
    
- Implemented a company-wide career leveling and promotion rubric and run the first 6‑month calibration.
    
- Published 40–80 high-quality technical posts (articles, threads, tutorials) and given 2 conference/talks.
    
- Mentored 3 engineers into measurable promotions or skill improvements.
    
- Built a resilient engineering habit (weekly reviews, monthly retros) and kept burnout under control.
    

---

# Year themes (quarterly)

- **Q1 — Consolidate & Lead:** finish high‑priority 2025 carryovers (Qasr, Ensat foundations), implement career leveling, stabilize a production system.
    
- **Q2 — Scale & Productize:** harden AI/LLM projects for production (RAG, inference infra), add observability and reliability.
    
- **Q3 — Influence & Mentor:** ramp mentoring, run internal workshops, publish content and conference proposals.
    
- **Q4 — Innovate & Portfolio:** ship a signature project (robot/voice assistant or DB agent), compile portfolio, prepare compensation/promotion negotiations.
    

---

# High‑priority projects (ranked)

1. **Qasr: Productionize & Analytics** — goal: reliable shortener with analytics, rate limits, Redis caching, and hosted runner. Deliverables: SLA, CI/CD, infra IaC, 99.9% avail target.
    
2. **LLM Productization (Local Llama + RAG + Voice)** — goal: deploy a cost‑efficient LLM microservice (Ollama/langchain), RAG pipelines, memory chains, and a voice front‑end prototype.
    
3. **Career Leveling System for Your Company** — goal: define levels, competencies, rubric, promotion process, interview scorecards, and one calibration meeting.
    
4. **Ensat (Sign Language Avatar) — foundation** — gloss dataset, repo skeleton, SiGML pipeline, MVP demo.
    
5. **Robotics (Hand‑sized spider robot)** — prototype legs & servos, basic mobility demo, voice chat integration.
    
6. **Research spike: Rousha / AI compression** — 6‑week exploration, produce a short technical report.
    

> Each project must have: one owner (you), measurable success criteria, milestones every 2 weeks, and a postmortem.

---

# OKRs (example, change per quarter)

**Q1 Objective:** Ship Qasr MVP to production

- KR1: CI/CD pipeline with automatic deploys to staging & prod (done).
    
- KR2: Add analytics event pipeline and dashboard (50% of required metrics).
    
- KR3: Implement request rate‑limiting & caching, reduce P95 latency by 40%.
    

**Q2 Objective:** Productionize LLM service

- KR1: Deploy a RAG pipeline with vector DB (chroma/milvus) + autoscaling inference endpoint.
    
- KR2: Latency under 500ms for cached hits; cost per 1k queries documented.
    
- KR3: 2 customer/internal integrations using the API.
    

---

# Weekly cadence (repeatable)

- **Monday — Planning & System Design (AM), Deep work (PM)**
    
- **Tuesday — Code day (pairing / PRs / ship small features)**
    
- **Wednesday — Learning & Content (readings, course sections, write one short post)**
    
- **Thursday — Meetings, Mentorship, Architecture reviews**
    
- **Friday — Ops & polish (deploy, observability, small refactors) + weekly review (30–45m)**
    
- **Saturday — 3–4 hours for side project (prototype sprint)**
    
- **Sunday — Rest / catchup; weekly plan for the next week**
    

**Time allocation target:** Deep work 60% (design/code), Shallow work 20% (meetings), Learning+writing 15%, Mentorship/hiring 5%.

---

# Daily micro‑rituals

- Morning 60–90 mins: 1 LeetCode problem OR 45m focused reading + 15m notes.
    
- 30m writing: one snippet or draft (LinkedIn, thread, article outline) — aim for micro‑content daily.
    
- End‑of‑day 10m: quick triage & 3 priorities for tomorrow.
    

---

# Career & Leadership (specific actions)

1. **Implement career leveling**
    
    - Levels (example): IC2 (Senior), IC3 (Staff), IC4 (Senior Staff/Principal). For each: responsibilities, example deliverables, interview rubric, promotion evidence checklist.
        
    - Create scorecards for: architecture, code quality, delivery track record, mentoring, cross‑team influence.
        
    - Run a 6‑month calibration with concrete data (PR reviews, shipped features, mentoring outcomes).
        
2. **Mentorship program**
    
    - 1:1 cadence: 30–45m weekly with direct reports; set growth plan and measurable goals.
        
    - Run monthly brown‑bag sessions and 2 internal workshops per quarter (system design, LLMs, debugging).
        
3. **Hiring / HR scaffold** (since you have no HR)
    
    - Build hiring checklist, interview rounds, scorecards; a one‑page onboarding runbook; probation evaluation form.
        
    - Template: 1-week onboarding, 30/60/90 day plan per hire.
        
4. **Visibility & influence**
    
    - Publish technical posts (2–3 per month). Reuse course notes and project docs as blog posts.
        
    - Prepare two conference/talk proposals by June.
        

---

# Engineering craft (skills to sharpen)

- **System design & distributed systems:** consistent hashing, read/write caches, rate limiting, CBs, Sagas.
    
- **Observability & reliability:** APM, tracing (OpenTelemetry), SLOs/SLA, postmortems.
    
- **LLMs & ML infra:** RAG, vector DBs, quantization, cost/perf tradeoffs, grounding, hallucination mitigation.
    
- **Performance:** profiling, p95/p99 improvements, query optimization.
    
- **Security & infra:** RBAC, secrets rotation, zero trust principles.
    

Actionable: pair each learning topic with a 2‑week hands‑on mini project + a short writeup.

---

# Learning resources (curated)

- _Designing Data‑Intensive Applications_ — systems fundamentals.
    
- _Hands‑On Machine Learning_ / Practical Deep Learning videos (your previous entries).
    
- Cookbooks: OpenTelemetry docs, NGINX official blog, Raft/RocksDB.
    
- Courses: Amazon Generative AI, Coursera Deep Learning mini‑courses (you already used some).
    
- Podcasts/YT: pick 1–2 longform sources and extract notes weekly.
    

---

# Content strategy (reusing your workflow)

- Turn course notes and project retros into 2–3 posts each.
    
- Microcontent plan: 100‑post plan you started — split into _tutorials_, _threads_, _case studies_, _postmortems_.
    
- Aim: 40–80 pieces/year; 2 longer articles (5–10k words total) and many 200–800 word posts.
    

---

# Promotion & compensation prep

- Track impact: features shipped, revenue/impact metrics, uptime improvements, cost savings.
    
- Keep a promotion packet: PRs, architecture docs, mentorship outcomes, feedback quotes, shipped features with dates and metrics.
    
- When negotiating: aim to show business outcomes, not only lines of code.
    

---

# Hiring and building team culture (since you own a company)

- Run regular hiring sprints, use scorecards, and rotate interviewers.
    
- Create a lightweight HR template (onboarding, handbook, compensation bands).
    
- Promote async comms: docs-first culture, recorded demos, and public RFCs.
    

---

# Measurement: KPIs & dashboards

Track weekly/monthly:

- PR cycle time, mean time to deploy, % of urgent bug fixes, number of mentoring sessions, number of public posts, uptime, p95 latency.
    
- Personal metrics: weekly deep work hours, learning hours, burnout scale (self‑rated).
    

---

# Burnout prevention & wellbeing

- Keep a `no‑work` day per week (Sunday light). Maintain 10–15km walking habit (you already do).
    
- Block 2 hours daily for deep work; schedule meetings in afternoons only.
    
- Quarterly long rest: align with Ramadan & Umra/Eid cycles in your calendar; be flexible.
    

---

# Templates (copy/paste friendly)

**Weekly review (30m)**

- Wins this week (3).
    
- Biggest blockers.
    
- Metrics (PR cycle, deploys, uptime, learning hours).
    
- Top 3 priorities next week.
    
- One thing to delegate.
    

**PRD / Project brief**

- Problem statement.
    
- Success metrics (3 measurable KRs).
    
- Timeline & milestones (2‑week sprints).
    
- Risks & mitigations.
    
- Rollout plan + rollback criteria.
    

**Postmortem template**

- Incident timeline.
    
- Root cause analysis (5 Whys).
    
- Impact (users, revenue, uptime).
    
- Action items & owners.
    

---

# 90‑day starter plan (Q1 focus)

**Days 0–30:** finalize career leveling draft, ship Qasr basic CI/CD + staging, clear backlog, weekly posts (6).  
**Days 31–60:** instrument observability for Qasr, start LLM infra prototype (vector DB + small RAG), publish a long article about one system design concept.  
**Days 61–90:** run first mentoring program batch, hold leveling calibration meeting, ready LLM alpha for internal testing.

---

# Risks & contingencies

- **Risk:** Overcommitment → _Mitigation:_ ruthlessly prune, reduce WIP, follow weekly review.
    
- **Risk:** Burnout from back‑to‑back deep learning courses → _Mitigation:_ alternate heavy weeks with more practical weeks.
    
- **Risk:** Projects stuck on infra cost/compute → _Mitigation:_ focus on small, cheap demos using quantized models or proxies.
    

---

# Final advice — 10 pragmatic rules

1. Ship small things weekly; optimise for feedback.
    
2. Measure impact first, ergonomics second.
    
3. Invest in documentation — it compounds.
    
4. Teach to learn — convert learning into content.
    
5. Mentor publicly (post helpful code reviews/snippets).
    
6. Automate boring ops (CI, infra checks, alerts).
    
7. Keep a promotion evidence folder (date‑stamped).
    
8. Say no to work that isn’t aligned to quarterly OKRs.
    
9. Regularly audit your learning sources — drop noise.
    
10. Protect deep work blocks — treat them like meetings you can’t move.
    

---

If you want, I can:

- Convert this plan into a month‑by‑month calendar with milestones, or
    
- Generate a promotion rubric and scorecards for your company, or
    
- Turn the 90‑day plan into a checklist with dates.
    

Good luck — you already have the right instincts; this plan just helps you focus, measure, and scale your impact in 2026.