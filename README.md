<p align="center">
  <img src="./assets/cybersecurity-ai-banner.png" alt="Cybersecurity and AI security portfolio banner" width="100%" />
</p>

<div align="center">

# Vinay K.

### Cybersecurity Data Scientist · AI Security · Security ML · Cloud, SaaS & Browser Security · Trust & Safety

**Building measurable, explainable security systems across AI agents, identity, detection, browsers, SaaS/OAuth, threat intelligence, cloud resilience, content integrity, and AI infrastructure.**

[![AI Security](https://img.shields.io/badge/AI%20Security-111827?style=flat-square)](https://github.com/VinayK88/AgentShield)
[![Security ML](https://img.shields.io/badge/Security%20ML-0F766E?style=flat-square)](https://github.com/VinayK88/DetectionForge)
[![Browser Security](https://img.shields.io/badge/Browser-Security-0284C7?style=flat-square)](https://github.com/VinayK88/BrowserGuard)
[![SaaS Security](https://img.shields.io/badge/SaaS%20%2F%20OAuth-Security-0F766E?style=flat-square)](https://github.com/VinayK88/SaaSGraph)
[![Threat Intelligence](https://img.shields.io/badge/Threat%20Intelligence-Graph%20ML-6D28D9?style=flat-square)](https://github.com/VinayK88/Threat-intelligence-knowledgegraph)
[![Cloud Security](https://img.shields.io/badge/Cloud%20Security-0369A1?style=flat-square)](https://github.com/VinayK88/CloudRescue)
[![Trust & Safety](https://img.shields.io/badge/Trust%20%26%20Safety-9A3412?style=flat-square)](https://github.com/VinayK88/riskos)

`Security ML` · `Agent Security` · `Detection Engineering` · `Graph ML` · `Sequence Modeling` · `Anomaly Detection` · `Model Monitoring` · `Trust & Safety`

</div>

---

## Profile

I build **security and AI systems that turn noisy telemetry, identity relationships, model behavior, and risk signals into defensible decisions**.

My portfolio combines cybersecurity with applied machine learning, graph analytics, detection engineering, AI-agent security, cloud/SaaS/browser security, trust & safety, threat intelligence, and production-oriented engineering. I emphasize **explainability, measurable evaluation, drift monitoring, human review, safe automation boundaries, reproducibility, and explicit failure modes**.

A recurring design principle across these projects is that ML should improve prioritization or inference **without silently overriding hard security controls**.

---

## Security ML Portfolio

| ML capability | Representative project | Security problem |
| --- | --- | --- |
| **Supervised alert prioritization + active learning** | [DetectionForge](https://github.com/VinayK88/DetectionForge) | Rank fired detections and surface uncertain alerts for analyst labeling while deterministic release gates remain authoritative |
| **Sequence / trajectory modeling** | [AgentShield](https://github.com/VinayK88/AgentShield) | Learn normal tool-call transitions and surface unusual AI-agent action sequences without replacing runtime policy |
| **Graph ML / link prediction** | [Threat Intelligence Knowledge Graph](https://github.com/VinayK88/Threat-intelligence-knowledgegraph) | Rank plausible missing CTI relationships for analyst investigation using structural graph features |
| **Multivariate temporal anomaly detection** | [AI Data Center Security Digital Twin](https://github.com/VinayK88/ai-datacenter-security-digital-twin) | Detect unusual combinations of GPU, power, identity, BMC, Kubernetes, network, thermal, and model telemetry |
| **Unsupervised browser anomaly detection** | [BrowserGuard](https://github.com/VinayK88/BrowserGuard) | Combine Isolation Forest behavior signals with extension posture and browser→SaaS blast radius |
| **AI-agent posture anomaly detection** | [AgentAtlas](https://github.com/VinayK88/AgentAtlas) | Prioritize unusual agent identities using Isolation Forest, peer deviation, and effective-access graph features |
| **OAuth / SaaS behavioral anomaly detection** | [SaaSGraph](https://github.com/VinayK88/SaaSGraph) | Detect unusual token, scope, API, publisher, consent, and resource-reach patterns |
| **NLP clustering** | [DeepTrace](https://github.com/VinayK88/DeepTrace) | Use TF-IDF + DBSCAN to cluster semantically similar narratives under explicit coordination evidence gates |
| **Supervised recovery forecasting** | [CloudRescue](https://github.com/VinayK88/CloudRescue) | Forecast restore time / RTO pressure with Random Forest while deterministic recovery blockers remain authoritative |
| **Decision science / calibration** | [RiskOS](https://github.com/VinayK88/riskos) | Combine behavioral, graph, calibration, expected-loss, and analyst-capacity signals into risk decisions |

---

## Latest Security Projects

<table>
<tr>
<td width="50%" valign="top">

### [DetectionForge](https://github.com/VinayK88/DetectionForge)
**Detection engineering + supervised ML prioritization**

Sigma-style detection-as-code, KQL compilation, attack/benign replay, precision/recall/FPR quality gates, ATT&CK coverage, **Gradient Boosting alert ranking**, and uncertainty-based active learning.

**Focus:** Security ML · detection lifecycle · active learning · SIEM · CI/CD

</td>
<td width="50%" valign="top">

### [AgentShield](https://github.com/VinayK88/AgentShield)
**Runtime AI-agent security + learned trajectory risk**

Intent-aware tool policy with `ALLOW / REDACT / APPROVAL / BLOCK`, plus a learned **Markov trajectory-surprisal model** for unusual multi-step tool behavior.

**Focus:** Agent security · MCP · sequence ML · least privilege · human approval

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Threat Intelligence Knowledge Graph](https://github.com/VinayK88/Threat-intelligence-knowledgegraph)
**CTI evidence paths + graph ML**

Typed threat graph, retrieval-grounded investigations, explainable paths, and **logistic link prediction** over structural graph features to rank missing relationships for analyst review.

**Focus:** Threat intelligence · graph ML · link prediction · evidence retrieval

</td>
<td width="50%" valign="top">

### [AI Data Center Security Digital Twin](https://github.com/VinayK88/ai-datacenter-security-digital-twin)
**Cyber-physical AI infrastructure + multivariate ML**

Directed attack paths, blast radius, control what-if analysis, and **PCA reconstruction-based anomaly detection** across GPU, power, identity, BMC, Kubernetes, network, thermal, and model telemetry.

**Focus:** AI infrastructure · multivariate anomaly detection · attack graphs · resilience

</td>
</tr>
</table>

---

## Security Platforms

| Capability | Representative projects | Core question |
| --- | --- | --- |
| **Discover & govern AI agents** | [AgentAtlas](https://github.com/VinayK88/AgentAtlas) | What agents exist, what can they reach, and which identities are unusual or overprivileged? |
| **Control agent execution** | [AgentShield](https://github.com/VinayK88/AgentShield) | Is this action authorized, and is the trajectory becoming behaviorally unusual? |
| **Engineer & prioritize detections** | [DetectionForge](https://github.com/VinayK88/DetectionForge) | Does this detection meet measurable release gates, and which fired alerts deserve attention first? |
| **Secure the browser** | [BrowserGuard](https://github.com/VinayK88/BrowserGuard) | Which extensions behave abnormally, what can they access, and what is their browser-to-SaaS blast radius? |
| **Govern OAuth / SaaS trust** | [SaaSGraph](https://github.com/VinayK88/SaaSGraph) | Which grants, tokens, API patterns, and third-party apps create material enterprise exposure? |
| **Investigate threat intelligence** | [Threat Intelligence Knowledge Graph](https://github.com/VinayK88/Threat-intelligence-knowledgegraph) | Which CTI evidence paths exist, and which missing relationships should analysts investigate? |
| **Analyze attack paths** | [AttackPath AI](https://github.com/VinayK88/attackpath-ai), [Counterfactual Security Engine](https://github.com/VinayK88/Counterfactual-security-engine) | How can compromise propagate and which controls reduce reachability? |
| **Recover after cloud compromise** | [CloudRescue](https://github.com/VinayK88/CloudRescue) | Can critical workloads actually recover when the production control plane is no longer trusted? |
| **Verify digital content** | [DeepTrace](https://github.com/VinayK88/DeepTrace) | What evidence supports authenticity, manipulation risk, or coordinated narrative activity? |
| **Assure AI infrastructure** | [AI Data Center Security Digital Twin](https://github.com/VinayK88/ai-datacenter-security-digital-twin), [InfraGuard AI](https://github.com/VinayK88/InfraGuard-AI) | Can high-consequence infrastructure remain safe under anomalous telemetry, model, identity, or control conditions? |

---

## Production ML Practices Demonstrated

Across the portfolio, the projects intentionally cover more than model fitting:

- **Model evaluation** — holdouts, hard negatives, confusion metrics, clustering evidence, regression error, synthetic scenario checks.
- **Model monitoring** — PSI-style feature drift, vocabulary/distribution drift, residual degradation, versioned feature schemas.
- **Robustness testing** — low-and-slow behavior, permission growth, token reactivation, paraphrase variation, recovery stress conditions.
- **Explainability** — feature deviations, graph evidence, rule reasons, sequence transitions, reconstruction contributors, policy rationale.
- **Human-in-the-loop workflows** — active learning, approval gates, analyst candidate links, review prioritization.
- **Safe decision boundaries** — deterministic authorization, recoverability blockers, provenance rules, and policy gates remain separate from learned scores.
- **Reproducibility** — deterministic synthetic fixtures, seeded models, APIs/CLIs, tests, Docker, and GitHub Actions.

> **Evaluation boundary:** public datasets and scenarios are intentionally synthetic or simulation-based where real security telemetry would be sensitive. Repository metrics validate implementation and evaluation paths; they are not presented as production efficacy claims.

---

## Technical Focus

<table>
<tr>
<td width="33%" valign="top">

**Cybersecurity**

AI / agent security  
Detection engineering  
Browser / extension security  
Cloud security  
SaaS / OAuth security  
Identity / IAM  
Threat intelligence / CTI  
MITRE ATT&CK  
Trust & Safety  
Attack-path analysis  
Critical infrastructure / AI infrastructure

</td>
<td width="33%" valign="top">

**Machine Learning**

Supervised classification  
Gradient Boosting  
Isolation Forest  
Random Forest  
PCA anomaly detection  
Sequence / Markov modeling  
Graph ML / link prediction  
TF-IDF / DBSCAN  
Active learning  
Calibration / decision science  
Model drift & robustness testing

</td>
<td width="33%" valign="top">

**Engineering**

Python  
SQL  
PySpark / Spark  
FastAPI  
Streamlit  
NetworkX  
scikit-learn  
Docker  
GitHub Actions  
Jupyter  
SARIF

</td>
</tr>
</table>

---

## More Security & AI Work

- **[MacSentinel](https://github.com/VinayK88/macsentinel)** — privacy-preserving macOS threat analytics with provenance graphs and anomaly/sequence/graph ML.
- **[SupplyChain Guardian AI](https://github.com/VinayK88/supplychain-guardian-ai)** — SBOM, CI/CD, provenance, dependency graphs, auditable ML ranking, policy gates and SARIF.
- **[GPU Trust Guardian](https://github.com/VinayK88/gpu-trust-guardian)** — GPU telemetry, synthetic attestation, behavioral trust scoring and policy gates.
- **[LLM Security Evaluation Lab](https://github.com/VinayK88/LLM-Security-Evaluation-Lab)** — prompt-injection, misuse, tool-safety and safeguard evaluation.
- **[Frontier Agent Evals](https://github.com/VinayK88/frontier-agent-evals)** — long-horizon agent environments, perturbations, process/outcome/safety graders and calibration.
- **[Agentic SOC Investigator](https://github.com/VinayK88/Agentic-soc-investigator)** — evidence-grounded investigation across identity, endpoint, cloud and OAuth.

---

<div align="center">

### Selected Portfolio

[**DetectionForge**](https://github.com/VinayK88/DetectionForge) · [**AgentShield**](https://github.com/VinayK88/AgentShield) · [**BrowserGuard**](https://github.com/VinayK88/BrowserGuard) · [**AgentAtlas**](https://github.com/VinayK88/AgentAtlas)  
[**Threat Intelligence KG**](https://github.com/VinayK88/Threat-intelligence-knowledgegraph) · [**SaaSGraph**](https://github.com/VinayK88/SaaSGraph) · [**CloudRescue**](https://github.com/VinayK88/CloudRescue) · [**DeepTrace**](https://github.com/VinayK88/DeepTrace)  
[**AI Data Center Digital Twin**](https://github.com/VinayK88/ai-datacenter-security-digital-twin) · [**RiskOS**](https://github.com/VinayK88/riskos) · [**InfraGuard AI**](https://github.com/VinayK88/InfraGuard-AI)

[Browse all repositories →](https://github.com/VinayK88?tab=repositories)

</div>
