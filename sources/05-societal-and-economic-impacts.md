# Societal & Economic Impacts

High-level topic on the labs' research into how AI affects society, labor, and the economy. Currently Anthropic-only from the source list (their dedicated research teams).

> Scraped 2026-05-29 for the Konstanz AI & Public Governance course. Anthropic pages scraped directly. The Economic Index page renders data dynamically, so only its framing was captured — see note below.

---

## Anthropic

### Societal Impacts (research team)
Source: https://www.anthropic.com/research/team/societal-impacts

A technical research team working closely with the Policy and Safeguards teams, focused on how AI systems function and are used in the real world.

- **Sociotechnical alignment:** which human values models should embody and how to navigate conflicting/unclear values; studying legitimate and problematic uses; building experiments, training methods, and evaluation frameworks.
- **Policy relevance:** technically oriented but choosing research questions with policy implications — "providing trustworthy research concerning topics policymakers care about will lead to better policy (and overall) outcomes for everyone."
- **Recent projects:** a large-scale qualitative study of ~81,000 Claude.ai users (uses, hopes, concerns); internal research on how AI adoption is changing work at Anthropic (esp. software developers); analysis of 700,000 interactions on which values Claude expresses; **Anthropic Interviewer**, an automated interview tool for large-scale research.

### Economic Research (research team)
Source: https://www.anthropic.com/research/team/economic-research

Investigates how AI transforms economic systems — employment, productivity, and economic opportunity — through rigorous empirical analysis.

- **Mission:** establish "the empirical foundation for understanding AI's economic impact." Flagship initiative: the **Anthropic Economic Index**, measuring actual global AI-adoption patterns rather than predictions.
- **Focus:** implications for individual workers, businesses, and overall economic conditions; "the speed of AI development means the stakes are unusually high."
- **Notable findings:** geographic adoption varies with income levels; **directive automation rose from 27% to 39% of conversations between December 2024 and September 2025**, with businesses automating substantially more than consumers.
- Related teams: Alignment, Interpretability, Societal Impacts.

### Anthropic Economic Index
Source: https://www.anthropic.com/economic-index
Last updated: March 24, 2026.

An interactive resource for "Understanding AI's effects on the economy." The page loads data dynamically; the detailed statistics/methodology weren't captured in the scrape. **Action item:** capture specific figures from the live, fully-loaded page (or the linked reports/datasets) for the course. The Index is the data source behind much of the Economic Research team's published findings.

### Labor Market Impacts of AI: A New Measure and Early Evidence
Source: https://www.anthropic.com/research/labor-market-impacts
Date: March 5, 2026.

Introduces **"observed exposure,"** a metric combining theoretical LLM capabilities with real-world usage data, weighting automated/work-related applications more heavily.

**Key findings:**
- Actual AI adoption significantly lags theoretical potential — "actual coverage remains a fraction of what's feasible."
- Occupations with higher exposure show weaker projected employment growth through 2034 (per BLS data).
- Highly exposed workers tend to be older, female, more educated, and higher-paid.
- No significant unemployment increase detected for exposed occupations since late 2022, though hiring of younger workers has "slowed slightly."
- **Computer programmers** have the highest exposure (~75% coverage), then customer-service reps and data-entry clerks. ~30% of workers have **zero** coverage (cooks, mechanics, lifeguards, bartenders).
- Young workers (22–25) entering high-exposure occupations saw a **14% reduction in job-finding rates** post-ChatGPT (interpret cautiously due to survey-data limits).

**Methodology:** combines O*NET task databases, Anthropic usage metrics, and prior task-exposure estimates. Framework establishes baseline metrics for longitudinal tracking; authors stress significant uncertainty about future disruption timing/magnitude.

---

## OpenAI *(not in the source list — flagged for follow-up)*

No OpenAI societal/economic-research page was in the link list. Candidates for balanced coverage: OpenAI's economic-impact research and any "jobs/economy" reports or the OpenAI economic blueprint. *(Note for the team — not yet scraped.)*

---

## Cross-lab observations (for course design)

- Anthropic has **institutionalized** societal/economic research as standing teams (now folded into The Anthropic Institute — see [Policy, Governance & Public Benefit](04-policy-governance-and-public-benefit.md)).
- Strong **empirical, measurement-first posture** ("observed exposure," the Economic Index) — excellent primary material for teaching how to reason about AI labor effects with data rather than speculation.
- Findings connect directly to **Education** (which skills to teach; reskilling) and **Nonprofits/Public Good** (distributing gains).
- For balance, the course should add OpenAI-side economic research to compare methodologies and conclusions.
