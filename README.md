# Muhammad Meeran

**Senior Platform Engineer at PAM AI · Founder of Burki · Co-founder & former CTO of BiteBuddy**

I build voice AI infrastructure and products people actually use: from conversation orchestration and telephony to the app, the backend, and the customer deployment.

[Explore my work](https://meeran.dev) · [Résumé](https://meeran.dev/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/meeran-malik-34431316b/) · [Email](mailto:muhammadmeeran2003@gmail.com)

## Production work

| Work | My ownership | Outcome / current stage |
| --- | --- | --- |
| **[PAM AI](https://meeran.dev/pam)** | Senior Platform Engineer. In-house voice orchestration, conversation controls, provider routing, SIP, transfers, and failure recovery. | Systems handling **50,000+ calls/day**; approximately **$100k/month estimated vendor-cost savings**. |
| **[BiteBuddy](https://meeran.dev/bitebuddy)** | Co-founder & CTO, Dec 2024–May 2026. Personally built the core voice, SMS, and web ordering product, backend, menu ingestion, and restaurant deployments. | **300,000 production calls**, **10 restaurant deployments**, approximately **$50k ARR**. Recruited a five-engineer team. |
| **[Burki](https://meeran.dev/burki)** | Founder & engineer. A weekend replacement for a voice provider grew into a reusable phone-agent platform. | **5 agency customers in week one**; a white-label UAE deployment handling approximately **20,000 calls/day**. |

These are product and deployment outcomes; the public examples below are separate, self-contained demonstrations. Commercial and employer implementations remain private.

## Products I built end to end

- **[Brimigo](https://meeran.dev/brimigo)** — pet discovery, mutual matching, real-time chat, and meetups. React Native / Expo, Supabase, PostgreSQL, and PostGIS, including approximate-location privacy and row-level access controls. Delivered through Apple App Store review.
- **[Kalbi](https://meeran.dev/kalbi)** — a private shared space for everyday moments, pings, countdowns, widgets, and small rituals. Currently in private beta.

## Engineering you can inspect

- **[GaariGar](https://github.com/meeran03/gaarigar)** — **first place in my sixth-semester Software Design and Analysis class**. A Java/Spring Boot roadside-assistance platform with Android clients and web administration. Inspect layered architecture, notification-handler interfaces, a payment-gateway abstraction, and reusable query specifications. **[Design walkthrough](https://github.com/meeran03/gaarigar/blob/main/docs/software-design.md)** · **[Live sample](https://backend-production-17213.up.railway.app)**.

- **[Voice Session Lab](https://github.com/meeran03/voice-session-lab)** — synthetic conversation sessions for examining provider failover, interruption, tool idempotency, and transfer recovery. Executable scenarios, event traces, and tests.
- **[TrajectoryShield](https://github.com/meeran03/trajectoryshield)** — AI safety research on policy violations across agent tool sequences. Effect tracking, 300 authored fixtures, reproducible evaluation, and an honest audit of the evaluation limits. **[Explore the interactive trace demo](https://meeran03.github.io/trajectoryshield/)**.
- **[Agent Trace Evals](https://github.com/meeran03/agent-trace-evals)** — evaluate an agent's tool actions against explicit policies, with evidence attached to each finding. Synthetic fixtures and reproducible reports.
- **[Streaming + function calling in FastAPI](https://github.com/meeran03/streaming_with_function_calling_fastapi)** — an API example for streamed model output and validated tool execution.
- **[Hybrid search with PostgreSQL](https://github.com/meeran03/hybrid_search_with_postgres)** — vector retrieval, full-text search, and reciprocal-rank fusion.
- **[RL Bandits](https://github.com/meeran03/rl-bandits)** — reproducible experiments with ε-greedy, UCB, and gradient bandits, including tests and comparison plots.
- **[Burki documentation](https://github.com/meeran03/mintlify-docs)** — public integration and architecture documentation for the voice platform.

## Research and background

I completed my **M.S. in Computer Science at Texas Tech University in May 2026**, working with Professor Akbar Namian on policy following and deceptive behavior in AI tool-calling systems. I focus on what an agent actually does, including the actions hidden behind a plausible final answer.

The [TrajectoryShield research brief](https://github.com/meeran03/trajectoryshield/blob/main/docs/research-brief.md) explains the approach, findings, and limitations. Code and reproducible examples are public; the paper has not been released.

Previously: engineering and team leadership at SHARE Mobility, and founding-engineer work at Doodhwala.

**Core tools:** Python, TypeScript, FastAPI, PostgreSQL, Redis, AWS, Docker, WebSockets, SIP, and React Native. My recurring interests are conversation lifecycle, failure recovery, evaluations, observability, and shipping the whole product.

Based in Northern Virginia / Washington, DC.
