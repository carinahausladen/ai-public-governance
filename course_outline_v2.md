# AI and Public Governance — revised outline (v2)

**Core question:** How should governments, public institutions, and civil society govern, deploy, and respond to increasingly capable AI systems?

This is a politics / public-administration course first, and an AI course second.

> **v2 changes (vs. `course_outline.md`):** (1) adds the missing **Module 1 (Weeks 1–2)**; (2) redistributes the lab material out of Module 5 — government adoption moves to **Module 2**, self-governance structures to **Module 6**, economic research becomes cross-cutting; (3) adds a **critical-reading lens** treating lab sources as corporate self-presentation, not neutral fact; (4) cross-links every module to the scraped files in [`sources/`](sources/). Original outline preserved in `course_outline.md`.

> **v2.1 addition:** integrates the external current-affairs digest in [`sources/current_media_digest.md`](sources/current_media_digest.md) as a cross-cutting **media dataset**. This gives the course a live archive of newspaper coverage and platform discourse that complements the lab sources with contested, time-sensitive public cases.

---

## How to use the lab sources in this course

The `sources/` files are **primary documents of corporate self-presentation** (product announcements, partnership PR, and lab-funded research). For a politics-first course that is an asset: they show how powerful private actors frame their own role in public life. Throughout, students should read them on two levels — *what is claimed* and *what the framing reveals / omits*. Recurring critical prompts:

- Who benefits, and who is absent from the framing?
- Is "near-free" or "philanthropic" access a public good, or market capture / dependency / agenda-setting?
- Is self-governance (trusts, public-benefit charters) genuine accountability or reputational insurance?
- What does lab-funded research measure well, and where is it conflicted?

Use [`sources/current_media_digest.md`](sources/current_media_digest.md) differently: it is not self-presentation, but a **secondary live-case dataset**. It is useful for asking:

- Which AI governance issues are visible enough to become public controversies?
- How do newspapers frame the state: as regulator, customer, victim, or promoter of AI?
- Which topics produce concrete institutional responses, and which remain abstract?

---

## Learning objectives

By the end, students should be able to:

1. Understand what modern AI systems can and cannot do.
2. Analyze public-policy implications of AI.
3. Evaluate AI use in government and public services.
4. Assess risks, governance mechanisms, and regulatory approaches.
5. Design practical public-sector AI interventions.
6. **Critically interpret claims made by AI developers** and distinguish evidence from positioning. *(new)*

---

## Module 1: Foundations — What AI Can and Cannot Do (Weeks 1–2) *(new / was missing)*

Topics:

* Capabilities and limits of modern AI (LLMs, agents); the pace of change
* Augmentation vs. automation
* How capability claims are made — and how to read them critically
* How media narratives about AI capability differ from lab narratives

Sources:

* [05 Societal & economic impacts](sources/05-societal-and-economic-impacts.md) — Anthropic's **"observed exposure"** measure (what is *actually* automatable vs. theoretically possible; "actual coverage remains a fraction of what's feasible"); occupation exposure (programmers ~75%; ~30% of workers at zero).
* [01 Education](sources/01-education.md) — real augmentation/automation patterns (student-facing tasks lean augmentation 67–77%; routine admin leans automation).
* [04 Policy/governance/public benefit](sources/04-policy-governance-and-public-benefit.md) — the Anthropic Institute's capability-progress narrative (good specimen for *reading capability claims critically*).
* [Current media digest](sources/current_media_digest.md) — contrast lab framings with newspaper framings of adoption, misinformation, and political controversy.

---

## Module 2: AI and the State (Weeks 3–4)

Topics:

* Public-sector adoption
* Digital government
* **Procurement** ← now has a flagship case
* Administrative capacity
* **AI and austerity / state retrenchment** *(new topic suggested by the digest)*
* **Vendor dependence and cloud intermediation** *(new topic suggested by the digest)*

Cases (existing): Tax administration · Benefits administration · Immigration systems · Public health

Cases (added from sources — [02 Government & public sector](sources/02-government-and-public-sector.md)):

