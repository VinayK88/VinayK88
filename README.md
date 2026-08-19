<p align="center">
  <img src="./assets/cybersecurity-ai-banner.png" alt="Cybersecurity and AI security portfolio banner" width="100%" />
</p>

<div align="center">

# Vinay K.

### Cybersecurity Data Scientist · AI Security · Security ML · Trust & Safety

**I build data-science systems that measure whether security controls and AI-powered defenses actually reduce risk — while quantifying false positives, user friction, detection quality, remediation, and downstream outcomes.**

[![Agent Security](https://img.shields.io/badge/Agent%20Security-AgentShield-2F81F7?style=flat-square)](https://github.com/VinayK88/AgentShield)
[![Finding Intelligence](https://img.shields.io/badge/AI%20Finding%20Intelligence-VulnSignal-238636?style=flat-square)](https://github.com/VinayK88/VulnSignal)
[![LLM Evaluation](https://img.shields.io/badge/LLM%20Security-Evaluation-8957E5?style=flat-square)](https://github.com/VinayK88/LLM-Security-Evaluation-Lab)
[![Detection ML](https://img.shields.io/badge/Detection%20ML-DetectionForge-D29922?style=flat-square)](https://github.com/VinayK88/DetectionForge)

`Security Measurement` · `Agent Security` · `Experimentation` · `Detection ML` · `Anomaly Detection` · `Graph ML` · `Model Monitoring` · `Trust & Safety`

</div>

---

## What I Focus On

I work at the intersection of **cybersecurity, machine learning, and decision science**.

The recurring question across my projects is not simply whether a model can generate a score or detect an event. It is:

> **Did the system improve a real security outcome, and what operational cost did it introduce?**

That means measuring things like:

- risky actions prevented;
- legitimate task completion;
- false-positive and escalation burden;
- approval latency and time-to-detection;
- finding precision, severity, and actionability;
- developer acceptance and remediation;
- verified resolution;
- calibration, drift, and threshold tradeoffs;
- treatment effects and uncertainty.

<p align="center">
  <img src="./assets/security-measurement-map.svg" alt="Security data science measurement portfolio map" width="100%" />
</p>

---

## Flagship Projects

<table>
<tr>
<td width="50%" valign="top">

### [AgentShield](https://github.com/VinayK88/AgentShield)
**AI-agent runtime security + safeguard measurement**

Intent-aware runtime controls with `ALLOW / REDACT / APPROVAL / BLOCK`, learned trajectory-risk signals, and security-control measurement focused on **risk reduction versus user friction**.

**Measures:** prevented-risk rate · false positives · task completion · approval latency · recovery · security utility

**Focus:** Agent security · MCP · sequence modeling · experimentation · human approval

</td>
<td width="50%" valign="top">

### [VulnSignal](https://github.com/VinayK88/VulnSignal)
**AI security finding quality + remediation intelligence**

Evaluates the full lifecycle after an AI system reports a vulnerability: correctness, severity, duplication, actionability, developer triage, remediation, and verified resolution.

**Measures:** precision/recall · actionability · duplicate burden · acceptance · remediation · verified resolution

**Focus:** Security product analytics · workflow experiments · decision science · Streamlit dashboard

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [LLM Security Evaluation Lab](https://github.com/VinayK88/LLM-Security-Evaluation-Lab)
**Model / agent safeguard evaluation**

Evaluation framework for prompt injection, leakage, tool authorization, human approval, repeated trials, and longitudinal misuse/intervention quality.

**Measures:** safeguard failures · actor-level detection · hard-negative friction · repeated-run uncertainty · intervention quality

**Focus:** LLM safety · security evaluation · misuse detection · guardrails

</td>
<td width="50%" valign="top">

### [DetectionForge](https://github.com/VinayK88/DetectionForge)
**Detection engineering + ML prioritization**

Detection-as-code with replay-based precision/recall/FPR gates, ATT&CK coverage, supervised alert ranking, and uncertainty-based analyst review.

**Measures:** precision · recall · FPR · F1 · release gates · analyst prioritization

**Focus:** Security ML · detection lifecycle · active learning · SIEM · CI/CD

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [RiskOS](https://github.com/VinayK88/riskos)
**Trust & Safety decision science**

Behavioral, graph, sequence, calibration, exposure, and capacity-aware risk decisioning with explicit `ALLOW / CHALLENGE / REVIEW / BLOCK` policy outcomes.

**Measures:** calibration · expected loss · review capacity · threshold economics · drift

**Focus:** Adversarial ML · trust & safety · graph risk · decision optimization

</td>
<td width="50%" valign="top">

### [Frontier Agent Evals](https://github.com/VinayK88/frontier-agent-evals)
**Long-horizon agent evaluation**

Versioned environments, perturbations, process graders, safety checks, deterministic replay, and calibration for multi-step agent behavior.

**Measures:** outcome · process · safety · efficiency · calibration

**Focus:** Agent evaluation · robustness · process quality · reproducibility

</td>
</tr>
</table>

---

## Security Measurement & AI Evaluation

| Question | Project | Measurement approach |
| --- | --- | --- |
| **Do agent safeguards reduce risk without excessive friction?** | [AgentShield](https://github.com/VinayK88/AgentShield) | Risk prevention, false positives, task success, approval latency, recovery, utility |
| **Are AI security findings trustworthy and acted on?** | [VulnSignal](https://github.com/VinayK88/VulnSignal) | Precision/recall, severity, duplication, actionability, remediation, verified resolution |
| **Do model safeguards hold across interactions and actors?** | [LLM Security Evaluation Lab](https://github.com/VinayK88/LLM-Security-Evaluation-Lab) | Single-trace grading, longitudinal misuse, intervention quality, repeated trials |
| **Can long-horizon agent behavior be evaluated beyond final answer quality?** | [Frontier Agent Evals](https://github.com/VinayK88/frontier-agent-evals) | Outcome/process/safety separation, perturbations, replay, calibration |
| **Do detections deserve to ship and which alerts matter most?** | [DetectionForge](https://github.com/VinayK88/DetectionForge) | Replay metrics, release gates, supervised prioritization, active learning |
| **What action minimizes security loss under finite review capacity?** | [RiskOS](https://github.com/VinayK88/riskos) | Calibration, expected loss, capacity constraints, policy optimization |

---

## Experimentation & Decision Science

The portfolio includes more than predictive modeling. Several projects explicitly evaluate **interventions and operating policies**:

- **A/B-style workflow comparisons** for enriched versus raw security findings;
- **bootstrap confidence intervals** for treatment deltas and remediation improvement;
- **security utility / cost functions** balancing risk reduction against friction;
- **calibration and reliability analysis** rather than treating model scores as probabilities by default;
- **threshold optimization** under analyst-capacity or review-cost constraints;
- **champion / challenger evaluation** before policy promotion;
- **guardrail metrics** such as task completion, hard-negative false positives, and approval latency.

`A/B Testing` · `Bootstrap CIs` · `Calibration` · `Guardrail Metrics` · `Cost-sensitive Decisioning` · `Treatment Effects` · `Threshold Optimization`

---

## Production ML Practices Demonstrated

| Practice | Examples across portfolio |
| --- | --- |
| **Evaluation** | Holdouts, hard negatives, confusion metrics, long-horizon graders, severity error, duplicate burden |
| **Monitoring** | PSI-style drift, feature/schema versioning, distribution movement, model/threshold tracking |
| **Robustness** | Low-and-slow behavior, prompt injection, permission growth, transient failures, shifted populations |
| **Explainability** | Rule reasons, feature deviations, graph paths, sequence transitions, actionability components |
| **Human-in-the-loop** | Approval gates, analyst review queues, active learning, developer disposition feedback |
| **Safe automation boundaries** | Deterministic authorization and policy controls remain separate from learned scores |
| **Reproducibility** | Seeded fixtures, tests, APIs/CLIs, dashboards, Docker, GitHub Actions |

> **Evaluation boundary:** security telemetry is often sensitive, so many public portfolio projects use deterministic synthetic fixtures and explicit hard negatives. Metrics are presented as implementation/evaluation evidence, not production efficacy claims.

---

## Technical Focus

<table>
<tr>
<td width="33%" valign="top">

**Security**

AI / agent security  
Detection engineering  
Identity / IAM  
Threat intelligence  
Cloud / SaaS security  
Trust & Safety  
Attack-path analysis  
MITRE ATT&CK

</td>
<td width="33%" valign="top">

**Data Science / ML**

Supervised classification  
Gradient Boosting  
Isolation Forest  
Sequence modeling  
Graph ML  
Anomaly detection  
Calibration  
Experimentation  
Active learning  
Drift monitoring

</td>
<td width="33%" valign="top">

**Engineering**

Python  
SQL  
PySpark / Spark  
FastAPI  
Streamlit  
scikit-learn  
NetworkX  
Docker  
GitHub Actions  
Jupyter

</td>
</tr>
</table>

---

<details>
<summary><b>Additional Security & AI Projects</b></summary>

<br/>

- **[AgentAtlas](https://github.com/VinayK88/AgentAtlas)** — AI-agent posture, permission drift, effective-access graphs, and anomaly prioritization.
- **[Threat Intelligence Knowledge Graph](https://github.com/VinayK88/Threat-intelligence-knowledgegraph)** — CTI evidence paths and graph link prediction.
- **[AttackPath AI](https://github.com/VinayK88/attackpath-ai)** — identity + agentic attack-path detection and early-stop measurement.
- **[BrowserGuard](https://github.com/VinayK88/BrowserGuard)** — browser/extension anomaly detection and SaaS blast-radius analysis.
- **[SaaSGraph](https://github.com/VinayK88/SaaSGraph)** — OAuth/SaaS risk, token behavior, permissions, and resource reach.
- **[CloudRescue](https://github.com/VinayK88/CloudRescue)** — cloud recovery forecasting and deterministic recoverability gates.
- **[DeepTrace](https://github.com/VinayK88/DeepTrace)** — NLP clustering and content-integrity evidence analysis.
- **[AI Data Center Security Digital Twin](https://github.com/VinayK88/ai-datacenter-security-digital-twin)** — cyber-physical attack paths and multivariate anomaly detection.
- **[MacSentinel](https://github.com/VinayK88/macsentinel)** — macOS threat analytics with provenance and behavioral ML.
- **[SupplyChain Guardian AI](https://github.com/VinayK88/supplychain-guardian-ai)** — software supply-chain graphs, SBOM/provenance, ML ranking, and policy gates.

</details>

---

<div align="center">

### Selected Portfolio

[**AgentShield**](https://github.com/VinayK88/AgentShield) · [**VulnSignal**](https://github.com/VinayK88/VulnSignal) · [**LLM Security Evaluation Lab**](https://github.com/VinayK88/LLM-Security-Evaluation-Lab)  
[**DetectionForge**](https://github.com/VinayK88/DetectionForge) · [**RiskOS**](https://github.com/VinayK88/riskos) · [**Frontier Agent Evals**](https://github.com/VinayK88/frontier-agent-evals)

[Browse all repositories →](https://github.com/VinayK88?tab=repositories)

</div>
