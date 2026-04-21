<h1 align="center">Agent Skills</h1>

<p align="center">
  A curated list of papers, benchmarks, and ecosystem resources for skill-centric LLM agent ecosystems.
</p>


<p align="center">
  <img src="https://img.shields.io/badge/Scope-Agent%20Skills-blue" alt="scope"/>
  <img src="https://img.shields.io/badge/Taxonomy-4%20Modules-6f42c1" alt="taxonomy"/>
  <img src="https://img.shields.io/badge/Updated-2026--04--21-success" alt="updated"/>
</p>


<p align="center">
  <a href="#taxonomy">Taxonomy</a> •
  <a href="#research-papers">Paper List</a> •
  <a href="#benchmarks-and-evaluation">Benchmarks</a> •
  <a href="#ecosystem-platforms-and-resources">Resources</a> •
  <a href="#citation">Citation</a>
</p>


This repository follows the lifecycle perspective in our survey:

- **Skill Representation**
- **Skill Acquisition**
- **Skill Retrieval and Selection**
- **Skill Evolution and Governance**

This repository is built for our **Agent Skills** survey project and will be continuously updated.

---

## Updates

- **2026-04-21**: Initial public release aligned with the survey taxonomy.

---

## Historical evolution of skills

<p align="center">
  <img src="https://raw.githubusercontent.com/JayLZhou/Awesome-Agent-Skills/main/history.png" width="95%" alt="history"/>
</p>



---

## Table of Contents