* **Procurement seminar — the GSA × OpenAI $1/agency deal** (ChatGPT Enterprise to the federal workforce for $1/agency/year). Discuss: acquisition mechanics (MAS), the OMB-memo policy frame, and the lock-in / dependency critique.
* **ChatGPT Gov / OpenAI for Government** — compliance & deployment (FedRAMP High, IL5, CJIS, ITAR; Azure Government) → administrative-capacity and data-governance constraints.
* **Adoption case studies:** Pennsylvania pilot (~105 min/day saved on days used), Minnesota translations office, Air Force Research Laboratory, Los Alamos. Scale: 90,000+ users across 3,500+ agencies.

Current-affairs overlay — [current media digest](sources/current_media_digest.md):

* **Washington Post federal adoption story** — use for mapping where AI is actually entering the administrative state.
* **New Zealand cuts + AI uptake** — introduces the politics of using AI to justify downsizing, restructuring, or efficiency drives.
* **IRS workforce-capacity case** — helps distinguish digitization rhetoric from the human capacity needed to administer complex systems.
* **OpenAI-through-AWS deal** — sharpens the procurement discussion by showing how state access to AI is often mediated by hyperscalers.

> Flagged gap: no Anthropic government page in the source list. Add Claude's gov offering for a two-vendor procurement comparison (see `sources/README.md`).

---

## Module 3: AI and Democracy (Weeks 5–6)

Topics: Elections · Misinformation · Political persuasion · Civic participation · **Election administration** *(new)* · **Platform governance** *(new)* · **Authenticity and public trust** *(new)*

Cases: Election-related AI deployments · Deepfakes · Government communication

Exercise: Students evaluate a hypothetical election commission's AI policy.

Media dataset — [current media digest](sources/current_media_digest.md):

* **Scottish election chatbot-errors case** — ideal for AI misinformation, voter reliance, and the institutional limits of existing election law.
* **Scottish and Welsh deepfake pilot** — adds election administration and emergency response capacity, not just abstract misinformation.
* **Political deepfakes / propaganda case** — strengthens the political persuasion topic by emphasizing synthetic personas, monetization, and belief reinforcement.
* **White House AI-image case** — gives the module a government-communication angle and a public-trust debate.

> **Source gap (intentional):** the labs' public pages don't cover elections/deepfakes — this module therefore leans especially heavily on the media dataset and external scholarship. Two partial bridges from [05](sources/05-societal-and-economic-impacts.md) and [04](sources/04-policy-governance-and-public-benefit.md): the "which values Claude expresses" study (700k interactions) for *political/value alignment*, and the Institute's "AI Systems in the Wild" agenda (epistemic shifts, critical-thinking degradation) for *information ecosystem* effects.

---

## Module 4: AI Policy and Regulation (Weeks 7–8)

Topics: Risk-based regulation · The EU AI Act · US approaches · International governance · **Federalism and pre-emption** *(new)* · **Implementation politics** *(new)* · **Compliance as governance practice** *(new)*

Key entities: OECD · United Nations · European Commission

Added lens — **public regulation vs. private self-regulation** ([04](sources/04-policy-governance-and-public-benefit.md)):

* Anthropic's "race to the top" safety rhetoric and PBC status as *self-regulation* — contrast with the EU AI Act's binding, risk-based approach.
* Lab-funded research as a policy input: the Institute's claim that "trustworthy research on topics policymakers care about leads to better policy." Discuss the conflict-of-interest question.

Media dataset — [current media digest](sources/current_media_digest.md):

* **Reuters on stalled AI Act negotiations** — good for showing that AI regulation remains politically negotiable even after headline legislation is passed.
* **Reuters on U.S. federal pre-emption** — adds a clear U.S. federalism case that the current outline was missing.
* **LinkedIn EU AI Act compliance post** — useful not as authority, but as evidence of how regulation gets translated into operational and managerial language.

