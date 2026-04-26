# Aarogya-Path
# AarogyaPath 🏥
### Agentic Healthcare Intelligence for India's 1.4 Billion

Built for the Databricks Hackathon — Serving A Nation track.

## What We Built
AarogyaPath eliminates the Discovery-to-Care gap in Indian healthcare 
by turning 10,000 messy facility records into a living intelligence network.

## Key Results
- ✅ 10,000 facilities analysed across India
- ⚠️ 9,359 contradiction flags raised by trust scorer
- 🔴 8,607 facilities in medical desert zones
- 📍 174 regions identified needing urgent intervention
- 🏆 Maharashtra, UP, Gujarat — top 3 priority states

## How It Works
1. **Data Pipeline** — Loads 10,000 Indian healthcare facility records
2. **Two-Stage Extraction** — Keyword extraction for full coverage + LLM enrichment on top facilities
3. **Trust Scorer** — Flags contradictions (surgery claim + no anesthesiologist = LOW trust)
4. **Survivability Window** — Tells patients if they will survive the journey to nearest care
5. **Last Mile Score** — Composite metric: 45% trust + 30% reachability + 25% capability match
6. **Desert Detection** — Identifies PIN codes with zero trusted emergency coverage
7. **NGO Dashboard** — Priority map for infrastructure investment

## Tech Stack
- **Databricks** — Data pipeline, LLM serving, MLflow tracking
- **Llama 4 Maverick** — via Databricks Model Serving
- **Tavily** — Live facility verification
- **Lovable** — Patient-facing frontend
- **Python + Pydantic** — Virtue Foundation Schema validation

## Evaluation Criteria Coverage
| Criterion | Weight | What We Built |
|---|---|---|
| Discovery & Verification | 35% | 10k extraction + 9,359 contradiction flags + MLflow tracing |
| IDP Innovation | 30% | Two-stage hybrid pipeline + Pydantic schema |
| Social Impact | 25% | 8,607 desert zones + NGO priority report |
| UX & Transparency | 10% | Citations on every recommendation + trust badges |

## Live Demo
[AarogyaPath Web App](https://aarogya-path-aid.lovable.app/)

## Architecture
