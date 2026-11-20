# LLM Survey Digest, May–Nov 2026

Eighteen recent survey papers on generative AI (agents, memory, tool and skill use, reasoning, evaluation, LLMOps and serving, on-device, safety and security), summarised by taxonomy, key techniques and metrics, plus an original article, a slide deck and a narrated video.

## Deliverables

| Item | File |
|---|---|
| Survey spreadsheet (titles linked to PDFs) | [`llm_surveys_2026.xlsx`](llm_surveys_2026.xlsx), [`.csv`](llm_surveys_2026.csv) |
| Original article  | [`medium_article`](https://medium.com/@yashu.paladugu/eighteen-fresh-surveys-one-message-agents-are-loops-and-loops-need-gates-bb8653937986?postPublishedType=initial) |
| Slide deck | [`LLM_Surveys_2026.pptx`](LLM_Surveys_2026.pptx), [`.pdf`](LLM_Surveys_2026.pdf) |
| Figures | [`figures/`](figures) |
| Video | [`You_tube_video_explaining`](https://drive.google.com/file/d/1OPPWqIKFNRXGdaCBd1Jz5Z3VWum2chge/view?usp=sharing) |



## The surveys

Window: roughly May to November 2026 (the survey date range is described below). Titles link to the PDF.

| # | Paper (PDF link) | Date | Venue | Topic |
|---|---|---|---|---|
| 1 | [Software Engineering for LLM-Based Agents: A Lifecycle-Oriented Survey](https://arxiv.org/pdf/2611.23260) | 3 Oct 2026 | arXiv preprint (cs.SE) | AI engineering |
| 2 | [Safety in Self-Evolving Agents: A Survey](https://arxiv.org/pdf/2610.00093) | 2 Oct 2026 | arXiv preprint | AI safety |
| 3 | [Rollout Efficiency in Reinforcement Learning for Reasoning Large Language Models: A Taxonomy and Future Directions](https://arxiv.org/pdf/2609.25463) | Sep 2026 | arXiv preprint | LLM development / RL training |
| 4 | [LLM Agents for Time-Series: A Survey](https://arxiv.org/pdf/2608.26226) | 26 Aug 2026 | arXiv preprint | Agent applications |
| 5 | [Dynamic Agent Skills: A Lifecycle Survey and Taxonomy of Evolving Skill Libraries](https://arxiv.org/pdf/2607.10113) | 11 Jul 2026 | TMLR (07/2026) | Tool / skill use |
| 6 | [Towards Efficient Large Language Model Serving: A Survey on System-Aware KV Cache Optimization](https://arxiv.org/pdf/2607.08057v1) | 9 Jul 2026 | Findings of ACL 2026 | LLMOps / serving |
| 7 | [Isolation as a First-Class Principle for LLM-Agent System Safety: Concepts, Taxonomy, Challenges and Future Directions](https://arxiv.org/pdf/2607.12406) | Jul 2026 | arXiv preprint | AI safety |
| 8 | [Data-Centric Perspectives on Agentic Retrieval-Augmented Generation: A Survey](https://aclanthology.org/2026.findings-acl.78.pdf) | Jul 2026 | Findings of ACL 2026 | RAG / data |
| 9 | [A Survey of Reinforcement Learning for Large Language Models under Data Scarcity: Challenges and Solutions](https://aclanthology.org/2026.acl-long.1045.pdf) | Jul 2026 (2-7 Jul) | ACL 2026 (long, main conference) | Reasoning / RL |
| 10 | [LLM-Based Agents on the Edge: A Survey of Privacy, Scalability, Heterogeneity, and Autonomy](https://www.ijcai.org/proceedings/2026/0858.pdf) | 2026 | IJCAI-26 Survey Track | On-device / edge |
| 11 | [LLM agents security duality: a comprehensive survey of self-security and empowered cybersecurity](https://arxiv.org/pdf/2606.28450) | 26 Jun 2026 | arXiv preprint (cs.CR) | AI security |
| 12 | [Agents That Know Too Much: A Data-Centric Survey of Privacy in LLM Agents](https://arxiv.org/pdf/2606.26627) | 25 Jun 2026 | arXiv preprint (cs.CR) | Privacy |
| 13 | [The Periodic Table of LLM Reasoning: A Structured Survey of Reasoning Paradigms, Methods, and Failure Modes](https://arxiv.org/pdf/2606.11470) | 9 Jun 2026 | arXiv preprint (cs.CL) | Reasoning |
| 14 | [Toward Secure LLM Agents: Threat Surfaces, Attacks, Defenses, and Evaluation](https://arxiv.org/pdf/2606.10749) | 9 Jun 2026 | arXiv preprint (cs.CR) | AI security |
| 15 | [Large Language Models for Agentic NetOps and AIOps: Architectures, Evaluation, and Safety](https://arxiv.org/pdf/2605.12729) | May 2026 (v2 15 Jun 2026) | arXiv preprint (cs.NI) | LLMOps / operations |
| 16 | [Beyond Individual Intelligence: Surveying Collaboration, Failure Attribution, and Self-Evolution in LLM-based Multi-Agent Systems](https://arxiv.org/pdf/2605.14892) | 14 May 2026 | arXiv preprint (cs.AI) | Multi-agent |
| 17 | [From Storage to Experience: A Survey on the Evolution of LLM Agent Memory Mechanisms](https://arxiv.org/pdf/2605.06716) | 7 May 2026 | Findings of ACL 2026 | Memory |
| 18 | [Evaluating LLM-based Agents for Multi-Turn Conversations: A Survey](https://arxiv.org/pdf/2503.22458) | 28 Mar 2025 (revised 2026) | arXiv preprint (cs.CL) | Evaluation |

Related but outside scope: Agent-as-a-Judge (Jan 2026), and two preprints.org surveys (search agents, Aug 2026; multi-agent efficiency, Sep 2026). See the second sheet of the spreadsheet.

## Taxonomies at a glance

| Layer | Survey | Taxonomy |
|---|---|---|
| AI engineering | SE for LLM agents | 5 lifecycle stages |
| Multi-agent | LIFE | Lay, Integrate, Find faults, Evolve |
| Memory | Storage to Experience | Storage, Reflection, Experience |
| Skills / tools | Dynamic Agent Skills | 6 senses, 8 stages, 10 operators |
| Reasoning | Periodic Table | 36 families in a 6x6 grid |
| RL training | Rollout efficiency | System lever vs algorithmic lever, 7 families |
| Serving | KV cache (sKis) | Temporal, spatial, structural x 7 objectives |
| Edge | LLM agents on the edge | Deployment, role, topology, adaptation |
| Safety | SAVER | Substrate, Adaptation, Violation, Exposure, Response |
| Safety | Isolation | 5 boundaries |


```