- [Related Surveys](#related-surveys)
- [Research Papers](#research-papers)
  - [0. Foundations: Tools, Protocols, Retrieval, Memory](#0-foundations-tools-protocols-retrieval-memory)
  - [1. Skill Representation](#1-skill-representation)
  - [2. Skill Acquisition](#2-skill-acquisition)
  - [3. Skill Retrieval and Selection](#3-skill-retrieval-and-selection)
  - [4. Skill Evolution and Governance](#4-skill-evolution-and-governance)
- [Benchmarks and Evaluation](#benchmarks-and-evaluation)
- [Ecosystem Platforms and Resources](#ecosystem-platforms-and-resources)
- [Application Scenarios](#application-scenarios)
- [Contributing](#contributing)
- [Citation](#citation)

---

## Related Surveys

- (TechRxiv 2026) *A Systematic Survey of Self-Evolving Agents: From Model-Centric to Environment-Driven Co-Evolution* [[Paper](https://www.techrxiv.org/doi/abs/10.36227/techrxiv.177203250.05832634/v2)]
- (arXiv 2026) *Externalization in LLM Agents: A Unified Review of Memory, Skills, Protocols and Harness Engineering* [[Paper](https://arxiv.org/abs/2604.08224)]
- (arXiv 2026) *SoK: Agentic Skills -- Beyond Tool Use in LLM Agents* [[Paper](https://arxiv.org/abs/2602.20867)]

---

## Research Papers

### 0. Foundations: Tools, Protocols, Retrieval, Memory

- (NeurIPS 2023) *Toolformer* [[Paper](https://arxiv.org/abs/2302.04761)]
- (ICLR 2023) *ReAct* [[Paper](https://arxiv.org/abs/2210.03629)]
- (arXiv 2023) *HuggingGPT* [[Paper](https://arxiv.org/abs/2303.17580)]
- (arXiv 2023) *ToolLLM* [[Paper](https://arxiv.org/abs/2307.16789)]
- (Anthropic 2024) *Model Context Protocol (MCP)* [[Paper](https://www.anthropic.com/news/model-context-protocol)]
- (OpenAI 2023) *Function Calling* [[Paper](https://openai.com/blog/function-calling-and-other-api-updates)]
- (NeurIPS 2020) *RAG* [[Paper](https://arxiv.org/abs/2005.11401)]
- (EMNLP 2020) *DPR* [[Paper](https://aclanthology.org/2020.emnlp-main.550/)]
- (arXiv 2025) *In-depth Analysis of Graph-based RAG in a Unified Framework* [[Paper](https://arxiv.org/abs/2503.04338)]
- (arXiv 2025) *ArchRAG: Attributed Community-based Hierarchical Retrieval-Augmented Generation* [[Paper](https://arxiv.org/abs/2502.09891)]
- (arXiv 2025) *Clue-RAG* [[Paper](https://arxiv.org/abs/2507.08445)]
- (arXiv 2025) *BookRAG: A Hierarchical Structure-aware Index-based Approach for RAG on Complex Documents* [[Paper](https://arxiv.org/abs/2512.03413)]
- (arXiv 2025) *EraRAG* [[Paper](https://arxiv.org/abs/2506.20963)]
- (arXiv 2023) *MemGPT* [[Paper](https://arxiv.org/abs/2310.08560)]
- (arXiv 2023) *Think-in-Memory* [[Paper](https://arxiv.org/abs/2311.08719)]
- (arXiv 2026) *EverMemOS* [[Paper](https://arxiv.org/abs/2601.02163)]
- (arXiv 2026) *HyperMem* [[Paper](https://arxiv.org/abs/2604.08256)]
- (arXiv 2026) *MSA* [[Paper](https://arxiv.org/abs/2603.23516)]

### 1. Skill Representation

#### Text-Based Skills

- (NeurIPS 2023) *Reflexion* [[Paper](https://arxiv.org/abs/2303.11366)]
- (AAAI 2024) *ExpeL* [[Paper](https://arxiv.org/abs/2308.10144)]
- (NeurIPS 2024) *Buffer of Thoughts* [[Paper](https://arxiv.org/abs/2406.04271)]
- (arXiv 2026) *Trace2Skill* [[Paper](https://arxiv.org/abs/2603.25158)]

#### Code-Backed Skills

- (NeurIPS 2023) *Voyager* [[Paper](https://arxiv.org/abs/2305.16291)]
- (arXiv 2026) *SkillCraft* [[Paper](https://arxiv.org/abs/2603.00718)]
- (ICLR 2026) *PolySkill* [[Paper](https://arxiv.org/abs/2510.15863)]
- (arXiv 2025) *Inducing Programmatic Skills for Agentic Tasks* [[Paper](https://arxiv.org/abs/2504.06821)]

#### Hybrid Skills

- (TPAMI 2025) *JARVIS-1* [[Paper](https://arxiv.org/abs/2311.05997)]
- (ICLR 2024) *Synapse* [[Paper](https://arxiv.org/abs/2306.07863)]
- (arXiv 2025) *SkillWeaver* [[Paper](https://arxiv.org/abs/2504.07079)]
- (arXiv 2026) *AgentSkillOS* [[Paper](https://arxiv.org/abs/2603.02176)]

### 2. Skill Acquisition

#### Human-Derived

- (arXiv 2026) *SkillNet* [[Paper](https://arxiv.org/abs/2603.04448)]
- (arXiv 2026) *AgentSkillOS* [[Paper](https://arxiv.org/abs/2603.02176)]
- (arXiv 2026) *SoK: Agentic Skills* [[Paper](https://arxiv.org/abs/2602.20867)]
- (arXiv 2024) *Agent Hospital* [[Paper](https://arxiv.org/abs/2405.02957)]

#### Experience-Derived

- (NeurIPS 2023) *Voyager* [[Paper](https://arxiv.org/abs/2305.16291)]
- (NeurIPS 2023) *Reflexion* [[Paper](https://arxiv.org/abs/2303.11366)]
- (AAAI 2024) *ExpeL* [[Paper](https://arxiv.org/abs/2308.10144)]
- (NeurIPS 2024) *Buffer of Thoughts* [[Paper](https://arxiv.org/abs/2406.04271)]
- (arXiv 2026) *Trace2Skill* [[Paper](https://arxiv.org/abs/2603.25158)]
- (ICML 2025) *Agent Workflow Memory* [[Paper](https://arxiv.org/abs/2409.07429)]
- (arXiv 2025) *AgentEvolver* [[Paper](https://arxiv.org/abs/2511.10395)]
- (arXiv 2025) *G-memory* [[Paper](https://arxiv.org/abs/2506.07398)]
- (arXiv 2025) *Nemori* [[Paper](https://arxiv.org/abs/2502.14828)]

#### Task-Derived

- (Findings EMNLP 2023) *CREATOR* [[Paper](https://aclanthology.org/2023.findings-emnlp.462/)]
- (ICLR 2024) *ToolMakers* [[Paper](https://arxiv.org/abs/2305.17126)]
- (arXiv 2024) *Cradle* [[Paper](https://arxiv.org/abs/2403.03186)]
- (arXiv 2024) *CodeAct* [[Paper](https://arxiv.org/abs/2402.01030)]

#### Corpus-Derived

- (arXiv 2023) *AppAgent* [[Paper](https://arxiv.org/abs/2312.13771)]
- (arXiv 2024) *AutoGuide* [[Paper](https://arxiv.org/abs/2403.08978)]
- (arXiv 2023) *HuggingGPT* [[Paper](https://arxiv.org/abs/2303.17580)]
- (arXiv 2023) *ToolLLM* [[Paper](https://arxiv.org/abs/2307.16789)]
- (arXiv 2024) *DS-Agent* [[Paper](https://arxiv.org/abs/2402.17453)]

### 3. Skill Retrieval and Selection

#### Retrieval

- (ICLR 2025) *ToolGen: Unified Tool Retrieval and Calling via Generation* [[Paper](https://arxiv.org/abs/2410.03439)]
- (arXiv 2023) *ToolLLM* [[Paper](https://arxiv.org/abs/2307.16789)]
- (arXiv 2026) *SkillRL* [[Paper](https://arxiv.org/abs/2602.08234)]
- (arXiv 2026) *AgentSkillOS* [[Paper](https://arxiv.org/abs/2603.02176)]
- (arXiv 2026) *SkillNet* [[Paper](https://arxiv.org/abs/2603.04448)]
- (arXiv 2026) *GraphSkill* [[Paper](https://arxiv.org/abs/2603.06620)]

#### Selection and Routing

- (arXiv 2024) *AutoGuide* [[Paper](https://arxiv.org/abs/2403.08978)]
- (arXiv 2026) *MemSkill* [[Paper](https://arxiv.org/abs/2602.02474)]
- (arXiv 2026) *Memento-Skills* [[Paper](https://arxiv.org/abs/2603.18743)]
- (arXiv 2026) *SkillRouter* [[Paper](https://arxiv.org/abs/2603.22455)]
- (Findings ACL 2025) *ToolExpNet* [[Paper](https://aclanthology.org/2025.findings-acl.811/)]

### 4. Skill Evolution and Governance

#### Skill Formation, Refinement, and RL Optimization

- (arXiv 2024) *TROVE* [[Paper](https://arxiv.org/abs/2401.12869)]
- (arXiv 2026) *Memento-Skills* [[Paper](https://arxiv.org/abs/2603.18743)]
- (arXiv 2026) *AutoSkill* [[Paper](https://arxiv.org/abs/2603.01145)]
- (arXiv 2026) *EvoSkill* [[Paper](https://arxiv.org/abs/2603.02766)]
- (arXiv 2026) *AutoRefine* [[Paper](https://arxiv.org/abs/2601.22758)]
- (arXiv 2026) *SkillRL* [[Paper](https://arxiv.org/abs/2602.08234)]
- (arXiv 2026) *Uni-Skill* [[Paper](https://arxiv.org/abs/2603.02623)]
- (arXiv 2026) *ARISE* [[Paper](https://arxiv.org/abs/2603.16060)]
- (arXiv 2025) *CASCADE* [[Paper](https://arxiv.org/abs/2512.23880)]

#### Memory-Centric and Runtime Re-entry

- (arXiv 2025) *ReasoningBank* [[Paper](https://arxiv.org/abs/2509.25140)]
- (arXiv 2026) *MemRL* [[Paper](https://arxiv.org/abs/2601.03192)]
- (arXiv 2026) *MemSkill* [[Paper](https://arxiv.org/abs/2602.02474)]
- (arXiv 2025) *MemEvolve* [[Paper](https://arxiv.org/abs/2512.18746)]

#### Governance, Trust, and Ecosystem Risk

- (arXiv 2026) *SkillRouter* [[Paper](https://arxiv.org/abs/2603.22455)]
- (arXiv 2026) *SkillNet* [[Paper](https://arxiv.org/abs/2603.04448)]
- (Preprints 2026) *SkillOS* [[Paper](https://www.preprints.org/manuscript/202602.1096/v1)]
- (arXiv 2025) *Audited Skill-Graph* [[Paper](https://arxiv.org/abs/2512.23760)]
- (Zenodo 2026) *PoisonedSkills* [[Paper](https://doi.org/10.5281/zenodo.19281322)]

---

## Benchmarks and Evaluation

- *AgentBench* [[Paper](https://arxiv.org/abs/2308.03688)]
- *WebArena* [[Paper](https://arxiv.org/abs/2307.13854)]
- *TaskBench* [[Paper](https://arxiv.org/abs/2311.18760)]
- *STULIFE* [[Paper](https://arxiv.org/abs/2508.19005)]
- *TRACE* [[Paper](https://arxiv.org/abs/2510.00415)]
- *Evo-Memory* [[Paper](https://arxiv.org/abs/2511.20857)]
- *SkillsBench* [[Paper](https://arxiv.org/abs/2602.12670)]

---

## Ecosystem Platforms and Resources

- **SkillNet**: https://skillnet.openkg.cn/
- **ClawHub**: https://clawhub.ai/
- **SkillHub**: https://www.skillhub.club/
- **SkillsMP**: https://skillsmp.com/
- **Skills.sh**: https://skills.sh/

---

## Application Scenarios

- **Code Agents**: reusable coding/debugging/test-repair skills (e.g., CodeAct, SWE-agent, DS-Agent).
- **Web/GUI Agents**: UI-script and workflow skills for browser/app control (e.g., Synapse, SkillWeaver).
- **Chatbots**: memory/tool-routing skills for long-horizon conversations and tool use (e.g., MemGPT, HyperMem).
- **Robotics/Embodied**: executable policy/skill libraries for grounded control (e.g., Voyager, Uni-Skill).
- **Healthcare/Finance**: domain-constrained procedural skills with safety and compliance requirements.
- **Game/Social Simulation**: open-ended skill growth and memory-driven behavior adaptation.

---

## Contributing

Contributions are very welcome.

If you want to add a paper/resource, please include:

1. Title
2. Venue/Year
3. Link (paper/code/project)
4. Suggested category in this taxonomy

You can open an issue or submit a pull request directly.

---

## Citation

If this repository is useful for your work, please cite our survey project.

```bibtex
@article{agentskills2026,
  title   = {Agent Skills: A Survey of Skill-Centric LLM Agent Ecosystems},
  author  = {Anonymous},
  year    = {2026},
  note    = {Manuscript in preparation}
}
```