Assignment: Compare three governance frameworks. *(Suggest: EU AI Act vs. US executive/GSA approach vs. a lab's voluntary self-governance — pulling M2 + M4 + M6 sources together.)*

---

## Module 5: AI for Public Good (Weeks 9–10)

Refocused on **non-state public benefit** (state adoption now lives in M2).

Topics: Education · Healthcare · Scientific discovery · Public services · Nonprofit applications · **Distribution of benefits** *(new, pulled forward from the economic-impact material)*

Sources:

* **Education** — [01 Education](sources/01-education.md): Claude for Education & Learning Mode; ChatGPT EDU rollouts (Wharton, Harvard, Maryland, Nebraska-Omaha; Northeastern, LSE, Champlain); AI-literacy curricula; the "How educators use Claude" usage study.
* **Nonprofits** — [03 Nonprofits & public good](sources/03-nonprofits-and-public-good.md): OpenAI's **$50M People-First AI Fund** (208 orgs, $40.5M first wave). Critical prompt: "build *with*, not *for*, communities" — philanthropy or agenda-setting?
* **Economic opportunity** — [05](sources/05-societal-and-economic-impacts.md): who captures the gains; distribution mechanisms.

Optional media bridge:

* [Current media digest](sources/current_media_digest.md) can be used here selectively to ask why "public good" stories receive less sharp coverage than democracy, regulation, or public-sector controversy. That absence is analytically useful.

> Flagged gaps: Anthropic nonprofit/access programs; OpenAI economic research — add for balance.

---

## Module 6: Future Governance (Weeks 11–12)

Topics: Frontier AI governance · National AI strategies · Compute governance · Institutional design · **Civil-military AI governance** *(new)* · **Contracts as governance tools** *(new)*

**Institutional design — using lab self-governance as live specimens** ([04](sources/04-policy-governance-and-public-benefit.md)):

* **Anthropic's Long-Term Benefit Trust** — Class T stock, phased board majority within ~4 years, financially disinterested trustees. A real attempt to govern "unprecedentedly large externalities." Critique: accountability or theater?
* **Public Benefit Corporation** structures and **The Anthropic Institute** (a "Head of Public Benefit"; an agenda covering economic diffusion, threats/resilience, AI systems in the wild, AI-driven R&D).
* **AI-driven R&D governance** — governing systems that build successor systems.

Media dataset — [current media digest](sources/current_media_digest.md):

* **Pentagon access to frontier models** — useful for connecting frontier governance to classified infrastructure and national-security demand.
* **Anthropic and the Pentagon** — gives a live case of contestation over what responsible frontier deployment means in practice.
* **Grok consent/safety controversy** — broadens the module beyond national strategy into deployment harms, safety controls, and enforcement questions.

Final question (retained):

> What institutions should exist in 2035 that do not exist today?

> Flagged gap: add OpenAI's nonprofit-parent / PBC restructuring + charter for a head-to-head on "who governs a frontier lab for the public good."

---

# Weekly activity — Frontier AI Governance Tracker

Each week students monitor:

* [OpenAI Newsroom](https://openai.com/news/)
* [Anthropic News](https://www.anthropic.com/news)
* [OECD AI Observatory](https://oecd.ai)
* [Stanford HAI](https://hai.stanford.edu)

Each student submits **one development, one governance implication, one policy recommendation** — plus *(added)* **one critical question** about how the development is being framed by its source. Align entries to the five source topics (education / state & public sector / nonprofits & public good / policy & governance / societal & economic impacts) so the tracker accumulates into the course's own evidence base.

Add one more tracker field: **source type** (`lab self-presentation`, `newspaper reporting`, `policy institution`, or `platform post`). This will make the class's own dataset analytically stronger.

---

## Source-to-module map (quick reference)

| Source file | M1 | M2 | M3 | M4 | M5 | M6 |
|---|:--:|:--:|:--:|:--:|:--:|:--:|
| 01 Education | ● | | | | ●● | |
| 02 Government & public sector | | ●● | | ○ | | |
| 03 Nonprofits & public good | | | | | ●● | |
| 04 Policy/governance/public benefit | ○ | | ○ | ●● | | ●● |
| 05 Societal & economic impacts | ●● | ○ | ○ | | ● | ● |
| current_media_digest | ● | ●● | ●● | ●● | ○ | ●● |

●● primary · ● supporting · ○ light/bridging
