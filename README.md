<p align="center">
  <img src="./assets/cybersecurity-ai-banner.png" alt="Cybersecurity and AI security portfolio banner" width="100%" />
</p>

<div align="center">

# Vinay K.

### Cybersecurity Data Scientist · AI Security · Trust & Safety

**Building measurable, explainable security and AI systems across agent safeguards, trust & risk, detection, threat intelligence, and critical-infrastructure resilience.**

[![AI Security](https://img.shields.io/badge/AI%20Security-111827?style=flat-square)](https://github.com/VinayK88/LLM-Security-Evaluation-Lab)
[![Agent Security](https://img.shields.io/badge/Agent%20Security-0F766E?style=flat-square)](https://github.com/VinayK88/AgentAtlas)
[![Trust & Safety](https://img.shields.io/badge/Trust%20%26%20Safety-9A3412?style=flat-square)](https://github.com/VinayK88/riskos)
[![Critical Infrastructure](https://img.shields.io/badge/Critical%20Infrastructure-334155?style=flat-square)](https://github.com/VinayK88/InfraGuard-AI)
[![Detection Engineering](https://img.shields.io/badge/Detection%20Engineering-1E3A8A?style=flat-square)](https://github.com/VinayK88/DetectionForge)

`Security ML` · `LLM / Agent Evaluation` · `Trust & Risk` · `Critical Infrastructure` · `SOC Analytics` · `Identity / IAM` · `Threat Intelligence` · `Graph Analytics`

</div>

---

## Profile

I design and evaluate **security and AI systems that turn complex signals into defensible decisions**. My work combines cybersecurity, applied machine learning, graph analytics, LLM/agent evaluation, trust & safety, and production-oriented engineering with an emphasis on **explainability, measurable quality, human review, and reproducibility**.

I am especially interested in problems where model quality alone is not enough. A useful security system also needs trustworthy data, interpretable evidence, explicit decision thresholds, safe automation boundaries, resilient failure modes, analyst or reviewer feedback, and continuous evaluation after deployment.

My portfolio spans four complementary areas:

| AI & Agent Security | Detection & Security Analytics | Trust & Risk | Threat, Infrastructure & Resilience |
| --- | --- | --- | --- |
| LLM safeguards, agent identity, prompt injection, tool abuse, containment and intervention evaluation | Detection-as-code, telemetry, anomaly/graph/sequence detection, SOC investigation and feedback loops | Fraud/abuse signals, calibration, review capacity, policy thresholds and decision economics | IAM attack paths, CTI, software supply chain, endpoint security, AI infrastructure and critical-infrastructure assurance |

### How the portfolio connects

The projects cover different parts of a broader security decision lifecycle rather than representing isolated demos:

| Capability | Representative projects | Core question |
| --- | --- | --- |
| **Understand the environment** | [AgentAtlas](https://github.com/VinayK88/AgentAtlas), [Security Telemetry Lakehouse](https://github.com/VinayK88/Security-Telemetry-Lakehouse) | What agents, identities, permissions, assets and events exist, and which relationships matter? |
| **Evaluate AI behavior** | [LLM Security Evaluation Lab](https://github.com/VinayK88/LLM-Security-Evaluation-Lab), [Frontier Agent Evals](https://github.com/VinayK88/frontier-agent-evals), [Model Containment Eval Lab](https://github.com/VinayK88/model-containment-eval-lab) | Does an AI system remain safe and reliable under misuse, prompt injection, tool use and adversarial conditions? |
| **Detect & investigate** | [DetectionForge](https://github.com/VinayK88/DetectionForge), [MacSentinel](https://github.com/VinayK88/macsentinel), [Agentic SOC Investigator](https://github.com/VinayK88/Agentic-soc-investigator) | Which behavior warrants attention, how good is the signal, and what evidence explains it? |
| **Assure high-consequence systems** | [InfraGuard AI](https://github.com/VinayK88/InfraGuard-AI), [AI Data Center Security Digital Twin](https://github.com/VinayK88/ai-datacenter-security-digital-twin) | Can AI-assisted infrastructure remain within safe operating bounds when data, models, identities or control paths become unreliable or compromised? |
| **Make risk decisions** | [RiskOS](https://github.com/VinayK88/riskos), [SupplyChain Guardian AI](https://github.com/VinayK88/supplychain-guardian-ai) | What action should be taken given risk, uncertainty, false positives, review capacity and policy constraints? |

---

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### [AgentAtlas](https://github.com/VinayK88/AgentAtlas)
**AI-agent identity & access governance**

Discovers managed, shadow, orphaned and dormant agents; models effective access, delegation risk, permission drift and sensitive-data reachability with transparent posture scoring.

**Focus:** Agent security · IAM · access graphs · governance

</td>
<td width="50%" valign="top">

### [LLM Security Evaluation Lab](https://github.com/VinayK88/LLM-Security-Evaluation-Lab)
**Frontier-model safeguards & misuse evaluation**

Claude API adapter, repeated trials, tool-safety and prompt-injection evaluation, actor-level misuse trajectories, intervention policies, hard negatives, and reproducible evaluation traces.

**Focus:** AI safety · LLM evaluation · safeguards · red-team methodology

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [RiskOS](https://github.com/VinayK88/riskos)
**Trust & Safety decisioning platform**

Behavioral, temporal and graph signals with calibration, expected-loss optimization, review-capacity thresholds, champion/challenger evaluation, and explainable policy decisions.

**Focus:** Trust & Safety · fraud risk · calibration · decision science

</td>
<td width="50%" valign="top">

### [DetectionForge](https://github.com/VinayK88/DetectionForge)
**Detection engineering as code**

Versioned detections with Sigma-style rules, KQL compilation, malicious/benign replay, precision/recall/FPR release gates, ATT&CK coverage, analyst feedback, FastAPI dashboard, and CI.

**Focus:** Detection lifecycle · SIEM · KQL · ATT&CK · regression testing

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [InfraGuard AI](https://github.com/VinayK88/InfraGuard-AI)
**Critical-infrastructure AI assurance & mission resilience**

Defensive IT/OT/ICS-style simulation with operational safety envelopes, AI/data provenance checks, least-privilege action controls, human override, degraded-safe operation, scenario replay and transparent mission-resilience scoring.

**Focus:** Critical infrastructure · AI assurance · OT/ICS · resilience · human control

</td>
<td width="50%" valign="top">

### [AI Data Center Security Digital Twin](https://github.com/VinayK88/ai-datacenter-security-digital-twin)
**AI infrastructure attack-path simulation**

Models GPU nodes, BMCs, Kubernetes, identity, network and power systems as directed attack/trust graphs to measure blast radius, chokepoints, and control impact.

**Focus:** AI infrastructure · attack graphs · resilience · security architecture

</td>
</tr>
</table>

> **Evaluation note:** most public datasets and attack scenarios are intentionally synthetic or simulation-based because real security telemetry is sensitive. Each repository documents its evaluation boundary and what its metrics do—and do not—establish.

---

## Engineering Principles

- **Threat and abuse model first** — define assets, trust boundaries, misuse cases and measurable failure conditions before choosing a model.
- **Evaluation before deployment** — use hard negatives, regression testing, calibration, drift checks and explicit quality gates.
- **Evidence over demos** — preserve traces, provenance, baselines, failure cases and machine-readable outputs.
- **Human control for sensitive actions** — keep high-impact actions behind least-privilege tooling, approvals and rollback paths.
- **Resilient failure behavior** — design degraded-safe states and recovery paths instead of assuming inputs, models and dependencies remain healthy.
- **Interpretable by default** — combine rules, classical ML, graph reasoning, sequence models and LLMs where each is actually useful.
- **Decision quality matters** — optimize not only model scores, but also false positives, reviewer workload, intervention timing and operational risk.

---

## Technical Focus

<table>
<tr>
<td width="33%" valign="top">

**Cybersecurity & Risk**

AI / agent security  
Trust & Safety  
SIEM / SOC analytics  
Identity / IAM  
MITRE ATT&CK  
CTI / OSINT  
Critical infrastructure / OT / ICS assurance  
Attack paths  
Software supply chain  
Endpoint & AI infrastructure security

</td>
<td width="33%" valign="top">

**AI / Machine Learning**

Anomaly detection  
Classification  
Graph analytics  
Sequence models  
Calibration  
Risk modeling  
RAG  
LLM / agent evaluation  
Safety & robustness metrics

</td>
<td width="33%" valign="top">

**Engineering**

Python  
SQL  
PySpark / Spark  
Swift  
FastAPI  
Streamlit  
Docker  
GitHub Actions  
Jupyter  
SARIF

</td>
</tr>
</table>

---

## More Security & AI Work

<details>
<summary><strong>AI safety, interpretability & agent evaluation</strong></summary>
<br>

- **[Frontier Agent Evals](https://github.com/VinayK88/frontier-agent-evals)** — long-horizon tool environments, perturbations, process/outcome/safety graders and calibration.
- **[Oversight Integrity Lab](https://github.com/VinayK88/oversight-integrity-lab)** — compromised oversight, hidden triggers, counterfactual pairs and independent monitoring.
- **[Model Containment Eval Lab](https://github.com/VinayK88/model-containment-eval-lab)** — shutdown compliance, tripwires, trace monitoring and strict-vs-audit containment experiments.
- **[Sparse Feature Interpretability Lab](https://github.com/VinayK88/sparse-feature-interpretability-lab)** — sparse autoencoders, feature recovery and causal interventions.

</details>

<details>
<summary><strong>Security engineering, detection & threat intelligence</strong></summary>
<br>

- **[MacSentinel](https://github.com/VinayK88/macsentinel)** — privacy-preserving macOS security analytics with Swift telemetry replay, provenance graphs, anomaly/sequence/graph ML, drift testing and macOS CI.
- **[Agentic SOC Investigator](https://github.com/VinayK88/Agentic-soc-investigator)** — evidence-grounded investigation across identity, endpoint, cloud and OAuth.
- **[AttackPath AI](https://github.com/VinayK88/attackpath-ai)** — hybrid detection and graph reconstruction for identity, cloud and agent attack paths.
- **[GPU Trust Guardian](https://github.com/VinayK88/gpu-trust-guardian)** — GPU telemetry, synthetic attestation, behavioral trust scoring and policy gates.
- **[SupplyChain Guardian AI](https://github.com/VinayK88/supplychain-guardian-ai)** — SBOM, CI/CD, provenance, dependency risk and release policy gates.
- **[Security Telemetry Lakehouse](https://github.com/VinayK88/Security-Telemetry-Lakehouse)** — normalization, deduplication, late-event handling and detection-ready features.
- **[Threat Intelligence Knowledge Graph](https://github.com/VinayK88/Threat-intelligence-knowledgegraph)** — typed CTI entities, evidence paths and retrieval-grounded graph investigation.
- **[OSINT Threat Intelligence Agent](https://github.com/VinayK88/Osint-threat-intell-agent)** — provenance, contradiction testing, entity correlation and ATT&CK context.

</details>

<details>
<summary><strong>AI systems & security architecture</strong></summary>
<br>

- **[Inference Scheduler Lab](https://github.com/VinayK88/inference-scheduler-lab)** — continuous batching, SLO-aware scheduling, TTFT, throughput and KV-cache pressure.
- **[Counterfactual Security Engine](https://github.com/VinayK88/Counterfactual-security-engine)** — enterprise attack paths and control-hardening counterfactuals.

</details>

---

<div align="center">

### Selected Portfolio

[**AgentAtlas**](https://github.com/VinayK88/AgentAtlas) · [**LLM Security Evaluation Lab**](https://github.com/VinayK88/LLM-Security-Evaluation-Lab) · [**RiskOS**](https://github.com/VinayK88/riskos) · [**DetectionForge**](https://github.com/VinayK88/DetectionForge) · [**InfraGuard AI**](https://github.com/VinayK88/InfraGuard-AI) · [**AI Data Center Digital Twin**](https://github.com/VinayK88/ai-datacenter-security-digital-twin)

[Browse all repositories →](https://github.com/VinayK88?tab=repositories)

</div>