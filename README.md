# Awesome-Developer-Portals-Microservices-Platform

markdown
# Top Developer Portals & Microservices Platform Ecosystem

**Curated List of SaaS/Hosted Platforms & Open-Source GitHub Projects**  
*Focused on Internal Developer Portals (IDPs), Service Catalogs, Golden Paths, Platform Engineering Orchestrators & Microservices Governance*  
**Last updated: November 2026**

This repository tracks notable **SaaS/hosted platforms** and **open-source projects** for **Developer Portals & Microservices Platforms**. These tools centralize service catalogs, scaffold golden-path templates, track microservice ownership and production readiness scorecards, and orchestrate self-service cloud infrastructure across platform engineering and DevOps teams.

**Examples** include Backstage by Spotify, Port, Cortex.io, Configure8, Atlassian Compass, OpsLevel, Rely.io, DX Platform, Roadie Backstage, Harness Internal Developer Portal, and kdlbs/kandev (the category leaders and popular runtimes). 

**Open-source emphasis**: This section is heavily expanded with every major active project for Internal Developer Portals (`Backstage`, `Red Hat Developer Hub / Janus IDP`, `kdlbs/kandev`), platform engineering & application delivery orchestrators (`KubeVela`, `Kratix`, `Crossplane`, `Score`, `Radius`), and microservice runtimes & GitOps engines (`Dapr`, `Argo CD`, `Porter`) — ideal for platform engineers, SREs, enterprise architects, and DevOps teams.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Support & Share](#support--share)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Port](https://getport.io)**  
  No-code/low-code Internal Developer Portal platform featuring a customizable software catalog, self-service developer actions, engineering scorecards, and real-time GitOps/CI integrations.

- **[Cortex.io](https://cortex.io)**  
  Enterprise Internal Developer Portal focused on microservice catalogs, automated production-readiness scorecards, incident tracking, and engineering excellence initiatives.

- **[Atlassian Compass](https://atlassian.com)**  
  Developer experience and distributed architecture platform uniting microservice component catalogs, health scorecards, DevOps metrics, and Jira/Bitbucket workflows.

- **[OpsLevel](https://opslevel.com)**  
  Service catalog and Internal Developer Portal designed to track microservice ownership, automate maturity checks, and provide self-service developer scaffolding templates.

- **[Roadie Backstage](https://roadie.io)**  
  Fully managed, zero-maintenance SaaS hosting for Spotify's Backstage offering enterprise RBAC, SOC2 compliance, and pre-built plugin integrations out of the box.

- **[Harness Internal Developer Portal](https://harness.io)**  
  Backstage-powered cloud developer portal deeply integrated with Harness CI/CD, feature flags, cloud cost management, and self-service golden paths.

- **[Rely.io](https://rely.io)**  
  AI-powered Internal Developer Portal and software catalog automating service discovery, DORA/reliability scorecards, and developer self-service workflows.

- **[DX Platform (GetDX)](https://getdx.com)**  
  Developer experience and engineering intelligence platform combining qualitative developer surveys with quantitative system telemetry and service catalog insights.

- **[Configure8](https://configure8.io)**  
  Universal Internal Developer Portal aggregating cloud resources, Kubernetes clusters, CI/CD pipelines, and microservice dependencies into unified service scorecards.

- **[Spotify Portal for Backstage](https://spotify.com)**  
  Commercial managed SaaS offering from the creators of Backstage providing turnkey cloud hosting, enterprise plugins, and simplified portal administration.


## Open-Source GitHub Projects

- **[kdlbs/kandev](https://github.com)**  
  Open-source developer portal and microservices platform toolkit engineered to streamline service organization, developer self-service, and modern platform workflows.

- **[Backstage by Spotify (`backstage/backstage`)](https://github.com)**  
  Flagship CNCF open-source framework for building Internal Developer Portals—featuring a centralized Software Catalog, Software Templates (Golden Paths), TechDocs, and hundreds of community plugins.

- **[Red Hat Developer Hub / Janus IDP (`janus-idp/backstage-showcase`)](https://github.com)**  
  Enterprise-ready open-source Backstage distribution maintained by Red Hat and the Janus community with dynamic plugin loading, Keycloak RBAC, and Kubernetes/Argo CD plugins.

- **[KubeVela (`kubevela/kubevela`)](https://github.com)**  
  Modern CNCF open-source application delivery and platform engineering engine built on the Open Application Model (OAM) for deploying microservices across hybrid and multi-cloud clusters.

- **[Crossplane (`crossplane/crossplane`)](https://github.com)**  
  Industry-standard CNCF open-source control-plane framework turning Kubernetes into a universal cloud API so platform teams can expose self-service infrastructure abstractions.

- **[Kratix (`syntasso/kratix`)](https://github.com)**  
  Open-source platform engineering framework enabling teams to compose, curate, and deliver as-a-Service APIs ("Promises") across multi-cluster Kubernetes environments.

- **[Score (`score-spec/spec`)](https://github.com)**  
  Open-source, platform-agnostic developer-centric workload specification (`score.yaml`) allowing developers to define microservice requirements once and run them identically on Docker Compose or Kubernetes.

- **[Dapr (`dapr/dapr`)](https://github.com)**  
  Portable, event-driven CNCF open-source runtime providing microservice building blocks—service-to-service invocation, state management, pub/sub, and secrets—via sidecar APIs.

- **[Argo CD (`argoproj/argo-cd`)](https://github.com)**  
  Declarative, GitOps continuous delivery engine for Kubernetes widely embedded inside Internal Developer Portals for live microservice sync status and self-service rollouts.

- **[Radius (`radius-project/radius`)](https://github.com)**  
  Cloud-native, open-source application platform from Microsoft enabling developers and platform engineers to define, deploy, and connect microservices and cloud dependencies together.

- **[Port Ocean (`port-labs/ocean`)](https://github.com)**  
  Open-source extensible integration framework by Port built in Python for ingesting real-time data from Kubernetes, GitHub, GitLab, PagerDuty, Jira, and AWS into developer portals.

### Additional Strong Open-Source Options

- **[Porter (`porter-dev/porter`)](https://github.com)** and **[Qovery Engine (`Qovery/engine`)](https://github.com)** for open-source PaaS layers turning your own AWS, GCP, or Azure Kubernetes clusters into Heroku-like self-service developer platforms.
- **[KubeSphere (`kubesphere/kubesphere`)](https://github.com)** for a distributed open-source container platform featuring a multi-tenant developer portal, DevOps pipelines, and Istio service mesh observability.
- **[Cycloid / Terragrunt & OpenTofu (`opentofu/opentofu`)](https://github.com)** for open-source Infrastructure-as-Code engines powering golden-path self-service provisioning behind Backstage templates.
- **[Istio (`istio/istio`)](https://github.com)** and **[Linkerd (`linkerd/linkerd2`)](https://github.com)** for open-source service meshes providing zero-trust mTLS, traffic routing, and service dependency topology graphs for microservices platforms.
- **[Cookbook / Copier (`copier-org/copier`)](https://github.com)** for deterministic microservice scaffolding templates with upstream lifecycle updates alongside Backstage Scaffolder.

**Frameworks for building custom systems**: Combine **Backstage** or **kdlbs/kandev** for the unified developer portal and service catalog, **Crossplane + KubeVela** for self-service infrastructure provisioning, and **Dapr + Argo CD** for portable microservices runtime and GitOps delivery.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS/hosted or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Support & Share

If you find this curated list helpful, consider supporting the project:

- ⭐ **Star this repository** to help others discover it.
- 🍴 **Fork & Share** it with your team, friends, or community on X/Twitter, LinkedIn, and Reddit.
- ☕ **Buy me a coffee / Sponsor** my open-source work on [GitHub Sponsors](https://github.com) — featuring tiers for profile badges, README shoutouts, logo placements, and prioritized bug fixes/features!

[![Sponsor @ishandutta2007](https://shields.io)](https://github.com)

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Internal Developer Portals (`Backstage`, `Crossplane`, `Argo CD`) centralize access to production deployment pipelines and cloud credentials; always enforce strict RBAC, OIDC/SSO authentication, least-privilege IAM roles, and audit logging.
Use code with caution.
• Standing up a full self-hosted Backstage instance requires dedicated frontend/backend engineering maintenance; smaller teams may prefer lightweight orchestrators (Score, KubeVela, Porter) before scaling to a full portal.
Made for platform engineers, SREs, microservice architects, DevOps teams, and open-source contributors.
Let's make developer portals and microservices platforms more open, self-service, and developer-friendly.
